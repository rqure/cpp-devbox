# Minimum CMake version
cmake_minimum_required(VERSION 3.15)

# Set the project name and version
project(App VERSION 1.0 LANGUAGES CXX)

# Enable C++23
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add include directories if you have headers
include_directories(include)

# Add the executable target (replace main.cc with your actual source files)
add_executable(app src/main.cc)

# Optionally add additional libraries if required
# target_link_libraries(app some_library)