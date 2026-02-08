# BMP390 Pressure + Temperature Sensor

## Overview
The BMP390 is a high-precision barometric pressure and temperature sensor designed for altitude measurement, weather monitoring, and environmental sensing applications.

## Features
- **Low Power Consumption**: Ideal for battery-powered applications
- **Compact Package**: Small form factor for space-constrained designs

## Applications
- Altitude measurement
- Weather stations
- Drone altimetry
- IoT environmental monitoring

## Technical Specs

- Altitude Resolution: Can detect changes as small as 17cm.
- Pressure Range: 300 to 1250 hPa.
- Temperature Range: -40°C to +85°C.

- Communication:
-   I2C: SDI (Data) and SCK (Clock).
-   SPI: Full 4-wire support available.
-   Power: VDDIO and GND pins for flexible power management.

## Pinout Reference

| Label | Function |
| :--- | :--- |
| **POWER / VDDIO** | Main Power Supply. |
| **SDI / SDA** | I2C Data / SPI MOSI. |
| **SCK / SCL** | I2C Clock / SPI Clock. |
| **SDO** | I2C Address Select / SPI MISO. |
| **CSB** | Chip Select (Pull high for I2C). |
| **INT** | Data Ready Interrupt output. |
| **GND** | Ground. |
