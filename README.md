# DoorBerry
Use a Raspberry Pi as a VoIP door intercom system.

I use it with my FritzBox to alert all my DECT Phones.
Tested on a Pi 2B+ and a Pi Zero with raspbian (and mono).

## Software

Please find it [here](https://github.com/User65k/DoorBerryServer).

## Hardware

All Files are creaded with [KiCad](http://kicad-pcb.org/).

### Old Door system

The new System replaces the indoor part of a RITTO intercom system.

![RITO Door bell](./doc/RITTO.jpg)

The old system had a fairly simple circut:

![RITO Inside](./doc/Old_Circut.jpg)

![Circut](./doc/tel_schaltung.png)

### New Door Intercom

The system is replaced by a Raspberry with a custum Hat (utilizing the GPIOs of the Pi):

![Hat](./doc/pi_schaltung.png)
