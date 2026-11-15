# JLCPCB EAGLE Library – Basic Parts

An EAGLE library containing JLCPCB Basic Parts with their corresponding LCSC part numbers. Includes a custom ULP script for easy BOM and CPL file generation.

## ⚠️ Project Discontinued – EAGLE Is Dead

**This project is no longer maintained.**

Autodesk EAGLE has reached the end of its life as a standalone product, and I have decided to discontinue further development of this library and its accompanying ULP script.

The project will remain available for archival purposes and for anyone still using EAGLE.

Thank you to everyone who found this project useful!

## About the Library

This was originally released as a beta version of the library and ULP script, covering a selection of commonly used components:

- SMD resistors in 0402, 0603, 0805, and 1206 packages
- SMD capacitors in 0402, 0603, 0805, and 1206 packages
- Basic SMD inductors
- Common diodes
- SOT-23 bipolar and MOSFET transistors
- SOIC-8 dual operational amplifiers

**Known limitation:** The original CSV catalog download link disappeared from the LCSC website, preventing further automated library updates.

## Installation and Usage

1. Copy `JLC PCB Basic Parts_loc.lbr` to your EAGLE `libraries` directory.
2. Copy `JLC PCB_SMTA_Exporter.ulp` to your EAGLE `ulps` directory.
3. Activate the library in the EAGLE Control Panel.
4. Create your schematic and PCB layout as usual.
5. Generate the Gerber files from the Board Editor using the green Factory icon.
6. Run `JLC PCB_SMTA_Exporter.ulp` from the Board Editor. Select your user scripts directory from the dropdown menu if necessary.
7. Upload the generated files to JLCPCB.

The ULP script was designed to generate BOM and CPL files compatible with JLCPCB's SMT assembly service, without requiring manual modifications.

---

**Project status: Discontinued / Archived**

No further updates, component additions, or bug fixes are planned.
