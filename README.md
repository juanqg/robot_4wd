# robot_4wd
4WD Wheeled Robot Simulation with ROS, RVIZ and Gazebo

## CatKin Package
```
catkin_create_pkg robot_model_pkg roscpp rospy urdf rviz xacro std_msgs tf tf2 geometry_msgs joint_state_publisher_gui
```

## Validate urdf (In case you're in a container perhaps you'd have to install the URDF tools at the host...)
```
sudo apt-get install liburdfdom-tools
```

To validate an URDF
```
check_urdf PATH_TO_MODEL.urdf
```

Sample output:

check_urdf robot.urdf
robot name is: fourwheel_robot
---------- Successfully Parsed XML ---------------
root Link: body_link has 4 child(ren)
    child(1):  wheel1_link
    child(2):  wheel2_link
    child(3):  wheel3_link
    child(4):  wheel4_link


