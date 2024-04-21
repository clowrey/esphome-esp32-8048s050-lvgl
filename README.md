Sunton display general info https://github.com/rzeldent/platformio-espressif32-sunton
![sunton-esp32-8048s050](https://github.com/clowrey/esphome-esp32-8048s050-lvgl/assets/6935928/d6f8c34f-c5f3-4a33-b4c1-738e710de04a)
```yaml
# Required to achieve sufficient PSRAM bandwidth
    sdkconfig_options:
      CONFIG_ESP32S3_DEFAULT_CPU_FREQ_240: y
      CONFIG_ESP32S3_DATA_CACHE_64KB: y
      CONFIG_SPIRAM_FETCH_INSTRUCTIONS: y
      CONFIG_SPIRAM_RODATA: y
```
without that the screen will look like this ;)

![sunton-esp32-8048s050-no-sdkoptions](https://github.com/clowrey/esphome-esp32-8048s050-lvgl/assets/6935928/344fae6d-93c3-4caf-94ad-23281d86bf61)
