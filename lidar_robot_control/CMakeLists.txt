cmake_minimum_required(VERSION 3.0.2)
project(lidar_robot_control)

find_package(catkin REQUIRED COMPONENTS
  actionlib
  actionlib_msgs
  control_msgs
  controller_manager
  robot_state_publisher
  sensor_msgs
)

catkin_package()


include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
