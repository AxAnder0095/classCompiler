cmake_minimum_required(VERSION 3.27)
project(classCompiler)

set(CMAKE_CXX_STANDARD 17)

add_executable(classCompiler main.cpp
        LexAnalyzer.cpp
        LexAnalyzer.h)
add_executable(classCompiler2 synAnalyzerMain.cpp
        SyntaxAnalyzer.cpp
        SyntaxAnalyzer.h)