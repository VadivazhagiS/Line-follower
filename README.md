# *Line-follower*
This project involves the construction of a differential robot capable of line following using infrared sensor inputs. The robot's movements are controlled by an Arduino UNO microcontroller, interpreting the data from the mounted infrared sensor to make real-time decisions.
## *Introduction*
The line-following differential robot is designed to autonomously follow a path, such as a line on the ground, using infrared sensors for guidance. The robot's behavior is dictated by the data received from the infrared sensors, allowing it to traverse a defined route effectively.
## *Components*
- Infrared Sensors: Mounted on the robot to detect and interpret the line or path to be followed.
- Arduino UNO: The microcontroller responsible for processing sensor data and controlling the motors accordingly.
- DC Motors: Drive the robot's wheels and are controlled by the Arduino UNO based on sensor inputs.
## *setup*
- Hardware Assembly:
  - Mount the infrared sensors on the robot at appropriate positions to detect the line or path.
  - Connect the DC motors to the appropriate motor driver pins on the Arduino UNO.
- Software Configuration:
  - Program the Arduino UNO microcontroller to read data from the infrared sensors and control the motors accordingly.
  - Ensure the correct logic and algorithms are implemented to achieve the desired line-following behavior.
## *usage*
- Power on the robot with the Arduino UNO connected.
- The infrared sensors will continuously scan the ground to detect the line or path to follow.
- Based on the sensor readings, the Arduino UNO will adjust the motors to keep the robot on the desired path.
- The robot will autonomously follow the path as guided by the infrared sensor inputs.
