cmake_minimum_required(VERSION 3.23)
enable_testing()
project(warped2 VERSION 1.0.0 DESCRIPTION "warped2-models" LANGUAGES C CXX)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
set(CMAKE_CXX_STANDARD 17)

find_package(MPI REQUIRED)

set(WARPED2_INSTALL_DIR ${PROJECT_SOURCE_DIR}/../warped2/install)

add_subdirectory(models/airport)