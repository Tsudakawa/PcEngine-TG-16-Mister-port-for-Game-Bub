# GameBub TurboGrafx-16 / PC Engine Core

An FPGA core for playing **TurboGrafx-16 / PC Engine games** on the GameBub Rev4 handheld.

## Overview

This project ports the TurboGrafx-16 / PC Engine core, originally developed for MiSTer, to the GameBub Rev4 FPGA handheld.

The goal is to bring classic 8-bit and 16-bit-era PC Engine gaming to the GameBub platform.

## Features

- TurboGrafx-16 / PC Engine hardware core
- Targeted at the GameBub Rev4 FPGA handheld
- Based on the MiSTer core
- Source code and configuration files for the GameBub platform

## Repository Contents

- `source/` contains the core source code and supporting build files.
- `SDcard/` contains core configuration and metadata files intended for the GameBub SD card structure.
- `README.md` provides an overview of the project.
- License files are included in the repository.

## Building

Building the core requires the appropriate GameBub FPGA development environment and compatible toolchain. Refer to the repository's build scripts and configuration files for the relevant settings.

Build instructions and toolchain compatibility may need further refinement.

## AI Assistance

AI tools were used to assist with code development, modifications, troubleshooting, and repository preparation. The project is maintained as a GameBub-focused port of the existing TurboGrafx-16 / PC Engine core.

## Credits

**MiSTer project and core contributors** for the original TurboGrafx-16 / PC Engine implementation.
Gregory Estrade: Original FPGAPCE core.
Sorgelig: MiSTer port, including Arcade Card support, memory support, mappers, and other modifications.
srg320: Additional improvements and CD support.
greyrogue: Additional bug fixes.
Kitrinx: Color palettes and audio filters.
dshadoff: Further refinements and ongoing maintenance


**GameBub project** for the target handheld platform.

Special Thanks
Florin-Byte
Hiroyuki T
Eli 
& Game Bub community

Please retain the original license notices and comply with the applicable licenses when using or modifying this code.

## License

See the license files included in this repository for the applicable licensing terms.
