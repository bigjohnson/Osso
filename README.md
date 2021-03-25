Atmega328p low power development boards programmable with Arduino bootloader or withouth bootloader with USBasp.

Very slow clock, very low current!

I added two USBasp variants

Bone Slow USBasp

Bone Ultra Slow Usbasp

use them with slow clock, the USBasp normal config is too fast and don't work.

WARNING: Some internal slow clock mode can brick your atmega328p, to unbrick it you must use an external programmer, USBasp won't work. I use the [XGecu TL866II](http://www.xgecu.com/EN/TL866_main.html)

For clock over 4Mhz the brwownout voltage is 2,7 volt.
Clock from 4Mhz and under have 1,8 volt brownout.

Arduino ide package:

https://raw.githubusercontent.com/bigjohnson/bigjohnson.github.io/master/Ossi/package_Bone_Tech_Inc._Ossi_index.json

![Osso](https://raw.githubusercontent.com/bigjohnson/bigjohnson.github.io/master/Ossi/doc/osso.jpg)
