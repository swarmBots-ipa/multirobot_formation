# Multi Robot Formation for SwarmBot 

## 1. Bringup the multirobot simulation, Localization and Pathplanning
````
ros2 launch multirobot_bringup multirobot_bringup.launch.xml
````
## 2. Send pallet pose from rviz2
````
ros2 run multirobot_navigation compute_pallet_pose
````

### To perform Localization error experiments
1. Run the launch files in 1 and 2.
2. Select 2D Goal Pose on the rviz and choose a pose and wait for the robot navigation to complete.
3. Repeat the experiment by selecting multiple pose within the map.