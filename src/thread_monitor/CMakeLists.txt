add_library (thread-liveness-monitor thread_monitor.cpp thread_monitor_central_repository.cpp)

target_include_directories(thread-liveness-monitor PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/..)
