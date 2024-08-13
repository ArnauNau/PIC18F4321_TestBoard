# TestBoard for PIC18F4321
A PCB design to be used as a test/development board for the PIC18F4321 microcontroller.


## Features
 - 20MHz crystal oscillator,
 - 5V voltage regulator (if powered with an external power supply, to be enabled with a Jumper),
 - an LED to indicate when the board is powered,
 - Connectors for:
   - the PicKit3, allowing for programming and debugging via MPLAB X, and for powering the board,
   - a 3-pin header for a serial connection via *USB-TTL*,
   - a 5-pin header for a Joystick,
 - 2 LEDs and 2 push buttons for testing purposes,
 - a 7-segment display for testing purposes with a pinout legend next to it,
 - a Reset push button for the microcontroller,
 - a switch to change between programming and running modes,
 - microcontroller pinout legends around the PIC on both sides of the board,
 - a component legend on the back of the board with the values of all resistors and capacitors.

 > [!IMPORTANT]
 > If using an external power supply, it is recommended to supply 9V for the voltage regulator to better regulate to 5V.

 > [!TIP]
  > The PIC18F4321 is a 40-pin microcontroller, so it is recommended to use a 40-pin DIP socket to easily replace the microcontroller if needed.

 > [!NOTE]
 > Remember to check the datasheet of the PIC18F4321 to know the pinout and the functions of each pin.

## How to import into EasyEDA
Within the [EasyEDA editor](www.easyeda.com), import it via "File" > "Open" > "EasyEDA...", and select the ZIP file.

---
*Authors: Arnau Sanz following the original PCB design from Joan Navarro at LaSalle Campus Barcelona, Universitat Ramón Llull*
