# Hardware Documentation

## PCB Design

### Design Tool
- **Software:** EAGLE
- **Layers:** 4-layer PCB
- **Dimensions:** 50mm x 45mm
- **Thickness:** 1.6mm

### Manufacturing

**Recommended Manufacturer:** JLCPCB

**Specifications:**
- Base Material: FR-4 TG 130-140
- Layers: 4
- PCB Thickness: 1.6mm
- Copper Weight: 1oz
- Surface Finish: HASL (Lead-Free) or ENIG
- Min Track/Spacing: 6/6 mil
- Min Hole Size: 0.3mm

**Cost Estimate:** ~$2 per board (5 boards + shipping)

### Assembly

See [../docs/assembly-guide.md](../docs/assembly-guide.md) for detailed instructions.

**Difficulty:** Intermediate
- SMD soldering required
- Hot air station recommended for QFN packages
- Can be hand-soldered with patience

### Main Components
- ESP32-C3-MINI-1
- BME688 environmental sensor
- TP4056 charging controller
- MAX17048 fuel gauge
- 18650 battery holder

### Bill of Materials

See [bom/basement-sensor-bom.csv](bom/basement-sensor-bom.csv)

**Total Cost per Unit:** ~$15-20 (excluding battery and tools)

### Schematic Overview

[Add schematic image or PDF link here]

### PCB Layout

[Add PCB render or layout image here]

## Design Files

### Eagle Project
- **Schematic:** `PHT_logger.sch`
- **Board:** `PHT_logger.brd` *(if applicable)*
- **Design Tool:** Autodesk Eagle

### Opening Files

1. Download and install [Autodesk Eagle](https://www.autodesk.com/products/eagle)
2. Open the schematic: `File → Open → PHT_logger.sch`
3. Open the board: `File → Open → PHT_logger.brd`

## Version History

### v1.0 (Current)
- Initial release
- TP4056 charging circuit
- ESP32-C3-MINI-1 module
- BME688 sensor
- MAX17048 fuel gauge