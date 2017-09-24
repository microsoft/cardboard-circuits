# micro:bit Foil Keyboard

In this module, you are the conductor! The micro:bit pins can be used to detect that a connection is made through a human body (or multiple).
By using foil and glue, it is possible to create any kind of patterns and custom keyboards.

## Materials

* Aluminium foil
* Hot glue or school glue
* 4 crocodile clips
* 1 USB connector

## Make

* Strip the USB cable and connect it to two binder clip terminals to provide power
* From the ground terminal, connect a crocodile clip to a foil section on the side where the user will have to press
* Layout 3 other sections of foil (preferrable as a single piece) and connect them to pins ``P1``, ``P2``.

## Code

The code below plays a note for each pin pressed.

```blocks
pins.onPinPressed(TouchPin.P1, function() {
    music.playTone(Tone.A4, music.beat(BeatFraction.Half));
})
pins.onPinPressed(TouchPin.P1, function() {
    music.playTone(Tone.C4, music.beat(BeatFraction.Half));
})
```