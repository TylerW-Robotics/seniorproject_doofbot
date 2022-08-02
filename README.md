# Senior project Doofbot

Doofbot was a Capstone project done by Robert B and Tyler W. 
A Doofbot is a turtle bot that uses a Raspberry pi 3B+ and uses ROS kinetic as a framework. 
The goal of this project is to create an autonomous mobile robot that creates a mobile robot that uses image processing to guide the robot through a flat grid platform and use an A* search algorithm to find the shortest path to the goal, all wrapped together with ROS. The Raspberry Pi is capable of communicating with the sensors and motors driver through an SPI Bus and UART communication protocols. Encoders on each motor were used as feedback for a PID controller for distance control on the robot. The robot utilizes a heuristic A* search algorithm to plan paths in mapped areas, known as the workspace, that contain unknown obstacles. Due to the simplicity of the 2D grid that was used, the A* search algorithm was the best option. Image processing was used to detect obstacles during the robot’s movements. The connection to the robot utilizes an onboard Raspberry Pi that communicates wirelessly with a host computer through ROS. The host computer did the path planning and the image processing calculations. 



![image](https://user-images.githubusercontent.com/50836413/182407431-8f739654-0fb5-40e5-be24-cb9803d4b14a.png)

Top image shows the Mobile Robot and the bottom image is the mounted electronic. 



![image](https://user-images.githubusercontent.com/50836413/182407029-19c44388-bfcc-49bc-8aa9-fcf716cabe83.png)

Updated GUI that includes live streaming from the webcam and manual control options.


