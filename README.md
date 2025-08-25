# Awesome Pico

This repository maintains a collection of documentation, tutorials, tools, articles and more for the Raspberry Pico / Pico 2 microcontrollers.

## Documentation

- [Pico Datasheet](https://datasheets.raspberrypi.org/pico/pico-datasheet.pdf) - Compact hardware specification (mechanical and electrical specification, circuit board), 30 pages.
- [RP2040 Datasheet](https://datasheets.raspberrypi.org/rp2040/rp2040-datasheet.pdf) - In depth explanation of the RP2040 ARM Processor, everything from GPIO, DMA, ADC, to Peripherals and the Programmable Input/Output System, 642 pages.
- [RP2350 Datasheet](https://datasheets.raspberrypi.org/rp2350/rp2350-datasheet.pdf) - In depth explanation of the RP2350 ARM Processor, everything from GPIO, DMA, ADC, to Peripherals and the Programmable Input/Output System, 1380 pages.
- [Hardware design with RP2040](https://datasheets.raspberrypi.org/rp2040/hardware-design-with-rp2040.pdf) - Explains the RP2040 arm processor schematics and how to build additional hardware that incorporates this processor, 32 pages.
- [Getting started with Raspberry Pi Pico](https://datasheets.raspberrypi.org/pico/getting-started-with-pico.pdf) - Manual for installing Pico development toolchain on Linux, Mac OSX, and Windows, and how to setup the C SDK or MicroPython development environments, 77 pages.
- [C/C++ development](https://datasheets.raspberrypi.org/pico/raspberry-pi-pico-c-sdk.pdf) - In depth explanation of the C/C++ SDK, its architecture, the full library, examples and a guide to the PIO state machines, 281 pages.
- [MicroPython development](https://datasheets.raspberrypi.org/pico/raspberry-pi-pico-python-sdk.pdf) - Introduction to the MicroPython development environment, explains how to use the interactive interpreter, lists library functions, and shows the Thonny IDE, 47 pages.
- [Get Started with Micro Python Development](https://hackspace.raspberrypi.org/books/micropython-pico) - Handbook with step-by-step example to assemble and program Pico projects like a traffic light LED controller, temperature sensors, movements sensors and more, available as paid printed, or paid/free e-book, 139 pages.

## Tools

### SDK

- [pico-sdk](https://github.com/raspberrypi/pico-sdk) - Raspberry Pi Pico SDK.
- [arduino-pico](https://github.com/earlephilhower/arduino-pico) - Raspberry Pi Pico Arduino core, for all RP2040 and RP2350 boards.
- [MicroPython](https://micropython.org/download/?mcu=rp2040) - MicroPython downloads.
- [CircuitPython](https://circuitpython.org/board/raspberry_pi_pico/) - CircuitPython downloads.
- [rp-hal](https://github.com/rp-rs/rp-hal) - Rust support for the Raspberry Pi family of microcontrollers.

### Simulators

- [RP2040 PIO Simulator](https://github.com/soundpaint/rp2040pio) - Still in development, but promising PIO simulator. You upload a PIO program, and then can step-through the instructions. UI windows show which GPIO pins are active, or you can get a time-sequence of all pins.
- [rp2040](https://github.com/pyTony/rp2040) - Early Development Prototype, no release yet.
- [Pico Emu](https://github.com/Supercip971/pico-emu) - Early Development Prototype, no release yet.
- [rp2040js](https://github.com/wokwi/rp2040js) - Pico simulator in JavaScript, in active development, you can even see live coding video from the [project page](https://hackaday.io/project/177082-raspberry-pi-pico-emulator).

## Projects

### Emulators

- NES:
    + [PicoSystem_InfoNes](https://github.com/fhoedemakers/PicoSystem_InfoNes) - PicoSystem_InfoNes a NES emulator for the Pimoroni PicoSystem RP2040 gaming handheld.
    + [pico-infonesPlus](https://github.com/fhoedemakers/pico-infonesPlus) - NES Emulator with SD card and menu support for the Raspberry PI Pico, Pico 2 and other RP2040/RP2350 based microcontrollers. Play your games from SD card on a HDMI display.


- ZX Spectrum:
    + [zx2040](https://github.com/antirez/zx2040) - ZX Spectrum emulator.
    + [Speccy_P](https://github.com/billgilbert7000/Speccy_P) - ZX Spectrum Emulator on RP2040 OTG USB keyboard and USB mouse + PS/2 keyboard I2S sound, PSRAM 8Mb, HARD/Soft Turbosound.


- CHIP-8:
    + [pico-chip8](https://github.com/Y2K-x/pico-chip8) - CHIP-8 Emulator.
    + [RP2040TinyChip8](https://github.com/rpsubc8/RP2040TinyChip8) - Chip8 emulator.


- MURMULATOR project:
    + [MURMULATOR\_classical\_scheme](https://github.com/AlexEkb4ever/MURMULATOR_classical_scheme) - KiCAD project.
    + [Murmulator\_rp2040](https://github.com/MadedCat/Murmulator_rp2040) - ZX Spectum emulation on RP2040.
    + [pico-megadrive](https://github.com/xrip/pico-megadrive) - Sega Megadrive / Sega Genesis emulator for MURMULATOR devboard.
    + [pico-gameboy](https://github.com/xrip/pico-gameboy) - GameBoy Emulator for MURMULATOR devboard.
    + [pico-286](https://github.com/xrip/pico-286) - RP2040/RP2350 286 PC emulator for MURMULATOR dev board.
    + [pico-xt](https://github.com/xrip/pico-xt) - PC XT (8086/8088) Emulator for MURMULATOR devboard.
    + [pico-nes](https://github.com/xrip/pico-nes) - NES (Nintendo Entertainment System) / Dendy Emulator for MURMULATOR devboard.
    + [pico-sms](https://github.com/xrip/pico-sms) - Sega Master System / Game Gear for MURMULATOR devboard.
    + [pico-pce](https://github.com/xrip/pico-pce) - PC Engine / Turbografx 16 for MURMULATOR devboard.
    + [pico-lynx](https://github.com/xrip/pico-lynx) - Atari Lynx Emulator for MURMULATOR devboard.
    + [pico-wonderswan](https://github.com/xrip/pico-wonderswan) - Wonderswan Color emulator for MURMULATOR devboard.
    + [pico-gamate](https://github.com/xrip/pico-gamate) - Bit corp. Gamate emulator for Raspberry Pi Pico (RP2040) @ MURMULATOR devboard.
    + [pico-watara](https://github.com/xrip/pico-watara) - Raspberry Pi Pico Watara Supervision Emulator for MURMULATOR devboard.


- Other:
    + [picox86](https://github.com/mathijsvandenberg/picox86) - Running x86 on your Pico completely with a graphical GUI.
    + [MEMU Emulator](https://github.com/Memotech-Bill/MEMU) - Emulates the 8-bit Memotech MTX computer on your Pico.
    + [DECstation2040](https://github.com/rscott2049/DECstation2040) - DECstation emulator.
    + [Pico_1140](https://github.com/Isysxp/Pico_1140) - A PDP11/40 emulator that will run Unix v5/6.
    + [pico-smsplus](https://github.com/fhoedemakers/pico-smsplus) - Sega Master System & Game Gear Emulator with SD card and menu support.
    + [picocalc-umac](https://github.com/benob/picocalc-umac) - A stratforward port of pico-umac, the Macintosh emulator for pico.
    + [rpi8080](https://github.com/erfan-khadem/rpi8080) - Intel 8080 emulator with debugger, physical & virtual IN/OUT port and interrupt.


### Instruments
- [scoppy](https://github.com/fhdm-dev/scoppy) - Use your Rasperry Pi Pico and Android Phone as an Oscilloscope and Logic Analyzer.
- [oscilloscope_rp2040](https://github.com/dgatf/oscilloscope_rp2040) - Oscilloscope with OpenHantek protocol.
- [sigrok-pico](https://github.com/pico-coder/sigrok-pico) - rp2040 as a logic analyzer and oscilloscope with sigrok.
- [μLA: Micro Logic Analyzer](https://github.com/dotcypress/ula) - SUMP/OLS compatible logic analyzer firmware for RP2040 based boards.
- [Usb Sniffer Lite](https://github.com/ataradov/usb-sniffer-lite) - A simple USB sniffer based on a Raspberry Pi RP2040 that supports Low Speed and Full Speed modes.
- [RP2040-TestPatternGenerator](https://github.com/nmur/RP2040-TestPatternGenerator) - A simple test pattern generator.
- [pico-usb-blaster](https://github.com/thisiseth/pico-usb-blaster) - Altera USB-Blaster-compatible programmer.
- [xvc-pico](https://github.com/kholia/xvc-pico) - Raspberry Pico powered Xilinx Virtual Cable - Xilinx JTAG Cable.
- [RP2040-SWD-Programmer](https://github.com/Edith-Cowan-University-Racing/RP2040-SWD-Programmer) - SWD and UART Bridge.

### Other
- [VGA Display](https://github.com/GregAC/pico-stuff/tree/main/pio_vga) - Running complex videogame graphics.
- [Pico Tone Generation](https://github.com/martinkooij/pi-pico-tone) - Low-Level library to output tone by composing sound signals (e.g. sine waves).
- [Pico Webserver](https://github.com/maxnet/pico-webserver) - Turn your Pico into an USB powered ethernet device running a web server.
- [SD Card Manager](https://github.com/carlk3/no-OS-FatFS-SD-SPI-RPi-Pico) - A complete program with a CLI interface to format, write and read to an attached SD card with the ExFAT filesystem format.
