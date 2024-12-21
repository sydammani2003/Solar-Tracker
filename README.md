# Solar-Tracker

This project involves a smart solar panel system designed to maximize energy capture by adjusting the panel’s angle according to the direction of sunlight. The system uses Arduino, servo motors, and sensors to track the sunlight and optimize the solar panel’s orientation.

Key Features:
Sunlight Tracking:
The system uses light sensors (such as LDRs) to detect the direction of sunlight. Based on the sensor readings, the system continuously adjusts the angle of the solar panel to ensure it is always oriented towards the sun, maximizing energy capture throughout the day.

Solar Panel Adjustment:
A servo motor is used to adjust the angle of the solar panel. The servo motor is controlled by the Arduino, which interprets the sensor data to move the panel to the optimal position for maximum exposure to sunlight.

Irrigation Control:
The solar panel is connected to a motor that helps in irrigating the land. When the solar panel captures energy, the motor is powered to pump water for irrigation purposes. This integration ensures that the irrigation system is both energy-efficient and autonomous.


Components:
Arduino: Acts as the central control unit, processing data from sensors and controlling the servo motor and irrigation system.
Servo Motors: Used to adjust the angle of the solar panel.
Light Sensors (LDRs): Detect the intensity and direction of sunlight.
Water Pumping Motor: Controlled by the Arduino to pump water for irrigation.

How It Works?
The light sensors continuously monitor the direction of sunlight. The Arduino processes the sensor data and uses it to calculate the optimal angle for the solar panel.
The servo motors adjust the panel’s angle accordingly to ensure maximum solar exposure.
Simultaneously, the solar panel generates energy, which powers a motor that aids in irrigation, providing water to the crops or land.


<img width="410" alt="second solar" src="https://github.com/user-attachments/assets/ca6a3b55-fef8-49c9-b4c4-e7f3889de763" />


<img width="418" alt="fisrt solar" src="https://github.com/user-attachments/assets/b355bb3b-4cb8-407a-b359-6bb2f4793bf6" />

