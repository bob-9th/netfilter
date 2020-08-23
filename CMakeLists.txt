cmake_minimum_required(VERSION 3.17)
project(netfilter)

set(CMAKE_CXX_STANDARD 17)

add_executable(netfilter main.cpp)
target_link_libraries(netfilter -lpcap)
target_link_libraries(netfilter -lnetfilter_queue)