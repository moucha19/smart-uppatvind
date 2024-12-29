Smart Uppatvind
===================

## Description

*Redesigned control board for IKEA Uppatvind with smart capabilities.*

The IKEA's air purifiyer lineup is very affordable, and that's especially true for the cheapest Uppatvind. Although it is not the most powerful, it can still improve air quality in a smaller room, while not taking a lot of space. Regardless of the pricepoint, there is not a lot of commercial options, that are this compact.

Unfortunately, it does not come with any smart controls, so I decided to create a replacement board, that should be reliable, relatively easy to make and that also provides some improvements over the original.

## Features

* Part for part replacement of the original - no modifications necessary
* Designed to be integrated into Home Assistent
* Flexible MCU options - both **ESP8684-WROOM-02C** and **ESP32-C3-WROOM-02C** are supported
* Adressable RGB for speed preset and filter life indicators
* Auto-reset circuit to simplify firmware flashing process
* **QWIIC** connector for external sensors
* Optional onboard EEPROM