# ANAVI Fume Extractor Default Arduino Sketch

The open source smart solder smoke absorber!

Open source Arduino sketch for ANAVI Fume Extractor powered by ESP8266 and with support for mini OLED display, analog 5V [MQ gas sensor](https://playground.arduino.cc/Main/MQGasSensors/) and up to 3 additional I2C sensor modules. For more details
have a look at:

* https://www.crowdsupply.com/anavi-technology/fume-extractor
* http://anavi.technology/
* https://blog.anavi.technology/?cat=129

# User's Manual

[ANAVI Fume Extractor user's manual is available here](https://github.com/AnaviTechnology/anavi-docs/blob/master/anavi-fume-extractor/anavi-fume-extractor.md).

# Dependencies

The default firmware of ANAVI Fume Extractor depends on the following Arduino libraries:

* [WiFiManager by tzapu](https://github.com/tzapu/WiFiManager) (version 0.15.0)
* [ArduinoJson by Benoit Blanchon](https://arduinojson.org/) (version 6.11.2)
* [PubSubClient by Nick O'Leary](https://pubsubclient.knolleary.net/) (version 2.7.0)
* [Adafruit HTU21DF Library by Adafruit](https://github.com/adafruit/Adafruit_HTU21DF_Library) (version 1.0.1)
* [Adafruit APDS9960 Library by Adafruit](https://github.com/adafruit/Adafruit_APDS9960) (version 1.0.5)
* [U8g2 by oliver](https://github.com/olikraus/u8g2) (version 2.23.18)
* [Adafruit Unified Sensor by Adafruit](https://github.com/adafruit/Adafruit_Sensor) (version 1.0.2)
* [Adafruit BMP085 Unified](https://github.com/adafruit/Adafruit_BMP085_Unified) (version 1.0.0)
* [NTPClient by Fabrice Weinberg](https://github.com/arduino-libraries/NTPClient) (version 3.1.0)
