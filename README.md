# CS490 Ingenion Senior Design 2023
Embry-Riddle 2023 CS490 Ingenion Senior Design Project

# Product Vision

Our goal for this project is to lay the groundwork for the enhancement of Ingenion's Total Verification System (TVS), a specialized piece of testing equipment used by NASA's Goddard Space Flight Center to simulate, test, and verify Sattelite hardware components. We plan to add features and functionality to this system by implementing a Xilinx MicroBlaze soft-core CPU on the Artix 7 FPGA, running FreeRTOS, an open-source real-time operating system, within it, then hosting an interactive web server on the processor's operating system, which will be able to connect to an external computer using TCP over Ethernet, which will have the capabilities of reading telemetry from the onboard AXI bus and other peripherals, as well as send various commands to the CPU. This system will first be implemented on the Digilent Nexys A7 development board, and then ported over to the TVS in the form of a plug-and-play package.

![Design Diagram](https://github.com/HamiltonHenneberg/CS490Ingenion2023/assets/99364961/4e19f402-c06c-4658-8d5a-9cbf53eaa573)
