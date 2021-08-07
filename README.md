# Outdoor Navigation:

## Overview -
This is a research project to explore navigation strategies in outdoor terrains that have diverse topographical features. The setup we used are:
- ClearPath Jackal
- Intel Realsense D435i (RGB-D) camera
- Hokuyo URG Lidar
- Alienware Laptop


Setup -
<p align="center">
<img src="/setup_jackal.png" height="500" width="500" />
</p>
We explored terrains such as grass, pavements, brick road, and tar road. Our solution works both indoor and outdoor. We were able to achieve short navigation goals in an outdoor scene and excellent Visual SLAM implementation indoors. 

## Results:
Outdoor Mapping results 
<p align="center">
<img src="/odom_pcl.png" height="300" width="300" />
</p>

<p align="center">
<img src="/odom_imu_pcl_match.png" />
</p>

[Indoor Navigation Video](https://drive.google.com/file/d/1ofelgKvekMCnvTF6X7wl-AqVWJtGFIdP/view?usp=sharing)

## Dependencies -
- ROS Kinetic/Melodic
- RTABMAP
- robot_localization

## Run
```
roslaunch outdoor_waypoint_nav robot_sim_mapping.launch
```

## References:
- [Husky Localization](https://github.com/nickcharron/waypoint_nav/)
- [Initial lab experiment](https://github.com/utsavpatel22/waypoint_nav/)
- [Jackal Tutorials](https://www.clearpathrobotics.com/assets/guides/kinetic/jackal/index.html)
- [Jackal user Guide](https://www.generationrobots.com/media/Jackal_Clearpath_Robotics_Userguide.pdf)
- [Original Jackal Repo](https://github.com/jackal/jackal/tree/kinetic-devel)
