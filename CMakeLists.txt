cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "Adafruit_Sensor.cpp" "Adafruit_Sensor.h"
                       INCLUDE_DIRS "."
                       REQUIRES arduino)

project(Adafruit_Sensor)