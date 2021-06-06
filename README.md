# UBMP4.1

UBMP4.1 (USB-Based Beginner Multipurpose Project 4 rev. 1) KiCad schematic and PCB design files.

![UBMP4 1-top-black](https://user-images.githubusercontent.com/4099144/120913301-14a02180-c664-11eb-8325-3a5cc9fb6abf.png)

UBMP4.1 is a development board for learning or teaching PICmicro programming in C using almost any device – including Chromebooks!

## UBMP4.1 Hardware Features

- Microchip PIC16F1459 USB-capable microcontroller with 8k words of program FLASH (6k words free when using the USB bootloader), 128B of user FLASH, 1kB of RAM, 10-bit ADC, and a built-in temperature sensor
- 5 built-in pushbuttons
- 5 visible light LEDs
- 1 piezo beeper output
- optional 8-pin header for PORTC I/O pin expansion (great for servos, a SONAR module, NeoPixels, an LCD, etc.)
- optional IR LED output for remote control transmitter applications (or a high-current transistor-driven output)
- optional IR demodulator for remote control decoding
- optional IR phototransistor or visible-light ambient light sensor for light sensing
- USB 2.0 type-C port for power and programming
- 6-pin ICSP (In-Circuit Serial Programming) header for PICkit-4

## UBMP4.1 Software Features

UBMP4.1 uses the [USB uC](https://github.com/johnnydrazzi/USB-uC) bootloader, which makes UBMP4.1 appear as a USB mass storage device. Programs can be developed in C or assembly code using Microchip Technology's MPLAB X IDE or the MPLAB Xpress web-based IDE, or in any programming language or software that creates a Microchip-compatible .hex output file.

Just plug UBMP4.1 into a USB port, wait for it to appear on your computer as drive ***PIC16F1459***, and drag your compiled .hex file onto the drive. UMBP4.1 starts running your program as soon as the .hex file is transferred.

## UMBP4.1 is Open

UBMP4.1 is open hardware and uses open source software. The following permissions and conditions apply to UBMP4.1:
- the KiCad UBMP4.1 files stored in GitHub are open hardware licensed under the terms of the MIT license (except the mirobo.tech logo - see below)
- UBMP4.1 programs stored in GitHub are open source software licensed under the terms of the MIT license
- UMBP4.1 learning materials on the mirobo.tech website are licensed under the terms of the Creative Commons CC-BY 4.0 license
- the USB uC bootloader is open source and licensed under the terms of the GPL3.0 license by John Izzard
- the mirobo.tech logo mark is a trademark of mirobo Technolgy and may not be used without prior permission

## Where can I buy UBMP4.1?

UBMP4.1 boards and kits are available at [mirobo.tech](https://mirobo.tech/ubmp4).  
Bare UBMP4.1 printed circuit boards are also available from [OSHPARK](https://oshpark.com/shared_projects/b04AabPV).
