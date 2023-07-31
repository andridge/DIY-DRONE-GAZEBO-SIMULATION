## Readme 
<img width="1440" alt="Screenshot 2023-07-30 at 22 24 36" src="https://github.com/andridge/DIY-DRONE-GAZEBO-SIMULATION/assets/46260701/13237d5b-52b1-4a50-919d-8c06d6242375">
File

This readme file provides the correct order of commands for executing a specific task.

## Instructions

1. Open a terminal.
2. Navigate to the root of the workspace.
3. Run the following commands in the given order:

```bash
roscore
4.include this folder with a your workspace folder inside a src folder
4. Open another terminal on your workspace folder .
catkin_make
source devel/setup.bash
roslaunch DRONE101_description gazebo.launch
