cmake_minimum_required(VERSION 3.1.3)
project(ar3_hardware)

find_package(catkin REQUIRED
    COMPONENTS
        roscpp
        rospy
        std_msgs
)

catkin_package()
