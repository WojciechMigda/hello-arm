# based on https://github.com/Bagira80/More-Modern-CMake

cmake_minimum_required( VERSION 3.5 )

project( hello-arm )

 # Always use '-fPIC'/'-fPIE' option.
set( CMAKE_POSITION_INDEPENDENT_CODE ON )

# Create the targets for the entire example-app.
add_subdirectory( app )
