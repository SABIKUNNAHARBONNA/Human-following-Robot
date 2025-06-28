The Human-Following Robot is an autonomous mobile system designed to detect and follow a human target while navigating its environment. This project was completed as part of my Robotics course during my undergraduate studies. The objective was to build a robot capable of sensing human presence and movement using low-cost sensors, then adjusting its path and speed dynamically to maintain a fixed distance from the person.

The robot utilizes a combination of Ultrasonic and Infrared (IR) sensors for accurate detection and navigation. The ultrasonic sensor measures the distance between the robot and the target, helping to avoid obstacles, while the IR sensors detect motion direction and alignment. The core control unit is an Arduino UNO microcontroller, which processes sensor input and outputs commands to control the robot’s movement via four gear motors.

Hardware Components:

Ultrasonic Sensor (1x): Measures distance and avoids obstacles.

IR Sensors (2x): Detects human motion and direction.

Arduino UNO (1x): Controls logic, motor control, and sensor processing.

Gear Motors (4x): Drive the wheels and control movement.

Software Tools:

Arduino IDE: Used to write, compile, and upload code to the Arduino board.

NewPing Library (<NewPing.h>): Improves ultrasonic sensor performance with faster, non-blocking distance measurement.

The robot’s logic allows it to move forward when the person moves and stop when the person stops, maintaining a safe distance at all times. The system adjusts behavior in real time, enabling smooth and responsive tracking.

Outcome:
The project successfully delivered a functional prototype of a human-following robot. It provided valuable hands-on experience in embedded system design, sensor integration, real-time programming, and motion control. This project sparked my interest in autonomous systems and strengthened my foundation in robotics, automation, and hardware-software integration.

