# Outdoor Weather with Temp and PM2.5- ESPHome Version

<img src='/img/outdoorweather.jpeg' width='200'>
## Parts/Supplies

* [Wemos D1 Mini ESP8266 module] (https://www.amazon.com/gp/product/B08C7FYM5T/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=10)
* [PMS5003 particle sensor] (https://www.amazon.com/EC-Buying-Particle-Concentration-Precision/dp/B0B38J2836/ref=sr_1_4?crid=2OGGYGOJE7F2I)
* [DS18B20 temperature sensor] (https://www.amazon.com/gp/product/B012C597T0/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
* [19mm / .75 inch tobacco pipe filters] (https://www.amazon.com/gp/product/B01CC3VS08/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)

## Wiring
Connect the DS18B20 to the 5V, ground, and D5 on the Wemos D1 mini.
Connect the PMS5003 to D6 and D7 on the Wemos D1 mini.

## Enclosures / Parts
Print the Stevenson screen for the DS18B20 sensor:
https://www.printables.com/model/88215-stevenson-screen/files


Print the case for the PMS5003 Sensor:
https://www.printables.com/model/39560-outdoor-enclosure-for-pms5003-particulate-matter-s

## YAML Code
![ESPHome YAML](/pm25sensor_esphome.yaml)