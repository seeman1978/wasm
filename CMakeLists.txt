cmake_minimum_required(VERSION 3.19)
project(wasm C)

set(CMAKE_C_STANDARD 11)

include_directories("/Users/wangqiang/CLionProjects/Emscripten/emsdk/upstream/emscripten/system/include")

add_executable(wasm main.c)