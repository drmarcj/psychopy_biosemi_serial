#psychopy_biosemi_serial_pyxid2
Small Psychopy demo showing how to send triggers via biosemi serial adapter using pyxid2 package.
 
Created in Psychopy v2023.2.1. 

This demo shows you how to send triggers in conjunction with a text stimulus. All triggering is done using code. (Attempting to do this with a Serial Port Component in Builder doesn't seem to work very well.) Text and trigger values/corresponding lines to be raised via the serial port connector to the BioSemi system are set in the provided Excel sheet. 

Note that the pyxid2 package will need to be installed prior to running this code. In the PsychoPy builder, this can be done by accessing the 'Tools>Plugins & Packages Manager'. You must also have downloaded the appropriate Stimtracker driver (https://cedrus.com/support/stimtracker_1g/)

This code is provided for educational purposes only and I make no representations on whether it provides adequate timing or works correctly. I can't guarantee I can help with technical issues. But if you find a bug or would like to contribute, click 'issues' above.
