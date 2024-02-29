cmake_minimum_required(VERSION 3.21)
project(imgui)

set(SOURCES
    imconfig.h
    imgui.h
    imgui.cpp
    imgui_demo.cpp
    imgui_draw.cpp
    imgui_internal.h
    imgui_tables.cpp
    imgui_widgets.cpp
    imstb_rectpack.h
    imstb_textedit.h
    imstb_truetype.h
)

add_library(${PROJECT_NAME} ${SOURCES})