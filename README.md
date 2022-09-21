# CANpaca-EB
This is the extruder board from the CANpaca printer board family.

## Features
 - CAN input (with 7.5A@24V) input
 - 1 extrudder stepper (via tmc2130 with SPI control)
 - 2 PWM fans
 - support for klicky probe / bltouch
 - 1 hotend
 - 1 regular thermistor
 - 1 thermistor via MAX31865
 - ADXL345 Accererometer
 - runout sensor
 - RGB lighting

## Changelog

### V0.2
 - changed caps from 0603 to 0402
 - changed resistors from 0603 to 0402
 - decoupling caps are now properly placed close to power pins
 - added thermal vias below rp2040

### V0.1
 - initial release
