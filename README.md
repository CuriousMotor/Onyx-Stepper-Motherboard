# Onyx-Stepper-Motherboard

<p align="center">
<img src="https://raw.githubusercontent.com/CuriousMotor/Onyx-Stepper-Motherboard/main/Pictures/onyx_front_render.PNG" width="300" >
</p>
<p align="center">
<img src="https://raw.githubusercontent.com/CuriousMotor/Onyx-Stepper-Motherboard/main/Pictures/Onyx_prototype.jpg" width="300" >
</p>

The Arduino UNO + CNC shield has been the go-to setup for several CNC machines, robotic arms, drawing machines and what not! It's about time we replace the 8-bit microcontroller, with a powerful 32-bit, Wifi + BLE enabled ESP32!

**Bonus: It's 100% open source, including the PCB layout files!**

This project builds upon pioneering work done by GitHub user [Barton Dring](https://github.com/bdring).

## Features

1. Control upto 4 stepper motors
2. Supports all stepper drivers in STEP/DIR mode (A4988, DRV8825, TMC2208, TMC2209, TMC2130)
3. 5V PWM outputs x 3
4. Limit switch ports x 3 (X, Y and Z Axes)
5. 12/24V input power supply port
6. Wifi + BLE support (Thanks to GRBL_ESP32)
7. MicroSD card Support

## Firmware

Currently the firmware works superb with GRBL_ESP32. We are in the process of adding support for Marlin.

## Hardware

All of the hardware is designed in **KiCAD**. It's a 2 layer PCB the uses all standard components available at JLCPCB. Currently the board only supports stepper drives in STEP/DIR mode, v2 would support SPI and UART as well.

## Contributors

<a href="https://github.com/CuriousMotor/Onyx-Stepper-Motherboard/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=CuriousMotor/Onyx-Stepper-Motherboard" />
</a>

## Support and Sponsorship
We believe open source is the future, collaboration over competition. A lot of time and money goes into development and prototyping. If such projects make your work easier, consider '⭐-ing' the repository. (Yes, that's all it takes!)
