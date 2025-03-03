# CS350 Final Project: Smart Thermostat Prototype
# Daviel Machet

Project summary:
This project involved developing a smart thermostat prototype for SysTec, a company aiming to enter the smart thermostat market. 
The prototype focused on low-level embedded system functionality, such as reading room temperature from an AHT2 temperature sensor (I2C), 
controlling LED indicators (GPIO) for heating/cooling states, processing user inputs via buttons (GPIO interrupts), 
and displaying real-time data on an LCD screen.

Accomplishments in this project:
One strength in this project was efficiently integrating multiple peripherals and managing system states, Implementing:
-GPIO-based button handling using GPIOZero ensuring transitions between heating, cooling, and off states.
-I2C communication to read room temperature accurately.
-PWM-based LED control to visually see what was the current state.

Area for improvement:
There are many areas I need to improve is to refine the codebase to make it reusable for future projects, and implementing fail-safe mechanisms when the code fails while running.

Tools used:
-Raspberry Pi 4B
-AHT2 temperature sensor
-LEDs
-Buttons
-LCD display
-Solderless Breadboard

Transferable skills:
-Embedded software development with GPIO, I2C, and UART
-Hardware and software integration that ensures seamless communication between peripherals
-Evaluating hardware architectures based on business and technical requirements

Maintainability and Adaptability:
Code functions were seperated for sensor reading, button handling, LED control, and UART communication.
