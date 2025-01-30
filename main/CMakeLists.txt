idf_component_register(SRCS "connect_wifi.c" "hello_world_main.c"
                    PRIV_REQUIRES spi_flash
                    REQUIRES driver
                    INCLUDE_DIRS "")
