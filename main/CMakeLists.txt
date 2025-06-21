idf_component_register(SRCS "main.c"
                    PRIV_REQUIRES
                    log
                    bt
                    nvs_flash
                    freertos
                    esp32-camera
                    
                    driver
                    INCLUDE_DIRS "")
