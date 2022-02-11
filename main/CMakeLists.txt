
set(SOURCES main.cpp)
set(INCLUDES .)

idf_component_register(SRCS ${SOURCES}
                    INCLUDE_DIRS ${INCLUDES}
					REQUIRES lvgl_esp32_drivers lvgl)
