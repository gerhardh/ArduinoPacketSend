# ArduinoPacketSend

This project is a simple Arduino sketch to be used as a companion to the ORSSerialPort PacketParsingDemo project for OS X. It can currently only be run on the [Arduino Esplora](http://arduino.cc/en/Main/ArduinoBoardEsplora). However, the sketch can very easily be ported to run on other Arduino boards, and the concept demonstrated is broadly applicable.

The program simply polls the value of the Esplora's hardware slider, and any time the value changes, it sends a packet on the serial port (at 57600 baud):

`$pos<x>;` (where `<x>` is the slider position, from 1 to 100.)

For more information, please see the ORSSerialPort [PacketParsingDemo project](https://github.com/armadsen/ORSSerialPort/tree/master/Examples/PacketParsingDemo) as well as the [Packet Parsing API Documentation](https://github.com/armadsen/ORSSerialPort/wiki/Packet-Parsing-API).

This project is licensed under the terms of the MIT [license](LICENSE.md).
