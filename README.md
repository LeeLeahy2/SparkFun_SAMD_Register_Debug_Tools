SparkFun SAMD Register Debug Tools
==================================

Debug tools for the SAMD set of parts such as the SAMD21.

Decode is provided for:
* GCLK: Global clock generators and peripheral clocks
* GPIO: GPIO ports
* TCC: Timer/Counters for Control
* TC: Timer/Counter


Documentation
--------------

Library Initialization is done by calling samdRegisterDebugToolsInit
and specifying the address of a Print object which defaults to &Serial.
This call allows output to be directed to a file or other serial device.

The following routines decode and print output:

* samdGclkgenClocks(): Generic clock controllers
* samdGclkPeripheralClocks(): Peripheral, AHB and APB clocks
* samdGpioPortsConfig(): GPIO configuration
* samdTimerConfigs(): Timer configuration

Detailed register descriptions are available in the [Atmel SAMD21 Datasheet](https://cdn.sparkfun.com/datasheets/Dev/Arduino/Boards/Atmel-42181-SAM-D21_Datasheet.pdf).


Repository Contents
-------------------

* **/examples** - Example sketches for the library (.ino). Run these from the Arduino IDE.
* **/src** - Source files for the library (.cpp, .h).
* **library.properties** - General library properties for the Arduino package manager.


License Information
-------------------

This product is _**open source**_!

Various bits of the code have different licenses applied. Anything SparkFun wrote is beerware; if you see me (or any other SparkFun employee) at the local, and you've found our code helpful, please buy us a round!

Please use, reuse, and modify these files as you see fit. Please maintain attribution to SparkFun Electronics and release anything derivative under the same license.

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
