cmake_minimum_required(VERSION 3.20)
project(learnCpp)
set(subDir Cpp_11_14_Houjie)
# set(targetDir ${subDir}/1_Start)
# set(targetDir ${subDir}/2_VariadicTemplate)
# set(targetDir ${subDir}/3_nullptr_auto)
# set(targetDir ${subDir}/4_uniformInitialization)
# set(targetDir ${subDir}/5_initializerList)
# set(targetDir ${subDir}/6_ExplicitCtors)
set(targetDir ${subDir}/7_rangeBasedForStatement)


set(CMAKE_BINARY_DIR ${CMAKE_SOURCE_DIR}/build)
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_BINARY_DIR})
add_subdirectory(${CMAKE_SOURCE_DIR}/${targetDir})
