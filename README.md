# launch_chip
A model rocket launch control chip. A better push button?

## Datasheet
Semiconductors start out as an idea. Early datasheets allow exploration of the functionallity to meet the system need.
I've created a mock datasheet for a launch control chip, to both inspire and try to ground my design as a practical device with multiple applications.
Key functions and parameters set and documented. A compact module was defined which encompassed core functionallity centered around the device. Considering
multiple applications for this module firmed up the I/O to ease integration with clean schematics for each situation. A development board was then designed,
fully integration the LCC into a single board handheld lauch controller, and enabling chip development.

[Datasheet](Launch_chip_arch.pdf)

## Development Board PCB Design
Guided by the datasheet thought process the development board PCB was designed. The KiCad schematic and pcb have been developed and added to the repo.
The design will be revisioned until tapeout release. I'll use this board to bring up the LCC.

[KiCAD Project](dev_board.kicad_pro)

[KiCAD Schematic](dev_board.kicad_sch)

[KiCAD PCB](dev_board.kicad_pcb)

[Bill of Materials](dev_board.csv)



## Datasheet Snapshots

![features](lcc_ds_draft_1.png)

![application](lcc_ds_draft_2.png)

![performance](lcc_ds_draft_3.png)

![pinout](lcc_ds_draft_2b.png)

![package](lcc_ds_draft_4.png)

![evalboard](lcc_eb_draft_1.png)

![eb_1chan](lcc_eb_draft_2.png)

![eb_4chan](lcc_eb_draft_3.png)
