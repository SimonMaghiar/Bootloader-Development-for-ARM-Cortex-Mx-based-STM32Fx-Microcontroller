# Bootloader-Development-for-ARM-Cortex-Mx-based-STM32Fx-Microcontroller

What's a bootloader and why its needed?
A: Bootloader is nothing but a small piece of code stored in the MCU flash or ROM to act as an application loader as well as a mechanism to update the applications whenever required.

The main use of bootloader is to download/upload binaries for all 3 boards you mention in this video. But since the ST nucleo board and the TI board have on-board debugger so it is not necessary to use the bootloader to download/upload binaries.
For example, Arduino Uno uses bootloader whenever we want to flash a program into the memory. Upon reset, Arduino bootloader runs first.
