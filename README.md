# tiny-hid-als
This project contains open-source firmware for an USB HID Ambient Light Sensor (ALS) implementation using Digispark Attiny85-based microcontroller development board and BH1750FVI I2C light sensor module.

# Schematic

![Digispark connected to BH1750](https://github.com/3cky/tiny-hid-als/raw/main/doc/tiny-hid-als.png)

# OS support

USB HID sensors framework is supported out of the box since Linux 3.7 and Windows 8. 

# Compiling and installing

First, please install [PlatformIO](http://platformio.org/) open source ecosystem for IoT development compatible with **Arduino** code and its command line tools (Windows, MacOs and Linux). Also, you may need to install [git](http://git-scm.com/) in your system. 

Note: with `platformIO` you don't need the Arduino IDE and install libraries, this will do it for you.

Clone the project:
``` bash
git clone https://github.com/3cky/tiny-hid-als && cd tiny-hid-als
```

Compiling and installing:
``` bash
pio run --target upload
```

Note: you need connect your Digispark after each compiling for upload the new firmware or reset it. More info [here](http://digistump.com/wiki/digispark/tutorials/connectingpro).

## License
This project is distributed with GPL license, see [LICENSE](https://github.com/3cky/tiny-hid-als/blob/main/LICENSE) file for more informations.