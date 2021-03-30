cmake_minimum_required(VERSION 3.12)
project (GF_SDK 
  VERSION 0.0.0
  LANGUAGES Fortran
)

option(GIT_SUBMODULE "" OFF)

add_subdirectory(gFTL)
add_subdirectory(gFTL-shared)
add_subdirectory(fArgParse)
add_subdirectory(pFUnit)