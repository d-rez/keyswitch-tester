Cherry-Compatible Keyswitch Tester for the DROP sample pack
==================================

A fork of CandyGumdrop/keyswitch-tester that is more oriented for DROP's [switch sample pack](https://drop.com/buy/assorted-mechanical-mx-switches-sampler-pack)

Notable changes:
* Increased switch count to 20
* Increased resistor value to 680 as LEDs I have are bright enough at 5mA
* Redesigned PCB a bit, re-arranged keys, added printed names of switches included with the sample pack to top layer
* This also lets us stay below 100mA total current draw if you press all at once for whatever reason

==================================

This is a simple keyswitch tester PCB for Cherry-compatible mechanical keyboard
switches.  It holds four keyswitches using Kailh's hotswap switch sockets and
has an LED wired to each switch, providing a quick and simple way to test the
actuation point of various switches.  This board is powered either by a
MicroUSB connector, or optionally instead via a 2 x 0.1" header connected to a
5 V power supply.

Most of this board can easily be assembled by hand, except for the MicroUSB
connector which is a bit more tricky, so if soldering this by hand, you may
prefer to use the header pins instead.

![Schematic](https://raw.githubusercontent.com/CandyGumdrop/keyswitch-tester/master/schematic.png)

![PCB Drawing](https://raw.githubusercontent.com/CandyGumdrop/keyswitch-tester/master/pcb_drawing.png)
