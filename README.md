# ROS
How to install ROS Kinetic in Ubuntu 16.04

Download Ubuntu 16.04:
http://ftp.rediris.es/sites/releases.ubuntu.com/16.04/ubuntu-16.04.4-desktop-amd64.iso


Steps:

sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'

sudo apt-key adv --keyserver hkp://ha.pool.sks-keyservers.net:80 --recv-key 421C365BD9FF1F717815A3895523BAEEB01FA116

sudo apt-get update

sudo apt-get install ros-kinetic-desktop-full
have you had any problem here? Are you installing ROS Kinetic in Ubuntu 16.04 or are you using another Ubuntu distro?

sudo rosdep init

rosdep update
