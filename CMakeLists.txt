cmake_minimum_required(VERSION 3.20.0) 
project(Planning)
set(CMAKE_CXX_STANDARD 17)
 
set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)

aux_source_directory(. SRC_LISTS)

add_executable(
    PlanningMain
    ${SRC_LISTS}
)