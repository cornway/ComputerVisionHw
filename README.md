## PCB deisgns with focus on computer vision for embedded devices

I will be publishing here open-source kicad PCB designs, with primary focus on computer vision for embedded (MCU)

Boards available:

1. stm32u5_v1.0 - utilizing stm32u5g9jxx mcu + ov2640 compatible camera and spi display; This board was made using schematics from stm32u5g9j_dk2 and stm32h7 "WeAct" development board
2. stm32u5_v2.0 - simplified version of stm32u5_v1.0, but seems target mcu is out of stock
3. stm32n6_v1.0 - based upon stm32n6xx nucleo development board, no psram yet; Length equalization tables for both xspi can be found in "Resources" directory

Each board is validated, to the best o my knowledge, but may have some issues.
Each board can be manufactured at JLCPCB (each component contains apropriate symbol designator) using Kicad add-on **com.github.bennymeg.JLC-Plugin-for-KiCad**, or in any other preferred way. Key point was to produce easy to understand design, that can be manufactured at low cost and used for further prototyping

Example (and not only) software for these boards can be found here :

https://github.com/cornway/ComputerVisionEmbedded