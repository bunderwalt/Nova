cmake_minimum_required(VERSION 3.16)

project(Nova
    VERSION 1.0
    LANGUAGES C
)

add_executable(nova_compilator
    src/main.c
)

target_compile_features(nova_compilator PRIVATE c_std_11)