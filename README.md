# :lock: Application of the door lock system :lock:

### Team members
Guillermo Cortés Orellana. ['*Personal repository*'](https://github.com/GuicoRM) :bowtie:

Omar Bin Rahman. ['*Personal repository*'](https://moodle.vutbr.cz/course/view.php?id=229631) :bowtie:

### Project objectives
Current project it has been designed as final project of the subject **Digital Electronics 2** at Brno University Of Technology.

The main purpose of the project is program security software for door lock system based on Arduino.

There are only 4 possible combination

It is divided in several states:

1. **START**


2. **Intermediate state**

- 2.1 **Counter key < 5" AND correct key**

- 2.2 **Counter key > 5" OR incorrect key**

3. **Wait**

**Note:** the program will never stop due to it is a simulation for learning purposes

## Hardware description
Door lock system is divided in several hardware modules, such as:

- [x] 1. ATMega328P microcontroller
- [x] 2. Keypad
- [x] 3. Speaker
- [x] 4. Relay
- [x] 5. LCD screen
- [x] 6. LEDs

In the following lines it will be explain different functions of this modules and their relation with complete system:

- **AMega328P microcontroller**

    This module is similar to the microcontroller we have used for the semester. 

    You can find the datasheet ['*on this link*'](http://ww1.microchip.com/downloads/en/DeviceDoc/ATmega48A-PA-88A-PA-168A-PA-328-P-DS-DS40002061B.pdf).

- **Keypad**

The main different hardware module we have introduced on this topic is the keypad.

It consists on several push button connected between them by **ROWS** and **COLUMNS**, in our case we have 4 ROWS and 3 COLUMNS.

It is possible to configure keypad using some libraries by default included in Arduino, but we have programmed our own.

You can find the connection of keypad and how it works ['*on this link*'](https://www.circuitbasics.com/how-to-set-up-a-keypad-on-an-arduino/).

- **Speaker**

One of the others hardware modules we have introduced on this topic is the speaker.

- **Relay**

- **LCD screen**

- **LEDs**

## Code description and simulations
Write your text here.

## Video/Animation
Write your text here.

## References
Write your text here.
