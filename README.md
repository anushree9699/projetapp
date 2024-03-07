# Gazebo Camera Setup

## Required Packages

1. Download and install the RealSense D405 camera package from [rjwb1/realsense-ros](https://github.com/rjwb1/realsense-ros).
2. Replace the `realsense2_description` folder with the one available on [Issaiass' RealSense2 Description repository](https://github.com/Issaiass/realsense-ros).
3. Download the RealSense Gazebo Plugin by Pal Robotics.

## Setup Catkin Workspace

1. Ensure all downloaded packages are in the `src` folder of your Catkin workspace.
2. Run `catkin_make` to compile the workspace.

## Launch the Simulation

Execute the following command to launch the simulation with the RealSense D435 camera model in both RViz and Gazebo:

```bash
roslaunch realsense2_description view_d435_model_rviz_gazebo.launch
