# Fork of Marlin for the Two Trees Sapphire Plus 3D printer

LCD Scaler code used from this blog post:  https://escope.de/posts/sapphire-pro-marlin/

Bits and pieces borrowed from the MKS Marlin 2.0 repo: https://github.com/makerbase-mks/Mks-Robin-Nano-Marlin2.0-Firmware

Current configuration assumes that the TMC2208 drivers are connected to the 2:nd extruder steppers ENABLE, STEP and DIR pins modded to use UART in one-wire-mode per driver with custom cables soldered with a 1K resitor on the TX line.

# Marlin 3D Printer Firmware

![GitHub](https://img.shields.io/github/license/marlinfirmware/marlin.svg)
![GitHub contributors](https://img.shields.io/github/contributors/marlinfirmware/marlin.svg)
![GitHub Release Date](https://img.shields.io/github/release-date/marlinfirmware/marlin.svg)
[![Build Status](https://github.com/MarlinFirmware/Marlin/workflows/CI/badge.svg?branch=bugfix-2.0.x)](https://github.com/MarlinFirmware/Marlin/actions)

<img align="right" width=175 src="buildroot/share/pixmaps/logo/marlin-250.png" />

Additional documentation can be found at the [Marlin Home Page](http://marlinfw.org/).
Please let us know if Marlin misbehaves in any way. Volunteers are standing by!

