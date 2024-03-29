![PCB_Render](https://github.com/cross-bound/PurplePDK/assets/115736283/6c0b6959-8fb7-4a4b-b1e7-4137d9d2bf70)


Purple PDK is a redesign of the [Original FreePDK](https://free-pdk.github.io/) and [easy-pdk-programmer-lite](https://github.com/free-pdk/easy-pdk-programmer-lite-hardware) programmers. It was a challange to myself and practice PCB design. It was tested with the Padauk PFS-154. Should work with the all other MCU's that are supported by the original FreePDK programmer.

The board is a 4 layer board with the two inner layers being solid ground planes. The size of the PCB is small enough that it can be ordered unassambled from JLCPCB for $2 (at the time of this writing. With purple solder mask and order number removed it's around $8 for 5 boards).

Chances to the easy-pdk-programmer-lite schematic were made to use a SMD type oscillator. The mircoUSB port was changed to Type-C. Also added was a ESD protection IC which may or may not be needed.

Capacitors, resistors, and LEDs are mostly 0603, plus a few 0805 caps. The pads for 0603 components are slightly extended for hand soldering. But this is definitly not a beginner soldering project.

![PCB](https://github.com/cross-bound/PurplePDK/assets/115736283/088f4bfd-4a24-4259-8d16-39db83137005)
