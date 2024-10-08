# quadruped-robot
![quadruped](https://github.com/Hamza47477/Quadruped-robot-inverse-kinematics/blob/main/Robot_hardware.png)

A quadruped robot for a university capstone project. The associated CAD files can be found on [GrabCad](https://grabcad.com/library/quadruped-robot-w-code-1)

## Installation
To use this code simply download the repository onto the raspberry pi, install the requirements, set up the pi for camera and the servo library usage, and run `python3 control-quadruped`. This will start the walking motion and print out the pi's IP and port. Run the controller on your computer, setting the IP and port given by the pi and the robot will start taking momentum data from the controller.


## Project Info
### Intro
This project was created with the intention of developing a robot that can follow users as a proof of concept for a larger assistant quadruped. The associated code allows for keyboard based control and was structured such that new controllers can easily be implemented by sending momentum packets to the raspberry pi.

### Robot Control
The robot uses an inverse kinematic model to determine how to position the foot in the requested location. Some of the math for this can be seen in the model directory with the jupyter notebook 

