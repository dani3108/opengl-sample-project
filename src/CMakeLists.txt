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
