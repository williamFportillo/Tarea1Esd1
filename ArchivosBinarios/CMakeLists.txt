cmake_minimum_required(VERSION 3.7)
project(ArchivosBinarios)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Cuentas.cpp Cuentas.h Transacciones.cpp Transacciones.h)
add_executable(ArchivosBinarios ${SOURCE_FILES})