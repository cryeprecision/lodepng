cmake_minimum_required (VERSION 3.21)

set(LODEPNG_SOURCES
    "./lodepng.cpp"
)
set(LODEPNG_HEADERS
    "./lodepng.h"
)

declare_static_library(lodepng ${LODEPNG_HEADERS} ${LODEPNG_SOURCES})
