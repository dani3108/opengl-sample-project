# =========================================
# Compile flags
# =========================================

if (MSVC)
    add_compile_options(/W4 /permissive-)
else()
    add_compile_options(
        -Wall
        -Wextra
        -Wpedantic
        -Wconversion
    )
    if (CMAKE_CXX_COMPILER_ID MATCHES "Clang")
        add_compile_options(
            -Wconditional-uninitialized
        )
    endif()
endif()

# =========================================
# Lessons
# =========================================

# 1. Hello Window
add_demo(hello_window lesson_1_hello_window/hello_window.cpp)
