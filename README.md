# ECP5 High Speed USB Audio Board
This project aims to implement a High Speed USB audio interface using the Lattice Semiconductor ECP5 FPGA coupled with a USB3318C ULPI USB interface.

## Software
The FPGA Verilog software for the board is currently being developed in a private Github project. Once the board and the code are verified this page will be updated with a link to that project.

## How to setup KiCAD
Checkout the project and open it. In the Configure Paths dialog add: Name: ECP5_AUDIO and Path: "full path to your GitHub directory"/GitHub/ECP5_Tx_Audio

In the Manage Symbol Libraries click the Project Specific Libraries and add: Name: ECP5_AUDIO and Library Path: ${ECP5_AUDIO}/symbols/Symbols.kicad_sym

In the Manage Footprint Libraries click the Project Specific Libraries and add: Name: ECP5_AUDIO and Library Path: ${ECP5_AUDIO}/footprints/Footprints.pretty

## Project Status
The board is coming back from manufacturing soon. 

[Schematic PDF](https://github.com/gildobjanschi/ECP5_Tx_Audio/blob/main/kicad/ECP5 Audio Tx.pdf)
![Board 3D view](https://github.com/gildobjanschi/ECP5_Tx_Audio/blob/main/ECP5_Audio_Tx.jpg)