# HOMEWORK 1 - TURTLE_CONTROL
Author: Ian Kennedy
This homework assignment ROS package can be used to create a series of waypoints, 
and control a turtle in turtlesim to follow these points. 
To run the package code, after compiling and sourcing the code, run the following in a terminal window with ROS running:
1) 'roslaunch turtle_control run_waypoints.launch'
2) 'rosservice call /restart "x: 0.0 y: 0.0" '

Note:  ensure that the path from the root workspace directory is as follows for accessing
the yaml file through the roslaunch command: src/turtle_control/config/waypoint.yaml

This will cause the turtle to follow points in an infinite loop.
Link to video: https://drive.google.com/file/d/18eMbT0r-s2wkTrKHSjRVosSIJYwUYza4/view?usp=sharing


Gif:

![alt-text](https://github.com/ianpkennedy/ROS_Turtlesim/blob/main/giphy.gif)

Source for YAML file writing: http://wiki.ros.org/rosparam#YAML_Format

Launch file parameter file loading source: https://roboticsbackend.com/ros-param-yaml-format/#Loading_params_from_a_YAML_file
