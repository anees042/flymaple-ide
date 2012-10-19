FlyMaple
========

Information
-----------

This project is released under the GNU GPLv3 (see LICENSE file). Some code may have been copied from external projects. When it is the case the license is detailed in the file.
Please see the [wiki](http://wiki.open-drone.org/doku.php?id=flymaple) for more information.

How to use
----------

**Software**
Get the code in a folder named `FlyMaple1_0` in your sketchs folder. The following command can help you. Execute it from your sketchbook.
    git clone https://github.com/opendrone/flymaple-ide.git FlyMaple1_0

**Hardware**
You should take care of:
* Keeping the center of gravity centered <!-- be more precise here -->

Files
-----

* *FlyMaple1_0.pde* − Main file with the setup() and loop() functions
* *AHRS.pde* − Functions to manage the [Altitude and Heading Reference System](http://en.wikipedia.org/wiki/Attitude_and_heading_reference_system)
* *MOTOR.pde* − 
* *CapturePPM.pde* − 
* *Communication.pde* − Utility functions to help debugging
* *ADXL345.pde* − Librairy file for [ADXL](https://www.sparkfun.com/products/9836) 345 3-axis digital accelerometer
* *BMP085.pde* − Librairy file for [BMP085](https://www.sparkfun.com/products/9694) barometric pressure sensor
* *HMC5883.pde* − Librairy file for [HMC5883](https://www.sparkfun.com/products/10426) 3-axis digital compass
* *ITG3205.pde* − Librairy file for [ITG3205](http://www.flytron.com/sensors/160-itg3205-digital-gyro-breakout.html) digital gyroscope

Todo
----

* integrate PID and calibrate values

Resources
---------

* http://www.mstarlabs.com/control/znrule.html
* http://aeroquad.com/showthread.php?1167-Stable-Mode-Explained

Some examples
-------------

* [PID library for the arduino](https://github.com/mwoodward/Arduino-PID-Library/blob/master/PID_v1/Examples/PID_AdaptiveTunings/PID_AdaptiveTunings.pde) by [mwoodward](https://github.com/mwoodward)
