# AHAR (Autonomous Healthcare Assistant Robot)
## Description
The Autonomous Healthcare Assistant Robot (AHAR) is a state-of-the-art robotic system designed to transform healthcare delivery in India. AHAR is a three-wheeled
robot with a stainless steel cuboidal frame, equipped with advanced sensors and intelligent control systems. It's built on a robust architecture, featuring a Raspberry Pi
for high-level control, a Pi Cam for vision, a Pi LIDAR for environment mapping, and motors with encoders for precise mobility.

## ROS
<img width="420" alt="Screenshot_20230227_083836" src="https://github.com/adijams01/Medbot/blob/main/images/sih_gazebo.jpeg">
We are utilizing ROS as the operating system for our robot. ROS, which stands for Robot Operating System, is widely adopted by leading robotics companies in the industry. We are simulating the robot in the Gazebo Simulator, which is a physics simulator designed for ROS. This simulation allows us to control and observe the robot's actions through RVIZ.

For navigation, we are employing SLAM and Nav2, using LIDAR technology. The robot operates autonomously, but it can also be controlled via a web application. Additionally, you can view its live feed from the camera on the web. Furthermore, the robot can be controlled using a joystick or a keyboard.

## Electronics
<img width="398" alt="Screenshot_20230227_083836" src="https://github.com/adijams01/Medbot/blob/main/images/sih_schematics.jpeg">
The functionality of the robot heavily relies on its electronic components. It employs two DC geared motors equipped with encoders, managed by a Sabertooth motor driver, to enable movement. For steering control, there is a caster wheel located at the front. Serving as the central controller, a Raspberry Pi 4B module governs all the electronic elements. Additionally, the robot is equipped with an LCD screen for user interaction, a Lidar sensor for navigation and mapping purposes, and a Pi camera for visual input. To provide power to the entire system, a LiPo 5s battery is used.

## Mechanical
<img width="398" alt="Screenshot_20230227_083836" src="https://github.com/adijams01/Medbot/blob/main/images/Robot_cad.jpeg">
Grade 304 stainless steel is generally regarded as the most common austenitic stainless steel. It contains high nickel content that is typically between 8 and 10.5 percent by weight and a high amount of chromium at approximately 18 to 20 percent by weight. Other major alloying elements include manganese, silicon, and carbon. The remainder of the chemical composition is primarily iron.

## Contributors
* [Chandu Bayyavarapu](https://github.com/Chandu106)
* [Aaditya Nair](https://github.com/ad5454)
* [Prerna Sharma](https://github.com/prernasharma0)
* [Angad Singh](https://github.com/AnG0d)
* [Dherya Rana](https://github.com/ranaDherya)


