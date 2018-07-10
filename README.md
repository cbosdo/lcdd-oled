``lcd-to-ssd1306`` is a tiny daemon wrapping around LCDd to output on an SSD1306 OLED device rather
than on an LCD.

Install
-------

Dependencies:

* [Adafruit's SSD1306 python module](https://github.com/adafruit/Adafruit_Python_SSD1306)
* Python (either 2 or 3)
* Python Pillow library
* Python RPi.GPIO module

Install the systemd service:

    ln -s /path/to/lcdd-oled/lcdd-oled.service /etc/systemd/system/multi-user.target.wants/lcdd-oled.service
