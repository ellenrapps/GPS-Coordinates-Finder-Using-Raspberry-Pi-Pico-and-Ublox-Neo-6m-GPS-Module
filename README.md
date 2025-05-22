Lost? Find your way – no internet connection needed – via Raspberry Pi Pico, Ublox Neo-6m GPS Module, and 16x2 LCD Display with I2C

This machine can be used when you want to find your specific GPS (global positioning system) coordinates. While, the code looks for latitude, longitude, number of satellites, and GPS time, only the latitude and longitude are outputted on the LCD display.

MATERIALS: Raspberry Pi Pico, Ublox Neo-6m GPS Module, 16x2 LCD Display with I2C, Wires

&nbsp;

WIRING:

   . Pico Pin 7 to Ublox GPS TX
	
   . Pico Pin 3 to Ublo GPS GND
	
   . Pico Pin 40 to Ublox GPS VCC and to LCD VCC
	
   . Pico Pin 1 to LCD SDA
	
   . Pico Pin 2 to LCD SCL
	
   . Pico Pin 38 to LCD GND

&ensp;

CODING:

Copy my PicoGpsLcdEr.py and scan.py files to Raspberry Pi Pico. Copy as well T-622's lcd_api.py and pico_i2c_lcd.py files to your Raspberry Pi Pico. Run the PicoGpsLcdEr.py file.

&ensp;

CREDITS:

T-622
https://github.com/T-622/RPI-PICO-I2C-LCD 

Tinkernut
https://www.youtube.com/watch?v=B8Kr_3xHjqE&t

Ahmad Logs
https://github.com/ahmadlogs/rpi-pico-upy/blob/main/gps-rpi-pico/gps-rpi-pico.py
https://www.youtube.com/watch?v=Hd-BMknrZdg

&nbsp;

Support my work via:

GitHub Sponsors: https://github.com/sponsors/ellenrapps

Bitcoin donation: bc1qcnalqpnjdcpkl2dcv7qqug334h8hjlhw5g77gu

