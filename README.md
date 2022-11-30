# wta_mpc_ros_Simulation
Simulations for the paper "Prescient Collision-Free Navigation of Mobile Robots with Iterative Multi-modal Motion Prediction of Dynamic Obstacles"

To run the simulation, after building the workspace and sourcing it, lunch the main.launch file inside the mpc_motion_pred package:

>> roslaunch mpc_motion_pred main.launch

The simulation is going to start in paused state. This is to provide you the chance to prepare the prediction and planning program to run. When you are ready, you may start the simulation by pressing the run button at Gazebo Simulator.

You might not have the following packages in your system: ros-noetic-costmap-queue and libsdl-dev. You may install them using the apt package manager:

>> sudo apt-get install libsdl-dev
>> sudo apt-get install ros-noetic-costmap-queue
