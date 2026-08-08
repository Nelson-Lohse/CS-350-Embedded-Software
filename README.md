# CS-350

# CS-350 — Embedded Thermostat System

## Project Overview

This project focused on designing and implementing a state machine for an embedded thermostat system. The thermostat monitors temperature conditions and allows the user to configure the system to either **heat or cool**. The system tracks whether it is actively heating, actively cooling, or idle based on the current temperature and configured settings.

The project was developed using **Python on an Ubuntu/Linux-based Raspberry Pi environment** and required direct interaction between software and physical hardware.

### Hardware & Technologies

* Python
* Ubuntu/Linux
* Raspberry Pi
* AHTx0 Temperature Sensor
* GPIO
* PWM LEDs
* 16x2 LCD Display
* State Machine Architecture
* `gpiozero`
* `adafruit_character_lcd`
* `board`
* `digitalio`

### System Functionality

The thermostat uses a temperature sensor to obtain real-time environmental readings and uses those readings to determine the appropriate system state. The state machine manages transitions between heating, cooling, and inactive states based on the configured target temperature and operating mode.

The project also incorporates physical hardware to provide visual feedback. LEDs are controlled using PWM, while a 16x2 LCD provides information about the current thermostat configuration and operating state.

The project required troubleshooting both software and hardware interactions, including issues involving the LCD display, GPIO components, sensor integration, and communication between the Python application and the embedded hardware.

---

## Project Reflection

### What did you do particularly well?

I feel like my final product was pretty good. I had a lot of problems with the LCD display throughout the course, but it ultimately worked out pretty well. My code was simple and understandable, and by the end of the course I felt like I had a pretty good understanding of the key concepts.

### Where could you improve?

I could definitely improve on my understanding of different devices in embedded systems. I understand what embedded systems are and why they are helpful; however, I realized while completing the final report that I did not quite understand the different types of architecture as well as I should.

### What tools and/or resources are you adding to your support network?

I will make sure that I am reviewing material much more frequently. I found that as I was working, I would encounter problems that led me to just work in circles for long periods of time. After reviewing the resources much more in depth, I was able to figure things out and could continue making progress.

### What skills from this project will be particularly transferable to other projects and/or coursework?

After this project, I developed a much better understanding of how software interacts with hardware. In previous coursework, I would work primarily within the IDE I was developing in. Now I have been able to see the impacts of my changes directly in the embedded device.

This experience will be transferable to future projects involving physical devices, sensors, or other hardware because I am now more familiar with how software interacts with the components of an embedded system. It also gave me experience troubleshooting issues where problems could originate from either the software or the hardware.

### How did you make this project maintainable, readable, and adaptable?

I worked to ensure that the project had simple code that accomplished the goal without being overbearing. This way, fixes can be made easily, and working in a team can be streamlined since the code can be reviewed by many people without issue.

I also structured the thermostat around a state-machine design, which separates the different operating states and makes the system's behavior easier to understand and modify. This allows additional functionality or states to be introduced without requiring major changes to the overall structure of the program.

