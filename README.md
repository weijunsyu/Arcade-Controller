# Arcade-Controller
- Collection of CAD files for custom arcade controllers.
- Recommended total top panel thickness (including any acrylic panels) to not exceed 10mm.
- Recommended total top panel thickness is reduced to 3mm for snap-in buttons with a minimum thickness of 2mm.
- Plate mount MX-style keyboard switches require a structural panel (the plate) to be 1.5mm (+/- 0.1mm) thick to be properly mounted!
- Most .dxf files are imperial but some are metric. If in doubt, check the metadata (HEADER variable: $INSUNITS; 1:=inches, 4:=millimeter)

## Industrial Arcade Controller
*SPECIAL CONSIDERATIONS: Designed to be very modular; however, assembly requires 6 custom support blocks of which are difficult to manufacture. Support blocks are easily the most costly component in this build. These support blocks are essentially the "core" of the entire build.*
- Dimensions: 14.75" x 9.25" x (2 + top and bottom panel thickness)" Note: If side/front/back panels are significantly thick, outside dimensions may not be accurate.
- Can be easily modifed for any height, length, material, etc.
- Designed to be assembled with 6 support blocks and M4 machine screws (26 screws total).
- Most mounting holes are sized for a VERY close fit (d=4.04mm for M4); relax the tolerences if not using cnc to do manufacturing.
- Uses a standard Neutrik USB A-B connector (D-cut panel sizing).
- Panels are suffixed "Template" if they are meant to be modified with a layout before manufacture.
- "Cover" panels are optional panels that are meant to be the outermost panels (top/bottom). In the "Slot and Tab" version, these panels can be used to cover the exposed slots to give a more clean look.
1. **Accessories:**
    - NOTE: Some accessories require specific panels to be chosen!
    - D-panel Covers:
        - The 1x cover is universal and fits any d-panel cutout. (Identical to the cover found in the Parts folder.)
        - The 2-5x covers are designed for any panel with the "combined" keyword in the file name; used to cover multiple ports at once.
2. **Partial Templates:**
    - Template files that can be used to block in important features.
3. **Slot and Tab:**
    - Further organized by subfolders of which denote the thickness of the panels needed.
    - These panels have an additional slot and tab structure to further support the assembly.
4. **Supports:**
    - Support blocks can be machined from 1/2" square stock.
    - Meant to be tapped with M4 threads.
    - If machining supports by hand or if looser tolerences are desired, consider widening all panel mounting holes (M4) to d=4.5mm or even d=4.8mm to accommodate imperfect machining on support blocks.
    - STEP file and technical drawing is provided.
5. **Thickness Agnostic:**
    - Panels that do not have any protrusions to facilate the use of any thickness panel. This includes the use of combinations of various panel thicknesses in the same controller.

## Layouts
- Various layouts for button placements.
- Contains folders for different types of layouts:
    - Master Layouts: layouts with all lines for various iterations of which need to be modified prior to use.
    - Partial Layouts: layouts containing only partial cutouts, mainly for use when designing custom layouts not iterating off any master layout.
    - Finished Layouts: layouts that are finished and ready-to-cut. Contains various iterations of pre-modified master layouts and some unique layouts.
- Subfolders further segregate based on style of action button placement such as sega2P, viewlix, noir, etc.

## Mods
- Modifications of exisiting products.

## Parts
- Various arcade parts.
- Files contain a mix of imperial and metric units! (Inches/Millimeter).

## References
- Collection of reference files.

## Tools
- Collection of custom tools. 

# Technical
- MX-style keyboard switches:
    - plate thickness: 1.5mm +/- 0.1mm (0.059" +/- 0.004")
    - 30mm caps: d=1"
    - 24mm caps: d=0.85"
- D-shape housing (Neutrik NAUSB-W):
    - centre cutout: d=0.935" r=0.4675"
    - mounting holes: d=0.13" r=0.065"
- 30mm btn: d=30.25mm (1.19094488")
    - radius: 0.59547244"
- 24mm btn: d=24.2mm (0.95275590")
    - radius: 0.47637795"
    - NOTE: Crown 202 use r=0.482"
- J-lever mounting hole: d=22mm
    - radius: 0.433071"
    - NOTE: Official recommended diameter is 24mm
- K-lever mounting hole: d=35mm
    - radius: 0.6889764" (17.6mm)
- M2 d=2.39mm (0.099") r=1.195mm (0.0495")
    - Thread d=1.66mm (0.065") r=0.83mm (0.033")
- M2.5 d=2.49mm (0.103") r=1.245mm (0.0515")
- M3 d=3.18mm (0.130") r=1.59mm (0.065")
    - Close fit d=3.2mm (0.126") r=1.6mm (0.063")
    - Normal fit d=3.4mm (0.134") r=1.7mm (0.067")
    - Loose fit d=3.6mm (0.142") r=1.8mm (0.071")
- M4 d=4.04mm (0.164") r=2.02mm (0.082")
    - 0.005" fit d=4.04mm (0.164") r=2.02mm (0.082")
    - Close fit d=4.3mm (0.169") r=2.15mm (0.085")
    - Normal fit d=4.5mm (0.177") r=2.25mm (0.089")
    - 0.009" fit d=4.6mm (0.182") r=2.31mm (0.091")
    - Loose fit d=4.8mm (0.189") r=2.4mm (0.095")
- M5 d=5.00mm (0.202") r=2.50mm (0.101")
- M6 d=6.35mm (0.255") r=3.175mm (0.1275")
- M8 d=8.00mm (0.320") r=4.00mm (0.16")

