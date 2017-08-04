# DXF-to-JSCAD
Latest Update: 03 August 2017

Purpose: The purpose of this program is to convert DXF files to OpenJsCAD paths. This has not been extensively tested and has limited functionality for single closed profiles created with straight lines and splines, only. Tested with Mozilla Firefox and Google Chrome.

Instructions:

1) Design your profile using DraftSight Free (DraftSight 2017 x64 SP1)
	a) Use only straight lines and splines - other paths are not yet supported.
	b) Make sure there are no stray lines or points, and that your profile is closed.
2) Save your DraftSight design as a DXF.
3) Import your DXF into Inkscape (version 0.91 or 0.92).
4) While your profile is selected in Inkscape, click Path -> Combine.
5) Click Edit -> Preferences -> Input/Output -> SVG output and set "Path data" to "Absolute". (Relative coordinates are not yet supported.)
6) Save your file (Inkscape SVG).
7) In svg2jscad.html (tested with Firefox & Chrome), use the "Browse" button to load your SVG file.
8) Click "convert".
9) Copy and paste the text into your OpenJsCAD script.

I apologize for the limited development, but I guess you get what you pay for ;-).  Please feel free to message me with questions, tips, or improvements you make / would like to see.

Hope this helps someone out there!
