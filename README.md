# rpitx-coax-pcb

Expansion board for Raspberry PI allowing to use coaxial SMA output instead of direct wire connection to GPIO to connect radio equipment (antennas, amplifiers, switches, etc.) when working with the [rpitx][2] package.

The PCB is installed by attaching to the GPIO of the Raspberry PI and can be additionally fixed by using the holes on the Raspberry PI and expansion board side.

## Current development progress:
[![Progress](https://img.shields.io/badge/rpitx--coax--pcb-not%20tested-red.svg?longCache=true&style=for-the-badge)](https://easyeda.com/IgrikXD/rpitx-coax-pcb)&nbsp;[![Progress](https://img.shields.io/badge/version-1.0-blue.svg?longCache=true&style=for-the-badge)](./EasyEDA)

## Implementations at EasyEDA platform:
- [rpitx-coax-pcb][1] ([Components list](./Components-list.md), [Usage guide](./Usage-guide.md))

## How to use this repository?
In [Datasheets](./Datasheets) and [Schematics](./Schematics) directories, you can find all necessary technical documentation for the used components and schematic files in PDF format. If you only need GERBER files, you can find them in the appropriate [Gerbers](./Gerbers) directory. In the [EasyEDA](./EasyEDA) directory, you can find a list of files for implementing the ready device (files can be imported into EasyEDA editor). Based on submitted files, you can order PCB from factory manufacturing make the device independently.

## Basic device characteristics:
**PCB versions:**
* **PCB_rpitx-coax-pcb-NOFILTER** - no filtering, only output to SMA connector
* **PCB_rpitx-coax-pcb-GP1212** - the radio path passes through a filter in the GP1212 case

**RF connector:** SMA  
**Feed line:** 50 Ohm coaxial cable  
**Used PCB Material:** FR-4  
**PCB thickness:** 1.6 mm  
**PCB copper weight:** 1 oz  

## Resources:
[rpitx project page at GitHub][2]  
Buy RLP-30+ Low pass filter: [Mini-Circuits RLP-30+][3]  

## How to contact me?
- E-mail: igor.nikolaevich.96@gmail.com
- Telegram: https://t.me/igrikxd
- LinkedIn: https://www.linkedin.com/in/igor-yatsevich/

  [1]: https://easyeda.com/IgrikXD/rpitx-coax-pcb
  [2]: https://github.com/F5OEO/rpitx
  [3]: https://www.minicircuits.com/WebStore/dashboard.html?model=RLP-30%2B
