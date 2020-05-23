Build a robot with camera, and drive it with message and service

## Pre-requisites
1. ROS


## Install
    mkdir -p ros_robocam/src
    cd ros_robocam
    catkin_init_workspace
    cd src
    git clone -b robot_with_cam  https://github.com/Jay9z/building_a_robot.git simple_arm
    cd ..
    catkin_make


## How to use
1. source devel/setup.bash
2. roslanuch simple_arm my_robot robot_spawn.launch

### drive robot move along a fixed path
    $source devel/setup.bash
    $rosrun simple_arm simple_move
    $source devel/setup.bash


###