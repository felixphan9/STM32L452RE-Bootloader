# STM32L452RE-Bootloader
This is a custom bootloader for STM32L452RE:

🌀 Requirements: Implement a bootloader program using the FreeRTOS library to perform Firmware Over-The-Air (FOTA) updates via UART communication for STM32L452RE.

- Design the protocol for data communication between users and the bootloader program. Research and implement functions to verify CRC32 checksums.

- Explore the pySerial module, and write a Python program to establish communication based on the protocol defined in step 3 on a PC. Implement program updates.

- Learn about FreeRTOS and develop a bootloader program using the FreeRTOS library.

- Research the Android VIM3 Khadas board, establish UART communication between VIM3 Khadas and a PC; and establish UART communication between VIM3 Khadas and the Nucleo L452RE board using a shell script.

- Write a Python program to generate a shell script for firmware updates. The host for updates is the Android VIM3 Khadas board, using UART communication.

Languages: Python, C
