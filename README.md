# C128-Internal-Pi1541-Interface
Little board to help connect a RasPi to the internal IEC connector on the C128 main board to use as a Pi1541

I finally took some time to play with KiCad and designed my 1st PCB.  It's just a wee lil one but we all have to start somewhere.

PCBWay project link: https://www.pcbway.com/project/shareproject/Commodore_128_Internal_Pi1541_Interface_f66d35ac.html

The board is based on Stephen White's design (Option B).  Without his awesome work we wouldn't have the Pi1541.
https://cbm-pi1541.firebaseapp.com/

You can hook an OLED directly up to the i2c pins of the Pi (Pins 3 and 5) and get power from 3.3v (Pin 17).

Also can use a rotary encoder hooked up to the same pins you would use for buttons 1, 2 and 3 (13, 15 and 16) and get 5v power from anywhere on the system.

