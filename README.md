# SlimeVR-DIY-case-dev
Development of alternative cases for DIY components.
This case development is specifically for a 804040 LiPo battery, SS22F32 DPDT slide switch, and JST ZH 5p connector

Cases are numbered by [layout concept number].[major revision].[minor revision]

# Case model 5.3  
![Image](https://github.com/Sketch56/SlimeVR-DIY-case-dev/blob/d2e23e6f6cdbb311d32a4a8693514bffd53c932e/images/Case%205.3.5%201.png)
![Image](https://github.com/Sketch56/SlimeVR-DIY-case-dev/blob/d2e23e6f6cdbb311d32a4a8693514bffd53c932e/images/Case%205.3.5%202.png)
Dims: 57.6\*56.6\*20.5mm  
A "traditional" case similar to the Hyperion, though the switch is actually recessed into the lid rather than a side. This allows for a minimal tray size with a recessed SS22F32 switch, and has convenient cutouts for cable management and solder joints.

# Case model 8.0  
![Image](https://github.com/Sketch56/SlimeVR-DIY-case-dev/blob/da075a7e9d7ac8ae9d084d69cdff7b5b58a5a10f/images/case%208.0.12%201.jpg)
![Image](https://github.com/Sketch56/SlimeVR-DIY-case-dev/blob/da075a7e9d7ac8ae9d084d69cdff7b5b58a5a10f/images/case%208.0.12%20f360.png)
Dims: 44.2\*57.2\*21.6mm  
The tray orientation in this case is over the strap loops, and the Wemos D1 is overlapping part of the MPU. This is likely the most compact format where the battery is in the bottom of the case. Pretty easy cable management

# Case model 9.0  
![Image](https://github.com/Sketch56/SlimeVR-DIY-case-dev/blob/06c3cc5c6c8da82cac7aaef6484ed5e536fc3b83/images/case%209.0.6%201.jpg)
![Image](https://github.com/Sketch56/SlimeVR-DIY-case-dev/blob/06c3cc5c6c8da82cac7aaef6484ed5e536fc3b83/images/case%209.0.6%20interior%202.jpg)
Dims: 72.0\*44.2\*18.8mm  
The case is as thin as allows by having the battery sit above the strap loops. The D1, MPU and AUX connection sit below the battery, TP4056, and switch. Cable management is pretty difficult, but this form factor might be desireable in some cases. Has a second lid with vent holes over the TP4056.

Other existing models will be added shortly

# Components List
Current target components (and links personally sourced from):
 - Wemos D1 Mini
   - https://www.aliexpress.com/item/1005001621784437.html
 - TP4056
   - https://www.aliexpress.com/item/32649780468.html
 - MPU-6050
   - https://www.aliexpress.com/item/714775852.html
 - 804040 LiPo battery
   - https://www.aliexpress.com/item/33021202630.html
 - SS22F32 DPDT slide switch
   - https://www.aliexpress.com/item/32975535599.html

Note that components from different manufacturers may have slightly different dimensions and PCB thicknesses.
For alternative sizes, or to support different batteries and switches, one will need to edit the included F3D files.

Additional components
 - Schottky rectifier diodes (battery protection)
   - https://www.aliexpress.com/item/1005002945015597.html 
 - 180Kohm resistor (battery life sense)
   - https://www.aliexpress.com/item/1005001436946770.html (these are larger in size than necessary)
 - 28GA wire (safe and thin enough)
   - https://www.amazon.com/dp/B089CQ1C8L
 - JST ZH 5pin 1.5mm pitch (For aux IMU, can substitute with alternative connectors or directly soldered cables)
   - https://www.amazon.com/dp/B07HNKKXGN

 - Filament
   - You do you
