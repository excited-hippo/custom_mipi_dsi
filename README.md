# Custom MIPI DSI sample

Just a custom MIPI DSI sample which shows a slider to validate that the LVGL configuration and the touch screen works.

Tested with:

- ESP-IDF v5.5.3
- Waveshare ESP32-P4 module dev kit (board version 1.0)
- Waveshare 8inch MIPI DSI touch screen (JD9385 panel, GT911 touch controller)

I copied the Waveshare EPS LCD JD9365_8 module because by default it doesn't not release the I2C bus which means that the touch pad will not work.