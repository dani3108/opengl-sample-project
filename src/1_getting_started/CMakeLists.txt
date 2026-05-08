# =========================================
# Hello Window
# =========================================

add_executable(
    hello_window
    hello_window.cpp
)

target_link_libraries(
    hello_window
    glfw
    glad
    OpenGL::GL
)

# Add other lessons here
# Each lesson will have its own .exe file
