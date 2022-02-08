Casio2FDTI
==========

This is a small PCB that allows you to connect a CASIO FX-850P/FX-850P via aN FTDI USB cable to your computer (Win or Mac).

* Author: Lennart Hennigs (https://www.lennarthennigs.de)
* Copyright (C) 2021-2022 Lennart Hennigs.
* Released under the MIT license.


Description
-----------

This GIT contains the Fritzing source file and the Gerber files that allow you to get your own PCB. You'll also find the bill of material for the PCB and some more details.

Below is a picture of the completed PCB:

![casio with pcb](result.png)

As you can see, I used SMD components (805) on the PCB. They are large enough to be soldered by hand. They are a few resistors and LEDs to show activity on the RX/TX lines.

Bill of Materials
----------------
- 1 x SMD805 LED (green)
- 1 x SMD805 LED (blue)
- 2 x SMD805 1K Ohm Resistor
- 1 x SMD805 50 Ohm Resistor
- 1 x SMD805 0 Ohm Resistor
- 1 x 2-row right-angle 1.27mm pitch header (2x15 pin)s
- the PCB (e.g. via [JLCPCB](https://jlcpcb.com/))

**Note**: The PCB needs to be **1.2mm thick**. Otherwise it will not fit into the connctor slot.

Details
-------

*TBD*

![fritzing pcb view](fritzing.png)

