
idf_component_register(SRCS "hello_world_main.c"
                       "lvgl_demo_ui.c"
                       PRIV_REQUIRES spi_flash
                       REQUIRES esp_timer
                       REQUIRES waveshare__esp_lcd_jd9365_8
                       INCLUDE_DIRS "")
