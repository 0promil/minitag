Project: RFID & IR Signal Simulator (Flipper Zero-like Device)

This project demonstrates the creation of a device similar to Flipper Zero, using an ESP8266-based microcontroller. It integrates RFID functionality through the MFRC522 module, allowing the device to read and store the UID of an RFID card. If a matching card is detected, the device simulates an IR signal by activating an IR LED.

Features:

RFID Functionality: Reads RFID card UID using the MFRC522 module.
IR Signal Simulation: When a saved card is detected, the device simulates an IR signal by controlling an IR LED.
OLED Display: Displays information such as the status of the card and its UID on a 128x64 OLED screen.
LED Indicator: A built-in LED provides visual feedback during the card detection process.
Hardware Required:

Wemos ESP8266 (or similar ESP8266-based board)
MFRC522 RFID/NFC Module
SSD1306 I2C OLED Display
TSOP1738 IR Receiver (optional for future extensions)
IR LED
Jumper wires and breadboard for connections
Installation & Setup:

Install the necessary libraries: Adafruit_SSD1306, SPI, MFRC522.
Connect the hardware as described in the code.
Upload the code to the ESP8266 board using the Arduino IDE.
Open the Serial Monitor to view the UID of the scanned RFID card.
When a matching card is detected, the device simulates an IR signal.
Feel free to explore, modify, and expand the functionality of this project for various applications!

