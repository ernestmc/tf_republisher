cmake_minimum_required(VERSION 2.8.3)
project(tf_republisher)

find_package(catkin REQUIRED)

catkin_package()

catkin_install_python(PROGRAMS src/tf_republisher
                      DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION})
