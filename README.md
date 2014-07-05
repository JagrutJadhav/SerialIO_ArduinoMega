SerialIO_ArduinoMega
====================

Software Flow Control (Xon/Xoff) for Arduino Mega2560
There is a need for a robust, non binary transfer mechanism between a PC and an Arduino.

After some research it is aparant that some sort of flow control is required to insure
a reliable data transfer to/from the Arduino.

This project is my first attempt to create such a low level library to enable robust flow
control for a serial connection to an Arduino Mega board.
