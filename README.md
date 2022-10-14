# deck
An integrated instrument &amp; control surface based on norns

Starting things off: this project is licensed as a derivative work under GPLv3.0.

The core audio codec & voltage regulation circuitry are unmodified from the 211028 revision of the monome norns shield:
https://github.com/monome/norns-shield

The raspberry pi image is a very lightly modified fork of the mainline norns codebase, with just a few tweaks to map the 4th encoder, MIDI-over-serial, and soft shutdown via atxraspi.

The teensy firmware is a fork of Okyeron's DIY grid firmware. All credit for the grid emulation goes to him; I've only added what was necessary to get the potentiometers working over USB MIDI
https://github.com/okyeron/neotrellis-monome
