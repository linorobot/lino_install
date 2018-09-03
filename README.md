# Lino Installation   [![Build Status](https://travis-ci.org/linorobot/lino_install.svg?branch=master)](https://travis-ci.org/linorobot/lino_install)


The `install` file will install all the files you need to build an autonomous robot including:
- Teensy Firmware
- Sensor Driver
- Navigation Stack

You need to pass two arguments to the install file, where:
```
$ ./install <base> <sensor>
```

##### Base 
The type of robot you want to build. Valid arguments are 
- 2wd
- 4wd
- ackermann
- mecanum

##### Sensor 
The lidar you're going to use for your build. Valid arguments are 
- xv11
- rplidar
- ydlidar
- hokuyo
- kinect
- realsense
 

