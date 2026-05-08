# Adding source code files to the executable
add_executable(
    hello_window
    hello_window.cpp
)
# Linking the necessary libraries
target_link_libraries(
    hello_window
    glfw
    glad
    OpenGL::GL
)

# Other lessons with their associated files and libraries may be added below
# Each lesson will have its own executable

# add_executable(
#     lesson_2
#     lesson_2.cpp
# )

# target_link_libraries(
#     lesson_2
#     glfw
#     glad
#     OpenGL::GL
# )
