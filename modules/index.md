# Modules

Note: this guide is not meant as a complete reference for the various electronic components you will encounter. We recommend the [Encyclopedia of Electronic Components vol 1,2,3](https://www.makershed.com/products/make-encyclopedia-of-electronic-components-vol-1) for a complete reference.

* [Power modules]({{site.baseurl}}/modules/power)

### Switch

Switches select between a closed or open circuit. Of course, there's many different switches you will find when opening electronic components.

* Take a deep dive and read the [SparkFun's switch basics guide](https://learn.sparkfun.com/tutorials/switch-basics).

A simple switch has 2 terminals, called **pole** and **throw**.
If we are lucky, the switch terminals are soldered to cables
and we can use the cable-binder connecting to connect them into a
module.

![A switch module]({{site.baseurl}}/assets/switch.JPG)

Toggle switches have terminals with mounted screws. 
We can either thread recycled cables or use paper clips to connect them to the binder clips.

![A switch between two circuits]({{site.baseurl}}/assets/threewayswitch.jpg)

Buttons is another type of switches commonly found in toys.

![5 buttons refurbished from a Guitar Hero Handle]({{site.baseurl}}/assets/guitarherobuttons.jpg)

#### Light switch

You can also use light switches found in hardware stores.

![A single pole light switch]({{site.baseurl}}/assets/lightswitch.jpg)

Start by attach a paper clip to each poles and secure them in place with a
screwdriver

![Light switch with paper clips]({{site.baseurl}}/assets/lightswitchlegs.jpg)

Glue the switch to the cardboard cutout and route the paper clip wires 
into binder clips. Cover with glue after testing the connections.

![Paper clip connecto the binder clip]({{site.baseurl}}/assets/lightswitchterminals.jpg)

Add some decoration, and red/pink tape if you have any as this is an _input_ module.

![Light switch module]({{site.baseurl}}/assets/lightswitchdone.jpg)

### LED

An LED is Light Emitting Diode. It's a piece of electronics that contains 
a crystal that generates light under a current. Watch out, it only allows current to flow one way and blocks it the other way. An LED can be easily destroyed by high currents so it is recommended to mount it in series with a 200Ω (Ohm) resistor.

> Want to deep dive? Read the [SparkFun LED guide](https://learn.sparkfun.com/tutorials/light-emitting-diodes-leds) 
or watch [Adabot from Adafruit](https://youtu.be/E2WcaJySVuw).

The 200Ω resitors has 2 red lines and 1 black line. You can find tons of apps online that will help you compute this value based on the colors.

* Connect the ground terminal (-), the short one, to a binder clip.
* Connect the positive terminal (+), the long one, to a paper fasterner
together with a terminal of the resistor
* Clamp the remaining resitor terminal to a binder clip

![A LED module]({{site.baseurl}}/assets/ledmodule.jpg)

### Potentiometer

TODO
![A potentiometer module]({{site.baseurl}}/assets/potentiometermodule.jpg)

#### What can go wrong?

A potentiometer acts as a voltage dividing resitor. If large current are flowing via the resistor, it will start to heat up and potentially break down.

### DC motor

DC motors are found in most RC cars and many other toys. 
They can be controlled to turn forward or backward at various speed.

* a DC motor mounted in a cardboard module

![A DC motor mounted on cardboard]({{site.baseurl}}/assets/mounteddcmotor.jpg)

* the front drive train of a RC car hosts 2 DC motors (1 for traction, 1 for steering)

![A recycled drive train with DC motors]({{site.baseurl}}/assets/carmotor.jpg)

* removing the car controller and rewiring the motors
creates a driveable cardboard module!

![A rewired toy RC car module]({{site.baseurl}}/assets/rccarmodule.jpg)

### DC vibrating motor

Often found in game controllers to create the vibrations, the vibrating motors are just DC motor mounted with a assymetric metal head.
They can be used to build Junk Bots, small robots that move randomly based on the vibration of a motor.

![A vibrating DC motor harvested from a game controller]({{site.baseurl}}/assets/dcvibrator.jpg)

You can easily turn a DC motor into a assymetric motor by attach weight to it.

![A converted DC motor into a vibrating motor]({{site.baseurl}}/assets/converteddcvibrator.jpg)

### Cable

When opening up game controller, you will often end with a long and sturdy cable that can be used
to create wire modules!

#### Step 1: trim the wires

A cable typically various cables, including a grounfd (black), positive (red)
and a few logic cables. Strip out some casing and trim each wire.

![A cable with trimmed wires]({{site.baseurl}}/assets/cabletrimmed.jpg)

#### Step 2: prepare the module

Glue the cable at the center of carboard and layout a binder clip for
each wire. Annotate each binder with the color of the cable.

![Cable module layout]({{site.baseurl}}/assets/cableconnectors.jpg)

Once ready, connect all the wires to the binders.

#### Step 3: prepare the other side!

Do the same for the other end of the cable and you're done. If available, use orange tape to mark the cable.

![A cable module]({{site.baseurl}}/assets/cablemodule.jpg)

### Microcontrollers

Microcontrollers are tiny computers that receive and generate electrical currents. They can be used to control motors, lights and sounds.
Some microcontrollers have built-in sensors and buttons which makes even easier to integrate them in your project. 
We will use microcontrollers supported by https://makecode.com in this guide but there are many others out there.

#### Don't fry me

Microcontrollers interact with other electronic devices via their _pins_ using _small_ current. 
Without proper protection, it is really easy to accidently destroy the board by plugging the wrong cables or pulling too much current.
Any pin connected to a terminal should be properly protected.

#### LED optoisolator

If you plan to expose an _input_ pin with binder clips, it most likely that an accidental connection will destroy it. To make it more robust,
a LED optoisolator almost guarantees that the pin is safe. The optoisolator uses 2 LEDs connected on different circuits.
The input circuit controls the emitting LED and turns it on when the input is high. 
The receiving LED is used in reverse and acts as a light sensor connectoed to the micro-controller pin, which can pick up the tiny voltage variation
that occurs when the LED is turned on.

TODO 

#### MOSFET relay switch

A _output_ pin also needs protection as a user may connect to any other cable. We propose to use MOSFET to isolate the microcontroller and allow to drive large current in motors.

TODO

#### micro:bit

A [micro:bit](https://makecode.microbit.org) is a small computer, called _microcontroller_, 
that can interact with other electronic devices. Aside from the onboard screen, sensors and radio capabilities, the micro:bit can control LEDs, servos or motor controllers via large hole connector on the bottom. The micro:bit is easily programmed with a [kid frienly code editor](https://makecode.microbit.org).

#### micro:bit 1 input 1 output

In this module, we expose 1 input pin (using a LED optoisolator) and 1 output pin (via a MOSFET relay switch). Once built, the module can safely be used with other modules, it can also drive a motor.

### More modules

There are some many other eletronic components out there and this guide is not meant to be exhaustive. Be creative, curious, read up on the components you find and tell us what you were able to build!

