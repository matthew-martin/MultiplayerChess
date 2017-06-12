This project was created by Matthew Martin and Brian Khieu for the EEC 172 (Embedded Systems) class in Spring 2017. This is the final project of the class. The assignment is an open-ended embedded systems project that must communicate over the internet using a secured connection.
We decided on a multiplayer chess application that can be played over the internet on two TI CC3200 LaunchPad boards. User input is provided through the user of an IR TV remote (that communicates with the board using an IR receiver). The game board is displayed using a 128x128 Adafruit OLED display. Secure communication is transmitted over the internet using the AWS IoT module.

The core functionality of the project is implemented in main.c. The code to interface with the OLED is in Adafruit_*.c/h. This code was ported from existing Arduino code to work with the CC3200.

Please see LabReport6.pdf for a complete project explanation and write-up.