# KiCAD Libraries and Modules
updated and ordered KiCAD Library of symbols and Modules (footprints)
also added 3dModels

it contains common elements (at least in my bench:]), removed exotic ones

## IMPORTANT
in Kicad define custom path `$KUBALIBS` - all paths are relative to it, 
and `$KUBADATASHEET` - for datasheets PDF files,
or manually edit files and do massive replace with your preferences or sth


## 3D Models
KiCad accepts VRML 2.0
* look for `.step` `.stp` `.wrl` `.sldprt` `.dae` `.skp` etc.
* `.step` `.stp` etc. -> open with FreeCAD -> export to `.wrl`
* open with MeshLab -> export as `.dae` to sketchup
* in Sketchup resize/move to origin, paint with colors (kicad doesn't show textures) -> export to `.wrl` (but its VRML v1.0 - it looks messy in KiCAD)
* open in MeshLab -> export as `.wrl` (and now its VRML 2.0)
* copy to proper place in KiCad -> hooray its finished


## other notes
### SolderMask Colors:
* Green PCB color code #008C4A rgb(0, 140, 74)
* Black PCB color code #000000
* White PCB color code #ECECDF
* Blue PCB color code #4990E2
* Red PCB color code Red: #D0011B
* Yellow PCB color code Yellow: #F6A624 
