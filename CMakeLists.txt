cmake_minimum_required(VERSION 3.16)
project(Tinyhttpd C)

set(CMAKE_C_STANDARD 99)

add_executable(Tinyhttpd httpd.c)

target_link_libraries(Tinyhttpd pthread)