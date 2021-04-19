cmake_minimum_required(VERSION 3.17)
project(src)

set(CMAKE_CXX_STANDARD 14)

add_executable(src
        "pick_objects (不加waitforresult).cpp"
        "pick_objects (复件).cpp"
        pick_objects.cpp
        pick_objects原.cpp)
