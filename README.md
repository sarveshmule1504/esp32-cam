# Barebones ESP32-CAM


## Overview

When building a drone, space and weight are critical considerations. Most commercial ESP32-CAM modules feature a double-stacked design that complicates packaging and includes unnecessary features for aerial applications. This custom-designed board addresses these limitations with a compact, flat, single-stack PCB optimized for drone integration.

## Features

- **ESP32-WROOM-1U Module**
  - Native 8-bit camera interface
  - External antenna for extended range
  - Built-in USB flashing (eliminates USB-to-UART converter requirement)
- **40-Pin FPC Connector** for OV2640 camera module
  - Integrated 5V to 2.8V and 5V to 1.8V LDO regulators for camera power
- **USB-C Port** for programming and debugging
- **GPIO Expansion** - All GPIO pins exposed via headers
- **Flexible Power Options**
  - USB-powered or external 5V supply
  - Reverse current protection via Schottky diode

## Assembly

This board can be manufactured through JLCPCB with their PCB Assembly (PCBA) service. The bill of materials is provided below, and the complete PCBA BOM is available at [Output/JLC_BOM.xlsx](Output/JLC_BOM.xlsx).

**Note:** The ESP32-WROOM-1U module must be purchased and soldered separately, as it cannot be included in the standard JLCPCB PCBA service.


## Board Images

### Schematic

![Schematic](Images/Schematic.png)

### Top Layer (Signal / GND)

![Top PCB Layer](Images/Top%20Layer.png)

### Bottom Layer (Signal / GND)



## License

This ESP32-CAM is licensed under the MIT License. See the full license text in [LICENSE](LICENSE).


