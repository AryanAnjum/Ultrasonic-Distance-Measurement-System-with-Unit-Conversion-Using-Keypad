# Ultrasonic-Distance-Sensor.HC-SR04-OLED-Keypad-with-STM32F103C8T6

This repository contains the source code for my CSE331 final project, an embedded system that measures distance using an ultrasonic sensor and displays the result on an OLED screen, with unit conversion controlled via a 4×4 keypad.
The system is implemented using STM32CubeIDE and programmed on the STM32F103C8T6 (Blue Pill) microcontroller.

📌 Project Overview
This project measures distance using the HC-SR04 Ultrasonic Distance Sensor and allows the user to dynamically change the display unit using a 4×4 keypad.
The measured distance is displayed in real-time on an OLED display.
Supported Units:
 • Centimeter (cm)
 • Inch (in)
 • Feet (ft)
 Unit selection is handled entirely through the keypad, making the system interactive and user-friendly.

⚙️ Hardware Components Used
  • STM32F103C8T6 (Blue Pill)
  • HC-SR04 Ultrasonic Distance Sensor
  • 0.96" OLED Display (I2C)
  • 4×4 Matrix Keypad
  • STM32 ST-Link Programmer
  • Jumper wires and breadboard

🧠 Software & Tools
  • STM32CubeIDE – Code development and compilation
  • STM32 ST-Link Utility – Flashing and debugging
  • HAL Libraries – Peripheral configuration and control
  • Embedded C – Application logic
  
✨ Features
  • Real-time distance measurement using ultrasonic sensor
  • Unit conversion using 4×4 keypad
  • OLED display output
  • Efficient timing using STM32 hardware timers
  • Modular and readable code structure
  • Stable and accurate distance calculation

🧩 Keypad Unit Mapping (Example)
Key	         Unit
D	           Centimeter (cm)
D	           Inch (in)
D	           Feet (ft)

🛠 How to Build & Run
  • Open the project in STM32CubeIDE
  • Connect the STM32F103C8T6 (Blue Pill) using ST-Link
  • Build the project
  • Flash the program to the microcontroller
  • Power the board and observe output on the OLED display
  • Use the 4×4 keypad to change measurement units
  
🎓 Academic Information
Course: CSE331L
Project Type: Final Project
Platform: STM32 (ARM Cortex-M3)
