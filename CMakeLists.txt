cmake_minimum_required(VERSION 3.19)
project(ndpi_example)

set(CMAKE_CXX_STANDARD 14)

add_executable(ndpi_example ndpiex.c)
target_link_libraries(ndpi_example -lndpi -lpcap -lm)