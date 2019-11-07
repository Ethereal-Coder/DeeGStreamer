cmake_minimum_required(VERSION 3.15)
project(DeeGStreamer C)

set(CMAKE_C_STANDARD 11)
#set(CMAKE_CXX_STANDARD 14)

add_executable(DeeGStreamer main.c samples/basic-tutorial-1.c samples/basic-tutorial-2.c samples/basic-tutorial-3.c samples/basic-tutorial-4.c samples/basic-tutorial-5.c samples/basic-tutorial-6.c)