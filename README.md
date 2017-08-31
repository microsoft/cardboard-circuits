# [Cardboard Circuits](https://microsoft.github.io/cardboard-circuits/)

> WORK IN PROGRESS

## DYI electronic modules tinkerers

Cardboard circuits is electronic module system that allows kids to build circuits. Modules are built by the kids themselves and electronic parts are sourced from deconstructing toys and other every day electronic gadgets. The modules are built from common classroom materials such as cardboard and binder clips. Cardboard circuits are inspired from Tinkering Studio [circuit boards](https://tinkering.exploratorium.edu/sites/default/files/Instructions/circuit_boards.pdf) and [toy deconstruction](https://tinkering.exploratorium.edu/sites/default/files/Instructions/toy_take_apart_0.pdf).

![A LED dimmer circuit](/assets/leddimmer.gif)

### Deconstructing provides Context

As kids source the electronic parts from existing toys and machines, it gives an additional context to those components. A potentiometer is a somewhat boring and un-interresting element at first sight - however if it was extacted from a racing wheel controller, it gives that item a context meaningful to the children. Hence, their interrest is peaked and they understand why such component is important.

![Opening up toys to find components](/assets/toydeconstruction.JPG)

### Built by kids

In this module system, modules are built by the children themselves. Kids will naturally build modules to their taste, modules that have the right size for their hands, modules that have their favorite colors, modules that they want to reuse and can relate to.

![Customized speaked module](/assets/speakermod.JPG)

### No soldering required

Connections between modules are made via crocodile clips and binder clips. Using a bit of aluminium foil, a binder clip and hot glue, kids are able to manufacture their own connection -- without having to learn soldering. Just like Circuit Boards, modules can be connected together with tape, elastics and others.

![A switch module built with binder clips](/assets/switchbare.jpg)

### Read (and write) the manual!

Kids use the cardboard to down a manual of the component
they just built.

![User manual written on the cardboard](/assets/usbpower2.jpg)

Using colored masking tape, [little Bits color convention](http://discuss.littlebits.cc/t/what-do-the-different-colors-of-modules-mean/157) can
also be used to categorize the modules.

TODO

### Microcontrollers welcome

Students can use any microcontroller to build specialized modules, such as sound generation, servo or motor controllers. These modules may even involve breadboards!

![Servo motor controlled by micro:bit](/assets/microbitservo.JPG)

### Testing, testing, testing

As kids build their own modules, they are constantly encourage to test their circuits. Testing and validating a module is cornerstone of the approach. As a side effect, the students build a robust mental model of the components they are working with.

### Acknowledgments

A special thanks for the Tinker Tank team at the Pacific Science Center in Seattle. 

## Safety first!

Tinkering with electronics is a fun activity that should always be **safe**: 

![Never ever use wall power](/assets/wallpower.jpg)

* **never ever use wall power** 
* **wear protective glasses** 
* **fuse all batteries**
* **don't open batteries**

TODO

## Connectors

Cardboard circuits are made of materials easily found in classrooms: cardboard, binder clips and hot glue.

### Cable to binder clip

This is the most common connection between an electrical cable and a binder clip.
The springness of the binder clip arm is used to create a reliable connection with the cable without having to solder.

#### Step 1: Attach the binder clip

Position the binder clip to the side of the cardobard

![Attaching the binder clip to the board](/assets/binderclipattach.jpg)

#### Step 2: Clamp the cable

Lift the binder clip arm and clamp the cable under it.

![Clamping the cable](/assets/binderclipcable.jpg)

##### Cable too thin?: Add foil

If the cable is too thin on step 2, add a layer of Aluminium foil between the binder and the binder arm.

![Using foil for better connection](/assets/binderclipfoilcable.jpg)

#### Step 3: Testing!

Use a multi-meter or a connection tester to make sure that your connection
works... before adding glue!

![Testing circuits](/assets/bindercliptesting.jpg)

#### Step 4: Glue it all

![Securing connection with hot glue](/assets/binderclipglue.jpg)

### (Optional) Step 5: Add rubber bands

You can optionally add rubber bands to improve the connection on the connector.

![Using rubber bands for better connections](/assets/binderclipband.jpg)

You can run the rubber accross the module when positioning the clips on opposite sides of the board.

![Rubber bands accross the back of the module](/assets/bindercliprubberback.jpg)

#### Tips and tricks

* Test all your connection before gluing them. Be generous with glue.
* Use colored markers to describe the purpose of each connector.
* Trimming a cable with a cable cutter can be very trickly... and lead to no more cables! We highly recommend getting cable trimmers which make this operation seamless for kids.
* Thicker cables can be attached without Aluminium foil. Trial and error is generally the best way to determine if you can skip that step.
* Rubber bands can be used to strengthen the connection and ensure it does not get ripped out.

### Metal ring to binder clip

Some component may not have cables but have metal rings. Potentiometers or the micro:bit are example of those. 

### Paper fasterners

Paper fasteners allow to cramp on metal legs from resistors, diodes and other electronic components. They are very useful to create a small ad-hoc circuit involving resistors or LEDs.

## Modules

Note: this guide is not meant as a complete reference for the various electronic components you will encounter. We recommend the [Encyclopedia of Electronic Components vol 1,2,3](https://www.makershed.com/products/make-encyclopedia-of-electronic-components-vol-1) for a complete reference.

### Power

The modules assume that a 5V or 6V DC electrical power is available.
3 AA batteries, 4 recheargable AA or any USB power brick works in that setting.

#### USB power pack

USB power packs are fairly inexpensive, easy to charge and have integrate protections (check the manual) which makes them a great choice to build circuits. In order to tap in the 5V power, you will need to cut open a USB cable and connect the ground/positive cables to binder clip
connections.

Some battery packs automatically shut down when no current is drawn, so this solution might not work for low current makes. In most cases, if a motor is involved, you won't face that problem!

* Using a wire cutter, cut open a USB cable.
* Trim the red and black cables and cut out the rest of the cables.

![Trimmed cables in a USB cable](/assets/usbcables.jpg)

* Connect the cables using cable-binders connection.
* Mark each connection with their polarity using a marker. Use the correct color, it helps!
* Glue the battery to the cardboard to finish the module

![A USB power pack module](/assets/usbpower2.jpg)

#### AA or AAA Battery packs

When opening toys, we will often end up with a nice battery holder with two terminals. 
Because batteries may heat up a lot when shorted, a _reversible fuse_ should be added to the module.

It is likely that the kids will create shorted circuits. A shorted battery may be damage, heat up or even explode.
**For those reasons, it is very important to add a _reversible fuse_ to any battery pack.**

To create a fuse, you will need to find ``0.5A`` or ``1A`` ``Resettable Fuse Radial Lead PPTC Polyswitch``. 
When the circuit is shorted, the high current heats up the fuse which eventually trips. Let it cool down and your battery pack will be operational again. Because the fuse gets hot, it's important to add some heat shielding around it to avoid burns.

* using a paper connector, connect the positive cable to one end of the fuse. Connect the other end of the fuse to a binder clip.

![Connecting the positive cable through the resetable fuse](/assets/resetablefuse.jpg)

* Add add a protective layer of cardboard above the fuse to
prevent burns.

![A battery pack module](/assets/batterypower.jpg)

#### More choices

Lithium Polymer, Solar, wind, etc... There is a lot more options to store electrical power. **Always make sure your power supply are fused.**

### Switch

Switches select between a closed or open circuit. Of course, there's many different switches you will find when opening electronic components.

* Take a deep dive and read the [SparkFun's switch basics guide](https://learn.sparkfun.com/tutorials/switch-basics).

A simple switch has 2 terminals, called **pole** and **throw**.
If we are lucky, the switch terminals are soldered to cables
and we can use the cable-binder connecting to connect them into a
module.

![A switch module](/assets/switch.JPG)

Toggle switches have terminals with mounted screws. 
We can either thread recycled cables or use paper clips to connect them to the binder clips.

![A switch between two circuits](/assets/threewayswitch.jpg)

Buttons is another type of switches commonly found in toys.

![5 buttons refurbished from a Guitar Hero Handle](/assets/guitarherobuttons.jpg)

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

![A LED module](/assets/ledmodule.jpg)

### Potentiometer

TODO
![A potentiometer module](/assets/potentiometermodule.jpg)

#### What can go wrong?

A potentiometer acts as a voltage dividing resitor. If large current are flowing via the resistor, it will start to heat up and potentially break down.

### DC motor

DC motors are found in most RC cars and many other toys. 
They can be controlled to turn forward or backward at various speed.

* a DC motor mounted in a cardboard module

![A DC motor mounted on cardboard](/assets/mounteddcmotor.jpg)

* the front drive train of a RC car hosts 2 DC motors (1 for traction, 1 for steering)

![A recycled drive train with DC motors](/assets/carmotor.jpg)

* removing the car controller and rewiring the motors
creates a driveable cardboard module!

![A rewired toy RC car module](/assets/rccarmodule.jpg)

### DC vibrating motor

Often found in game controllers to create the vibrations, the vibrating motors are just DC motor mounted with a assymetric metal head.
They can be used to build Junk Bots, small robots that move randomly based on the vibration of a motor.

![A vibrating DC motor harvested from a game controller](/assets/dcvibrator.jpg)

You can easily turn a DC motor into a assymetric motor by attach weight to it.

![A converted DC motor into a vibrating motor](/assets/converteddcvibrator.jpg)

### Microcontroller

TODO

### More modules

There are some many other eletronic components out there and this guide is not meant to be exhaustive. Be creative, curious, read up on the components you find and tell us what you were able to build!

## Toys

Deconstruction suggestion for common toys found in thrift shops
and garage sales.

### Game Controller

A typical game controller is stuffed with buttons, vibrators
and other cools sensors. To open it up, you would typically need
a small Phillips screwdriver.

![A console game controller](/assets/gamecontroller.jpg)

* remove all the screws from the enclosure and open up the controller.

![A game controller without enclosure](/assets/gamecontrolleropened.jpg)

* If you are lucky, the controller has a "vibrate" feature and you'll find 2 DC motors in the handles. Remove them and keep as much cable as possible.

![vibrating motors from a game controller](/assets/gamecontrollermotors.jpg)

* assemble the motors into two modules so that you can use them in other projects!

![Game controller motors turned into modules](/assets/gamecontrollermodules.jpg)

### RC race car

A RC race car will usually have 2 or 3 DC motors and some radio electronics to control it. We can open it, remove the radio controller and wire the motors into a module.

![Race car start](/assets/racecarstart.jpg)

* using a small Phillips screwdriver, remove the cover

![Race car opened](/assets/racecaropened.jpg)

* remove the electronics and trim the cables

![Race car wired](/assets/racecarreadytowire.jpg)

* glue a cardboard and mount the cables using binder clips

![Race car module](/assets/racecarmodule.jpg)

* use power modules, switches and more to bring your car to life!

![Race car drifting](/assets/racecardrifting.gif)

## Projects

### LED circuit

![A LED dimmer circuit](/assets/leddimmer.gif)

#### Modules

* Power
* LED
* Switch

#### Make

Tinker to connect the 3 modules together.

### Junk Bots

![A junk bot built from a game controller](/assets/gamecontrollerbot.gif)

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

[Instructables - Build a Simple Circuit From a Pizza Box](http://www.instructables.com/id/Build-a-Simple-Circuit-from-a-Pizza-Box-No-Solder/)

[Encyclopedia of Electronic Components vol 1,2,3](https://www.makershed.com/products/make-encyclopedia-of-electronic-components-vol-1)

[little Bits color convention](http://discuss.littlebits.cc/t/what-do-the-different-colors-of-modules-mean/157)