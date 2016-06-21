## System Details
* Intel i7-3612QE @ 2.1GHz
* 4gb of ram
* ?? mSata hard drive


## Installing ROS
* Upgraded to ubuntu 14.04
   * Removed old groovy installation of ROS
   * Put all original source code in /old_asctec/
   * Painfully updated to xubuntu 14.04.2
* http://wiki.ros.org/ROS/Installation
* http://wiki.ros.org/indigo/Installation/Ubuntu
* Things seem to be stable, and updated to indigo



## VI-Sensor
* This needs to be hooked up to power, and a data line
* Plugged the vi sensor into a external power plug coming from the mastermind
* 1' ethernet gets feed into the mastermind for the datafeed
* The provided virtual machine does not work
* http://wiki.asctec.de/display/AR/VI-Sensor
* http://i.imgur.com/L49LbwL.jpg
* http://asctec.de/downloads/software/AscTec_Xubuntu-12.04-64Bit_VI-Sensor.ova
* Main vi-sensor page: http://wiki.ros.org/vi_sensor
* Calibration the sensor: https://github.com/ethz-asl/kalibr/wiki/calibrating-the-vi-sensor
* **Key Note:**
  * The sensor has been tested with the visensor node
  * https://github.com/ethz-asl/visensor_node
  * Camera feeds work, but the to further test it needs to be calibrated


