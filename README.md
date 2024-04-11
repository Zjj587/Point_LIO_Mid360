# Point_LIO_Mid360
This is the `launch` file and `yaml` file that the project runs on.You can clone this, and put into [Point-LIO](https://github.com/hku-mars/Point-LIO).
The overall changed code is in `master` branch.
## Install and configure
1. [livox-SDK2](https://github.com/Livox-SDK/Livox-SDK2.git)
2. [Point-LIO](https://github.com/hku-mars/Point-LIO) and [livox_ros_driver2](https://github.com/Livox-SDK/livox_ros_driver2) in a file bag.
## run
git clone the project file into [Point-LIO](https://github.com/hku-mars/Point-LIO), Change the whole document from `livox_ros_driver` to `livox_ros_driver2`.
```
catkin_make
```
# After lidar operation
```
# termianl 1: run livox_ros_driver2
roslaunch livox_ros_driver2 msg_MID360.launch

# terminal 2: run point_lio
roslaunch point_lio mapping_mid360.launch
```
![demo](https://github.com/Zjj587/Point_LIO_Mid360/blob/main/demo.png)
# Acknowledgements

Thanks to Point-LIO code authors. 
