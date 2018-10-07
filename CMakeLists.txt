cmake_minimum_required(VERSION 3.10)
project(mcw-clion-bug-2)

add_executable(mcw-clion-bug-2 main.cc)
target_compile_definitions(mcw-clion-bug-2 PRIVATE "-DHELLO_WORLD=1")