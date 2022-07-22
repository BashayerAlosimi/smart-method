These are the commands for installing ROS noetic on Ubuntu 20-04 
	1- source.list (echo "deb http://packages.ros.org/ros/ubuntu focal main" | sudo tee /etc/apt/sources.list.d/ros-focal.list)
	2- add official ROS key (sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654)
	3-update ROS package index (sudo apt update)
	4-installing ROS Noetic package "ros-noetic-desktop-full" (sudo apt install ros-noetic-desktop-full)
	5-set up ROS Noetic environment (source /opt/ros/noetic/setup.bash)
	(echo "source /opt/ros/noetic/setup.bash" >> ~/.bashrc)
	6-last step to make sure that ROS is installed correctly (roscore)
  
