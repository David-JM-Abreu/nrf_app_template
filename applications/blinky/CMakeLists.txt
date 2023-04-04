cmake_minimum_required(VERSION 3.20.0)

set(Zephyr-sdk_DIR /home/david/ncs/toolchains/v2.3.0/opt/zephyr-sdk/cmake)

find_package(Zephyr)
project(blinky)

target_sources(app PRIVATE src/main.c)
