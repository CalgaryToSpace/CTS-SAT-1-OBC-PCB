# CalgaryToSpace-Hardware-Designs

This is the design repository for the onboard computer PCB and its supporting boards. The entire history of the design is kept private, but to release the designs, please use the hardware_design_releases repository, which is currently on version 1.2.0. You can check the tags for the revisions available, which are rev1.0 (not functional), rev1.1 (functional with PCB modification, short), and rev1.2 (TBD).

It is important to consider the outgassing characteristics of all wires used, so PTFE insulation has been chosen as the standard insulation material. The recommended part number is 5853 BK005, and the maximum recommended current is 1 amp per conductor.

If constructing Space Grade PCBs, use Rogers material as it has low outgassing properties. You can find the pinout stm32cubeIDE file in the pinout directory, which should be copied and moved to an external directory.

For more information, please contact James Chen for any questions or concerns at chen.james2015@gmail.com .

## Todo
1. Y1 routing
3. TCXO output is too low for MCU to recognize
5. Route flipped MPI traces R107 and R109
6. Repopulate parts
7. R68 routing
