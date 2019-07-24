# wireless-weather-station
A simple wireless weather station based around an ESP8266 and BME280

## The Weather Station

### Sensors

The sensor installed is a BME280 which incorporates temperature, humidity and barometric pressure and connects to the ESP8266 via the I2C protocol.

The sensor is installed under the roof of our garden shed where it is protected from rain and direct sunlight. This isn't a perfect location as the shed itself will have some effect on the readings, however, it is sufficient for the time being.

A 4 core cable runs between the sensor and the ESP8266. This carries the V+, GND, SDA and SCK signals required for the I2C protocol.

<img src='https://lh3.googleusercontent.com/jxQaHf9efEayiMJxlSM_FlDOA-UMQeetjmqfqUpoaBWa-XLI7OY0jRYqPWWEkeAT_4OJ_nIewG4EEJ1LT09zdbaRxZkae9eIyXrcaG3gxWxLhriilYqdFHCWknxWN9414YfXLc87lZ2AguZjogJYcKP549ECmZF9tPObw5pkiZRsJL8mpxuJFeAxKUzWtfMwXWr6Niw4YqipEQzYOFYTXS0dK2fUEbTo2gnhpsZDHjqeDrOuQA8cB8lJ7vcx3rgGankrC8KvxpB07LlCAS2bhUFSJXqNF6s1_TTEWmsGQE5YWsPK2RRwBdfp3colezCiS645aJ6xo4uH_2BBnHXRqanM2o1AxDuGjC8LG3BdvPK9yjuRiiI06himhs_znPpLooV8hXyCDpJqq1yvXIsxrrxcv5SgMDrjd0biL8XaQfiSN3yPuEPGtKKryMu3PAdDqaAsV8_hhghUD-BdTg0xNl5RvzZYYFYfWSuJPr69lTeQJhl2GwtP9sqYEXTW5dMnJxnIs0Gi36yktmPA-R8zAEVKafXp7u9GqGz5zO4x5CY2kUfgJpcDM0UmtBvOg9amY7vauGfueWjVFFSzo4xXxvI5yqbYT0NtPiPKS6uLPpEvxWfrEJ6fPtir5a3VzVfP4mkhg6Ec9KIKnAKjtZZeRiLvS2FYEOUD=w2164-h1378-no' />

### ESP8266


