cmake_minimum_required(VERSION 3.11)
project(thread-liveness-monitor)

include_directories(src)

# specify the C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_library (thread-liveness-monitor src/thread_monitor/thread_monitor.cpp src/thread_monitor/thread_monitor_central_repository.cpp)

