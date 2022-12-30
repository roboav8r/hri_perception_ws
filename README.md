# hri_perception_ws
ROS workspace for my Ph.D. research regarding perception and tracking for human-robot interaction

## Installation
At your home (`~`) directory:
```
git clone --recursive https://github.com/roboav8r/hri_perception_ws
cd hri_perception_ws
catkin build
source devel/setup.bash
```

## First-time Setup
When running for the first time, create the robofleet configuration files for `leg_tracker`:
```
cd hri_perception_ws
rosrun robofleet_client generate_plugin_pkg.py leg_tracker -o src
catkin build
```
