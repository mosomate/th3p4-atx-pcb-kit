# What is th3p4-atx-pcb-kit?
A pair of PCBs to make cable management better for TH3P4 Thunderbolt dock. If you have one of these dock, you might know how a nightmare the cable management could be.

![Assembled PCBs](https://raw.githubusercontent.com/mosomate/th3p4-atx-pcb-kit/main/docs/assembled.png)

This kit contains two PCBs. One is the **TH3P4-ATX-24P16S** (**24** pin **P**CB + **16** pin **S**traight connector). This turns the 24 pin connector on the motherboard 180 degrees backwards and reduces the number of wires between the PSU and the motherboard.

![Assembled 24P16S](https://raw.githubusercontent.com/mosomate/th3p4-atx-pcb-kit/main/docs/collage_24p16s.png)

The other is the **TH3P4-ATX-8P8S** (**8** pin **P**CB + **8** pin **S**traight connector). This one only turns back 180 degress the connector as the previous one.

![Assembled 8P8S](https://raw.githubusercontent.com/mosomate/th3p4-atx-pcb-kit/main/docs/collage_8p8s.png)

# Disclaimer
**I don't take any responsibilities for injuries and/or any damage caused by this design. Build at you own risk!**

# BOM

### For one **24P16S** adapter:
- 1 pc of **TH3P4-ATX-24P16S.kicad_pcb** PCB
- 1 pc of **24 pin female ATX connector for PCB** - [Special Mini Low Profile ATX Power GPU PCIE Connector for PCB Board](https://www.moddiy.com/products/Special-Mini-Low-Profile-ATX-Power-GPU-PCIE-Connector-for-PCB-Board.html) (select the *ATX 24-Pin* option)
- 1 pc of **16 pin straight male ATX connector** - [16 Pin PSU Modular Male Header Connector Straight Black](https://www.moddiy.com/products/16-Pin-PSU-Modular-Male-Header-Connector-Straight-Black.html)
- 1 pc of **16 pin female ATX connector** - [ATX CPU PCIE Power Supply Unit PSU Connectors 20 Types 4 Pin to 24 Pin](https://www.moddiy.com/products/ATX-CPU-PCIE-Power-Supply-Unit-PSU-Connectors-20-Types-4-Pin-to-24-Pin.html) (select the *16 Pin Black* option)
- 1 pc of **18 pin Corsair female ATX connector** - [PSU Modular Connector 18 Pin for Corsair](https://www.moddiy.com/products/PSU-Modular-Connector-18-Pin-for-Corsair.html)
- 1 pc of **10 pin Corsair female ATX connector** - [PSU Modular Connector 10 Pin for Corsair](https://www.moddiy.com/products/PSU-Modular-Connector-10-Pin-for-Corsair.html)

### For one **8P8S** adapter:
- 1 pc of **TH3P4-ATX-8P8S.kicad_pcb** PCB
- 1 pc of **8 pin female ATX connector for PCB** - [Special Mini Low Profile ATX Power GPU PCIE Connector for PCB Board](https://www.moddiy.com/products/Special-Mini-Low-Profile-ATX-Power-GPU-PCIE-Connector-for-PCB-Board.html) (select the *CPU/EPS 8-Pin* option)
- 1 pc of **8 pin straight male EPS connector** - [8 Pin CPU EPS Power Male Header Connector Straight Black](https://www.moddiy.com/products/8-Pin-CPU-EPS-Power-Male-Header-Connector-Straight-Black.html)
- 2 pcs of **8 pin female EPS connector** - [8 Pin Motherboard Power Female Connector with Pins Black](https://www.moddiy.com/products/8-Pin-Motherboard-Power-Female-Connector-with-Pins-Black.html)

### Wires
I used color coded **20 AWG UL1007** wires for power lanes *(+12V, +5V, +3.3V, -12V, Ground)* and **22 AWG UL1007** wires for signal lanes *(+5V stand-by, Power on, Power OK)*. Find them below:
- 20 AWG with colors **yellow**, **red**, **orange**, **blue** and **black** - [UL1007 Gauge Electrical Stranded Copper DIY Hook Up Wire Cable 20AWG](https://www.moddiy.com/products/UL1007-Gauge-Electrical-Stranded-Copper-DIY-Hook-Up-Wire-Cable-20AWG.html)
- 22 AWG with colors **purple**, **green** and **grey** - [UL1007 Gauge Electrical Stranded Copper DIY Hook Up Wire Cable (22AWG)](https://www.moddiy.com/products/UL1007-Gauge-Electrical-Stranded-Copper-DIY-Hook-Up-Wire-Cable-%2822AWG%29.html)

# Pin assignment and Wiring
For crimping the pins I used the **Engineer PA-09** plier. Here is the pin assignment:

![Assembled PCBs](https://raw.githubusercontent.com/mosomate/th3p4-atx-pcb-kit/main/docs/pinout.png)

And the crimped cables:

![Crimped cables](https://raw.githubusercontent.com/mosomate/th3p4-atx-pcb-kit/main/docs/crimped_cables.png)

# License
Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg