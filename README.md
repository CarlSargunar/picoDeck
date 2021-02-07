picoDeck

A Crazy idea of Mine of using a Raspberry Pi Pico + a keyboard kit to make a basic streamdeck type utility. 

- Initially start with just macro keyboards which can be set-up with stream deck
- Hardware 
  - Pico : [https://www.raspberrypi.org/products/raspberry-pi-pico/](https://www.raspberrypi.org/products/raspberry-pi-pico/)
  - Keyboard : [https://shop.pimoroni.com/products/pico-rgb-keypad-base](https://shop.pimoroni.com/products/pico-rgb-keypad-base)
- Build to work with a basic main.py + a settings file


- Later versions can maybe do stuff with windows generally - eg 
  - Mute microphone (cough button)
  - Run windows explorer 
  - Open a terminal window
  - Any other ideas?







Lots of help from this video : [Getting started with C/C++ & MicroPython on Raspberry Pi Pico on Windows - NotEnoughTECH](https://www.youtube.com/watch?v=5l3W-brnO7E)

[Article](https://notenoughtech.com/featured/c-c-and-micropython-sdk-for-raspberry-pi-pico-on-windows/)


## Micropython

Instructions :

Assemble the Pico + Keyboard. You will need to solder the legs on if they don't already come soldered. Then set the pico up for Python using the instructions here : https://github.com/pimoroni/pimoroni-pico/blob/main/setting-up-micropython.md


References : 

Pimoroni Pico - https://github.com/pimoroni/pimoroni-pico







## C++

8.2.1. Installing the Toolchain

To build you will need to install some extra tools. Follow instructions in the SDK to get these set-up


- [ARM GCC compiler](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm/downloads)
  - When installing, choose the option to add the path to the compiler to the env variable
- [CMake](https://cmake.org/download/)
  - When installing, choose the option to add the path to the compiler to the env variable
- [Build Tools for Visual Studio 2019](https://visualstudio.microsoft.com/downloads/#build-tools-for-visual-studio-2019)
- [Python 3.7](https://www.python.org/downloads/windows/)
- Git