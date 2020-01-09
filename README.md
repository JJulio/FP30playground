# FP30 playground

This is an experimental app for roland fp30 digital piano.

Test the app here: [https://jjulio.github.io/FP30playground](https://jjulio.github.io/FP30playground)

FP30 is a fantastic piano!. With this app you could play a lot of new sounds and settings (effect types,reverbs,chorus,pitch bend, modulation,sound envelope settings...)
This app uses a Midi loopback to receive the midi notes of the FP30 and send back again with the posibility to select a lot of new sounds and settings!
By default it switches off the internal sound generator (main keyboard midi local off) but you could play with this enabled also if you want a layered sound.

This app works with the piano connected with USB cable (with bluetooth connection the lag is very bad). For Android use an OTG cable to connect your piano and for ipad use the camera adapter(USB). Connect the piano before open the app on your browser.

This app works on PC (chrome browser) and Android (chrome browser).
For ipad (IOS) users (like me) you could download the free Web MIDI Browser app. You need to configure the settings (left bottom button) and enable sysex (last option). Open the address bar (at top) and copy the app url(top of this page). You could save the url on the favorites (middle bottom button).

*Note1:* When you disconnect the app probably your fp30 doesn't sound. This is because the midi local off. You could enable with Function+F1(the more lower F key) or simple switch off/on your keyboard with the power on/off button.
*Note2:* Some of the sound envolope settings (attack, release, cutoff...) does not work on all sounds (for example this don´t work on piano sounds)

This is an experimental app that uses the webmidi interface. it´s based on the paino midi implementation doc and other internet sources. Special thanks to Picman for his inital help and for the sounds file.
Have fun!

*This app is not official, so play at your own risk*
