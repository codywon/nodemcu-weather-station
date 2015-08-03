# nodemcu-weather-station
Displays current weather conditions inside and out

This is a rough draft of what I have in mind, final version will have a second module outside collecting data (but it will stil probably call yahoo for the forecast).

![prototype](https://raw.githubusercontent.com/nfriedly/nodemcu-weather-station/master/media/prototpe-1.jpg)

## Current parts list:
* [ESP-12E w/ adapter board](http://www.electrodragon.com/product/esp8266-smd-adapter-board/) ([NodeMCU dev kit](http://www.electrodragon.com/product/nodemcu-lua-amica-r2-esp8266-wifi-board/) would also work here)
* [DHT11 Temp/Humidity sensor](http://www.electrodragon.com/product/humidity-and-temperature-sensor-dht11/)
* [128x64 i2c OLED](http://www.electrodragon.com/product/0-96-12864-oled-display-iicspi/)
* [BMP180 Temp/Pressure sensor](http://www.electrodragon.com/product/bmp180-barometric-pressure-sensor-board/)
* [Programmer](http://www.electrodragon.com/product/cp2102-usb-ttl-uart-module-v2/) (no need for this with NodeMCU dev kit)
* [Breadboard](http://www.electrodragon.com/product/breadboard-wside-power-channels/), [misc](http://www.electrodragon.com/product/prototype-cable-female-and-male-end-40p/) [wires](http://www.electrodragon.com/product/jumper-wire-60-70-pcs/)

Total cost: ~$25-30 w/ shipping

## Planned Changes

I'll probably drop the current sensors in favor of a [DHT22](http://www.electrodragon.com/product/dht22-pre-order-link/) (for higher accuracy),  and maybe choose a different display. I might also grab different ESP modules, probably an  [ESP-01](http://www.electrodragon.com/product/esp8266-wi07c-wifi-module/) for the outside part. I still need to figure out power...
