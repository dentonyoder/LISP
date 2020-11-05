# LISP
Autolisp routines for AutoCAD automation

Youtube clip explaining the program: https://youtu.be/OK8eMf-MWZI set the settings to 1080 if you want to read the text...
arrow.lsp (Drag to the AutoCAD screen to load, or place in the AutoCAD Path (I like to add my own folder Options -> Files -> Support file search path -> add your own folder.) or use the command (load"arrow")
  Program defines three new commands: arrow, farrow, sarrow
    arrow reads the dimasz length and multiplies by dimscale to draw a simple arrow.  Two picks minimum, or as many as you want to draw.
    farrow is a Fat Arrow, it is as wide as it is long.  Great for flow charts.
    sarrow is a Spline Arrow.  It draws an arrow then uses the spline command to draw the leader.  You really need to pick a third point to get the effect... Then hit enter to complete it.

Youtube clip explaining the program: https://youtu.be/X2Sa-EwZTn4
clevis.lsp (requires clevis-site and clevis-top blocks to be in the path, or in the drawing)
  Program is an automation example which draws linkage with a 12" clevis on each end of a 2" pipe.
  Choose the starting point (where you are pinning the clevis)
  Hit enter for a side view or type "t" for a top view.
  Choose the end point for the other end of the pole...
  Hit enter for a side view or type "t" for a top view...
  The clevis program and blocks utilize wipeouts to cover anything they cross.
