add_library(mdk_core STATIC
    esp32/boot.c
)

# Include header directories
target_include_directories(mdk_core PRIVATE
    ${CMAKE_SOURCE_DIR}/kernel
)
