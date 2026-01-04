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
- [PicoLibSDK](https://github.com/Panda381/PicoLibSDK) - Alternative extended C/C++ SDK library for Raspberry Pico/Pico2 and RP2040/RP2350.
- [PicoMite](https://geoffg.net/picomite.html) - Complete operating system with a Microsoft BASIC compatible interpreter and extensive hardware support including touch sensitive LCD panels, SD Cards, WiFi/Internet etc.
- [pico-vscode](https://github.com/raspberrypi/pico-vscode) - The official VS Code extension for Raspberry Pi Pico development. It includes several features to simplify project creation and deployment.

### Libraries

- TFT/OLED
    + [TFT\_eSPI](https://github.com/Bodmer/TFT_eSPI) - Arduino and PlatformIO IDE compatible TFT library optimised for the Raspberry Pi Pico (RP2040), STM32, ESP8266 and ESP32.
    + [pico\_st7735\_80x160](https://github.com/elehobica/pico_st7735_80x160) - ST7735 (80x160) library for Raspberry Pi Pico / Pico 2.
    + [pico-ssd1306](https://github.com/Harbys/pico-ssd1306) - SSD1306 OLED Library for RP2040.
    + [displaylib\_1bit\_PICO](https://github.com/gavinlyonsrepo/displaylib_1bit_PICO) - Display Library for 1-bit color graphic displays for Raspberry PI PICO C++ SDK.

- LEDs
    + [displaylib\_LED\_PICO](https://github.com/gavinlyonsrepo/displaylib_LED_PICO) - A SDK C++ library for a Raspberry PI PICO device to support HT16K33, MAX7219, TM1637 & TM1638 LED segment modules.
    + [neopixel\_rp2040](https://github.com/shreyask21/neopixel_rp2040) - Micropython Neopixel (WS2812B) Library.
    + [NeoPixelConnect](https://github.com/MrYsLab/NeoPixelConnect) - A PIO based WS2812 NeoPixel library for the Arduino Nano RP2040 Connect, and Raspberry Pi Pico.
    + [pico-ws2812](https://github.com/PDBeal/pico-ws2812) - RP2040 library for controlling strips/pixels using WS2812 (NeoPixel) LEDs using PIO and the pico-sdk.

- Sound
    + [BackgroundAudio](https://github.com/earlephilhower/BackgroundAudio) - Arduino library for easy, interrupt driven speech, MP3, AAC, and WAV playback on the Raspberry Pi Pico RP2040, Pico 2 RP2350, and ESP32.
    + [microphone-library-for-pico](https://github.com/ArmDeveloperEcosystem/microphone-library-for-pico) - Capture audio from a microphone on your Raspberry Pi Pico or any RP2040 based board.
    + [pico\_spdif\_rx](https://github.com/elehobica/pico_spdif_rx) - S/PDIF receiver library.
    + [pico-fmSynth](https://github.com/nyh-workshop/pico-fmSynth) - Basic DX9-inspired FM synth Arduino Library for Raspberry Pico RP2040 and RP2350.
    + [RP2040-PWM-Tone](https://github.com/TuriSc/RP2040-PWM-Tone) - Tone generation library for Raspberry Pi Pico. Plays melodies and chirping sounds via PWM through a buzzer or speaker.

- I2S
    + [arduino-pico-i2s-audio](https://github.com/sfera-labs/arduino-pico-i2s-audio) - I2S digital audio input Arduino library.
    + [i2s\_32bit\_rp2040](https://github.com/timbk/i2s_32bit_rp2040) - An up to 32bit I2S library for the RP2040 using PIO.

- Sensors
    + [pico\_dht](https://github.com/vmilea/pico_dht) - DHT sensor library.
    + [RP2040\_CPU\_Temperature](https://github.com/DeimosHall/RP2040_CPU_Temperature) - Arduino library to read the temperature from the Raspberry Pi Pico's internal temperature sensor.

- I2C bus
    + [PCF8574\_micropython\_library](https://github.com/xreef/PCF8574_micropython_library) - MicroPython library for pcf8574 an i2c digital expander for Arduino, esp32, SMT32 and ESP8266. Can read write digital values with only 2 wire.
    + [PCF8574_library](https://github.com/xreef/PCF8574_library) - PCF8574 library. i2c digital expander for Arduino, Raspberry Pi Pico and rp2040 boards, esp32, SMT32 and ESP8266. Can read write digital values with only 2 wire.
    + [PCF8575\_library](https://github.com/xreef/PCF8575_library) - i2c 16bits digital expander with i2c digital expander for Arduino, Raspberry Pi Pico and rp2040 boards, esp32, SMT32 and ESP8266. Can read write digital values with only 2 wire.
    + [PCF8591\_library](https://github.com/xreef/PCF8591_library) - Library to use pcf8591 i2c analog IC with Arduino, Raspberry Pi Pico and rp2040 boards, esp32, SMT32 and ESP8266. Can read analog value and write analog value with only 2 wire.
    + [pico\_i2c\_slave](https://github.com/vmilea/pico_i2c_slave) - I2C slave library.
    + [i2cperipheral](https://github.com/adamgreen/i2cperipheral) - MicroPython I2C Peripheral Library.

- USB
    + [usb\_library\_rp2040](https://github.com/dgatf/usb_library_rp2040) - A fast and lightweight USB device library for RP2040.
    + [pico\_usb](https://github.com/wiredopposite/pico_usb) - A lightweight, fully customizable USB device stack for the Pi Pico, which can use the built in USB peripheral or PIO.
    + [picousb](https://github.com/shreeve/picousb) - A smaller than tiny USB Host library for the Raspberry Pi Pico/W.

- Radio
    + [pico\_si470x](https://github.com/vmilea/pico_si470x) - Si4702 / Si4703 FM radio library.
    + [pico\_rda5807](https://github.com/vmilea/pico_rda5807) - RDA5807 FM radio library.
    + [SerialIO](https://github.com/Witty-Wizard/SerialIO) - An Arduino library for decoding multiple RC protocols.

- Files and file systems
    + [pico\_fatfs](https://github.com/elehobica/pico_fatfs) - FatFs library for Raspberry Pi Pico / Pico 2 with SPI interface.
    + [FatFs](https://elm-chan.org/fsw/ff/) - FatFs documentation.
    + [LittleFS\_Mbed\_RP2040](https://github.com/khoih-prog/LittleFS_Mbed_RP2040) - Wrapper of LittleFS for Arduino MBED RP2040 boards. This library facilitates your usage of LittleFS for the onboard flash. LittleFS supports power fail safety and high performance.
    + [ESP32-targz](https://github.com/tobozo/ESP32-targz) - An Arduino library to compress/decompress tar, gz, and tar.gz files on ESP32, ESP8266 and RP2040.
    + [logging\_system\_embedded](https://github.com/wikilift/logging_system_embedded) - Light Logging Library for RP2040, ESP, ARDUINO.

- Motors
    + [PicoStepper](https://github.com/DasenB/PicoStepper) - A Library to drive stepper motors.
    + [pico\_stepper](https://github.com/beshrkayali/pico_stepper) - Stepper Library.
    + [pico-servo](https://github.com/irishpatrick/pico-servo) - A simple Raspberry Pi Pico library for controlling servos.
    + [RP2040PioServos](https://github.com/RadekVoltr/RP2040PioServos) - Servo library for up to 25 (32 is theoretical maximum) servos on Raspberry Pico.

- Video
    + [PicoDVI](https://github.com/Wren6991/PicoDVI) - Bitbanged DVI on the RP2040.
    + [pico-vgaDisplay](https://github.com/tvlad1234/pico-vgaDisplay) - VGA display driver library for RP2040 pico-sdk.
    + [rp2040-uvc](https://github.com/yjdwbj/rp2040-uvc) - USB video class (UVC) for Pico.
    + [hm01b0-library-for-pico](https://github.com/ArmDeveloperEcosystem/hm01b0-library-for-pico) - Capture monochrome images with a Himax HM01B0 based camera module.
    + [kilipili](https://github.com/Megatokio/kilipili) - Raspberry Pico C++ Library: VGA video, graphics, ANSI term, USB host, Audio, SDCard.
    + [DispHSTX](https://github.com/Panda381/DispHSTX) - DVI (HDMI) and VGA display driver for Pico2 RP2350, using HSTX peripheral.
    + [rpi-pico-graphics-lib](https://github.com/seanbutler/rpi-pico-graphics-lib) - C/C++ graphics library.

- Unsorted
    + [Joystick](https://github.com/benjaminaigner/Joystick) - Joystick Library for Arduino (RP2040 based boards).
    + [rp2040-psram](https://github.com/polpo/rp2040-psram) - A header-only C library to allow access to SPI PSRAM via PIO on the RP2040 microcontroller.
    + [lorawan-library-for-pico](https://github.com/ArmDeveloperEcosystem/lorawan-library-for-pico) - Enable LoRaWAN communications on your Raspberry Pi Pico or any RP2040 based board. 
    + [OneWireNg](https://github.com/pstolarz/OneWireNg) - 1-wire service library. OneWire compatible. Dallas thermometers support.
    + [pico-mcp2515](https://github.com/adamczykpiotr/pico-mcp2515) - MCP2515 CAN-Bus Interface Library.
    + [Raspberry-PICO2040-Flash-Storage](https://github.com/NegasonicX/Raspberry-PICO2040-Flash-Storage) - Library performs Flash Write, Read and Erase functions on Raspberry Pico 2040.
    + [Pico-74HC595](https://github.com/mucahitkurtlar/Pico-74HC595) - Shift register 74HC595 header library.
    + [EZ\_USB\_MIDI\_HOST](https://github.com/rppicomidi/EZ_USB_MIDI_HOST) - Add the Arduino MIDI Library API to the usb_midi_host TinyUSB MIDI Host driver.
    + [rp2040-pico-shift-register-74HC595](https://github.com/admantium-sg/rp2040-pico-shift-register-74HC595) - C Library for working with the 74HC595 shift register.
    + [ADS1x15\_PICO](https://github.com/gavinlyonsrepo/ADS1x15_PICO) - Library Driver for Analog to digital converters (ADC) ADS1015 and ADS1115 modules. RPI PICO RP2040 SDK C++.
    + [PicoSPI](https://github.com/MarkTillotson/PicoSPI) - Lightweight SPI library.
    + [RP2040-DMA](https://github.com/drtimcollins/RP2040-DMA) - Micropython library for the RP2040 DMA controller.
    + [pico-ds3231](https://github.com/alpertng02/pico-ds3231) - C library for DS3231 RTC module.


### Simulators

- [RP2040 PIO Simulator](https://github.com/soundpaint/rp2040pio) - Still in development, but promising PIO simulator. You upload a PIO program, and then can step-through the instructions. UI windows show which GPIO pins are active, or you can get a time-sequence of all pins.
- [rp2040](https://github.com/pyTony/rp2040) - Early Development Prototype, no release yet.
- [Pico Emu](https://github.com/Supercip971/pico-emu) - Early Development Prototype, no release yet.
- [rp2040js](https://github.com/wokwi/rp2040js) - Pico simulator in JavaScript, in active development, you can even see live coding video from the [project page](https://hackaday.io/project/177082-raspberry-pi-pico-emulator).

## Projects

### Emulators

- NES:
    + [PicoSystem\_InfoNes](https://github.com/fhoedemakers/PicoSystem_InfoNes) - PicoSystem_InfoNes a NES emulator for the Pimoroni PicoSystem RP2040 gaming handheld.
    + [pico-infonesPlus](https://github.com/fhoedemakers/pico-infonesPlus) - NES Emulator with SD card and menu support for the Raspberry PI Pico, Pico 2 and other RP2040/RP2350 based microcontrollers. Play your games from SD card on a HDMI display.


- ZX Spectrum:
    + [zx2040](https://github.com/antirez/zx2040) - ZX Spectrum emulator.
    + [Speccy\_P](https://github.com/billgilbert7000/Speccy_P) - ZX Spectrum Emulator on RP2040 OTG USB keyboard and USB mouse + PS/2 keyboard I2S sound, PSRAM 8Mb, HARD/Soft Turbosound.


- CHIP-8:
    + [pico-chip8](https://github.com/Y2K-x/pico-chip8) - CHIP-8 Emulator.
    + [RP2040TinyChip8](https://github.com/rpsubc8/RP2040TinyChip8) - Chip8 emulator.


- MURMULATOR project:
    + [MURMULATOR\_classical\_scheme](https://github.com/AlexEkb4ever/MURMULATOR_classical_scheme) - KiCAD project.
    + [frank](https://github.com/rh1tech/frank) - A hardware fork of the Murmulator project.
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
    + [RP2040-GB](https://github.com/deltabeard/RP2040-GB) - Game Boy emulation on the Raspberry Pi RP2040 microcontroller.
    + [picox86](https://github.com/mathijsvandenberg/picox86) - Running x86 on your Pico completely with a graphical GUI.
    + [MEMU Emulator](https://github.com/Memotech-Bill/MEMU) - Emulates the 8-bit Memotech MTX computer on your Pico.
    + [DECstation2040](https://github.com/rscott2049/DECstation2040) - DECstation emulator.
    + [Pico\_1140](https://github.com/Isysxp/Pico_1140) - A PDP11/40 emulator that will run Unix v5/6.
    + [pico-smsplus](https://github.com/fhoedemakers/pico-smsplus) - Sega Master System & Game Gear Emulator with SD card and menu support.
    + [picocalc-umac](https://github.com/benob/picocalc-umac) - A stratforward port of pico-umac, the Macintosh emulator for pico.
    + [rpi8080](https://github.com/erfan-khadem/rpi8080) - Intel 8080 emulator with debugger, physical & virtual IN/OUT port and interrupt.
    + [picozx81](https://github.com/ikjordan/picozx81) - ZX81 emulator.


### Instruments
- [scoppy](https://github.com/fhdm-dev/scoppy) - Use your Rasperry Pi Pico and Android Phone as an Oscilloscope and Logic Analyzer.
- [oscilloscope\_rp2040](https://github.com/dgatf/oscilloscope_rp2040) - Oscilloscope with OpenHantek protocol.
- [sigrok-pico](https://github.com/pico-coder/sigrok-pico) - rp2040 as a logic analyzer and oscilloscope with sigrok.
- [μLA: Micro Logic Analyzer](https://github.com/dotcypress/ula) - SUMP/OLS compatible logic analyzer firmware for RP2040 based boards.
- [Usb Sniffer Lite](https://github.com/ataradov/usb-sniffer-lite) - A simple USB sniffer based on a Raspberry Pi RP2040 that supports Low Speed and Full Speed modes.
- [RP2040-TestPatternGenerator](https://github.com/nmur/RP2040-TestPatternGenerator) - A simple test pattern generator.
- [pico-usb-blaster](https://github.com/thisiseth/pico-usb-blaster) - Altera USB-Blaster-compatible programmer.
- [xvc-pico](https://github.com/kholia/xvc-pico) - Raspberry Pico powered Xilinx Virtual Cable - Xilinx JTAG Cable.
- [RP2040-SWD-Programmer](https://github.com/Edith-Cowan-University-Racing/RP2040-SWD-Programmer) - SWD and UART Bridge.


### Computer/Console parts and add-ons
- [ISA-PicoMEM](https://github.com/FreddyVRetro/ISA-PicoMEM) - ISA PicoMEM Extension board (For 8086/8088 PC).
- [ZuluIDE™](https://github.com/ZuluIDE) - a family of IDE/ATAPI computer storage emulation devices, developed by Rabbit Hole Computing, the creators of ZuluSCSI. ISOs/image files are stored on a standard FAT32 or exFAT-formatted SD card.
- [PicoBoot](https://github.com/webhdx/PicoBoot) - Raspberry Pi Pico (RP2040) based IPL replacement modchip for GameCube.
- [Modxo\_RP2040\_Zero\_Adapter](https://github.com/m4x10187/Modxo_RP2040_Zero_Adapter) - RP2040-Zero adapter for Shalx's Modxo modchip for the Original Xbox.
- [ModXo-RP2040-Zero](https://github.com/Electrical5/ModXo-RP2040-Zero) - Adapter board for 'ModXo' and 'RP2040 Zero' / 'RP2040 Tiny'.
- [GP2040-CE](https://github.com/OpenStickCommunity/GP2040-CE) - Multi-Platform Gamepad Firmware for Raspberry Pi Pico and other RP2040 boards.
- [OGX-Mini](https://github.com/wiredopposite/OGX-Mini) - RP2040 & RP2350 USB gamepad emulation for multiple platforms.
- [ZX81\_USB\_KBD](https://github.com/ikjordan/ZX81_USB_KBD) - This CircuitPython code for the Raspberry Pi Pico 2040 allows a Sinclair ZX81 keyboard matrix to be used as the basis for a USB keyboard that can be used in Linux, MS Windows or for [picozx81](https://github.com/ikjordan/picozx81).
- [SIDKick-pico](https://github.com/frntc/SIDKick-pico) - An inexpensive dual-SID-replacement for the C64 and C128.
- [pico9918](https://github.com/visrealm/pico9918) - A replacement for the classic TMS9918A/TMS9929A VDP.
- [PicoROM](https://github.com/wickerwaka/PicoROM) - An RP2040-based ROM emulator.
- [BlueSCSI-v2](https://github.com/BlueSCSI/BlueSCSI-v2) - Open source, open hardware, SCSI emulator using the Pi Pico PR2040 and Pico 2 RP2350.
- [atarist-sidecart-raspberry-pico](https://github.com/sidecartridge/atarist-sidecart-raspberry-pico) - AtariST cartridge emulator based on Raspberry Pi Pico and RP2040.
- [atari-st-rpikb](https://github.com/trickydee/atari-st-rpikb) - Connect USB keyboard and mouse to Atari ST using a Raspberry PI emulating the HD6301 keyboard controller.


### Other
- [VGA Display](https://github.com/GregAC/pico-stuff/tree/main/pio_vga) - Running complex videogame graphics.
- [Pico Tone Generation](https://github.com/martinkooij/pi-pico-tone) - Low-Level library to output tone by composing sound signals (e.g. sine waves).
- [Pico Webserver](https://github.com/maxnet/pico-webserver) - Turn your Pico into an USB powered ethernet device running a web server.
- [SD Card Manager](https://github.com/carlk3/no-OS-FatFS-SD-SPI-RPi-Pico) - A complete program with a CLI interface to format, write and read to an attached SD card with the ExFAT filesystem format.
- [eurorack-cable-tester-pico](https://github.com/lucblender/eurorack-cable-tester-pico) - Simple eurorack (both 10 pins and 16 pins) cable tester. 