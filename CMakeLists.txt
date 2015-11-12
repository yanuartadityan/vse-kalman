cmake_minimum_required (VERSION 2.8.9)

#name the project
project (vse-kalman)

#add add_subdirectories
add_subdirectory (common)

#add executable
add_executable (vse-kalman main/vseMain.cpp)

#link to libraries
target_link_libraries(vse-kalman common)
