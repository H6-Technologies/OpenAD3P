# Adventurer3Pro
Conversion of a Flashforge Adventurer 3 Pro into an open-source Core XZ enclosed printer

Welcome to the official project documentation for "OpenAD3P". I am modifying a bone stock FlashForge Adventurer 3 Pro enclosed 3D printer into an open source CoreXZ printer.

Stock Specs:
- Hotswappable 240 & 265 degree nozzles
- 150x150x150 build volume
- 24V/5v Power Operation
- Up to 100mm/s print speed

OpenAD3P Planned Features:
- Klipper Firmware w/ SKR Mini E3 v3 Mainboard & Raspberry Pi Controller
- Ender 3 MK8 All-metal hotend 0.4mm 0-260C nozzle
- 3x3, 4x4, 5x5 Auto Bed Leveling Matrix
- Input Shaping support
- PEI Build Plate & Glass Build Plate
- Up to 300 mm/s print speed (estimated, may need motor upgrade)

Parts List:
SKR Mini E3 v3 Mainboard
Raspberry Pi 3 or 4 (Not Zero)
Ender 3 MK8 All Metal Hotend
2- ADXL345 3-Axis Accelerometers
LML9B Linear Guide Rail
BLTouch Sensor

Printed Parts:
(Pending) Bed Adapter for Linear Rail
(Pending) AD3P>E3V2 Hotend Adapter
(Pending) Mainboard Mounting Adapter

Since this build will replace the existing hotend and will use Klipper on a old PC as it's control interface, the LCD will also not be retained. 
This build will attempt to use most of the machine parts on the Adventurer 3 Pro except for the mainboard and hotend assembly, which will be replaced with units shown above. 

The build plate assembly will be modified to use linear rails, instead of a bed that is on a small roller and belt driven from underneath.
