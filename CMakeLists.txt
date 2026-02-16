cmake_minimum_required(VERSION 3.18)
project(dattorro-verb)

add_library(dattorro-verb verb.c verb.h verb_structs.h)
target_include_directories(dattorro-verb PUBLIC .)
