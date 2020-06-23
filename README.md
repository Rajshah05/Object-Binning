# Autobots

Object binning and obstacle avoidance with SLAM and object detection in ROS

# How to run

1. Install ROS, Gazebo, and ROS packages such as gmapping, amcl, find_object_2d
2. Create a ROS catkin workspace if not already done: http://wiki.ros.org/ROS/Tutorials/InstallingandConfiguringROSEnvironment
3. Create catkin ros package in the ROS catkin workspace (cmd: catkin_create_pkg autobots std_msgs rospy roscpp)
4. Download and unzip the repository in the ROS workspace
5. update the workspace (like for python3, command: $ catkin_make -DPYTHON_EXECUTABLE=/usr/bin/python3)
6. Source the bash file of the workspace
7. make the files executable if required (cmd: chmod +x "file name")
8. Run "autobots.launch" file

# Please refer the following blogs for implementation and project details
https://medium.com/cse-468-568-robotic-algorithms/object-binning-and-obstacle-avoidance-using-slam-in-gazebo-part-1-3-902b9f4bd19e

https://medium.com/cse-468-568-robotic-algorithms/object-binning-and-obstacle-avoidance-using-slam-in-gazebo-part-2-3-118d2894c077

https://medium.com/cse-468-568-robotic-algorithms/7c3fe0210f17
