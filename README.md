# scratch-for-arduino
Programming Arduino using Scratch GUI Interface  

## About S4A
S4A is a Scratch modification that allows for simple programming of the Arduino open source hardware platform. It provides new blocks for managing sensors and actuators connected to Arduino

http://s4a.cat/

## Download and Install
Installing S4A requires you to install software both in your PC and your Arduino board. Here you'll find the detailed steps to get it up and running

Installing S4A into your computer
S4A works in the three major consumer operating systems. Download and install the one that fits your configuration:
* Windows
* Linux (Debian)
* Raspbian (Debian for RaspberryPi) (version 1.5)

## Installing the Firmware into your Arduino
This firmware is a piece of software you need to install into your Arduino board to be able to communicate with it from S4A.

* Download and install the Arduino environment by following the instructions on http://arduino.cc/en/Main/Software. Take in account Arduino Uno requires at least version 0022.
* Download our firmware from [here](http://s4a.cat/downloads/S4AFirmware16.ino)
* Connect your Arduino board to a USB port in your computer
* Open the firmware file ([S4AFirmware16.ino](http://s4a.cat/downloads/S4AFirmware16.ino)) from the Arduino environment
* In the Tools menu, select the board version and the serial port where the board is connected
* Load the firmware into your board through File > Upload

## Arduino drivers
If you are a Microsoft Windows user, you may need to install the Arduino drivers into your computer:
* [Arduino drivers for Microsoft Windows](http://s4a.cat/downloads/drivers.zip)
