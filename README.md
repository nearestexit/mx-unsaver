# mx-unsaver

Custom keyboard and numpad inspired by vintage Cherry keyboards and the [IBM "Unsaver"](https://sharktastica.co.uk/topics/keyboard-dictionary/unsaver).
Designed in Onshape and KiCad.
Powered by [QMK](https://github.com/qmk/qmk_firmware).

![Front](https://github.com/nearestexit/mx-unsaver/blob/main/Pictures/Main.JPG)

## Overview
- Side profile and shape inspired by the Cherry G80-5700 and G80-1800
- PCB Top-Mount
- Integrated USB Hub with 1x USB-C Upstream port and 2x USB-C and 2x USB-A Downstream ports
- Brass through-weight

![Back](https://github.com/nearestexit/mx-unsaver/blob/main/Pictures/Back.JPG)

![Combo1](https://github.com/nearestexit/mx-unsaver/blob/main/Pictures/Combo1.png)

**Case Source (Onshape):** https://cad.onshape.com/documents/1d9e79a61d42e7395c429f47/w/28912f958105e1c831f67a9e/e/537bd51b2d234361e6d6eea3

![Combo2](https://github.com/nearestexit/mx-unsaver/blob/main/Pictures/Combo2.png)

## PCB
The PCB supports ISO and ANSI. Unfortunately, due to an oversight, the Case only supports ANSI enter. It could be relatively easily modified to support ISO enter.
I ordered single bare PCBs from EuroCircuits and OSHPark and hand-soldered the components, so I do not have JLCPCB production files available.

![PCB](https://github.com/nearestexit/ms-unsaver/blob/main/Pictures/PCB.JPG)

## Bill of Materials

| Item  | Quantity | Link |
| ------------- | ------------- | ------------- | 
| M2x4x3mm Hex Standoff | 2 | https://www.ebay.com/itm/355663469861?var=624766479032 |
| M2x3x4mm Wafer head Screw | 2 | https://www.ebay.com/itm/355676691340?var=624776776427 |
| Feet | 8 | https://cannonkeys.com/products/akb-feet |
| M2.5x8mm BHCS | 57 | https://mcmaster.com/92095A459 |
| M2.5x6mm SHCS | 14 | https://mcmaster.com/91292A010 |
| M2.5x10mm SHCS | 7 | https://mcmaster.com/91292A014 |
| M2.5x25mm SHCS | 6 | https://mcmaster.com/91292A036 |
| M2.5x20mm SHCS | 4 | https://mcmaster.com/91292A019 |
| M3x6mm Countersunk | 5 | https://mcmaster.com/92125A126 |
| M3x8mm Countersunk | 9 | https://mcmaster.com/92125A128 |
| 1:1 JST-SH Cable (50mm) | 3 | https://www.digikey.com/en/products/detail/adafruit-industries-llc/4210/10230021 |



## USB Hub
The USB Hub utilizes two [FE1.1S](https://www.digikey.ca/datasheets/production/1879844/1/FE1-1s-Datasheet.html) USB 2.0 HS Hub chips in series. It can deliver a total of 400mA downstream (the keyboard is assumed to use 100mA).

## Firmware

A QMK .bin file is provided for flashing, as well as QMK source files.

![Unsaver](https://github.com/nearestexit/mx-unsaver/blob/main/Pictures/Unsaver.JPG)

(The original Unsaver in this picture is not for sale.)