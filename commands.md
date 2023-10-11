## terminal Commands
```
colcon build --symlink-install
```
```
source install/setup.bash
```
```
source /opt/ros/foxy/setup.bash
```
```
ros2 launch medbot rsp.launch.py
```
```
rviz2
```
```
ros2 run joint_state_publisher_gui joint_state_publisher_gui
```
```
ros2 launch medbot launch_sim.launch.py
```
```
ros2 run teleop_twist_keyboard teleop_twist_keyboard
```
```
ros2 run teleop_twist_keyboard teleop_twist_keyboard --ros-args -r /cmd_vel:=/diff_cont/cmd_vel_unstamped
```
```
ros2 launch slam_toolbox online_async_launch.py params_file:=./medbot/config/mapper_params_online_async.yaml use_sim_time:=true
```
```
ros2 run twist_mux twist_mux --ros-args --params-file ./medbot/config/twist_mux.yaml
```
```
ros2 launch nav2_bringup navigation_launch.py use_sim_time:=true
```
```
killall gzserver
```
```
killall gzclient
```
