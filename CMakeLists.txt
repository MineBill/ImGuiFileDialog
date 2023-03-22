cmake_minimum_required(VERSION 3.15)
project(ImGuiFileDialog)

add_library(ImGuiFileDialog
    ImGuiFileDialog.cpp
    ImGuiFileDialog.h
)

target_link_libraries(ImGuiFileDialog imgui)

target_include_directories(ImGuiFileDialog PUBLIC .)
