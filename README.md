# Voron Tool Controller
A 3D printer controller board

Inspired by the possibility of Klipper 3D printer firmware (https://www.klipper3d.org/) that allows to have several I/O controller boards, Voron Tool Controller is a small board intended to be mounted on the moving print head assembly of a Voron 3D printer.

This reduces the cabling effort significantly as only power supply and CAN is needed.

PrintHeadController has the following features:
* Based on STM32 , so it is supported by the Klipper firmware out of the box
* TMC2209 on board for the extruder
* Supports the UART configuration of TMC driver
* 12 V and 24 V capable
* 3 Digital inputs
* 3 MOSFET outputs (e.g. hotend heater, fans)
* 1 Thermistor inputs
* BLTouch support
* Debug pins accessible
* Accelerometer ADXL245
