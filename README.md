# CTS-SAT-1-OBC-PCB

This is the design repository for the onboard computer PCB and its supporting boards. The entire history of the design is kept private, but to release the designs, please use the hardware_design_releases repository, which is currently on version 1.2.0. You can check the tags for the revisions available, which are rev1.0 (not functional), rev1.1 (functional with PCB modification, short), and rev1.2 (TBD).

It is important to consider the outgassing characteristics of all wires used, so PTFE insulation has been chosen as the standard insulation material. The recommended part number is 5853 BK005, and the maximum recommended current is 1 amp per conductor.

If constructing Space Grade PCBs, use Rogers material as it has low outgassing properties. You can find the pinout stm32cubeIDE file in the pinout directory, which should be copied and moved to an external directory.

For more information, please contact James Chen for any questions or concerns at chen.james2015@gmail.com .

## Todo
- Change switch to https://datasheet.lcsc.com/lcsc/2102021636_Analog-Devices-HMC544AETR_C579555.pdf
- Add truth table for switch on schematic as text comment
- Check over MPI UART connections -> label it as what the device (comment it on the schematic), label it MISO/MOSI as microcontroller as Master, check all RX/TX like connections
- On the schematic, please add a comment next to J8 that says "Mates with EPS J7 VD3_OBC[1]"
- On the schematic, please add a comment next to J4 that says "Mates with EPS J10 VD3_OBC[0]"
- Add reset putton -> it'll go between the reset pin and ground, in parallel with a 100nF (0.1 uF) capacitor
- Change so that J10 pin 2 (MPI connector) is now a 12V MPI connector (so connect J10-Pin1 to J10-Pin2)
- Move boom deployment small components to be ontop
- Add LCSC Part # to every part
- Move all small passives ontop if possible
- Routing
- Some labelling on the stack header for ease, and all 2.5mm
- Please add a silkscreen label to J4 called "MPI Power In"
- IOC redo





