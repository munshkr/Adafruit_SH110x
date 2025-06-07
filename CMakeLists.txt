# Adafruit_SH110x
# https://github.com/adafruit/Adafruit_SH110X
# BSD License

cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS
  "Adafruit_SH110X.cpp"
  "Adafruit_SH1106G.cpp"
  "Adafruit_SH1107.cpp"
  INCLUDE_DIRS "."
  REQUIRES arduino-esp32 Adafruit-GFX-Library)

project(Adafruit_SH110x)
