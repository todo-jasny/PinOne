# PinOne PCB Designs

This folder contains all PCB designs for the PinOne project, including schematics, board layouts, and exported Gerber files for manufacturing.

## Board Versions

| Version  | Description                                               | Size (mm) |
|----------|-----------------------------------------------------------|-----------|
| **V1.0** | Initial prototype. Major Routing Error; Unavilable        | UNKNOWN   |
| **V1.1** | Corrected version with proper USB-A wiring + labeling.    | 23.5x16.5 |
| **V2.0** | Added I2C pins, Uses USB-C, Smaller footprint             | 15.0x10.0 |

## Structure

Each version folder includes:
- `gerber/`: Exported Gerber files ready for fabrication.
- `BOM/`: Exported Bill of Matierals files.

## Notes
- All boards use the **ATtiny85** microcontroller.
- USB wiring follows proper D+ / D− configuration starting from V1.1.
- Copper layer includes branding + version for clarity and style.
- Silkscreen includes labels and "JLCJLCJLC".
- Designed for open hardware use — remix, improve, share.

## Manufacturing
Boards were designed for **JLCPCB** but are compatible with most standard PCB services. Dimensions and design rules are noted per version.

---
Licensed under [MIT or CERN-OHL].

