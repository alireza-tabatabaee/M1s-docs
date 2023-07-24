M1S docs
---------
This is a hobbyist-written documentation for the Sipeed M1S module based on the BL808 chip.

BL808 chip
===========
The BL808 chip has three cores, M0(C906), D0(E907), and LP. M0 is 64-bit@480MHz, D0 is 32-bit@320MHz and LP is only used in low power modes.
This chip includes a MMU which means that it is capable of running linux, but in this wiki we will mostly focus on the FreeRTOS SDK provided by Sipeed to program the chip.
