Note that as of 17 June 2023, I deleted the adapter to go from the 0.75" square aluminum to Thrustmaster thread. It wasn't finished. I'd recommend using the direct to thrustmaster Gimbal right now until I get the new version up.

VPForceKit-ffb-joystick-base plywood WIP
This project contains CAD files necessary for the mechanical assembly of a base of the VPForce kit (2x57BLF03 + USB kit).
This fork uses plywood available in the U.S. 1/4" or 1/2" rather than the 8mm from the original files. My laser cutter can only do 1/4" plywood reliably so I double stack each cut for a total of 1/2" thick walls. In some cases like the top, the bottom peice is different from the top peice in order to accomodate 2.5D features like switch cutouts. Making the walls thicker also required the bearing retainers be re-made so those have been updated as well.

Additionally this adds different gear profiles that allow for higher gear ratios and no need to buy exact belt sizes or worry about belt tension. It also includes a gimbal adapter allowing 2020 aluminum extrusion as an extension before the actual stick is installed. 

![image](new_FFB_VPForce.jpg) 

3d-print-parts - all elements which need to be printed  
DXF - drawings for case parts for laser cutting  
CAD - full STP assembly

## Bill of Materials

| VPForce Kit   | Quantity | Link |
|-------------- |:--------:|-----:|
|57BLF03 - 57x101mm - 1.6Nm peak - 1.24kg - NEMA23|1|[link](https://vpforcecontrols.com/) |

| Print Parts   | Quantity |
| ------------- |:--------:|
|bearing_retainer_half|4|
|bearing_retainer|4|
|customizable_fan_cover v3|1|
|GIMBAL_ARM_BEARING_PILLOW|4|
|GIMBAL_ARM_FRAME|2|
|GIMBAL_CORE_JOINT_6mm|1|
|GIMBAL_STICK_CONNECTOR|1|
|Top_Adapter |1|
|PULLEY_96T|1|
|PULLEY_128T|1|
|VPForce_Controller_Holder|1|
|USB-B Panel Mount |1|

| LaserCut Parts Plywood 1/4"| Quantity |
| -------------- |:--------:|
|Rear|2|
|Bottom|2|
|Front|2|
|Left-Side|2|
|Mid-Panel|2|
|Right-Side|2|
|Top-Top |1|
|Top-2nd-Layer |1|

| Bearings                      | Quantity  | Link |
| ----------------------------- | --------- | ---- |
| 6802 (24x15x5mm)              | 8  |[link](https://www.ebay.com/itm/144972685318) |
| 6808 (52x40x7mm)              | 4  |[link](https://www.ebay.com/itm/131569718806) |
| F625 (16x5x5mm, 18x1mm flange)| 2  |[link](https://www.ebay.com/itm/143709341709) |


| Motor pulley                  | Quantity  | Link |
| ----------------------------- | --------- | ---- |
| 3GT -16Tooth-8mm Bore         | 2  |[link](https://www.ebay.com/itm/225592008473) |

| Belts                  		| Quantity  | Link |
| ----------------------------- | --------- | ---- |
| 3GT-3mm Open Loop Timing Belt | 1 meter|[link](https://www.ebay.com/itm/224467077690?var=523250397611) |

|Electronics                |Quantity | Link|
|---------------------------| -------- | ---- |
|DIN5 Female Connector      | 1  |[link] (https://www.digikey.com/en/products/detail/cui-devices/MD-50PL100/500828)|
|XT 60 Panel Mount Male & Female  | 2 (1ea)  |[link] (https://a.co/d/0gA4TEY) |
|19V 180W+ DC Power Supply | 1  | [link] (https://a.co/d/iy1mMZF)|
|Emergency Cutoff Switch 10A| 1  |[link](https://a.co/d/2vKUG6i) |
|10k Potentiometer          | 2  |[link] (https://a.co/d/dEJRBl2) |
|5 Conductor Cable          | 1ft| |
|80mm 24V fan | 1| [link](https://a.co/d/5TQbYCp)|
|USB-B Panel Mount | 1| [link](https://a.co/d/8rjkGPT)|

|Hardware                |Quantity | Link|
|---------------------------| -------- | ---- |

|M4x12mm Bolts for Bearing Pillows  |  8  | [link](https://www.boltdepot.com/Product-Details.aspx?product=13341)|
|M6x20mm Motor Mount Bolts          |  8  | [link](https://www.boltdepot.com/Product-Details.aspx?product=13352) |
|M6 Motor Mount Lock Washers        |  8  |[link]( https://www.boltdepot.com/Product-Details.aspx?product=4813) |
|M6 Motor Mount Washers        |  8  | [link](https://www.boltdepot.com/Product-Details.aspx?product=4516) | 
|M5x12mm Aluminum Square Tube to gimbal  | 8 | [link](https://www.boltdepot.com/Product-Details.aspx?product=13344) |
|M5x50mm Bolt through center gimbal connector | 1| [link](https://www.boltdepot.com/Product-Details.aspx?product=13344) |
|M5 Washer |  2 | [link](https://www.boltdepot.com/Product-Details.aspx?product=4515)|
|M5 Lock Nut | 1 | [link](https://www.boltdepot.com/Product-Details.aspx?product=4794)|
|M4 Locking Hex Nuts for Gimbal Arms | 12| [link](https://www.boltdepot.com/Product-Details.aspx?product=4793)|
|M4x35mm Cap Bolts to connect gears to Gimbal Arms | 12 | [link](https://www.boltdepot.com/Product-Details.aspx?product=18949)|
|M2.5 screws to hold VPForce board to standoffs |4|[link](https://www.boltdepot.com/Product-Details.aspx?product=24854) |
|M3x25 bolts to hold bearing holders in place | 16|[link]( https://www.boltdepot.com/Product-Details.aspx?product=18942) |
|M3 lock nuts | 16|[link]( https://www.boltdepot.com/Product-Details.aspx?product=4792)|
|M3 lock washers | 16 | [link](https://www.boltdepot.com/Product-Details.aspx?product=4810)|
|M3 washers |32 |[link](https://www.boltdepot.com/Product-Details.aspx?product=4513)|
|Bolt Depot with all hardware above| [link]([https://www.boltdepot.com/cart/215477](https://www.boltdepot.com/cart/215482))||
|M3 screws to install VPForce board into chassis |2| |
|#8-1" Self Drilling Wood Screws        |  20? | [link](https://a.co/d/aeVexTG)https://a.co/d/aeVexTG |
|Hardware to mount to your SIM PIT | 4 | |
|M4 Inserts High Quality | 8| [link](https://a.co/d/0r7RgK8)|


