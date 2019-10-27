turtlebot package:
Simulates a turtlebot by providing the basic drivers needed for running and navigating a turtlebot which is equipped with all the necessary sensors and cameras for navigation

turtlebot_interaction package:
defines how the turtlebot interacts with RVIZ so as to show the robot navigating through the environment in realtime viewing the cost cloud, trajectory and the path followed by the robot also displaying the markers that are published

SLAM_gmapping package:
Its responsible for the localization and mapping of the environment. It uses laser and odometry data to compute the map and robot position


turtlebot_simulator package:
its responsible for deploying the turtlebot in a gazebo simulation

pick_objects:
Provides the robot with 2d nav goals automatically

add_markers:
Publish markers in RVIZ to show the location of the 2d nav goals
