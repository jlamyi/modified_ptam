# Modified Ethzasl_ptam


Modified version of Ethzasl_ptam by James Lam Yi. See http://wiki.ros.org/ethzasl_ptam for a detailed overview.

[![Build Status](http://129.132.38.183:8080/job/ethzasl_ptam/badge/icon)](http://129.132.38.183:8080/job/ethzasl_ptam/)

## Feature

* Integrate usb_cam launch and RVIZ into one launch file

* Improve response speed while waiting for GrabFram in calibration

## Run
```
# launch camera calibrator

roslaunch ptam cameracalibrator_start.launch

# launch ptam

roslaunch ptam ptam_start.launch
```

## Documentation

https://sites.google.com/site/zhilongliuwebsite/research/ptam

