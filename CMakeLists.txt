cmake_minimum_required (VERSION 3.17)



# ===================
# Project Definition
# ===================

set (Project_Title "Chopper Rush")
set (Project_Description "C++ Videogame Project with Vulkan API. Learning from scratch to code in C++ and Vulkan with this project.")
set (Project_Author "Wasym A. Alonso")
set (Project_Version_Major 0)
set (Project_Version_Minor 1)
set (Project_Version_Patch 0)

set (Project_Version "${Project_Version_Major}.${Project_Version_Minor}.${Project_Version_Patch}")

set (Project_Copyright_Date "2022-2022")
set (Project_Copyright "Copyright © ${Project_Copyright_Date} ${Project_Author}.")

string(TOUPPER ${My_Project_Title} My_Project_Title_Caps  )
string(REGEX REPLACE " " "_" My_Project_Title_Caps ${My_Project_Title_Caps} )

project (${Project_Title})


# ======================
# Project Configuration
# ======================

