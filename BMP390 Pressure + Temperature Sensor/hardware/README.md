# BMP390 Pressure + Temperature Sensor

## Overview
The BMP390 is a high-precision barometric pressure and temperature sensor designed for altitude measurement, weather monitoring, and environmental sensing applications.

## Features
- **Pressure Range**: 300 hPa to 1250 hPa
- **Temperature Range**: -40°C to +85°C
- **High Accuracy**: ±0.5 hPa pressure, ±0.5°C temperature
- **I2C/SPI Interface**: Compatible with most microcontrollers
- **Low Power Consumption**: Ideal for battery-powered applications
- **Compact Package**: Small form factor for space-constrained designs

## Pinout
| Pin | Function |
|-----|----------|
| VDD | Power Supply (1.7V - 3.6V) |
| GND | Ground |
| SCL | I2C Clock / SPI Clock |
| SDA | I2C Data / SPI MOSI |
| SDO | I2C Address Select / SPI MISO |
| CSB | Chip Select (SPI) |

## Communication
- **I2C Address**: 0x76 (SDO to GND) or 0x77 (SDO to VDD)
- **SPI Speed**: Up to 10 MHz

## Getting Started
1. Connect the sensor to your microcontroller via I2C or SPI
2. Install the appropriate driver library
3. Initialize the sensor and configure sampling modes
4. Read pressure and temperature values

## Applications
- Altitude measurement
- Weather stations
- Drone altimetry
- IoT environmental monitoring
- Indoor navigation