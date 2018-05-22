# Heat-bed-anneal
Use 3D printer heated bed for annealing your printed parts. Creates G-code to control the bed as the heater.

This Python program generates Gcode to use a 3D printers heat bed as an annealing oven
Place part to be annealed above the bed and place a cardboard box over it. 
Run the g-code created by this Python program and wait a LONG time.

Based on the parameters you enter, g-code is created that increments the bed temperature every XX minutes
to give the correct temperature ramp ramp rate. It hold at the anneal temperature for the specified time,
and then ramps down.

The part should not be placed directly on the bed, space it above the bed with something that does not
insulate the bottom of the part. The box should cover most of the bed and should seal fairly well to it.
A small slow fan to stir the air is helpful. It must not blow on the part being annealed.

by Eric, May 13, 2018     email: eric@escapehandle.com

See program listing for more information
