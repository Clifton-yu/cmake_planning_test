
cmake_minimum_required(VERSION 3.29.0)
project(planing)
set(CMAKE_CXX_STANDARD 17)


aux_source_directory(. SRC_LISTS)
add_executable(plannig_main ${SRC_LISTS})

set_target_properties(
    plannig_main PROPERTIES
    RUNTIME_OUTPUT_DIRECTORY
    ${PROJECT_SOURCE_DIR}/bin
  )