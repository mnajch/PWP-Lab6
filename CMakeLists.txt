cmake_minimum_required(VERSION 2.8.9)

project(PWPlab6)

#-----------------------------------------------------------------------------
# Extension meta-information
set(EXTENSION_HOMEPAGE "http://slicer.org/slicerWiki/index.php/Documentation/Nightly/Extensions/PWPlab6")
set(EXTENSION_CATEGORY "Examples")
set(EXTENSION_CONTRIBUTORS "Mateusz Mnich (Politechnika Slaska)")
set(EXTENSION_DESCRIPTION "PWP, lab6, Mnich Mateusz Iwm1")
set(EXTENSION_ICONURL "http://www.example.com/Slicer/Extensions/PWPlab6.png")
set(EXTENSION_SCREENSHOTURLS "http://www.example.com/Slicer/Extensions/PWPlab6/Screenshots/1.png")

#-----------------------------------------------------------------------------
# Extension dependencies
find_package(Slicer REQUIRED)
include(${Slicer_USE_FILE})

#-----------------------------------------------------------------------------
# Extension modules
add_subdirectory(module)
## NEXT_MODULE

#-----------------------------------------------------------------------------
include(${Slicer_EXTENSION_CPACK})
