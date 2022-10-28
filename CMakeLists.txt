cmake_minimum_required(VERSION 3.1)

project(min_example)

add_subdirectory(external/bgfx.cmake)
add_subdirectory(external/glfw)

add_executable(min_example main.cpp)

target_link_libraries(min_example bgfx bx glfw)
