# hector_slam

See the ROS Wiki for documentation: http://wiki.ros.org/hector_slam

How to use:

Refer to http://wiki.ros.org/hector_slam/Tutorials/MappingUsingLoggedData

1) install
sudo apt-get install ros-melodic-hector-slam

2) record a bag file (More info on http://wiki.ros.org/rosbag/Tutorials/Recording%20and%20playing%20back%20data)
(cd into your bagfile folder): $ rosbag record -a
Move robot around, try to cover as many area as possible
Ctrl+C to stop and save the bag file

3) launch hector slam
$ roslaunch hector_slam_launch tutorial.launch

4) play the bag file
cd into your bagfile folder
$ rosbag play Team_Hector_MappingBox_RoboCup_2011_Rescue_Arena.bag



