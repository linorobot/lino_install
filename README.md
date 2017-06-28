### lino_install   [![Build Status](https://travis-ci.org/linorobot/lino_install.svg?branch=master)](https://travis-ci.org/linorobot/lino_install)
- - - -

## Installation:

This will install all the files you need to build an autonomous robot including:
- Teensy Firmware
- Sensor Driver
- Navigation Stack

You need to pass two arguments to the install file, where:

base = The type of robot you want to build. Valid arguments are 2wd, 4wd, ackermann, and mecanum.
sensor = The lidar you're going to use for your build. Valid arguments are xv11 and rplidar.
 
```
$ ./install <base> <sensor>
```