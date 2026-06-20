# Digital Lock System Using Keypad

## Project Overview

This project is a Digital Lock System developed using Arduino Uno, 4×4 Keypad, and a Servo Motor. The system allows users to enter a 4-digit password through the keypad. If the entered password matches the stored password, the servo motor unlocks the lock mechanism. This project was designed and tested using the Wokwi Arduino Simulator.

## Features

* 4-digit password protection
* Keypad-based user input
* Servo motor locking mechanism
* Automatic re-locking feature
* Simple and low-cost security system
* Easy to simulate using Wokwi

## Components Used

* Arduino Uno
* 4×4 Keypad
* Servo Motor (SG90)
* Jumper Wires
* Breadboard

## Circuit Connections

### 4×4 Keypad

* R1 → D9
* R2 → D8
* R3 → D7
* R4 → D6
* C1 → D5
* C2 → D4
* C3 → D3
* C4 → D2

### Servo Motor

* VCC (Red) → 5V
* GND (Brown/Black) → GND
* Signal (Orange/Yellow) → D10

## Working Principle

1. The user enters a 4-digit password using the keypad.
2. Arduino reads and stores the entered digits.
3. The entered password is compared with the predefined password.
4. If the password is correct, the servo motor rotates to unlock the lock.
5. After a few seconds, the servo automatically returns to the locked position.
6. If the password is incorrect, access is denied.

## Output

### Correct Password

* Password matches the stored password.
* Servo motor rotates and unlocks the lock.
* Lock automatically closes after a few seconds.

### Incorrect Password

* Password does not match.
* Lock remains closed.

## Applications

* Electronic Door Locks
* Home Security Systems
* Locker Security
* Access Control Systems
* Smart Security Projects

## Technologies Used

* Arduino IDE
* Embedded C / Arduino Programming
* Keypad Library
* Servo Library
* Wokwi Simulator

## Simulation

Wokwi Project:https://wokwi.com/projects/467316525575965697
## Conclusion

The Digital Lock System successfully provides password-based access control using a keypad and servo motor. This project demonstrates the implementation of embedded security systems, user input handling, and actuator control, making it a practical and educational Arduino project.

## Author

Meena K
