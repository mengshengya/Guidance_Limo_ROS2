# Limo_ROS2

## How to use LiDAR
Launch a new terminal and enter the command:

`ros2 launch ydlidar_ros2_driver ydlidar.launch.py`

### Using Cartographer mapping
First, start the LiDAR. Launch a new terminal and enter the command:

`ros2 launch limo_bringup limo_start.launch.py`

Then start the cartographer mapping algorithm. Open another new terminal and enter the command:

`ros2 launch limo_bringup limo_cartographer.launch.py`
