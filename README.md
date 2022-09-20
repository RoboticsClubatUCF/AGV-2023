# AGV-2023
RCCF's entry for annual IGVC competition occurring in 2023.

This repository contains a series of ROS packages used in the operation of an autonomous ground vehicle.

# Setup 
This package requires Ubuntu 20.04 (either as a VM, container, or actual system). Like all ROS1 packages, it's meant to be placed inside a catkin_ws at path /home/$USER/catkin_ws

1. Clone this repo into ~/catkin_ws/src with 
	' git clone https://github.com/RoboticsClubatUCF/AGV-2023.git '

2. Run the setup script with 
	' ./setup.sh '



# Directories

**agv_sim**
- This directory will contain the launch files, simulation worlds, and configuration files used for RVIZ. This may also contain any scripts we use to make working with the sim easier, and submodules for simulating sensors. 

**agv_nav**
- This directory will contain configuration and launch files for our navigation stack. Move-base, robot-localization, and slam-toolbox should be configured and launched here. 

**agv_vision**
- This directory will contain any scripts and plugins we use for computer vision.

**agv_model**
- This directory will contain the simulation model for our robot.

**agv_states**
- This directory will contain the launch files and scripts for our state machine.
	 
