# wireless-weather-station
A simple wireless weather station based around an ESP8266 and BME280

## The Weather Station

### Sensors

The sensor installed is a BME280 which incorporates temperature, humidity and barometric pressure and connects to the ESP8266 via the I2C protocol.

The sensor is installed under the roof of our garden shed where it is protected from rain and direct sunlight. This isn't a perfect location as the shed itself will have some effect on the readings, however, it is sufficient for the time being.

A 4 core cable runs between the sensor and the ESP8266. This carries the V+, GND, SCL and SDA signals required for the I2C protocol.

<a href="https://www.flickr.com/photos/black_friction/48409642706/in/album-72157718508798159/" title="BME280 Sensor"><img src="https://live.staticflickr.com/65535/48409642706_73f428cae7_b.jpg" width="1024" height="652" alt="BME280 Sensor"></a>

### ESP8266

<a href="https://www.flickr.com/photos/black_friction/50145800613/in/album-72157718508798159/" title="Wireless Weather Station"><img src="https://live.staticflickr.com/65535/50145800613_d8325e28d1_b.jpg" width="1024" height="768" alt="Wireless Weather Station"></a>


