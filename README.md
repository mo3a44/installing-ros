# installing-ros


installing ROS in Jesten Nano

first we need to make sure  Jetson Nano can  accept ros packages

```

 $ sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu 
 $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'

```


second we need to add new apt key  
```

$ sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654

```


now we make sure Debian packages is up-to-date:
```

$ sudo apt update

```


now we can install ros using this command line 
```

$ sudo apt install ros-melodic-desktop

```

