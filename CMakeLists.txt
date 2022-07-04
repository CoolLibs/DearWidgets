cmake_minimum_required(VERSION 3.8)

add_library(DearWidgets)
add_library(DearWidgets::DearWidgets ALIAS DearWidgets)

target_include_directories(DearWidgets PUBLIC
    src/api

    PRIVATE
    ..
)
target_sources(DearWidgets PRIVATE
    src/api/dear_widgets.cpp
)