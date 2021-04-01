# FALK PA-01

Images
![PA-01 built](/img/pa-01-overview.jpg)
Format: ![Alt Text](url)

### Introduction
The PA-01 Modular Preamplifier is a set of designs created to allow DIY audio enthusiasts a way to build a preamplifier that suits their individual needs by picking from a set of predefined components and putting them together to create a complete system.

Generally, a system is made from a minimum of four basic components:
* Input board (balanced or single ended)
* Volume board
* Output board (balanced or single ended)
* Control board

Other optional boards can be used, including daughter boards for single-ended to balanced or balanced to single-ended conversion and display / button boards. Optionally, third party boards can be included, for example audio buffers or phono stages.

At this time, the boards are available as design-ware, including schematics, PCB designs, BOM (bills of material) and Gerber files for PCB production. Any software required (firmware for microcontrollers) is also available.

To build your own system, select the boards that you need to build your system, have them produced at a PCB manufacturer of your choice, order the parts needed and finally assemble the boards and install them into an enclosure of your choice.

Throughout the design, care has been taken to isolate the control and audio paths. Relays are switched using pulses of 5V DC power, so power is not continuously provided to the audio boards. Additionally, the boards are designed to physically separate control and audio wherever possible.

### Skills required
In order to build one of these systems, you’ll need to know how to order PCBs (although it’s not difficult) from a manufacturer. There are many who cater to enthusiasts. You’ll need to be handy with a soldering iron (especially for the advanced control board). You need to know how to read and operate a multimeter as a minimum and for some components you need to be confident working with mains voltage. You’ll also need to be at least vaguely comfortable flashing microcontrollers, although this document will talk you through the process.

This set of designs was created to be as approachable as possible. Only one component is surface-mount, the ESP32 (because it doesn’t come any other way) and it’s large enough that you can solder it with an iron. Unless you’re modifying things, you don’t need to know how to write code, debug or anything of the sort.

Last of all, you need to be able to enjoy audio equipment!
