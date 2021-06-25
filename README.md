# eurobench_stairs

This repository contains the models for different stair configurations

# How to execute the simulation

You can use the ROS launch file and then insert the appropriate model in Gazebo dynamically:

`$roslaunch eurobench_stairs gazebo.launch`

Or you can specify a model to be explicitly launched (for example the Steps one):

`$roslaunch eurobench_stairs gazebo.launch world:=steps`


