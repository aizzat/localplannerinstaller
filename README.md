# localplannerinstaller
Simplified Installer for Local Planner Tutorial

# Dependency 

1. ROS Noetic

# Installation

1. Create catkin_ws if you have not done this: 
```
cd ~
mkdir -p ~/catkin_ws/src
cd ..
catkin_make
```
Please ensure it is compiled successfully. 

2. Download and run the installer: 

Type S for source install as instructed and enter Sudo password. 

```
cd ~
git clone https://github.com/aizzat/localplannerinstaller 
cd ~/localplannerinstaller
chmod +x localplannerinstaller
./localplannerinstaller
```

# Usage: 

The usage is similar with TED local planner usage. 

```
rosparam set /test_optim_node/enable_homotopy_class_planning False
roslaunch teb_local_planner test_optim_node.launch
```



