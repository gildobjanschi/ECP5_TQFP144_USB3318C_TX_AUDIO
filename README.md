# ECP5 High Speed USB Audio Board
This project aims to implement a High Speed USB audio interface using the Lattice Semiconductor ECP5 FPGA coupled with a USB3318C ULPI USB interface.

## Software
The FPGA Verilog software for the board is currently being developed in a private Github project. Once the board and the code are verified this page will be updated with a link to that project.

## Project Status
The board was manufactured and it is fully functional.

[Schematic PDF](https://github.com/gildobjanschi/ECP5_TQFP144_USB3318C_TX_AUDIO/blob/main/kicad/ECP5%20Audio%20Tx.pdf)

![Board 3D view](https://github.com/gildobjanschi/ECP5_TQFP144_USB3318C_TX_AUDIO/blob/main/ECP5_Audio_Tx.jpg)

## How to setup KiCAD
Checkout the project and open it. In the Configure Paths dialog add: Name: ECP5_AUDIO and Path: "full path to your GitHub directory"/GitHub/ECP5_TQFP144_USB3318C_TX_AUDIO

In the Manage Symbol Libraries click the Project Specific Libraries and add: Name: ECP5_AUDIO and Library Path: ${ECP5_AUDIO}/symbols/Symbols.kicad_sym

In the Manage Footprint Libraries click the Project Specific Libraries and add: Name: ECP5_AUDIO and Library Path: ${ECP5_AUDIO}/footprints/Footprints.pretty
