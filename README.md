Arduino Uno Dishwasher Automation Project 

DISH-O-MATIC
Introduction
In the era of smart homes and automation, there's a rising interest in integrating technology into household appliances to boost convenience and efficiency. This report presents a project aimed at automating a dishwasher using the Arduino Uno microcontroller. The goal is to enhance the dishwasher's functionality, optimize resource usage, and create a user-friendly experience.

Background
Dishwashers have become essential appliances in modern households. However, manual operation and limited customization options can lead to inefficient use of resources like water and energy. By automating a dishwasher, we can tackle these issues and make the appliance more adaptable to individual user needs.

Proposed Design
Hardware Components
Arduino Uno: Central processing unit for controlling and coordinating all dishwasher functions.
Proximity Sensor: Detects dishes in the dishwasher rack to determine when to start or pause the washing cycle.
Ultrasonic Sensor: Measures water level for precise control of water intake.
Water Motor: Regulates water flow based on input from the ultrasonic sensor to prevent overfilling.
Servo Motor (2): Controls detergent dispenser for accurate detergent dispensing.
Beeper: Provides audio signals for cycle completion and error notifications.
Connectors and Jump Wires: Ensure secure electrical connections between components and Arduino.

Software Implementation
Arduino Sketch: Custom program to control dishwasher functions based on sensor inputs and user commands.
Arduino Serial Monitor: Provides important readings such as ultrasonic sensor distance and proximity sensor detection status.
SimulIDE: Used for circuit simulation and testing electrical connections, including all components and Arduino Uno.


Testing Results / Test Cases
Various test cases were conducted to ensure system functionality, including:
Initial Testing: Verified Arduino's ability to read sensor data and control actuators.
Water Filling: Tested system's ability to fill dishwasher to appropriate level without overflow.
Heating: Confirmed heating element maintains consistent water temperature.
Detergent Dispensing: Ensured accurate detergent dispensing during wash cycle.


Conclusion
The Arduino Uno dishwasher automation project showcases the potential for enhancing home appliance automation. It optimizes resource usage, streamlines washing process, and offers users a more customizable experience.




