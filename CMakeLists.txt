cmake_minimum_required(VERSION 3.21)
project(SharedMemory C)

set(CMAKE_C_STANDARD 99)

add_executable(SharedMemory writerProcess.c readerProcess.c)
