Steps for building the stoutgat v2 prototype boards: 

1) Solder all the surface mount caps on the bottom of the PCB. 
These are easiest done by applying a small amount  of solder to one of the pads, then heating it up, and while molten, slide the cap into the molten puddle.
2) Solder the surface mount LEDS. These have the notch aligned with the L corner on the silkscreen. 
Use the same procedure to anchor one pin down and then do the rest.
3) Start installing diodes on the top ( or bottom if you are so inclined, just make sure of polarity ). 
If you are using 3 pin switches and a fingerlonger, do not install D31 (by the ISO enter key) yet, as this will interfere. 
Also note , D31 faces opposite to all the rest of the diodes. Save your diode legs for installing the Blackpill.

**ISO Steps**

4) Choose your layout, and start populating switches from the top downwards , leave the enter key till last as it will interfere if you are using a fingerlonger.
Populate SW49 and SW50 in the left Shift positions, and SW45 on the right.



**ANSI**
4) SW46 is left shift and SW70 is Enter. 

For spacebars, only SW71 is supported right now in the 6.25u position. (The stab holes for 7u went AWOL)
For stepped CAPS , populate SW73

5) Place your stabs
6) Place your encoder(s) if any. The two positions on the left of the board are shared for rotation, so only install in one of them
7) Solder in the BlackPill ( it should come pre-flashed with the default ISO keymap ) You can optionally socket it.
8) Before adding keycaps, mount your spacers :)

The default keymap has RESET bound to the top right switch position on layer 1. 
If you are placing the board in a case that will make getting to the reset and boot switches difficult , always map RESET somewhere.

To flash, either use the RESET key in the map, or press both BOOT0 and NRST , hold BOOT0 and release NRST to enter bootloader.
