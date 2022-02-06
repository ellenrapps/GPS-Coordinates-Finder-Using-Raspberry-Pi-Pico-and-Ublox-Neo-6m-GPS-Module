Lost? Find your way via Raspberry Pi Pico, Ublox Neo-6m GPS Module, and 16x2 LCD Display with I2C

This machine can be used when you want to find your specific GPS (global positioning system) coordinates. While, the code looks for latitude, longitude, number of satellites, and GPS time, only the latitude and longitude are outputed in the LCD display.


MATERIALS:

Raspberry Pi Pico

Ublox Neo-6m GPS Module

16x2 LCD Display with I2C

Wires


WIRING:

Pico Pin 5 to Ublox GPS TX

Pico Pin 3 to  Ublox GPS GND

Pico Pin 40 to Ublox GPS VCC and to LCD VCC 

Pico Pin 1 to LCD SDA

Pico Pin 2 to LCD SCL

Pico Pin 38 to LCD GND


CODING:

Copy my PicoGpsLcdEr.py and scan.py files to Raspberry Pi Pico. Copy as well T-622's lcd_api.py and pico_i2c_lcd.py files to your Raspberry Pi Pico. Run the PicoGpsLcdEr.py file.


CREDITS:

Raspberry Pi Pico I2C LCD: https://github.com/T-622/RPI-PICO-I2C-LCD

Raspberry Pi Pico GPS: https://github.com/ahmadlogs/rpi-pico-upy/blob/main/gps2-rpi-pico/gps2-rpi-pico.py


Ellenrapps accepts Bitcoin donation: bc1qdxglsvq6tzqcwrd0zhcva9ww2y7hz879600exs
