 #AlohaMini_Simulation
 
 AlohaMini Simulation includes the visualization of AlohaMini by rviz in ROS1/2.

Quick Start
git clone 
cd AlohaMini-Simulation

colcon build

source install/setup.bash
# Change to FastDDS
export RMW_IMPLEMENTATION=rmw_fastrtps_cpp

# Test
ROS2:
ros2 launch Aloha display.launch.py  #rviz2 visualization
ROS1:
roslaunch Aloha display.launch       #rviz visualization
roslaunch Aloha gazebo.launch        #gazebo visualization
