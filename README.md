# ESP-M3-Everything
I little universal ESP-M3 carrier board

At some point...  I should figure out this github stuff & clean this up.

But for now, esp-m3.lib, esp-m3.dcm & foo.kicad_mod are the symbol & footprint for the ESP-M3 module.  Symbol provided by Geekboy1011 on the AddOhms discord.  The footprint is roughly based on his design too...  (But I used his footprint to figure out how to build a new one that actually worked a bit better.)

J1 & J2 are just for power.  & laid out for any of 3 options.  USB micro jack, direct connection or my favourite Chinese breakout board.

J3 is actually compatible with the pin header on most Sonoff devices (if you ignore pins 5 & 6.

If you use pins 5 & 6, you can make it act like a D1-mini when flashing firmware.
