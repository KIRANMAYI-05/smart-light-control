# smart-light-control

COMPANY NAME : CODTECH IT SOLUTIONS 

NAME : KOMPELLA KIRANMAYI 

INTERN ID : CT04DF1700

DOMAIN: INTERNET OF THINGS 

DURATION : 4WEEKS 

MENTOR : NEELA SANTOSH KUMAR

 Task 1: Smart Light Control System Using LDR and Arduino
✅ Introduction:
The Smart Light Control System is an energy-efficient solution that automatically turns ON or OFF the lights based on the surrounding light intensity. It uses a Light Dependent Resistor (LDR) to detect ambient light levels and control output devices such as LEDs (representing street lights or home lights). This system eliminates the need for manual operation of lights and helps conserve electricity, making it ideal for street lighting, parking lots, home automation, and smart cities.

🧰 Components Used:
Arduino UNO:

Acts as the brain of the project.

Reads the input from the LDR sensor and controls the LEDs accordingly.

LDR (Light Dependent Resistor):

A light sensor whose resistance decreases with increasing light intensity.

Used to detect whether it is day or night.

10kΩ Resistor:

Used with the LDR to form a voltage divider circuit.

Helps convert the varying resistance of the LDR into a measurable voltage for Arduino.

LEDs (Red and Blue):

Used as output indicators for light control.

Represent the street or room lights turning ON/OFF.

220Ω Resistors:

Current-limiting resistors connected in series with each LED to prevent damage.

Breadboard and Jumper Wires:

For prototyping and making connections easily without soldering.

💻 Software Used:
Tinkercad Circuits (by Autodesk):

A web-based electronics simulator.

Used to design and simulate the circuit without physical hardware.

Provides virtual Arduino and components with drag-and-drop support.

Arduino IDE (optional):

A software used to write and upload code to the Arduino board in real-world applications.

🔌 Circuit Connections:
LDR Sensor (Light Detection):
One leg of the LDR is connected to 5V.

The other leg is connected to Analog pin A0 of Arduino and one leg of a 10kΩ resistor.

The other leg of the 10kΩ resistor is connected to GND.

This setup creates a voltage divider circuit that provides a variable voltage to A0 based on light intensity.

LED Outputs:
The red LED is connected to digital pin 3 via a 220Ω resistor.

The blue LED is connected to digital pin 4 via another 220Ω resistor.

The cathodes (short leg) of both LEDs go to GND.

⚙️ Working Principle:
The Arduino constantly reads the analog voltage from the LDR using analogRead(A0).

In bright light (daytime), the resistance of the LDR is low, and the voltage read is high.

When it is dark (nighttime), the resistance increases, and the voltage decreases.

The code compares the LDR value to a threshold (e.g., 500):

If the value is below the threshold (dark), the Arduino turns ON both LEDs.

If the value is above the threshold (bright), it turns OFF the LEDs.

This automation replicates how street lights or smart home lights should operate without human intervention.

📈 Applications:
Automatic Street Lighting: Lights up roads only when it gets dark.

Smart Home Automation: Automatically controls bedroom or hallway lights.

Energy Conservation Systems: Helps reduce energy consumption and bills.

Smart Campus and Industrial Automation: Used in larger systems for responsive lighting.

✅ Advantages:
Reduces human effort and error.

Saves electricity by turning lights off in daylight.

Can be scaled up to include motion sensors or real-time clocks.

Simple and cost-effective to implement.

📌 Conclusion:
This Smart Light Control System demonstrates a basic yet powerful automation concept using an LDR sensor and Arduino. By combining light sensing with microcontroller-based decision-making, this project showcases how embedded systems can bring smart functionality to everyday environments. Tinkercad’s simulation allows for risk-free design and testing, making it ideal for students, hobbyists, and prototyping teams alike.

output shown

![Image](https://github.com/user-attachments/assets/c4d3a3f0-a966-4f3c-a00a-f90e60d56b94)

