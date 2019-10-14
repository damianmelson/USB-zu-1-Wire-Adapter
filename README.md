# USB zu 1-Wire Adapter
Aktives USB-Interface für 1-Wire.

![Ansicht](https://github.com/damianmelson/USB-zu-1-Wire-Adapter/blob/master/images/ansicht.jpg)

## Schaltplan

![Schaltplan](https://github.com/damianmelson/USB-zu-1-Wire-Adapter/blob/master/images/schaltplan.png)

## Platine
[Gerberdaten](https://github.com/damianmelson/USB-zu-1-Wire-Adapter/tree/master/gerber) für [PCBWay](https://www.pcbway.com) und [ALLPCB](https://www.allpcb.com).

![Platine oben](https://github.com/damianmelson/USB-zu-1-Wire-Adapter/blob/master/images/pcb_oben.png)
![Platine unten](https://github.com/damianmelson/USB-zu-1-Wire-Adapter/blob/master/images/pcb_unten.png)

[Bauelemente](https://github.com/damianmelson/USB-zu-1-Wire-Adapter/tree/master/docs) von [reichelt elektronik](https://www.reichelt.de) und [LCSC](https://lcsc.com).<br>
1-Wire-Anschluss (CN1) optional bestückbar mit 3-pol. WAGO SMD-Leiterplattenklemme Typ 2060 sowie mit RIA Anschlussklemme Typ 59 (AKL 059-03).

## Gehäuse
[Strapubox](https://strapubox.de) Kleingehäuse Typ USB 1.

## FHEM
Device in [FHEM](https://wiki.fhem.de/wiki/FHEM_und_1-Wire) anlegen:<br>
`define <name> OWX /dev/ttyUSBx`<br>

USBx ist anzupassen an die aktuell benutzte Schnittstelle.