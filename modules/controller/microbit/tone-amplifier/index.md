# micro:bit Tone Amplifier

![micro:bit as speaker amplifier]({{site.baseurl}}/assets/modules/controller/microbit/relay/speakercircuit.jpg)

The **micro:bit** music blocks control the pin ``P0``. This current from this pin needs to be amplified in order to play in large speakers. Fortunately, the micro:bit produces very basic sounds (square sound waves) that can be amplified with a single transistor.

This module is built like the [relay]({{site.baseurl}}/modules/controller/microbit/relay).

## Code

The code below plays a "power up" melody when button **A** is pressed and "power down" when button **B** is pressed. The speaker should be connected
to the MOSFET connected to the pin ``P0``.

> Click on **Download** to transfer the code to your micro:bit

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_2MAModLFy0tj" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>
