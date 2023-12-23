## Modified to support that cute little "mini Smart Wifi Weather Clock". To purchase - search usual places: Ali, eBay, Amazon.
It is ESP8266 + ST7789 based + 4MB flash, perfect for Arduinot project.
It took me some time to figure out implementation specific pins. Unfortunately Adafruit examples do not work out of the box, in addition to pins, it need to use "SPI_MODE3". See example folder. Only .ino is edited.
![mini Smart Wifi Weather Clock](https://raw.githubusercontent.com/LsrSal/Adafruit-ST7735-Library/master/image.png)


This is a library for Adafruit displays based on ST77* drivers.

Check out the links above for our tutorials and wiring diagrams.
These displays use SPI to communicate, 4 or 5 pins are required to
interface (RST is optional).

Adafruit invests time and resources providing this open source code,
please support Adafruit and open-source hardware by purchasing
products from Adafruit!

Written by Limor Fried/Ladyada for Adafruit Industries.
MIT license, all text above must be included in any redistribution.

Recent Arduino IDE releases include the Library Manager for easy installation. Otherwise, to download, click the DOWNLOAD ZIP button, uncompress and rename the uncompressed folder Adafruit_ST7735. Confirm that the Adafruit_ST7735 folder contains Adafruit_ST7735.cpp, Adafruit_ST7735.h and related source files. Place the Adafruit_ST7735 library folder your ArduinoSketchFolder/Libraries/ folder. You may need to create the Libraries subfolder if its your first library. Restart the IDE.

Also requires the Adafruit_GFX library for Arduino.
