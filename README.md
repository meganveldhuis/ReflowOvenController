# ReflowOvenController
![reflowOven](https://github.com/user-attachments/assets/ce7285cf-1e0a-41e3-b3d3-d537a85b660f)

Group Capstone project for Electrical Engineering Undergrad

_By:  Connor Chin, Tait Richards, Megan Veldhuis, Mia Vukadin_


The Reflow Oven Controller will be controlled using a XInC2 Microcontroller from Eleven Engineering. The reflow oven was designed and built using an old microwave oven and a new heater, thermocouple, OLED, humidity sensor, and rotary encoder. We designed a custom PID controller to follow the reflow curve with a 5% accuracy. Each solder paste has a different melting temperature, and thus require a different reflow curve, so we designed three different profiles with three different reflow curves that the user can choose from before starting the process. (This repository contains all of the firmware used in this project. It is a bit messy; we didn't have time to clean up the code or write a nice README)

The final product successfully monitored and displayed the temperature inside the Reflow Oven! During our presentation, our demo successfully soldered a PCB.
![PCB](https://github.com/user-attachments/assets/fc1cffa8-006e-4229-9b7e-f9e18c7b4ec6)

