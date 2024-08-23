cmake_minimum_required(VERSION 3.5.0)
project(template VERSION 0.1.0 LANGUAGES CXX)
set (CMAKE_CXX_STANDARD 20)
set (CMAKE_CXX_STANDARD_REQUIRED ON)
set (CMAKE_CXX_EXTENSIONS OFF)

file(GLOB SOURCES
    "src/*.cc"
    "src/*.cpp"
)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_executable(template.out ${SOURCES})

target_include_directories(template.out PRIVATE ${PROJECT_SOURCE_DIR}/include)