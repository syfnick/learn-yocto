project(learn-yocto C)
cmake_minimum_required(VERSION 2.6.3)

add_executable (learn-yocto main.c)

install(TARGETS learn-yocto DESTINATION ${CMAKE_INSTALL_PREFIX}/bin)
