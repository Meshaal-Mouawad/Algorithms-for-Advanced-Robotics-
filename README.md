Welcome to the Algorithms-for-Advanced-Robotics-

Most of the information here are sources from Dr. Luo C. lectures, MSU, ECE.

(This Page have not been completed)

# Intelligent Robots consist of:
* Sensor Configuration (hardware)
* Path planning,
* Navigation,
* Perception,
* Localization,
* Mapping,
* Cognition,
* Motion control, and
* Multiple robots…

Intelligent Robots: 
* React to the environment – sensing
* Adapt to the current conditions
* Make decision and new goals (e.g., in robotic exploration)

Intelligent Robots: 
* Even though they are autonomous systems, the behavior is relatively well defined
* Adaptation and ability to solve complex problems are implemented as algorithms and techniques of Artificial Intelligence

Intelligent Complete Robot: 
1. Perception [Sensors]: Sensing Modeling the world
2. Cognition: Behaviors, action selection, planning, learning, Multi-robot coordination, path planning, navigation, localization.
3. Action [Actuators]: moving, control

# How to find research topics?
Manipulators
* Mobile robots
* Combination? Integration?
* Take advantage of two or more algorithms, or models…

# How to find research topics?
find a real problem ...

## [Problem]

![](https://scontent-hou1-1.xx.fbcdn.net/v/t1.6435-9/116107138_3156538307735289_5722845639577561145_n.jpg?_nc_cat=103&ccb=1-5&_nc_sid=8bfeb9&_nc_ohc=IkMRx9PZI8AAX8_HO3W&_nc_ht=scontent-hou1-1.xx&oh=41ca7ea5b7988d0339795145ea71720e&oe=61CDA057)

Concorde Air France Flight 4590 fire on runway The fallen part from previous taking off aircraft
that cause the disaster.

* Fallen parts from aircraft and other operating machine on the airport runways and taxiways are critical for aviation safety.
* Human capability of inspection for the fallen parts on runway and taxiway is restricted nowadays.

## [Solution]
* Idea: Inspection Robot System that can find such that material and remove it. 

![image](https://user-images.githubusercontent.com/72484101/144494807-470e5c55-6d5e-4b05-b814-d2f482e41dfd.png)

Dynamic Matlab-ROS mobile manipulator platform

1. Sensors:
* Hokuyo Lidar
* Microsoft Kinect Sensor
* Inertial Measurement Unit
2. Actuator:
* Pioneer3–AT Robot
* Trossen WidowX Robot Arm
3. Embedded System
* Intel NUC

![image](https://user-images.githubusercontent.com/72484101/144495168-519cce00-3662-4a15-8d1b-702192d8b540.png)

Hardware architecture

![image](https://user-images.githubusercontent.com/72484101/144495268-ebd3edf8-3795-41a2-a234-9d2c5a8ecf9a.png)

Hardware architecture showing the signal flowing and powering

![image](https://user-images.githubusercontent.com/72484101/144495571-95c6fa04-4825-481d-9d57-e4b7d88753f1.png)

WidowX Robot Arm working range

Figuers source:

1.Xihan Ma, Honglin Sun, Enwei Xu, Song Cui, Boqun Yin, Mariam Faied, "FSM for Robot Target Search and Retrieval under Semi-constructed Environment", Mechatronics and Automation (ICMA) 2020 IEEE International Conference on, pp. 296-301, 2020.

## [Publish]
A  Hybrid  Navigation  and  Image  Processing  Model  with  Dynamic Mobile  Manipulation. 

Abstract— A  mobile  manipulator  is  widely  used  for  manyscenarios such as warehouse management, and disaster rescuemissions.  The  autonomy  of  robots  operating  in  an  unknownenvironment  is  critical.  In  this  paper,  a  dynamic  mobile  ma-nipulation  robot  platform  based  on  the  Pioneer  3-AT  robot,equipped  with  one  6-DOF  manipulator  and  multiple  sensorsis  designed  and  tested.  This  autonomous  mobile  manipulatorrobot platform functions with mapping, path-planning, obstacleavoidance,  image  processing,  color-based  object  detecting  andmanipulation  algorithms  running  in  the  Matlab-ROS  environ-ment.  In  addition,  Arduino-based  devices  are  used  to  enablemanipulation control and other future add-on devices. The plat-form  is  operating  in  an  unknown  dynamic  environment  usinga  local  path  planning  algorithm  for  map  exploration,  color-based  object  detection,  and  manipulation  tasks.  The  projectaims to build a platform that is universally suitable for varioustask situations, as well as easy and efficient to modify and testalgorithms  with  the  advantage  of  data  processing  capabilityprovided  by  Matlab.  The  modification  for  integrating  Pioneer3-AT  robot  and  Trossen  Widow  X  robotics  arm  is  introducedon  both  hardware  and  software  levels.

https://ieeexplore.ieee.org/document/8961514

# Challenges in Robotics
* Autonomous vehicles – cars, delivers, etc
* Consumable robots – toys, vacuum cleaner, lawn mover, pool cleaner
* Robotic companions
* Search and rescue missions
* Environmental exploration
* Robotic surgery
* Multi-robot coordination 

In addition to other technological challenges, new efficient AI algorithms MUST be developed to address the nowadays and future challenges.
