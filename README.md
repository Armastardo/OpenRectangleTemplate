
# Open Rectangle Template
**RP2040 template for use with box style controllers for the GC**

<p align="center">
  <img src="https://github.com/Armastardo/OpenRectangleTemplate/blob/main/Pictures/KicadRender.png?raw=true" />
</p>

## Table of contents
* [About](#about)
* [Usage](#usage)
* [Featured projects](#projects)
* [To-do](#to-do)
* [Acknowledgements](#acknowledgements)

## About
This template was created for the purpose of easing development of box-styled controllers (rectangles) that work with a GameCube console and Nintendo 64 via a USB C to console cable. It uses a RP2040 as its main controller so compatibility to other devices will be limited to the firmware you are using. (Such as [HayBox](https://github.com/JonnyHaystack/HayBox), [Pico-Rectangle](https://github.com/JulienBernard3383279/pico-rectangle), etc). There's already a footprint added for a compatible USB-C port that will allow you to used said cables, as well as a USB C to C cable, or C to A cable for PC or Switch.

Labels are already assigned to the default pinout of the most popular firmware available as well as in stock parts for every component from LCSC. I recommend using the Fabrication Toolkit plugin that can be installed through KiCad's PCM.

## Usage
This templates requires for you to have a minium experience with Kicad and some EE basics. You can just download it as .zip and start creating your own. Make sure you are using **Kicad 7**.
- Download as a zip or clone the repository.
- Open KiCad (7 or newer!) and go to File -> New Project from Template
- Select the tab "User Templates" and click on the Folder icon top right.
- Look for the directory where the kicad project is and open it.
- Template should load. Just click OK and everything will be imported into your project.

## To-do:
- Write a more extensive guide.
- Feature more projects.

## Projects
Small section to highlight proyects that were devveloped using this template.
- [Open Rectangle Breakout](https://github.com/Armastardo/OpenRectangleBreakout) - Breakout board designed to make handwired builds easier.

## Acknowledgements:
- [@Sleepdealr](https://github.com/Sleepdealr/) - For creating the [RP2040 design guide](https://github.com/Sleepdealr/RP2040-designguide) which this template is mostly based from
- Crane's Lab - For having such an amazing community and inspiring creativity in everyone who steps there.
- [@rana-sylvatica](https://github.com/rana-sylvatica/) - For making the OFOF1/Rana Digital and inspiring me to design my rectangles.
- [@Ryanemzed](https://github.com/Ryanemzed/) - For posting a cool clear acrylic build and taking me into a new rabbit hole (and being an amazing community member!).
- The Phob project - For being an amazing standard for the open source-community.