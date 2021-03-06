# spis16-project-planning-robotics-Elaine-Tiffany
# Names, Area, Mentor
Elaine H. and Tiffany T., Robotics Lab, Mentor: David Le

#Brief Description
We are planning to create an obstacle course that the robot has to navigate through using an ultrasonic sensor placed on a servo. If we have time and it is available, we will use a camera to detect color and have the robot do different things to obstacles of different colors. Otherwise, we will add led lights and have certain colors light up depending on how far the robot is from the end of the course (or just have different colors light up at random times if we can't configure this). We will also try to have the robot pick up an object at the end of the course and push it back through the course to the start or we will have the robot circle around the object at the end of the course. Then, we plan to place multiple objects in the obstacle course and have a seven segment display show the number of objects the robot has found.

#Stages
* First stage: get the robot to turn when it gets too close to an obstacle.
* Second stage: If we get the camera to work, have the robot do different things in front of different colored objects. Otherwise, set up a few obstacles and test different types of obstacle avoidance.
* Third stage: Add the led lights - have light colors change after a certain rule e.g. after every turn.
* Fourth stage: Either have the robot pick up and object or circle around an object at the end of the course.
* Fifth stage: (If time - more advanced) place multiple objects for the robot to find in the obstacle course and have a seven segment display show the number of objects the robot has found.

#Where we are as of 8/29/16
We wrote code for a robot that dodges obstacles by turning right, detecting a certain distance in respect to a threshold, then turning left (obstacle avoidance). We did this through a set of 4 states (state0 - state3), however the current code is not working as we expect it to. Tomorrow we plan on fixing this problem and adding additional states that allow the robot to go around (or maneuveur) obstacles. 
---------------------
Pre writeup ideas:

Things you can do with a robot -
* obstacle detection
* drawing
* maze
* room coverage (movement in all four directions)
* can incorporate leds - button, seven segment display, led lights
* sensors can detect: light, motion, temperature, and sound (ultrasonic sensor)

Idea #1
* Design a robot that maneuvers around a certain color obstacle and hits a different color obstacle out of the way while going through a maze (uses camera).

Idea #2
* Design a robot that comes when called (when it detects motion from us) and does cool tricks.

Idea #3
* Find an object of specific color (scavenger hunt - uses camera).

Idea #4
* Have the robot find its way through an obstacle course (robot finds its way through light sensors seeing all the leds flashing or use led colors to lead the robot through), find objects, build something using objects, come to us when called (when it detects motion from us) or find an object and push towards a specific spot.
* More advanced - use seven segment display to show how many objects still need to be found.

