# [Cardboard Circuits](https://microsoft.github.io/cardboard-circuits/)

> WORK IN PROGRESS

## DYI electronic modules tinkerers

**#cardboardcircuits** are electronic modules built of cardboard, glue and scrap electronics. Modules are built by the kids themselves and electronic parts are sourced from deconstructing toys and other every day electronic gadgets. The modules are built from common classroom materials such as cardboard and binder clips. Cardboard circuits are inspired from Tinkering Studio [circuit boards](https://tinkering.exploratorium.edu/sites/default/files/Instructions/circuit_boards.pdf), [toy deconstruction](https://tinkering.exploratorium.edu/sites/default/files/Instructions/toy_take_apart_0.pdf) and [Paper:Bits](http://plakkenenknippen.nl/paper-bits-vrolijk-en-goedkoop/).

![A LED dimmer circuit]({{site.baseurl}}/assets/leddimmer.gif)

> Sharing your creations on social media? Use the **[#cardboardcircuits](https://twitter.com/search?q=%23cardboardcircuits)** handle!

### Deconstructing provides Context

As kids source the electronic parts from existing toys and machines, it gives an additional context to those components. A potentiometer is a somewhat boring and un-interresting element at first sight - however if it was extacted from a racing wheel controller, it gives that item a context meaningful to the children. Hence, their interrest is peaked and they understand why such component is important.

![Opening up toys to find components]({{site.baseurl}}/assets/toydeconstruction.JPG)

### Built by kids

In this module system, modules are built by the children themselves. Kids will naturally build modules to their taste, modules that have the right size for their hands, modules that have their favorite colors, modules that they want to reuse and can relate to.

![Customized speaked module]({{site.baseurl}}/assets/speakermod.JPG)

### No soldering required

Connections between modules are made via crocodile clips, binder clips or paper clips. Using common classroom materials, kids are able to manufacture their own modules -- without soldering. Just like Circuit Boards, modules can be connected together with tape, elastics and others.

![A switch module built with binder clips]({{site.baseurl}}/assets/switchbare.jpg)

### Modules are self-documented

Kids use the cardboard to down a manual of the component
they just built.

![User manual written on the cardboard]({{site.baseurl}}/assets/usbpower2.jpg)

Using colored masking tape, [little Bits color convention](http://discuss.littlebits.cc/t/what-do-the-different-colors-of-modules-mean/157) can
also be used to categorize the modules (power = blue, input = pink, output = green, wire = orange).

![Modules with colored masking tape]({{site.baseurl}}/assets/coloredmodules.jpg)

### Microcontrollers welcome

Students can use any microcontroller to build specialized modules, such as sound generation, servo or motor controllers. These modules may even involve breadboards!

![Servo motor controlled by micro:bit]({{site.baseurl}}/assets/microbitservo.JPG)

### Testing, testing, testing

As kids build their own modules, they are constantly encourage to test their circuits. Testing and validating a module is cornerstone of the approach. As a side effect, the students build a robust mental model of the components they are working with.

### Acknowledgments

A special thanks for the Tinker Tank team at the Pacific Science Center in Seattle. 

## Safety

**Please review carefully the [Safety guidelines]({{site.baseurl}}/safety)**

![Never ever use wall power]({{site.baseurl}}/assets/wallpower.jpg)

## Connectors

Cardboard circuits are made of materials easily found in classrooms: cardboard, binder clips and hot glue.

* [Cable-binder-clip]({{site.baseurl}}/connectors/cable-binder-clip)
* [Ring-binder-clip]({{site.baseurl}}/connectors/ring-binder-clip)
* [Fastener-bridge-clip]({{site.baseurl}}/connectors/paper-fastener-bridge)
* [Cable-paper-clip]({{site.baseurl}}/connectors/cable-paper-clip)

## Modules

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

## Toys

Deconstruction suggestion for common toys found in thrift shops
and garage sales.

### Game Controller

A typical game controller is stuffed with buttons, vibrators
and other cools sensors. To open it up, you would typically need
a small Phillips screwdriver.

![A console game controller]({{site.baseurl}}/assets/gamecontroller.jpg)

* remove all the screws from the enclosure and open up the controller.

![A game controller without enclosure]({{site.baseurl}}/assets/gamecontrolleropened.jpg)

* If you are lucky, the controller has a "vibrate" feature and you'll find 2 DC motors in the handles. Remove them and keep as much cable as possible.

![vibrating motors from a game controller]({{site.baseurl}}/assets/gamecontrollermotors.jpg)

* assemble the motors into two modules so that you can use them in other projects!

![Game controller motors turned into modules]({{site.baseurl}}/assets/gamecontrollermodules.jpg)

### RC race car

A RC race car will usually have 2 or 3 DC motors and some radio electronics to control it. We can open it, remove the radio controller and wire the motors into a module.

![Race car start]({{site.baseurl}}/assets/racecarstart.jpg)

* using a small Phillips screwdriver, remove the cover

![Race car opened]({{site.baseurl}}/assets/racecaropened.jpg)

* remove the electronics and trim the cables

![Race car wired]({{site.baseurl}}/assets/racecarreadytowire.jpg)

* glue a cardboard and mount the cables using binder clips

![Race car module]({{site.baseurl}}/assets/racecarmodule.jpg)

* use power modules, switches and more to bring your car to life!

![Race car drifting]({{site.baseurl}}/assets/racecardrifting.gif)

## Projects

### LED circuit

![A LED dimmer circuit]({{site.baseurl}}/assets/leddimmer.gif)

#### Modules

* Power
* LED
* Switch

#### Make

Tinker to connect the 3 modules together.

### Junk Bots

![A junk bot built from a game controller]({{site.baseurl}}/assets/gamecontrollerbot.gif)

#### Modules

* Power
* Switch
* vibrating DC motor

#### Materials

* Platic cup
* Markers
* Tape

#### Make

Attach the power and vibrating motor modules to a plastic box or cup
mounted on 3 or 4 markers. Connect the motors to the power and let it run away!

## Reference

[Tinkering Studio Circuit Boards](https://tinkering.exploratorium.edu/sites/default/files/Instructions/circuit_boards.pdf)

[Tinkering Studio Toy Deconstruction](https://tinkering.exploratorium.edu/sites/default/files/Instructions/toy_take_apart_0.pdf)

[Pacific Science Center Tinker Tank](https://www.pacificsciencecenter.org/tinker-tank/)

[Paper:Bits](http://plakkenenknippen.nl/paper-bits-vrolijk-en-goedkoop/)

[Instructables - Build a Simple Circuit From a Pizza Box](http://www.instructables.com/id/Build-a-Simple-Circuit-from-a-Pizza-Box-No-Solder/)

[Encyclopedia of Electronic Components vol 1,2,3](https://www.makershed.com/products/make-encyclopedia-of-electronic-components-vol-1)

[little Bits color convention](http://discuss.littlebits.cc/t/what-do-the-different-colors-of-modules-mean/157)

[microcontroller input protection techniques](http://www.kevinmfodor.com/home/My-Blog/microcontrollerinputprotectiontechniques)

[T³: Using LEDs as Light Sensors](https://www.sparkfun.com/news/2161)

[Relay switch circuit](http://www.electronics-tutorials.ws/blog/relay-switch-circuit.html)