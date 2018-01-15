# STM32 Smart v2 Skeleton
This repository contains a STM32CubeMX (STM32 Cube MX) profile and generated source code for STM32 Smart v2 board
(STM32F103C8T6 ARM STM32 Minimum System Development Board from noname chinese manufacturer) 
with all peripheria configured.

##Usage
Import and use it with SW4STM32 or Clion just as usual;

You can build it from console by running

`cmake --build ./cmake-build-debug --target STM32_Smart_v2_Skeleton.elf -- -j 2`

##Clion debugging notice
Install OpenOCD + STM32CubeMX support for CLion plugin (if not installed)
Change settings as described on the plugin page https://github.com/elmot/clion-embedded-arm
using STM32_Smart_v2_OpenOCD.cfg file as Board Config File