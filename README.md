OpenGL Glad loader with cmake

## Version
OpenGL 4.5 Core profile.
Generated from [webservice](https://glad.dav1d.de/)

## usage
~~~CMake
add_subdirectory(glad)

# other stuff

set(target target_name)
add_executable(${target} ${SOME_SOURCES})
target_link_libraries(${target}
    PUBLIC
        gl::glad
        ${OTHER_LIBS}
)
~~~