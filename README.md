# Radar Detector v2.0
#### Client: Griffin Doherty

## Project Requirements
### Board overview
There are two boards in the design namely:
1. Main Board
2. Secondary Board

### Task Description
- The radar sensor on the main board should now be changed to AWR1843 AOP 77 Ghz from Texas Instruments and its relevant circuitry and hardware support should be added.
- A suitable STM32 MCU that can handle both the AWR1843 AOP 77 Ghz and the Acconeer A121 on the secondary board simultaneously. The MCU should be selected with power consumption in mind as well but performance of MCU should not be compromised.
- The design should have support for [this vibration motor](https://www.digikey.com/en/products/detail/seeed-technology-co.,-ltd/316040001/5487672?utm_adgroup=&utm_term=&utm_content=&gad_source=1) which should be at the back of the enclosure.
- The design should have an RGB LED for battery level indication. The battery must be placed on the same location as the old reference client files.
- USB-C for programming and charging. The port should be horizontal laying flat on the board.
    - USB-C port to be on the back of the PCB in the middle at the top.
- Push button that does the following:
    - Turns PCB on/off on single button press
    - Should be present on left hand side of the PCB board in the middle similar to previous Main Board in docs/Client-Files
- 20+ meter detection for people and 40+ meter detection for cars. An antenna is available on the package of the AWR1843.
    - To achieve those distances, check to see if an antenna patch might be needed?
- At least 100 degree FOV.
- PCB can be dual sided to save space.
- The previous PCB was 30x20mm. Try to keep it to this size, however, the AWR1843 is larger than the last radar module. If the board needs to be bigger, increase the length and height proportionally.
- Filleted/ rounded corners on the PCB similar to the previous Main board.
- Suitable Interconnect between Main board and Secondary board to connect them together. Also have a little cutout for the connector so that it fits in the case smoothly. Put the connector on the right side of the PCB board. You could even put it on the back side of the board to remove the need for a cutout.
    - This way it is closest to the second PCB. Because the second PCB will be on the right side.
    - Suggestion for kind of connector in image below:
     ![image](https://github.com/eSpark-Consultants/griffin-radarsystem-hw/assets/76909080/5530f207-5d80-4ab6-a39a-757dc0ca598e)
- Ideally battery life should be estimated to work for 8 hours but not a strict requirement.





 
 
