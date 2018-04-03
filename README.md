# kobuki_localcontrol

## Introduction
This repo hold the files needed for running the floor robots in the Leonard Lab.  This repo forms a catkin workspace on the remote computer running on each robot. 

## Installation Instructions
1. Create a catkin workspace on the robot's computer.
2. In the src folder create a directory titled kobuki_localcontrol.
3. Clone this repository into kobuki_localcontrol.
4. Make the catkin workspace.

## Usage Instructions
On startup each robot is programmed to clone the master branch of this repository and run the start_active.launch file.  To edit what ROS nodes run on startup, edit the start_active.launch file.
