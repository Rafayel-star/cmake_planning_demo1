cmake_minimum_required(VERSION 3.30.2)
project(planning
VERSION 0.0.1
DESCRIPTION "a demo of cmake planning"
HOMEPAGE_URL "https://github.com/Rafayel-star/cmake_planning_demo1"
LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD 17)

#设置变量
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/bin)
set(Process_Dir ${CMAKE_SOURCE_DIR}/src/process)
set(PNC_Map_Dir %{CMAKE_SOURCE_DIR}/src/pnc_map)

#添加子目录
add_subdirectory(src)
