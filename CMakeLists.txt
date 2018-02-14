cmake_minimum_required(VERSION 2.4.6)

project(sophus)

catkin_package(
  INCLUDE_DIRS include
  LIBRARIES sophus)

include_directories(include)
add_subdirectory(sophus_src)
