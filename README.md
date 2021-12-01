# JLC PCB Basic Parts.lbr
## Eagle Library with the JLC PCB Basic Parts and their corresponding LCSC Part Numbers. A special ULP script is included for the easiest BOM and CPL export ever!

This is a BETA release of the library and the ULP. So far, there is a selection of the very basic components. The library contains:
- All SMD resistors of 0402, 0603, 0805, 1206 sizes
- All SMD capacitors of 0402, 0603, 0805, 1206 sizes
- Basic SMD Inductors
- Basic diodes
- SOT-23 PNPs, NPNs, MOSFETs.
- SOIC-8 Dual Op-Amps

The device list should grow by time. Please report any issues. Thank you.

---
How to use:

Place the `JLC PCB Basic Parts_loc.lbr` into your homedir/libraries

Place the `JLC PCB_SMTA_Exporter.ulp` into your homedir/ulps

Activate the library from the Eagle's Control Panel

Now create your schematics

When ready, generate gerber files from the Board Editor by pressing the greenish Factory icon

Execute the `JLC PCB_SMTA_Exporter.ulp` (again, from the board editor. Don't forget to choose the correct location from the dropdown list)

Go to JLCPCB.com and upload your files. You don't have to modify anything.
