# ESP32 USB Host Shield using alternative SPI (HSPI) port pins
Intended as a bare-bones for use on TTGO T-Beam, due to other SPI pins being already allocated to on-board devices.

```
MISO    33
MOSI    13
SCK     14
SS      2
INT     32 (possibly not needed...?)
```

##  Hardware:
* Generic ESP32 DevKit board, or TTGO T-Beam
* Using PlatformIO

##  Credits:
* Downloads & patches https://github.com/felis/USB_Host_Shield_2.0 with alternative pin assignments & uses one of its examples