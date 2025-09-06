cmake_minimum_required(VERSION 3.31)

project(
    jRead
    LANGUAGES C
)

add_executable(${PROJECT_NAME} jRead.c main.c)

#target_link_libraries(
#    ${PROJECT_NAME}
#    INTERFACE
#    rocknitive_printf
#)
#
#target_include_directories(
#    ${PROJECT_NAME}
#    INTERFACE
#    ../lib/jsmn
#    ../lib/jread
#    ../lib/jwrite
#)
#
#target_compile_definitions(
#    ${PROJECT_NAME}
#    INTERFACE
#    JREAD_SINGLE_PRECISION
#    JWRITE_SINGLE_PRECISION
#)
