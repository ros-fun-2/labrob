cmake_minimum_required(VERSION 2.8.3)
project(labrob_gazebo)

find_package(catkin REQUIRED COMPONENTS
  gazebo_msgs
  gazebo_plugins
  gazebo_ros
  gazebo_ros_control
  hector_gazebo_plugins
  labrob_description
  turtlebot_bringup
)


catkin_package()

include_directories(
  ${catkin_INCLUDE_DIRS}
)
