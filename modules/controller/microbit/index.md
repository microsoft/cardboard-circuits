# micro:bit

A [micro:bit](https://makecode.microbit.org) is a small computer, called _microcontroller_, 
that can interact with other electronic devices. Aside from the onboard screen, sensors and radio capabilities, the micro:bit can control LEDs, servos or motor controllers via large hole connector on the bottom. The micro:bit is easily programmed with a [kid frienly code editor](https://makecode.microbit.org).

## micro:bit MOSFET switch output

![A micro:bit dual switch with MOSFET]({{site.baseurl}}/assets/microbit_dual_switch.jpg)

### Example

The wiring below turns on a vibrating DC motor when pressing button A on the micro:bit

![A micro:bit dual switch with MOSFET]({{site.baseurl}}/assets/microbit_dual_switch-wired.jpg)


## micro:bit LED opto-isolator input

In this module, we expose 1 input pin (using a LED optoisolator) and 1 output pin (via a MOSFET relay switch). Once built, the module can safely be used with other modules, it can also drive a motor.
