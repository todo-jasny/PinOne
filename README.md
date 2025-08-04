# PinOne — Open Source Microcontroller Platform

PinOne is a compact, minimalist, and open-source family of microcontroller boards designed for creative, educational, and experimental electronics projects. Developed with simplicity, versatility, and approachability in mind, PinOne aims to make small microcontroller use and prototyping accessible — whether you're building for yourself, gifting, or simply learning. It also offers to challenge users and creators through overcomming hurderls that have never been jumped.

## Project Goals
- Provide small, easy-to-use, and hackable boards.
- Encourage personal use, customization, and open-source collaboration.
- Enable straightforward programming with tools like Arduino IDE.
- Explore unique hardware forms (USB, SD card, and more).

## Current Focus
- **PinOne Base (P1)**: Core USB-based microcontroller board.
  - Versions: V1.0 (Unavilable), V1.1 (corrected), V2.0 (smaller + USB-C + more pins).
  - Based on the ATtiny85 microcontroller. 

## Planned Builds
- Future PinOne Base versions
- PinOne Micro SD
  - Build that uses micro sd slot for porgramming. 

## Repository Structure
- `pcb/` – Board designs, schematics, and Gerber files (V1.0–V2.0).
- `firmware/` – Example code for PinOne (e.g., LED blink, I/O tests). (to be added)
- `README.md` – This overview file.

---

# PinOne Naming Scheme

PinOne is the name of the overall microcontroller project, shortened to **P1** for naming and versioning purposes. The following naming scheme helps organize versions and specialized boards consistently.

## Structure
- **Base Name**: `PinOne` → **P1**
- **Versioning**: Follows `x.x` format (e.g., Version 1.1 → **11**)
- **Specialization**: Descriptive suffixes for functional variants, based on widely recognized naming standards.

---

## Examples
| Full Name                   | Shortened Name |
|----------------------------|----------------|
| PinOne Version 1.1         | P111           |
| PinOne Micro SD 1.0        | P110SD         |
| PinOne Power Board 2.0     | P120PWR        |
| PinOne Sensor Variant 1.2  | P112SEN        |

---

## Common Suffixes

| **Suffix**   | **Use Case**                              |
|--------------|-------------------------------------------|
| `SD`         | MicroSD-programmable version              |
| `PWR`        | Power-only board / supply module          |
| `AMP`        | Audio amp module                          |
| `ROM`        | I2C Flash or EEPROM expansion             |
| `W`          | Wireless (WiFi, Bluetooth, etc.)          |
| `LED`        | LED driver or controller                  |
| `SEN`        | Any kind of sensor expansion board        |
| `BAT`        | Battery-powered variant                   |

---

## Notes for Contributors
- If you're creating a new variant, use **existing suffixes** where possible.
- For new specializations, propose a clear suffix via GitHub Issues or Pull Request.
- Keep names short, intuitive, and aligned with common hardware naming practices.


## Status
PinOne is actively being developed. Contributions, feedback, and forks are welcome — this is a personal learning and community-building project.

## Why PinOne?
As a student-driven idea, PinOne blends learning and real-world prototyping. These boards are meant to be shared, modified, and enjoyed — with no expectation to sell or profit from them.

## Learn More
Project by Anthony Albright.  
See more updates at AlbriByte.surge.sh and here on GitHub.
