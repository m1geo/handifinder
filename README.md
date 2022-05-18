# Handi-Finder
This repository is a KiCad 5.1 design of the published Handi-Finder DF project. 

The Handi-Finder Project is a radio direction finder, which connectso to an existing radio receiver such as a hand-held radio, and adds some direction finding capabiltiy to it.

The device works by switching between the two wire antennas mounted on H1 and H2 on the PCB. When the two antennas are directly lined towards the source of transmission, the arriving signal is in phase between both antennas. When the Handi-Finder is held non-squarely toward the signal source, the phase difference between the two wire antennas causes the switching frequency (here, approximately 1 kHz) to be audiable with loudness proportional to phase difference.

There are many resources online for this project, with some links here:
- [May 1993 QST Article by Bob K8DTS](https://www.ve5nn.ca/images/FoxHunt/handi-finder.pdf)
- [The HANDI-Finder](https://www.handi-finder.com/)

The [outputs](https://github.com/m1geo/handifinder/tree/main/Outputs) folder contains the Gerber files which can be zipped up and sent for manufacture at your chosen board-house.

## 3D View

![3D View](https://raw.githubusercontent.com/m1geo/handifinder/main/Outputs/3d_render.png "3D View")

## Schematic

![Schematic](https://raw.githubusercontent.com/m1geo/handifinder/main/Outputs/schematic.png "Schematic")

