# Set the component name
set(COMPONENT_NAME "esp32-bg95")

# Create the component library
idf_component_register(SRCS "src/esp32-BG95.cpp"
                       INCLUDE_DIRS "src"
                       REQUIRES "espressif__arduino-esp32"
                                "arduino-time"
                      )
