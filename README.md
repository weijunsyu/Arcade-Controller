# Arcade-Controller
- Collection of CAD files for custom arcade controllers.
- dxf files can be opened/modifed using LibreCAD.
- All controllers are designed for arcade screwbuttons with plate mount MX-style keyboard switches for mixbox styles.
- Plate mount MX-style keyboard switches require a structural panel (the plate) to be 1.5mm (+/- 0.1mm) thick to be properly mounted!
- Recommended total top panel thickness (including any acrylic panels) to not exceed 10mm.
- Many top panels have extra button cutouts (button layout) to be easily customized by removing unwanted extras.
- Most dxf files are imperial but some are metric. If in doubt check the metadata (HEADER variable: $INSUNITS; 1:=inches, 4:=millimeter)

## Customs
- Custom projects and one-offs.
- Use these as reference or inspiration or attempt them yourself.
- Note: Not all designs here have been tested, some builds in here may have CAD files that require post-processing and further machining that may not always be documented.

## Metal Arcade Controller
- Dimensions: 16" x 8" x (2.063 + acrylic panel thickness)"
- Designed to be assembed with just M4 machine screws (10 screws total).
- Uses a standard Neutrik USB A-B connector.
- There are no PCB mount points for compatibility; use adhesive mounting hardware.
1. **Acrylic Top Panels:**
    - Optional acrylic top panels
1. **Chassis:**
    - Required to be constructed from 0.063" thick sheet metal.
    - Recommended material: 5052 Aluminum.
    - Dashed lines denote bend lines. Blue for down, and red for up.
    - Bottom half requires the 4 smaller M4 holes (d=0.164") to have flush mounted threaded nuts be inserted.
    - Bottom half has 2 versions: One with a stick cuttout for inserting a screwdriver into the back without opening the box and one without.
    - Top half files are located within the subfolder "chassis_TopHalf (.063in)".
    - Top half requires the 6 smaller M4 holes (d=0.164") to have flush mounted threaded nuts be inserted.
3. **Layout Template Images:**
    - Image files for doing custom art prints.
    - Act as templates for cutting and lining up prints.
    - 300 dpi image.

## Industrial Arcade Controller
*SPECIAL CONSIDERATIONS: Designed to be very modular; however, assembly requires 6 custom support blocks of which are difficult to manufacture. Support blocks are easily the most costly component in this build. These support blocks are essentially the "core" of the entire build.*
- Dimensions: 14.5" x 9" x (2 + top and bottom panel thickness)" Note: If side/front/back panels are significantly thick, outside dimensions may not be accurate.
- Can be easily modifed for any height, length, material, etc.
- Designed to be assembled with 6 support blocks and M4 machine screws (26 screws total). Note, 4 support blocks can be used (omitting the 2 central supports).
- Most mounting holes are sized for a VERY close fit (d=4.04mm for M4); relax the tolerences if not using a laser to do manufacturing. Non-metal panels should always be modified to have larger tolerences (recommend d=4.5mm for M4).
- If using the front panel with buttons, REMOVE the top row of buttons/toggle cutouts from the top panel!
- Uses a standard Neutrik USB A-B connector.
- There are no PCB mount points for compatibility; use adhesive mounting hardware.
1. **Accessories:**
    - Various accessories such as handles that can be used.
    - NOTE: Some accessories require specific panels to be chosen!
    - Neutrik Covers:
        - The 1x cover is universal and fits any Neutrik cutout. (Identical to the cover found in the Parts folder.)
        - The 2-5x covers are designed for any panel with the "combined" keyword in the file name; used to cover multiple ports at once.
2. **Layout Template Images:**
    - Image files for doing custom art prints.
    - Act as templates for cutting and lining up prints.
    - 300 dpi image.
3. **Top Panels:**
    - Acrylic panels are meant to be clear covers over a structural panel and not meant to be the sole top panel.
    - If there is no explicit acrylic panel, modify the standard top panel for the acrylic panel (increase M4 hole tolerences).
    - Most panels use the Sega 2P layout.
    - Mixbox panels use plate mount MX-style keyboard switches for the movement buttons.
4. **Universal Panels:**
    - These are the shared panels for the sides, front, bottom, and back.
    - The side/front/back panels have various versions with extra button cutouts, extra Neutrik cutouts, and combined cutouts.
    - Default panels are 2" tall to accommodate japanese screwbuttons and quick disconnects regardless of top panel thickness.
    - The bottom panel has 2 versions: One with a stick cuttout for inserting a screwdriver into the back without opening the box and one without.
5. **Support Blocks:**
    - Support blocks can be machined from 1/2" square stock.
    - Meant to be tapped with M4 threads.
    - If machining supports by hand or if looser tolerences are desired, consider widening all panel mounting holes (M4) to d=4.5mm or even d=4.8mm to accommodate imperfect machining on support blocks.
    - STEP file and technical drawing is provided.
    - A STL file is provided for 3D printing that is designed to be screwed directly into. Will need modification if M4 inserts are desired.
    - Consider using wooden blocks if manufacturing costs are too high.

## Parts
- Various arcade parts.
- Files contain a mix of imperial and metric units! (Inches/Millimeter)
- JLF mounting plate can be countersunk for M3 screws; original plate is 1.5mm thick.

## Layouts
- Various layouts for button placements.
- Contains folders for different types of layouts:
    - Master Layouts: layouts with all lines for various iterations of which need to be modified prior to use.
    - Partial Layouts: layouts containing only partial cutouts, mainly for use when designing custom layouts not iterating off any master layout.
    - Finished Layouts: layouts that are finished and ready-to-cut. Contains various iterations of pre-modified master layouts and some unique layouts.
- Subfolders further segregate based on style of action button placement such as sega2P, viewlix, noir, etc.

## References
- Collection of reference files such as technical drawings and CAD files.

# Technical
- Neutrik:
    - centre cutout: d=0.935" r=0.4675"
    - mounting holes: d=0.13" r=0.065"
- 30mm btn: 30.25mm / 1.19094488"
    - radius: 0.59547244"
- 24mm btn: 24.2mm / 0.95275590"
    - radius: 0.47637795"
- M2 d=2.39mm (0.099") r=1.195mm (0.0495")
- M2.5 d=2.49mm (0.103") r=1.245mm (0.0515")
- M3 d=3.18mm (0.130") r=1.59mm (0.065")
    - Close fit d=3.2mm (0.126") r=1.6mm (0.063")
    - Normal fit d=3.4mm (0.134") r=1.7mm (0.067")
    - Loose fit d=3.6mm (0.142") r=1.8mm (0.071")
- M4 d=4.04mm (0.164") r=2.02mm (0.082")
    - Close fit d=4.3mm (0.169") r=2.15mm (0.085")
    - Normal fit d=4.5mm (0.177") r=2.25mm (0.089")
    - Loose fit d=4.8mm (0.189") r=2.4mm (0.095")
- M5 d=5.00mm (0.202") r=2.50mm (0.101")
- M6 d=6.35mm (0.255") r=3.175mm (0.1275")
- M8 d=8.00mm (0.320") r=4.00mm (0.16")