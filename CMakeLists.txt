cmake_minimum_required(VERSION 2.8)
project(cblas_dgemm_dummy CXX)
add_library(cblas_dgemm_dummy_static STATIC cblas_dgemm_dummy.cpp)
add_library(cblas_dgemm_dummy SHARED cblas_dgemm_dummy.cpp)
