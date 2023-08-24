# psychopy_biosemi_serial

A set of Psychopy demos showing how to send triggers via the biosemi
serial adapter using serial port calls in code, or using the pyxid2
library. Although the serial code works fine in some cases, pyxid2 is
recommended for more complex cases such as using a Cedrus Stimtracker
device.w
 
Created in Psychopy v2022.2.4. 

This demo shows you how to send triggers in conjunction with a text
stimulus. Demos are created using the PsychoPy Builder, but with a few
code components. Note that attempting to do this with a Serial Port
Component in Builder doesn't seem to work very well. Text and trigger
values are set in the provided Excel sheet. 

Thanks to Dr. Blake Butler, U. Western Ontario, for adapting the serial
port code for use with the pyxid2 library and a Cedrus Stimtracker.

This code is provided for educational purposes only and I make no
representations on whether it provides adequate timing or works
correctly. I can't guarantee I can help with technical issues. But if
you find a bug or would like to contribute, click 'issues' above.
