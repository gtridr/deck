# deck
An integrated instrument &amp; control surface based on norns

!{panel}(/images/deck-panel.png)
![3D](/images/deck_model.png)

## Credits & Licensing

Starting things off: this project is licensed as a derivative work under GPL-3.0. All due credits to the following individuals & projects:

 - The core audio codec & voltage regulation design are unmodified from the 210330 revision of the [norns shield](https://github.com/monome/norns-shield) save for some rerouting & cleanup

 - The raspberry pi image is a very lightly modified fork of the mainline norns codebase, with just a few tweaks to map the 4th encoder, serial pins for MICROMIDITRS, and soft shutdown via ATXRaspi.

 - The teensy firmware is a fork of Okyeron's [DIY grid](https://github.com/okyeron/neotrellis-monome) firmware. All credit for the grid emulation goes to him; I've only added what was necessary to get the potentiometers working over USB MIDI
