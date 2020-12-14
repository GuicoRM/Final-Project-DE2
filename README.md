# :lock: Application of the door lock system :lock:

### Team members
Guillermo Cortés Orellana. ['*Personal repository*'](https://github.com/GuicoRM) :bowtie:

Omar Bin Rahman. ['*Personal repository*'](https://moodle.vutbr.cz/course/view.php?id=229631) :bowtie:

### Project objectives
Current project it has been designed as final project of the subject **Digital Electronics 2** at Brno University Of Technology.

The main purpose of the project is program security software for door lock system based on Arduino.

System counts with 4 possible passwords made for 4 digits which allow the user open the door.

Initially, the system's door will stay closed. The user will have to enter her/his personal password in order to open it (as it has been said, there are only 4 possible combinations). If the user enters **correct password**, the door will open and the user can access to the hall. If on the contrary, the user enters **wrong password**, he/she will have another 2 opportunities (in total 3) to unlock the door. Just in case the user introduces wrong password 3 times in a row, the system will be locked and the access will be forbidden.

On the other hand, at the moment the user enters first digit of the password, he/she will have **5 seconds** to complete the rest of the password, otherwise, he/she will have to enter again the code.

All the process is divided in several states:

1. **START**
This is the initial state. Door will be close (relay), state LEDs off and there will display welcome message on LCD screen.

2. **Intermediate state**

- 2.1 **Counter key < 5" AND correct key**

- 2.2 **Counter key > 5" OR incorrect key**

3. **Wait**

**Note:** the program will never stop due to it is a simulation with learning purposes.

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
