cmake_minimum_required(VERSION 3.10) # Versión mínima de CMake requerida
project(Biblioteca) # Nombre del proyecto, realmente da igual al momento de ejecutarlo

set(CMAKE_CXX_STANDARD 20) # Configurar C++20
set(CMAKE_CXX_STANDARD_REQUIRED True)
add_executable(biblioteca main.cpp) # Crear el ejecutable
