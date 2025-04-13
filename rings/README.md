

Collections of files I used to assemble my own clone of Mutable Instrument's Rings Eurorack module.

The main interest of this repository is the Eagle file outputs from the original schematic and pcb layout available at github.com/pichenettes/eurorack.


In the rings_eagle_output folder you will find the following files from the main board exported from Eagle :
- The gerbers and assembly files, located in the Assets folder.
- PNG renders of the front and back of the PCB.
- The original schematic in PDF format.
Please note that I made one change to the board, that is the removal of the ROHS logo because I use leaded solder for assembly.
Also note that any files relevant to automated SMT assembly are untested. I have only had the bare boards made at JLCPCB, the rest is untested.

In the rings_panel folder you will find the original rings.svg file kindly provided by Printable Instruments, as well as the Kicad 6 project where I imported said svg file before making a few personal changes to them.

In the root folder you will find the two zip files containing the gerbers for both the panel and the main board, as well as the BOM. The BOM has been taken from the pichenettes repository and I just added links to the parts available at my favorite distributor (TME), but also those sourced from Thonk (pots and jacks). The crystals, as well as the now discontinued DAC IC were not available at TME and should be sourced elsewhere.

This is distributed under the CC 3.0 BY SA licence. Credits go to Emilie Gillet for designing this awesome module and generously making the design open source, and Printable Instruments, for their elegant take on the Rings Panel.