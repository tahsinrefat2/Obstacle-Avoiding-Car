# Obstacle-Avoiding-Car

The Obstacle Avoiding Car is an innovative and autonomous vehicle designed to navigate its surroundings intelligently and avoid obstacles in its path. This project combines the power of Arduino Uno R3, HC SR04 ultrasonic sensors, L293D Motor Driver Shield, servo motor, and DC motors to create a versatile and efficient obstacle avoidance system.

Main Components:

Arduino Uno R3: The brain of the project, Arduino Uno R3 serves as the microcontroller that processes sensor data and controls the motors and servo motor based on the programmed logic.

HC SR04 Ultrasonic Sensors: These sensors play a crucial role in obstacle detection. By emitting ultrasonic waves and measuring the time taken for the waves to bounce back, the car can determine the distance between itself and nearby obstacles.

L293D Motor Driver Shield: The L293D Motor Driver Shield is responsible for controlling the DC motors that drive the car's wheels. It provides the necessary power and direction control to ensure smooth movement.

Servo Motor: The servo motor is typically used to control the orientation of the ultrasonic sensors. By rotating the sensors, the car can scan its environment effectively and gather obstacle information from different angles.

DC Motors: DC motors drive the wheels of the car, enabling it to move forward, backward, and turn. The motor control is managed through the L293D Motor Driver Shield, allowing precise control over the car's movements.

How It Works:

The HC SR04 sensors continuously send and receive ultrasonic signals, allowing the Arduino Uno to calculate the distances to surrounding objects. When an obstacle is detected within a predefined range, the Arduino triggers the servo motor to rotate the sensors for a better view. Based on the gathered information, the Arduino then commands the DC motors through the L293D Motor Driver Shield to navigate around obstacles, ensuring a collision-free path.

Check out the project with photos here : https://lnkd.in/gUUm3stF
