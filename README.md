# Golf Cart Wiring Harness

A KiCad project for designing a golf cart wiring harness with CAN bus communication and microcontroller integration.

## Project Overview

This project contains the complete KiCad design files for a golf cart wiring harness system that includes:

- Microcontroller-based control unit
- CAN bus communication interface
- Wire harness connector layouts
- PCB design for control electronics

## Files Structure

```
wire_harness/
├── wire_harness.kicad_pro     # Main project file
├── wire_harness.kicad_sch     # Main schematic
├── mcu-can.kicad_sch          # MCU and CAN interface schematic
├── wire_harness.kicad_pcb     # PCB layout
├── plots/                     # Generated gerber files and plots
└── wire_harness-backups/      # Automatic project backups
```

## Documentation

### Schematic
[View Schematic (PDF)](./schematic.pdf)

### PCB Layout
[View PCB Layout (PDF)](./pcb.pdf)

## Production

- **PCB Order Date**: June 29, 2025
- **Tag**: `production_order_062925`

## Generated Files

The `plots/` directory contains manufacturing files:
- Gerber files for PCB fabrication
- Drill files for hole placement
- Pick and place files
- Bill of materials

## KiCad Version

This project was created with KiCad 9.0.

## License

This project is open source hardware. Feel free to modify and use for your own golf cart projects.