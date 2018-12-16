cmake_minimum_required(VERSION 3.0.0)
project(SfmlHello VERSION 0.1.0)

include(conanbuildinfo.cmake)

conan_basic_setup(NO_OUTPUT_DIRS)

add_executable(SfmlHello main.cpp)

target_link_libraries(SfmlHello ${CONAN_LIBS})