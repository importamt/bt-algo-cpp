cmake_minimum_required(VERSION 3.17)
project(bt_algo_cpp)

set(CMAKE_CXX_STANDARD 14)

add_executable(bt_algo_cpp programmers/hash/phone_number_list/phone_number_list.cpp programmers/hash/phone_number_list/phone_number_list.h programmers/hash/phone_number_list/phone_number_list_test.cpp programmers/hash/phone_number_list/phone_number_list_test.h)