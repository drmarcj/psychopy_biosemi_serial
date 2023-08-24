# psychopy_biosemi_serial

A set of Psychopy demos showing how to send triggers via the biosemi
serial adapter using serial port calls in code, or using the pyxid2
library. Although the serial code works fine in some cases, pyxid2 is
recommended for more complex cases such as using a Cedrus Stimtracker
device.w

Created in Psychopy v2022.2.4.

These demos show you how to send triggers to a Biosemi EEG system,
synchronized with a text stimulus. The demos are created using the
PsychoPy Builder, but with a few code components. Note that attempting
to do this with a Serial Port Component in Builder doesn't seem to work
very well.

The **psychopy_biosemi_serialusb** example shows you how to do this with
the Biosemi-provided USB to serial adapter.

The **psychopy_biosemi_pyxid2** example shows how to do this with a
Cedrus Stimtracker device, in conjunction with the pyxid2 Python
library. Thanks to Dr. Blake Butler, U. Western Ontario, for
contributing this code.

All code is provided for educational purposes only and I make no
representations on whether it provides adequate timing or works
correctly. I can't guarantee I can help with technical issues. But if
you find a bug or would like to contribute, click 'issues' above.

