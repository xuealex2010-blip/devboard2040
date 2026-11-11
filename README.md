
# A custom devboard based on the RP2040
This is my very own design of a devboard, it is very similar to the Rasberry Pi Pico, I created it to learn more about microcontrollers, it is also my first design with a microcontroller.
<img width="1506" height="1562" alt="Screenshot_20261102_195927" src="https://github.com/user-attachments/assets/48447792-a7a7-4889-a603-0f6dbd262bec" />

## Overview
This devboard uses an RP2040, it exposes 28 total GPIO pins.

The devboard has 2 LEDs on it, a red one to signal the power connection, and a green one that can be controlled with GPIO 25.

It uses a USB-C connector instead off the Micro USB connector on the official one. And it has the necessary CC1 and CC2 resistors so it can be connected to a USB C port.

The external pins are also labeled, so that you don't always need to reference a pinout when working on projects.

Details with the source files can be previewed with KiCanvas: 

[https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2Fxuealex2010-blip%2Fdevboard2040%2Ftree%2Fmain%2FPCB](url)


<img width="1024" height="726" alt="1794408269729-741374ca-f85f-4f71-a0f6-448f25303ec1_1" src="https://github.com/user-attachments/assets/7b550711-7ff8-4905-9094-b674def1bfb9" />

### Fabrication
The files necessary to manufacture your own version of this board can be found in the production folder, it has all of the necessary files and more, formatted for JLC PCB.
If you use another vendor, you may need to use the source files from the PCB folder to create your own production files.
