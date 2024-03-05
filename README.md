This is the changed package, you can clone it and compile it directly. 
## Prerequisites

## compile
```
    cd ~/point-lio-mid360/src
    git clone https://github.com/Zjj587/Trajectory_saving_for_SLAM.git
    cd ../
    catkin_make
    source devel/setup.bash
```
## run
After the device(mid360) is connected, you can run:
```
# termianl 1: run livox_ros_driver2
roslaunch livox_ros_driver2 msg_MID360.launch

# terminal 2: run point_lio
roslaunch point_lio mapping_mid360.launch
```

