Greg's Wade reloaded
==================
This derivative of Greg's Wade Extruder collects all the best ideas and latest features and improvements:

* Greg's excellent "Guidler" for perfectly lined up filament feed AND easy access of the hobbed bolt
* Tiltable idler-screws for opening the idler without removing the screws entirely
* 4mm elevation of whole extruder body/bolt/motor mount to allow slightly bigger 9/47 herringbone gears
* 2mm extra bolt-motor-distance for the same reason
* M4 nuts and screws for idler, since M3 screws in more than 60mm length are sometimes hard to source (at least in the common hardware stores of northern germany..)
* Well, 9/47 herringbone gears!
* All nut-traps have been corrected for correct fit (all prusa parts seem to use slightly wrong sizes.. should be 5.5mm wrench size for M3 nuts, I changed all of them to the right ISO values with additional 0.2mm clearance. Fits great for a precisely calibrated prusa)
* Additional hotend-mount option "reprapfaborg" for Stoffel15's great hotends that use 10mm shaft diameter of 20mm length (shown on one of the pictures as a cut-view); you can get one via reprap-fab.org
* 8mm thickness of motor mount (instead of 10mm) in reference to wider herringbone gear

I made STL-exports for these three hotend-mounts:
* groovemount
* jhead mount
* reprap-fab.org

My configurations were made for 0.25mm layerheight (using 0.35mm nozzle), so if you're using larger values please change the parameter in the SCAD and export your own STL. Otherwise the support-layers of bearing-hole and idler mount may not be sliced correctly.

Enjoy!
Updates
==================
UPDATE 2012-03-12:

As Zarquon requested via comments, I uploaded a SAE compatible version of the groovemount-extruder-body as well as the big gear. Actually I simply replaced the parameters for M3/M4/M8 nuts to the values Zarquon submitted. Please leave a comment if something still doesn't fit.

UPDATE 2012-03-16:

* Added gear-sided nut traps for GRRF hotend mount in the main wade SCAD file
* Uploaded additional small gear STL for 4.2mm center hole diameter as requested by pharaohabq in the comments

UPDATE 2012-03-26:

* Added new parameter "less_idler_bolt_dist" to adjust distance between idler and hobbed bolt, in case the idler isn't exactly vertical when tightened but slightly angled towards to hobbed bolt, which could cause the spring loaded screw to popp off the slots to the top of the idler. Default is "0", adjust for your own requirements if neccesary.

------

Files collected from: http://www.thingiverse.com/thing:18379
