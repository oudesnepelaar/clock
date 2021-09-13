# 4 digit 7 segment wall clock

A PCB design for a wall clock.

This is a circuit and PCB design that uses small LEDs tubes as segments for the clock digits.
It's a simple device, driven by an Arduino Nano (including Sketch .INO) that does not connect to
a remote data source, does not have a Wifi GUI for set-up, and it does not even persist its time setting,
nor does it use a Real-time clock unit or offer an alarm function.

All these shortcomings are of course potential expansions for the future. For now I just wanted to toy
around with the bunch of LED tubes I got from AliExpress and see if I can fill the segments with epoxy
to make them beefier and shine nicely uniformly. The epoxy is transparent, but I use some droplets of white and yellow
epoxy dye to make it slightly opaque.

The clock plugs into a 5V 2A power source (like most USB phone chargers) so indirectly it connects to a wall socket.
Setting the time is done by use of 4 momentary push-buttons.
The body casing of the clok is made from black foam board (like architects use for maquettes).
A piece of clear acrylic can be used to cover the digits.


Ferrie J Bank,
Amsterdam 11 September 2021

https://github.com/oudesnepelaar


transistors: C189428 (LCSC.com) 1W NPN 0.6A 40V SOT-223 Bipolar Transistors - BJT ROHS
capacitors: C15850 (10 uF) C307348 (100 nF) C29823 (4.7 uF)
shift register: C161627 (MC14094BDR2G 3-state outputs, 8 bits shift register)
pinheaders 15F (Nano): C124408
switches: C669810
