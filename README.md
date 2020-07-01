# TwiPi-follows-Sparki

1. Create catkin workspaces on both machines.

    We will call them pub and sub
    
    http://wiki.ros.org/catkin/Tutorials/create_a_workspace
    
2. Create rostopics namely pub and sub

    in pub
    ```bash
    cd catkin_ws/src
    catkin_create_pkg pub rospy
    cd pub/src
    curl -o pub.py https://github.com/KedarMore/TwiPi-follows-Sparki/blob/master/Pub/ 
    ```
    in sub
    ```bash
    cd catkin_ws/src
    catkin_create_pkg sub rospy
    cd pub/src
    curl -o sub.py https://github.com/KedarMore/TwiPi-follows-Sparki/blob/master/Sub/ 
    ```
3. Run the .sh files making certain changes
    
    in pub
    ```bash
    curl -o init.sh https://github.com/KedarMore/TwiPi-follows-Sparki/blob/master/Pub/
    curl -o pub.sh https://github.com/KedarMore/TwiPi-follows-Sparki/blob/master/Pub/
    ./init.sh
    ./pub.sh
    ```
    in sub
    ```bash
    curl -o sub.sh https://github.com/KedarMore/TwiPi-follows-Sparki/blob/master/Sub/
    ./sub.sh
    ```
