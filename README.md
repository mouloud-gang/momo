Concepts Réseau & DDS
echo "source /opt/ros/jazzy/setup.bash" >> ~/.bashrc
echo "source ~/ros2_ws/install/setup.bash" >> ~/.bashrc
source ~/.bashrc
export ROS_DOMAIN_ID=42
ros2 doctor
ros2 multicast receive
dans le 2eme terminal:
ros2 multicast send
dans le 1er terminal on a:
Received from <IP>: 'Hello World!'
