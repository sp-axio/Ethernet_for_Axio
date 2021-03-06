Ethernet Library for Axio-Builder [![Linux build status](https://travis-ci.org/sp-axio/Arduino_Ethernet_for_Axio.svg?branch=master)](https://travis-ci.org/sp-axio/Arduino_Ethernet_for_Axio)
=================================


== License ==

Copyright (c) 2010 Arduino LLC. All right reserved.

This library is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation; either
version 2.1 of the License, or (at your option) any later version.

This library is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU
Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public
License along with this library; if not, write to the Free Software
Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA 02110-1301 USA

== Ethernet Library for Axio-Builder ==

With the Arduino Ethernet Shield, this library allows an Axio-Builder to connect to the internet.


== How to use ==

* Copy 'w5100.h' file from 'src/utility' and overwrite to your default Ethernet library 'libraries/Ethernet/src/utility/w5100.h'.

* Connect Ethernet Shield to Axio-Builder with jumper wires as shown below.

![w5100 arduino shield](https://raw.githubusercontent.com/sp-axio/Arduino_Ethernet_for_Axio/master/eth_w5100_axio.png "w5100 Ethernet shield connect to Axio-Builder")

![w5100 arduino module](https://raw.githubusercontent.com/sp-axio/Arduino_Ethernet_for_Axio/master/wiz811mj_ab.png "w5100 Ethernet module connect to Axio-Builder")

Note:
* W5100 Ethernet shield uses ICSP pins(SPI) to communicate with the Axio-Builder(Arduino).
* Digital pin 10 is used to SPI SSN.
* This code was tested by the DFRobut Ethernet Shield v2.2.
* Axio-Builder does not support analogRead() which used in 'examples/WebServer/WebServer.ino'.
