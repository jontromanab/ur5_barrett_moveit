# ur5_barrett_moveit

This package is automatically generated from MoveIT. Some files are modified manually as per need.
To run the demo:

roslaunch ur5_barrett_moveit demo.launch

We can also run the moveit pacakge with Gazebo. To run the robot in gazebo:

roslaunch ur5_barrett_bringup ur5_barrett_table_world.launch limited:=true

roslaunch ur5_barrett_moveit ur5_barrett_moveit_planning_execution.launch limited:=true


The rviz file is already included in the planning_execution file. So we don't have to run RVIZ separately. 
We are using the joint limited version urdf for better planning. Please try to use the  RRTkConfigDefault planner. The default planner fails most of the time.
