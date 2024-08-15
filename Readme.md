# Weatherstation for Lilygo T-Display S3 (2024 version), by VolosR
For use in Arduino IDE. 

⚠️ You *must* use the 2.x version of the Espressif ESP32 library for this to work as some functions have changed in 3.x Your Arduino IDE will continually suggest updating to 3.x which would make this project not compile.

This is another ESP32 Internet Weather station. This time I am using affordable (13.99 USD) board, LilyGo T-Display S3. My last "weather station" project is outdated so I decided to make new one. I hope you like this Black&White user interface.

You need an OpenWeatherMap API key: https://home.openweathermap.org/  
(here you can make you free API Key, keep in mind that it needs few hours for activation of your key)

BOARD USED FOR THIS PROJECT:
[LilyGo T-Display S3](https://www.lilygo.cc/CsVsMu) (Affiliate link that supports the author)

☕️ Support me on:
KO-FI https://ko-fi.com/volosprojects
PATREON: https://www.patreon.com/VolosProjects

# Libraries
Remember to install the requisite libraries; all should be available to find directly in the Arduino IDE. 

Version numbers are just the ones that are current as of this writing; later versions might work.

| Library | Version |
|---|---|
| [WiFiManager by tzapu](https://github.com/tzapu/WiFiManager) | `2.0.17` | 
| [TFT_eSPI](https://github.com/Bodmer/TFT_eSPI) | `2.5.43` |
| [ArduinoJson](https://arduinojson.org/) | `7.1.0` |
| [ArduinoHttpClient](https://github.com/arduino-libraries/ArduinoHttpClient) | `0.6.1` |
| [ESP32Time](https://github.com/fbiego/ESP32Time) | `2.0.6` |
