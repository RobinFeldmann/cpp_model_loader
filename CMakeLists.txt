cmake_minimum_required(VERSION 3.0 FATAL_ERROR)
project(custom_ops)

find_package(Torch REQUIRED)

add_executable(loader loader.cpp)
target_link_libraries(loader "${TORCH_LIBRARIES}")
set_property(TARGET loader PROPERTY CXX_STANDARD 17)