cmake_minimum_required(VERSION 3.10)

project(main.cc)

add_executable(main main.cc utils.h hittable.h hittable_list.h sphere.h material.h)
