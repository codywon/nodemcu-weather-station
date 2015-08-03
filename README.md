# nodemcu-weather-station
Displays current weather conditions inside and out

This is a rough draft of what I have in mind, final version will have a second module outside collecting data (but it will stil probably call yahoo for the forecast). I may also switch the display.

Current parts list:
* ESP-12E w/ adapter board - http://www.electrodragon.com/product/esp8266-smd-adapter-board/ ([NodeMCU Dev Kit](http://www.electrodragon.com/product/nodemcu-lua-amica-r2-esp8266-wifi-board/) would also work here)
* DHT11 Temp/Humidity sensor - http://www.electrodragon.com/product/humidity-and-temperature-sensor-dht11/
* 128x64 i2c OLED - http://www.electrodragon.com/product/0-96-12864-oled-display-iicspi/
* BMP180 Temp/Pressure sensor - http://s4.electrodragon.com/wp-content/uploads/2014/06/BMP180-Barometric-Pressure-Sensor-Board-150x150.jpg
* Programmer - http://www.electrodragon.com/product/cp2102-usb-ttl-uart-module-v2/ (no need for this with NodeMCU Dev Kit)
* Breadboard, misc wires - http://www.electrodragon.com/product/breadboard-wside-power-channels/ http://www.electrodragon.com/product/jumper-wire-60-70-pcs/ http://www.electrodragon.com/product/prototype-cable-female-and-male-end-40p/