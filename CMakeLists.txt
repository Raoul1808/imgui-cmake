cmake_minimum_required(VERSION 3.0)
project(imgui-cmake)

add_library(imgui-cmake imgui/imgui.cpp
                        imgui/imgui_demo.cpp
                        imgui/imgui_draw.cpp
                        imgui/imgui_tables.cpp
                        imgui/imgui_widgets.cpp)
target_include_directories(imgui-cmake PUBLIC imgui/)
