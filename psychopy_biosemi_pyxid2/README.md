#psychopy_biosemi_serial_pyxid2
This is a small Psychopy demo showing how to send triggers via biosemi serial adapter using the pyxid2 package.
 
Created in Psychopy v2023.2.1. 

Cedrus provides the pyxid2 Python pachage to interface with its devices.
This demo shows you how to use Psychopy and pyxid2 to send triggers
through a Cedrus Stimtracker device in conjunction with a text stimulus.
All triggering is done using code. (Attempting to do this with a Serial
Port Component in Builder doesn't seem to work very well. Using the
serial calls in the psychopy_biosemi_serialusb example can sometimes
work for simpler cases like an M-Pod, but not the Stimtracker). Text and
trigger values/corresponding lines to be raised via the serial port
connector to the BioSemi system are set in the provided Excel sheet. 

Note that the pyxid2 package will need to be installed prior to running
this code. In the PsychoPy builder, this can be done by accessing the
'Tools>Plugins & Packages Manager'. You must also have downloaded the
appropriate Stimtracker driver
(https://cedrus.com/support/stimtracker_1g/)

This code is provided for educational purposes only and I make no
representations on whether it provides adequate timing or works
correctly. I can't guarantee I can help with technical issues. But if
you find a bug or would like to contribute, click 'issues' above.
