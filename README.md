# USB-C Charger PCB — Altium Designer  
*(May 2025)*  

## Introduction  
This project delivers a **compact, two-layer portable-charger printed-circuit board** that accepts power through a USB-C connector, charges a single-cell Li-ion/Li-poly battery, and boosts the battery voltage to a regulated **5 V / 1.5 A** output.  
All schematic, library, and layout work was performed in **Altium Designer**, resulting in a fully rule-checked board prepared for fabrication.

---

## Project Overview  

| Stage | Summary |
|-------|---------|
| **Schematic Design** | Organized across two sheets: (1) a **Battery-Charger sheet** built around the MCP73831 for constant-current/constant-voltage charging from USB-C, and (2) a **Boost-Converter sheet** that employs the PAM2401 to step the battery voltage up to a stable 5 V output. |
| **Library Development** | Generated custom schematic symbols, IPC-7351 footprints, and 3-D STEP models for the MCP73831 and PAM2401 using Altium’s IPC Compliant Footprint Wizard, and integrated them into the project library. |
| **PCB Layout** | 2-layer FR-4 board (42 mm × 25 mm) with short, wide power paths, solid reference planes, and clear silkscreen markings to aid assembly and test. |
| **Design Verification** | Every net and component passed ERC, DRC, and 3-D clearance checks; power-integrity and thermal margins were validated against USB-C and Li-ion safety requirements. |

---

## Conclusion  
The USB-C Charger PCB demonstrates the complete Altium Designer workflow—from custom footprint creation through rule-driven layout and rigorous verification—while meeting the electrical, thermal, and mechanical demands of a portable power module. The project sharpened skills in mixed-signal design, USB-C power-path implementation, and IPC-compliant library generation, and the board is ready for prototype manufacture and validation.
