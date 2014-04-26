Sets a PS3 Move controller to random colors in time with beats heard in the
surrounding audio.

This is a fairly straightforward example of beat detection in Python using
aubio, and of interfacing with Bluetooth-based PS Move controllers.

Requires Python, NumPY, pyaudio, aubio (https://github.com/piem/aubio), and
the PS Move API (https://github.com/thp/psmoveapi). Before running, use
examples/python/pair.py in the psmoveapi repository to pair the Move
controller with the host running the script.
