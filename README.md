# installing-ros


installing ROS in Jesten Nano

first we need to make sure  Jetson Nano can  accept ros packages

```
{
  console.log("notice the blank line before this function?");
}
```
$ sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'

Add a new apt key:

$ sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654



Update the Debian packages index:

$ sudo apt update

Install the ROS Desktop package, including support for rqt, rvizand other useful robotics packages:

$ sudo apt install ros-melodic-desktop

