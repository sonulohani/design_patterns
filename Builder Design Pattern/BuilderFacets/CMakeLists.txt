cmake_minimum_required(VERSION 3.5)

project(BuilderFacets LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(BuilderFacets 
	PersonAddressBuilder.h 
	PersonBuilder.h 
	Person.h 
	PersonJobBuilder.h 
	Facets.cpp 
	PersonBuilder.cpp 
	Person.cpp)
