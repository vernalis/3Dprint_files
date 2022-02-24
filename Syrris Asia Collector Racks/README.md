# Syrris Asia Collector Racks

## Overview

Modular 3D printed racks compatible with the Syrris Asia Automated Collector (Gilson FC203B). A keyway .stl file has also been supplied allowing further designs to be made that will interlock into the Automated Collector bed. 

![CAD Diagram][CAD]

[CAD]: CAD.png

The racks have been designed to hold the following vials:
* 8mL: 15-425 Screw Neck, 17 mm × 60 mm (e.g [Supelco 27072-U](https://www.sigmaaldrich.com/GB/en/product/supelco/27072u)) 
* 30mL: 24-400 Screw Neck, 72.5 x 27.5mm (e.g [BGB EPA30](https://www.bgb-info.com/product.php?productid=941987)) 

## Folder Contents

Each rack comprises of six .stl files that make up the rack, alongside two .rmr files wich can be imported into Syrris Asia Manager to quickly provide rack geometries that can be fine-tuned based on your print. The .rmr file with suffix _V10 partially fills the vial to just below half full - allowing it to be used directly on a Biotage V10 evaporator. 

## Assembly Instructions

All components were printed in PLA. Parts were stuck together using a polypropylene (PP) glue gun, however other adhesives could also be used. Note: Apply as minimal glue as possible to ensure a flush fit, with no gaps between parts. 

Apply glue to both ends of the base component. Glue need not be applied to the lugs.

Using the collector bed as a jig, quickly affix the front and rear pieces to the base. 

Whilst glue is still setting repeat the process with the mid and then top layers - applying glue to end surfaces of the layer, and then introducing the layer at a diagonal angle into the front lug holes before levelling to insert the rear lugs. 

Apply glue to the flat surface of the handle that will contact the rear of the rack. Insert the handle lugs into the rear panel. 

Once fully assembled allow glue to set before use. 

## Asia Manager Setup 

Navigate to the Configuration menu in Asia Manager, then open the Rack/Layout editing sub menu. 

In the Rack Definitions tab, right click on the table of current racks and click import and select the rack .rmr file. 

Move to the Layout Definitions tab, click Add. 

Enter a name and description. Select the "PCM using FC203b robot and gilson deck" template. 

Click next. Click add and then select the imported rack from the Rack type drop down menu.

Click next, acknowledge any errors (e.g. overhangs the bed area) and then finish. 

The rack can then be selected in manual control mode, tested by moving the collector head to varying positins and fine adjustments made in the Rack Definitions settings area. 
