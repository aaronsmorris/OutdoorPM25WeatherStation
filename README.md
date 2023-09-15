# Outdoor Weather with Temp and PM2.5- ESPHome Version

<img src='/img/outdoorweather.jpeg' width='200'>
Parts/Supplies

Wemos D1 Mini ESP8266 module
PMS5003 particle sensor
DS18B20 temperature sensor
19mm / .75 inch tobacco pipe filters 

Wiring:
Connect the DS18B20 to the 5V, ground, and D5 on the Wemos D1 mini.
Connect the PMS5003 to D6 and D7 on the Wemos D1 mini.

Print the Stevenson screen for the DS18B20 sensor:
https://www.printables.com/model/88215-stevenson-screen/files

Print the case for the PMS5003 Sensor:
https://www.printables.com/model/39560-outdoor-enclosure-for-pms5003-particulate-matter-s

![ESPHome YAML](/pm25sensor_esphome.yaml)