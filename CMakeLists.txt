# Set the component name
set(COMPONENT_NAME "esp32-bg95")

# Set the component sources
file(GLOB COMPONENT_SOURCES "*.c")

# Create the component library
idf_component_register(SRCS ${COMPONENT_SOURCES}
                       INCLUDE_DIRS .
                      )
