cmake_minimum_required(VERSION 2.8.3)
project(ackermann_vehicle_description)
find_package(catkin REQUIRED)
catkin_package()

install(DIRECTORY urdf/
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/urdf
)

install(DIRECTORY launch/
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/launch
)