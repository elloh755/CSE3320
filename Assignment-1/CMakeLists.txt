#Specify the version being used as well as the language
cmake_minimum_required(VERSION 2.6 FATAL_ERROR)

#Name of the project
project(Assignment-1)

#makecmake aware that we have all our headerfiles in the include
#subdirectory(the include pathshould contain that include_directories(include)

#Could manually add the sources using the set command as follows
set(SOURCES mfs.c)
#but this is easier to add all files of one type

#file(GLOB SOURCES "mfs.c")

#This tell cmake to creake the executable based on those sources
add_executable(Assignment-1 mfs.c)
