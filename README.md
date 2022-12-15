# Addressable LED library

GIT link

-------------------------------
LED SK6812
-------------------------------
Written for LED SK6812 a.k.a. built-in LED of ESP32 Stamp Pico:
https://cdn-shop.adafruit.com/product-files/1138/SK6812+LED+datasheet+.pdf

-------------------------------
HOW TO USE
-------------------------------
Use this library to address the addressable LED SK6812.
Use set_led() to pass the RGB values (0 - 255) to the LED. The value of the colour parameter can be calculated by x * 255, where x is the amount of percentage you want to turn on that colour.

-------------------------------
DEPENDENCIES
-------------------------------
This library needs the following ESP-IDF libraries to function:
esp_log.h
driver/rmt_tx.h
esp_check.h

Those libraries are standard included in the ESP-IDF.