# ICE40-Board
*Work in progress*  
This is a 4-layer FPGA PCB which is used for [RV5-MCU](https://github.com/SyedAnasAlam/RV5-MCU). The goal is to use this FPGA PCB as a microcontroller development board. 
## Parts
- ICE40HX4K
- 2 x W25X20CL 2Mbit SPI Flash (104MHz)
    - 1x For FPGA configuration bitstream (FPGA flash)
    - 1x for MCU program memory (MCU flash)
- USB-C for programming both FPGA and MCU flash
    - Also has option for programming the flash with a external device though breakout headers
- Select between powering board from USB or barrel jack
- FTDI4222 for USB to SPI conversion
- 64 x IO pins  
  
![3D Rendering of the PCB](https://i.imgur.com/5hSbpcV.png)