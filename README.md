# SMuFF remix
SMuFF for Duet 3d Printer by technik-gegg


Remix of servo Variant...Removed IFC and Skr mini

Running on just Duet2Wifi and Duex5 Expansion board.


Changes: 
All selector rods upgraded to 8mm.
Servo holder extended so horn is centered.
R01 and R02 modified to fit 8mm rods..
Feeder endstop is now a mechanical switch.
Added direct drive motor. DD unloads first then Smuff feeder does the rest. and vise versa

Connections:
Feeder endstop is connected to E1 endstop on Duet.
Selector is connected to E0 on Duet.
Feeder motor is connected to E1 driver.
Directdrive motoris connected E0.
Selector motor is connected to E5 driver on Duex5.


