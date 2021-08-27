# gayatri-marlin
Edits to Marlin to allow simultaneous infill with two extruders

 There are two main changes:
 - `Configuration.h (Line 573)`
 - `Marlin_main.cpp` in the implementation of `gcode_M605()` starting at `Line 6478`.
