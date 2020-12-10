# TTN BME280 Weather Station - Heltec CubeCell HTCC-AB01

This repository contains all the code and steps required to setup a BME280 with the Heltec CubeCell HTCC-AB01 on TTN Australia.

# Getting Started

This code is for a BME280 sensor attached to the Heltec CubeCell HTCC-AB01 via i2c. The code is set to send the temperature, humidity, pressure, battery voltage, and battery level values to The Things Network every 100 seconds. The TTN Development EUI, Application EUI, Application Key, and time period can all be configured in main.ino.

Download this repository and open the main.ino file in the Arduino IDE, enter your TTN Dev EUI, App EUI, App Key, and upload the project to your CubeCell HTCC-AB01. The CubeCell HTCC-AB01 needs to be preconfigured in the Arduino board manager to set your LoRaWAN region and enable OTAA authentification.

# License

This project is licensed under the MIT License. This project contains code from [chrisys/mini-lora-weatherstation](https://github.com/chrisys/mini-lora-weatherstation).
