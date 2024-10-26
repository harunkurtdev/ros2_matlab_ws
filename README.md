
# ROS2 MATLAB WS

### WHAT SUPPORT MSGS/SRV

autoware_msgs
px4_msgs

Download this repository with the submodules


It is important to download it to a directory like `C:/robotics/`. As the folder path gets longer, it may cause issues with the project.

```
git clone --recurse-submodules https://github.com/harunkurtdev/ros2_matlab_ws.git
```


```bash
cp -r msgs_matlab/autoware_msgs/* msgs_matlab/
cp -r msgs_matlab/automative_autonomy/* msgs_matlab/
```


run for the current project directory ros2_matlab_ws

## So important
all msg and srv pkg inside msgs_matlab file,

matlab generate a folder like this `matlab_msg_gen` and so big file.

your all ros2 pkg must be inside `src/ros_pkg`.

```bash
matlab ros2_matlab_ws
```

