cmake_minimum_required(VERSION 3.20)
project(CppProjectTemplate VERSION 1.0)

set(CMAKE_CXX_STANDARD CXX17)
set(CMAKE_CXX_STANDARD_REQUIRED True)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR})

include_directories("./includes/")

add_executable(
  ${PROJECT_NAME}
  "./src/main.cpp"
)
