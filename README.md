# ros_Ws_template

My ROS workspace template

## Install

```
sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
sudo apt-key adv --keyserver hkp://pool.sks-keyservers.net --recv-key 0xAB17C654
sudo apt-get update
sudo apt-get install python3-vcstool
```

## Usage

```
git clone git@github.com:scepter914/ros_ws_template.git
cd ros_ws_template
mkdir src
vcs import src < autoware.proj.repos
```


