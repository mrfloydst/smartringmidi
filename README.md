# smartringmidi
MIDI Ring Demo
This will turn a Colmi R02 smart ring into a MIDI controller. Look at this pages' source code for explanations. Press "connect" to select your ring, then enable RAW data mode by pressing that button, then select MIDI CC the ring should control.

Some of the code here (in particular, the bit-shifting stuff that enables to turn the accelerometer data into angular values) is directly lifted from @atc1441's work. Please subscribe to his YouTube channel. On his github page, you'll also find a firmware that speeds up RAW data transmission intervals considerably, which allows for more precise motion tracking.

Homework for you: Turn the ring's "camera button" into a "clap" trigger. The camera gesture detection can be turned on by sending "0204" and turned off by sending "0206" to the ring.
