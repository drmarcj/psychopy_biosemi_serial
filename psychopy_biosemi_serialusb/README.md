# psychopy_biosemi_serial
Small Psychopy demo showing how to send triggers via biosemi serial adapter.
 
Created in Psychopy v2022.2.4. 

Biosemi provides a USB-serial trigger interface for coordinating stimulus presentation with its EEG system (https://www.biosemi.com/faq/USB%20Trigger%20interface%20cable.htm). This cable simulates a parallel port cable via serial port messaging. Allowable inputs are one-byte integer values (0-255), which are used to simulate pins 1-8 of a paralel port interface.

This demo shows you how to send triggers in conjunction with a text stimulus. All triggering is done using code. (Attempting to do this with a Serial Port Component in Builder doesn't seem to work very well.) Text and trigger values are set in the provided Excel sheet. Allowable trigger values range from 1-255, in integers. The trigger is converted to a one-byte value and sent to the specified port at the start of the text stimulus. The port is then reset to zero 15 ms later. 

You will probably need to change the port number; you can find this in the 'Before experiment' code of the Intro routine. Please see Psychopy Serial documentation for details on how to figure out what port to use https://psychopy.org/hardware/serialPortInstr.html

This code is provided for educational purposes only and I make no representations on whether it provides adequate timing or works correctly. I can't guarantee I can help with technical issues. But if you find a bug or would like to contribute, click 'issues' above.
