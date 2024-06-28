# CTS-SAT-1-OBC-PCB

This is the design repository for the CTS-SAT-1 ("FrontierSat") onboard computer (OBC) PCB.

This OBC is host to an STM32 and several flash chips, and interfaces with all other electrical components on the 3U CubeSat.

## PCB Stackup

This PCB uses the JLCPCB `JLC0616H-2116A` stackup. It is a 6-layer, impedance-controlled PCB.

## Electrical Wire Comments

It is important to consider the outgassing characteristics of all wires used, so PTFE insulation has been chosen as the standard insulation material. The recommended part number is 5853 BK005, and the maximum recommended current is 1 amp per conductor.

If constructing Space Grade PCBs, use Rogers material as it has low outgassing properties.

## Repository Contents

* OBC PCB
* STM32CubeIDE Pinout/IOC configuration
* Unused early-stage umbilical connection board

## Contributors

* James Chen (contact chen.james2015@gmail.com with any questions)
* Others
