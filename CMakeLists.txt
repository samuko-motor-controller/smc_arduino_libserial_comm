cmake_minimum_required(VERSION 3.16)
project(smc_arduino_libserial_comm LANGUAGES CXX)



include_directories(include)
add_executable( example_control_code examples/example_control_code.cpp )
target_link_libraries( example_control_code serial )

