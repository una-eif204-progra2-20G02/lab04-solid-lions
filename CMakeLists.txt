cmake_minimum_required(VERSION 3.14)
project(lab04-solid)

set(CMAKE_CXX_STANDARD 17)
add_executable(game Game.h Game.cpp MainGame.cpp Idiscount.h  DigitalGame.cpp DigitalGame.h StreamingGame.cpp StreamingGame.h PhysicalGame.cpp PhysicalGame.h)