
# Open Rectangle Template
**RP2040 template for use with box style controllers for the GC - CURRENTLY UNTESTED**

<p align="center">
  <img src="https://github.com/Armastardo/OpenRectangleTemplate/blob/main/Pictures/KicadRender.png?raw=true" />
</p>

## Table of contents
* [About](#about)
* [Usage](#usage)
* [To-do](#to-do)
* [Acknowledgements](#acknowledgements)

## About
This template was created for the purpose of easing development of box-styled controllers (rectangles) that work with a GameCube console and Nintendo 64 via a USB C to console cable. It uses a RP2040 as its main controller so compatibility to other devices will be limited to the firmware you are using. (Such as [HayBox](https://github.com/JonnyHaystack/HayBox), [Pico-Rectangle](https://github.com/JulienBernard3383279/pico-rectangle), etc). There's already a footprint added for a compatible USB-C port that will allow you to used said cables, as well as a USB C to C cable, or C to A cable for PC or Switch.

## Usage
This templates requires for you to have a minium experience with Kicad and some EE basics. You can just download it as *.zip and start creating your own. Make sure you are using **Kicad 7**. The most finicky part of the template is 
### Changes from the Raspberry Pi Pico
~~This template is not 1:1 with the Raspberry Pi Pico, so you will need to change some of the default pins in order to this to work. For example:~~
~~- VBUS sensing on the pico is GPIO24, while the template has it on GPIO28.~~
~~- PICO_LED is on GPIO25 on pico, while the template has it on GPIO27.~~
~~- Default pinout for GC has the data pin , template has it on GPIO29.~~

~~All of these changes can be seen (an edited!) in the schematic and the pcb. This was made only for convenience with the wiring. *You should recompile the firmware you're planning on use to accomodate for these changes.*~~
Reverted back to original Pico wiring! Thanks for the feedback!

## To-do:
- Prototype it! It's currently untested. Most of the design is tested except:
	- C to C functionality
	- VBUS sensing
	- LED
- Add LCSC part number to every component.
- Write a more extensive guide.

## Acknowledgements:
- [@Sleepdealr](https://github.com/Sleepdealr/) - For creating the [RP2040 design guide](https://github.com/Sleepdealr/RP2040-designguide) which this template is mostly based from
- Crane's Lab - For having such an amazing community and inspiring creativity in everyone who steps there.
- [@rana-sylvatica](https://github.com/rana-sylvatica/) - For making the OFOF1/Rana Digital and inspiring me to design my rectangles.
- [@Ryanemzed](https://github.com/Ryanemzed/) - For posting a cool clear acrylic build and taking me into a new rabbit hole (and being an amazing community member!).
- The Phob project - For being an amazing standard for the open source-community.