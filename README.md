# Heat-bed-anneal
Use 3D printer heated bed for annealing your printed parts. Creates G-code to control the bed as the heater.

This program generates Gcode to use a 3D printers heat bed as an annealing oven
by Eric, May 13, 2018     email: eric@escapehandle.com

!!!!! I found that the sleep command G4 displays Sleep..... and I cannot get
my desired display of the countdown time to show. I suppose it does flash
between each temperature change but it is not visible.
Only solution I see is to overload the G4 command so that it can take a 
text string to display. I guess this could be my addition to Marlin.

Version 2.02
User inputs expanded to include
	Name
	Anneal temperature, deg C
	Heating rate
	Soak time
	Cooling rate
Writes file in same directory as the source code & waits for an ENTER before closing
Most anneal parameters from:  http://www.plasticsintl.com/literature-pdf-library.htm
http://www.4spepro.org/view.php?article=005392-2014-03-28 looks good for PLA
