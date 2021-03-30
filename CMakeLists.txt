cmake_minimum_required(VERSION 3.12)
project (GF_SDK 
  VERSION 0.0.0
  LANGUAGES Fortran
)
cmake_policy(SET CMP0074 NEW)

option(GIT_SUBMODULE "" OFF)

add_subdirectory(gFTL)
add_subdirectory(gFTL-shared)
add_subdirectory(fArgParse)
add_subdirectory(pFUnit)
add_subdirectory(yaFyaml)
add_subdirectory(pFlogger)