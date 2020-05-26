# Build A Robot
simulation robot with gazebo and rviz

## Introduction



## Pre-requisites
1. ROS

## Install


## How to use it
set up Camera,robotmodel and LaserScan in rviz

$ cd /home/workspace/catkin_ws/
$ source devel/setup.bash
$ rostopic pub /cmd_vel geometry_msgs/Twist  "linear:
  x: 0.1
  y: 0.0
  z: 0.0
angular:
  x: 0.0
  y: 0.0
  z: 0.1" 