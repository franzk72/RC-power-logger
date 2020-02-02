# RC power data logger - INA226

The following guide presents how to make a RC boat power current/voltage/power
monitor using an INA226 IC.

# Block scheme

![System block scheme](/resource/block-scheme.png)

# Hardware needed

1. Teensy 3.2 (or similar development board)
1. SD card adapter & SD card
1. INA226 adapter
1. 3.3V voltage regulator (for 3.3V Teensy 3.2)
1. Misc items (connectors, wires, etc.)

# INA226 adapter schematics

Below is the INA226 adapter schematics. The resistor R1 value must be selected based on expected current in the system.
Solder bridges SB1 and SB2 can be connected or left open to set the I2C device address.

![Schematics](/hw/power-data-logger-sch.png)

# Connection

# Example
