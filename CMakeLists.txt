cmake_minimum_required(VERSION 3.9)
project(Update)

set(CMAKE_CXX_STANDARD 11)
set(BUILD_USE_64BITS on)
#add_executable(Update 01.cpp com_epro_zlw_Main.h)
add_library(Update SHARED blocksort.c bzlib.c bzlib.h bsdiff.cpp example_BsDiff.h
        bzlib_private.h compress.c crctable.c decompress.c huffman.c jni_md.h jni.h randtable.c)