Old ROS Webcam Drivers [![Build Status](https://travis-ci.org/ros-drivers/camera_umd.svg?branch=kinetic-devel)](https://travis-ci.org/ros-drivers/camera_umd)
======================

This repository contains `uvc_camera`, a Video4Linux-based webcam driver for ROS. It is **deprecated**,
and it has been replaced by [libuvc_camera](https://github.com/ktossell/libuvc_ros) ([wiki](http://wiki.ros.org/libuvc_camera)), a cross-platform driver
for USB Video Class cameras. Please consider using `libuvc_camera` or another camera driver if your camera
supports the USB Video Class specification (as most webcams and several machine vision cameras do).

Documentation for this package can be found at [its wiki page](http://wiki.ros.org/uvc_camera).


## To run
roslaunch uvc_camera camera_node.launch // use rviz to visualize


## ZED supported modes
- discrete: 2560x720:   1/60 1/30 1/15
- discrete: 1344x376:   1/100 1/60 1/30 1/15
- discrete: 3840x1080:   1/30 1/15
- discrete: 4416x1242:   1/15
