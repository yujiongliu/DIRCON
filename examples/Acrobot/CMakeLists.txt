# -*- mode: cmake -*-
# vi: set ft=cmake :

configure_file(Acrobot.urdf "${CMAKE_CURRENT_BINARY_DIR}" COPYONLY)
configure_file(Acrobot_floating.urdf "${CMAKE_CURRENT_BINARY_DIR}" COPYONLY)

find_package(GFlags MODULE REQUIRED COMPONENTS shared)

