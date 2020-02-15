cmake_minimum_required(VERSION 3.0)
project(glm-cuda)

add_library(glm-cuda src/glm_cuda_impl.cc)
target_include_directories(glm-cuda INTERFACE 
  ${CMAKE_CURRENT_SOURCE_DIR}/include
)
