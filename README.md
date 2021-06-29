# Navbot

Navbot is a project aiming to create a software navigation system for home robots. 

## Stage 0

_Stage 0_ aims to create the robotics platform that will be used for development and testing of the software. Likely a tracked or a three-wheeled (with two driving and one parasite wheels) scheme of movement. Various sensors will be tested to study their capabilities, including 360-degree LIDAR, fixed LIDAR, oscilating and fixed ultrasonic sensors, IR rangefinders etc.
Likely features:
1. two motors for movement. The precise movement scheme is yet to be decided.
2. RaspberryPi integrated in the platform for handling the calculations
3. wireless communication with base station
4. probably database for storing mapping data will be integrated in base station. This will allow data requests to be handled by a more powerful CPU.
5. most, if not all of the hardware will be 3d-printed. 

## Stage 1

At this stage the algorighm to map the enviroment will be devised as well as an algorithm for finding the path in the mapped environment. 
The mapping algorithm will be statistically based, to allow for storing the probable positions of movable objects and minding those when calculating paths. 

## Stage 2

At this stage the robotics platform will be reingeneered for flight and hover capabilities and the algorithms will be adapted to work in three-dimensional enviroment.
