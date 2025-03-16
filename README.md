# Arcade-Controller
- Collection of CAD files for custom arcade controllers.
- dxf files can be opened/modifed using LibreCAD.
- All controllers are designed for arcade screwbuttons with plate mount MX-style keyboard switches for mixbox styles. Snap-in buttons will fit but keep in mind the top panel total thickness.
    - Recommended total top panel thickness (including any acrylic panels) to not exceed 10mm.
    - Recommended total top panel thickness is reduced to 3mm for snap-in buttons with a minimum thickness of 2mm.
- Plate mount MX-style keyboard switches require a structural panel (the plate) to be 1.5mm (+/- 0.1mm) thick to be properly mounted!
- Most dxf files are imperial but some are metric. If in doubt, check the metadata (HEADER variable: $INSUNITS; 1:=inches, 4:=millimeter)

## Industrial Arcade Controller
*SPECIAL CONSIDERATIONS: Designed to be very modular; however, assembly requires 6 custom support blocks of which are difficult to manufacture. Support blocks are easily the most costly component in this build. These support blocks are essentially the "core" of the entire build.*
- Dimensions: 14.75" x 9.25" x (2 + top and bottom panel thickness)" Note: If side/front/back panels are significantly thick, outside dimensions may not be accurate.
5. **Support Blocks:**
    - Support blocks can be machined from 1/2" square stock.
    - Meant to be tapped with M4 threads.
    - If machining supports by hand or if looser tolerences are desired, consider widening all panel mounting holes (M4) to d=4.5mm or even d=4.8mm to accommodate imperfect machining on support blocks.
    - STEP file and technical drawing is provided.
    - A STL file is provided for 3D printing that is designed to be screwed directly into. Will need modification if M4 inserts are desired.

## Layouts

## References
- Collection of reference files such as technical drawings and CAD files.

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
    - Close fit d=4.3mm (0.169") r=2.15mm (0.085")
    - Normal fit d=4.5mm (0.177") r=2.25mm (0.089")
    - 0.009" fit d=4.6mm (0.182") r=2.31mm (0.091")
    - Loose fit d=4.8mm (0.189") r=2.4mm (0.095")
- M5 d=5.00mm (0.202") r=2.50mm (0.101")
- M6 d=6.35mm (0.255") r=3.175mm (0.1275")
- M8 d=8.00mm (0.320") r=4.00mm (0.16")
