cmake_minimum_required(VERSION 3.5)

project(AbstractFactory LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(AbstractFactory 
	Creational.Creational.AbstractFactory.cpp
	Creational.Creational.CoffeeFactory.h
	Creational.Creational.DrinkFactory.h
	Creational.Creational.HotDrinkFactory.h
	Creational.Creational.HotDrink.h
	Creational.Creational.TeaFactory.h)
