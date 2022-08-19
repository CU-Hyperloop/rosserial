# rosserial - CU Hyperloop Edition!

This fork of the main [rosserial package](http://wiki.ros.org/rosserial) fixes some issues with how Ethernet communication is handled on the Teensy 4.1. To install into ROS, you need to build this package rather than installing the binaries directly from the ROS Package Manager.

Where <ws> is the Catkin workspace you want to install into:

```
  cd <ws>/src
  git clone https://github.com/ros-drivers/rosserial.git
  cd <ws>
  catkin_make
  catkin_make install
```

# rosserial

[![Build Status](https://travis-ci.org/ros-drivers/rosserial.svg?branch=melodic-devel)](https://travis-ci.org/ros-drivers/rosserial)

Please see [rosserial on the ROS wiki](http://wiki.ros.org/rosserial) to get started.
