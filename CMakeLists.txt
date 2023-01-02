cmake_minimum_required(VERSION 2.8)
project(main)

add_definitions("-Wall -g -Wno-unknown-warning-option"
        " -Wno-format-extra-args -Wno-format -Wno-pragmas"
        " -Wno-incompatible-pointer-types")

add_executable(main
    main.cpp
)

