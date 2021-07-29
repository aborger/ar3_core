cmake_minimum_required(VERSION 2.8.3)
project(ar3_gazebo)
find_package(catkin REQUIRED)
catkin_package()

install(PROGRAMS
    src/tf_world_transform.py
    DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)