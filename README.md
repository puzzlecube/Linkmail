Linkmail: Parametric modular semi print-in-place linkable mesh!

Linkmail is an overly parametric linkable NASA style chainmail type fabric in which an end piece is indestinguishable from ones printed in the center. Designed to be printable on any FDM 3D printer but it also has some helper features that leverage some special tools available in Slic3r Prusa Edition and probably Slic3r regular edition.

WARNING: This openSCAD file has a bunch of parameters, some of which probably shouldn't be touched unless you know what you're doing. Lots of them have extreme, unintended, or undesirable effects on the general form and thus the function of the parts. Default presets are designed for a less than ideal situation so things, "should?" print okay with the default parameters but the customization option is there.

Printing advice:
	99% certain that you will break at least one chain every so often so I have included singular pieces as spare or just for printing singular. 100% sure you will break one if you're impatient like me. ;)
	I printed all of mine in Priline PETG (Mid-grade PETG) that may or may not have been slightly wet and they almost all turned out usable and pretty strong for how thin the rings are.
	Make sure you've got your prints to have as little stringing as possible because any stringing becomes a pain in the rear REALLY fast with these and inhibits or completely stops the parts from being assembled.
	BE EXTREMELY GENTLE WHEN FREEING THE CHAINS FROM ANY SUPPORT MATERIAL YOU PRINT WITH! I find a set of round tipped pliers usually used for beads to be an incredible asset to my chain links but needle nose should work too.
	Before assembling the caps and chains together I found success only after the holes were primed a bit with the forementioned round nosed pliers but anything connical and about pinRadius milimeters in radius at some point on the cone. I am nearly certain this is a problem because of the monsterous stringing.
	This information and more is written at the top of the OpenSCAD file.

TODO:
	Other geometries and tesselating shapes to allow for more flex control
	Fittings for things that can allow for cross compatability, or maybe just more fun.
	fix printCapAndChains.
	fix protrusion.
	refactor the annoying multiple bools controlling which part to render.
	set asside an hour or two to allow for rendering really big patches.
