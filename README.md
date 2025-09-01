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

### Libraries

- [TFT_eSPI](https://github.com/Bodmer/TFT_eSPI) - Arduino and PlatformIO IDE compatible TFT library optimised for the Raspberry Pi Pico (RP2040), STM32, ESP8266 and ESP32.
- [BackgroundAudio](https://github.com/earlephilhower/BackgroundAudio) - Arduino library for easy, interrupt driven speech, MP3, AAC, and WAV playback on the Raspberry Pi Pico RP2040, Pico 2 RP2350, and ESP32.
- [microphone-library-for-pico](https://github.com/ArmDeveloperEcosystem/microphone-library-for-pico) - Capture audio from a microphone on your Raspberry Pi Pico or any RP2040 based board.
- [Joystick](https://github.com/benjaminaigner/Joystick) - Joystick Library for Arduino (RP2040 based boards).
- [pico_dht](https://github.com/vmilea/pico_dht) - DHT sensor library.
- [pico_rda5807](https://github.com/vmilea/pico_rda5807) - RDA5807 FM radio library.
- [PCF8574_library](https://github.com/xreef/PCF8574_library) - PCF8574 library. i2c digital expander for Arduino, Raspberry Pi Pico and rp2040 boards, esp32, SMT32 and ESP8266. Can read write digital values with only 2 wire.
- [PCF8575_library](https://github.com/xreef/PCF8575_library) - i2c 16bits digital expander with i2c digital expander for Arduino, Raspberry Pi Pico and rp2040 boards, esp32, SMT32 and ESP8266. Can read write digital values with only 2 wire.
- [PCF8591_library](https://github.com/xreef/PCF8591_library) - Library to use pcf8591 i2c analog IC with Arduino, Raspberry Pi Pico and rp2040 boards, esp32, SMT32 and ESP8266. Can read analog value and write analog value with only 2 wire.
- [rp2040-psram](https://github.com/polpo/rp2040-psram) - A header-only C library to allow access to SPI PSRAM via PIO on the RP2040 microcontroller.
- [lorawan-library-for-pico](https://github.com/ArmDeveloperEcosystem/lorawan-library-for-pico) - Enable LoRaWAN communications on your Raspberry Pi Pico or any RP2040 based board. 
- [pico-ssd1306](https://github.com/Harbys/pico-ssd1306) - SSD1306 OLED Library for RP2040.
- [ESP32-targz](https://github.com/tobozo/ESP32-targz) - An Arduino library to compress/decompress tar, gz, and tar.gz files on ESP32, ESP8266 and RP2040.
- [pico_i2c_slave](https://github.com/vmilea/pico_i2c_slave) - I2C slave library.
- [OneWireNg](https://github.com/pstolarz/OneWireNg) - 1-wire service library. OneWire compatible. Dallas thermometers support.
- [pico_spdif_rx](https://github.com/elehobica/pico_spdif_rx) - S/PDIF receiver library.
- [pico-mcp2515](https://github.com/adamczykpiotr/pico-mcp2515) - MCP2515 CAN-Bus Interface Library.
- [pico_fatfs](https://github.com/elehobica/pico_fatfs) - FatFs library for Raspberry Pi Pico / Pico 2 with SPI interface.
- [pico-fmSynth](https://github.com/nyh-workshop/pico-fmSynth) - Basic DX9-inspired FM synth Arduino Library for Raspberry Pico RP2040 and RP2350.
- [NeoPixelConnect](https://github.com/MrYsLab/NeoPixelConnect) - A PIO based WS2812 NeoPixel library for the Arduino Nano RP2040 Connect, and Raspberry Pi Pico.
- [Raspberry-PICO2040-Flash-Storage](https://github.com/NegasonicX/Raspberry-PICO2040-Flash-Storage) - Library performs Flash Write, Read and Erase functions on Raspberry Pico 2040.
- [displaylib_1bit_PICO](https://github.com/gavinlyonsrepo/displaylib_1bit_PICO) - Display Library for 1-bit color graphic displays for Raspberry PI PICO C++ SDK.
- [LittleFS_Mbed_RP2040](https://github.com/khoih-prog/LittleFS_Mbed_RP2040) - Wrapper of LittleFS for Arduino MBED RP2040 boards. This library facilitates your usage of LittleFS for the onboard flash. LittleFS supports power fail safety and high performance.
- [PicoStepper](https://github.com/DasenB/PicoStepper) - A Library to drive stepper motors.
- [pico-servo](https://github.com/irishpatrick/pico-servo) - A simple Raspberry Pi Pico library for controlling servos.
- [neopixel_rp2040](https://github.com/shreyask21/neopixel_rp2040) - Micropython Neopixel (WS2812B) Library.
- [Pico-74HC595](https://github.com/mucahitkurtlar/Pico-74HC595) - Shift register 74HC595 header library.
- [i2cperipheral](https://github.com/adamgreen/i2cperipheral) - MicroPython I2C Peripheral Library.
- [hm01b0-library-for-pico](https://github.com/ArmDeveloperEcosystem/hm01b0-library-for-pico) - Capture monochrome images with a Himax HM01B0 based camera module.
- [rp2040-uvc](https://github.com/yjdwbj/rp2040-uvc) - USB video class (UVC) for Pico.
- [EZ_USB_MIDI_HOST](https://github.com/rppicomidi/EZ_USB_MIDI_HOST) - Add the Arduino MIDI Library API to the usb_midi_host TinyUSB MIDI Host driver.
- [pico_stepper](https://github.com/beshrkayali/pico_stepper) - Stepper Library.
- [RP2040-PWM-Tone](https://github.com/TuriSc/RP2040-PWM-Tone) - Tone generation library for Raspberry Pi Pico. Plays melodies and chirping sounds via PWM through a buzzer or speaker.
- [rp2040-pico-shift-register-74HC595](https://github.com/admantium-sg/rp2040-pico-shift-register-74HC595) - C Library for working with the 74HC595 shift register.
- [pico-vgaDisplay](https://github.com/tvlad1234/pico-vgaDisplay) - VGA display driver library for RP2040 pico-sdk.
- [arduino-pico-i2s-audio](https://github.com/sfera-labs/arduino-pico-i2s-audio) - I2S digital audio input Arduino library.
- [SerialIO](https://github.com/Witty-Wizard/SerialIO) - An Arduino library for decoding multiple RC protocols.
- [pico_st7735_80x160](https://github.com/elehobica/pico_st7735_80x160) - ST7735 (80x160) library for Raspberry Pi Pico / Pico 2.
- [pico_si470x](https://github.com/vmilea/pico_si470x) - Si4702 / Si4703 FM radio library.
- [ADS1x15_PICO](https://github.com/gavinlyonsrepo/ADS1x15_PICO) - Library Driver for Analog to digital converters (ADC) ADS1015 and ADS1115 modules. RPI PICO RP2040 SDK C++.
- [PicoSPI](https://github.com/MarkTillotson/PicoSPI) - Lightweight SPI library.
- [rpi-pico-graphics-lib](https://github.com/seanbutler/rpi-pico-graphics-lib) - C/C++ graphics library.
- [displaylib_LED_PICO](https://github.com/gavinlyonsrepo/displaylib_LED_PICO) - A SDK C++ library for a Raspberry PI PICO device to support HT16K33, MAX7219, TM1637 & TM1638 LED segment modules.
- [RP2040-DMA](https://github.com/drtimcollins/RP2040-DMA) - Micropython library for the RP2040 DMA controller.
- [RP2040_CPU_Temperature](https://github.com/DeimosHall/RP2040_CPU_Temperature) - Arduino library to read the temperature from the Raspberry Pi Pico's internal temperature sensor.
- [i2s_32bit_rp2040](https://github.com/timbk/i2s_32bit_rp2040) - An up to 32bit I2S library for the RP2040 using PIO.
- [pico-ds3231](https://github.com/alpertng02/pico-ds3231) - C library for DS3231 RTC module.
- [usb_library_rp2040](https://github.com/dgatf/usb_library_rp2040) - A fast and lightweight USB device library for RP2040.
- [RP2040PioServos](https://github.com/RadekVoltr/RP2040PioServos) - Servo library for up to 25 (32 is theoretical maximum) servos on Raspberry Pico.
- [logging_system_embedded](https://github.com/wikilift/logging_system_embedded) - Light Logging Library for Embedded Systems RP2040 , ESP, ARDUINO.
- [PCF8574_micropython_library](https://github.com/xreef/PCF8574_micropython_library) - MicroPython library for pcf8574 an i2c digital expander for Arduino, esp32, SMT32 and ESP8266. Can read write digital values with only 2 wire.
- [pico-ws2812](https://github.com/PDBeal/pico-ws2812) - RP2040 library for controlling strips/pixels using WS2812 (NeoPixel) LEDs using PIO and the pico-sdk.
- [kilipili](https://github.com/Megatokio/kilipili) - Raspberry Pico C++ Library: VGA video, graphics, ANSI term, USB host, Audio, SDCard.

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
