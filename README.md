# Voron Tool Controller
A 3D printer controller board

Inspired by the possibility of Klipper 3D printer firmware (https://www.klipper3d.org/) that allows to have several I/O controller boards, Voron Tool Controller is a small board intended to be mounted on the moving print head assembly of a Voron 3D printer.

This reduces the cabling effort significantly as only power supply and CAN is needed.

PrintHeadController has the following features:
* Based on STM32 , so it is supported by the Klipper firmware out of the box
* TMC2209 on board for the extruder
* Supports the UART configuration of TMC driver
* 12 V and 24 V capable
* 2 Digital inputs
* 3 MOSFET outputs (e.g. hotend heater, fans)
* 1 Thermistor inputs
* BLTouch support
* Debug pins accessible
* Accelerometer ADXL245
* Don't Touch It connector (https://github.com/Richy42/DontTouchIt)

![](https://github.com/Richy42/votoco/assets/77325271/66683038-32b1-4f2c-ac21-8021638bf092)

![](https://github.com/Richy42/votoco/assets/77325271/6e57feab-d8fd-4907-b572-e4be047bbc6e)

![](https://github.com/Richy42/votoco/assets/77325271/181b58bb-cb74-4cc7-92c3-180138e30a95)

![](https://github.com/Richy42/votoco/assets/77325271/816ae06a-3e99-4f48-903c-83e1cf3d723f)

