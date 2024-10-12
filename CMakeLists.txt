cmake_minimum_required(VERSION 3.15)

project(App VERSION 1.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

include_directories(include)

add_executable(app src/main.cc)

# target_link_libraries(app some_library)