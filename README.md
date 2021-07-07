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
6. ROS based

## Stage 1

At this stage the algorighm to map the enviroment will be devised as well as an algorithm for finding the path in the mapped environment. 
The mapping algorithm will be statistically based, to allow for storing the probable positions of movable objects and minding those when calculating paths. 

## Stage 2

At this stage the robotics platform will be reingeneered for flight and hover capabilities and the algorithms will be adapted to work in three-dimensional enviroment.

## Reading material

https://create.arduino.cc/projecthub/Isaac100/getting-started-with-the-hc-sr04-ultrasonic-sensor-036380

https://create.arduino.cc/projecthub/team-diy/arduino-ultrasonic-radar-a7cd97

https://create.arduino.cc/projecthub/jrance/arduino-obstacle-avoidance-robot-with-ultrasonic-hc-sr04-23035d

https://create.arduino.cc/projecthub/microlab-greece/arduino-two-ultrasonic-sensor-radar-360-degrees-rotation-de16ae

https://create.arduino.cc/projecthub/chandran0303cn/obstacle-avoidance-bot-using-ir-sensors-08f8e9

https://create.arduino.cc/projecthub/Abhinav_Abhi/arduino-lidar-917404

https://create.arduino.cc/projecthub/faweiz/arduino-radar-69b8fe

https://create.arduino.cc/projecthub/Satyavrat/ultrasonic-map-maker-using-an-arduino-yun-37c72e

https://create.arduino.cc/projecthub/TravisLedo/arduino-lidar-scanning-java-rendering-6b2124

https://create.arduino.cc/projecthub/lbf20012001/sound-location-finder-92e6b0

https://electronoobs.io/tutorial/48#

https://www.youtube.com/watch?v=zc0YykEFcR8

https://www.instructables.com/How-to-Use-the-RPLIDAR-360-Laser-Scanner-With-Ardu/

https://www.eevblog.com/forum/projects/hobby-lidar-build/msg1567591/

https://www.ardumotive.com/arduino-3d-scanner.html

https://medium.com/robotics-weekends/2d-mapping-using-google-cartographer-and-rplidar-with-raspberry-pi-a94ce11e44c5

