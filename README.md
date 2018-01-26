# F_QUAD
F_QUAD is a notation referring to formation quadrotor and is meant to be used for quadrotors formation and co-operation projects.
In this project, ArUco carpets are used to achieve hight frequency and accurate navigation for lab-based experiments. Actually it
serves as a very lowcost alternative for Motion Capture systems and calculation is on-board and runs about 50 to 100 Hz on an Odroid XU4 mini 
computer.
This repository contains a ROS(Robot Operating System) package for ArUco positioning system that publishes accurate camera position
and orientantion data. OpenCV ArUco module is implemented in order to get these values. Also a server is added in order to encode and 
decode messages from a paparazzi autopilot.
In addition, all of the guidance procedures are done using Matlab Simulink (or any other ROS node), externally via wifi. And the 
resultant guidance model is converted to code and uploaded on-board automatically by Simulink.
