Installation
1. Clone this repo into the src folder of your workspace.
2. Install dependencies :-

sudo apt update
sudo apt install
ros-humble-cartographer
ros-humble-cartographer-ros
ros-humble-navigation2
ros-humble-nav2-bringup
ros-humble-turtlebot3-gazebo
pip3 install numpy scikit-learn

4. Build the ws and source ws/install/setup.bash
5. Launch using command
   
ros2 launch autonomous_tb exploration.launch.py

6. Save map using :-

ros2 run nav2_map_server map_saver_cli -f map
