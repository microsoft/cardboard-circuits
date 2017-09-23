# Speaker

The speaker module turns electrical current into sounds! This module is a bit special because it requires to be connected to a module that produce electrical "tones" rather than flat current. Typically, you'll use a [controller]({{site.baseurl}}/modules/controler) to do that.

![A LED module]({{site.baseurl}}/assets/modules/output/speaker/demo.jpg)

Some tiny speakers can be powered directly from a micro-controller, however other ones need to have an amplifier. For simple square tones, a single transistor or MOSFET can be used.

## Make

<div style="position:relative;height:0;padding-bottom:56%;overflow:hidden;"><iframe width="560" height="315" src="https://www.youtube.com/embed/DwmAobdB1XY" frameborder="0" allowfullscreen></iframe></div>

* Trim out the two cables coming out of the speaker
* Connect them to binder clip
* Secure everything with glue and add **green** tape to mark the module

## Circuits

In this circuit, the speaker is attached to the MOSFET ``0`` of the [micro:bit relay module]({{site.baseurl}}/modules/controller/microbit/relay).
The code on the micro:bit generates square tones on pin ``0`` which open and close the current flowing via the MOSFET.

![A circuit using speaker module]({{site.baseurl}}/assets/modules/output/speaker/circuit.jpg)

<div style="position:relative;height:0;padding-bottom:56%;overflow:hidden;"><iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/fi5YdQAJYJI" frameborder="0" allowfullscreen></iframe></div>

## Gallery

![A speaker module]({{site.baseurl}}/assets/modules/output/speaker/speaker2.jpg)
