## About
This repository contains basic settings, instructions and recommendations for setting up workspace to make work with ROS easy. 


## Setup Workspace to work with vscode

1. Just clone it into your workspace
    ```bash
    git clone https://github.com/pktiuk/vscode_ros_config.git .vscode
    ```
2. Open workspace using vscode
3. Install recommended plugins
4. (not recommended if you have installed all dependencies) Install ROS dependencies by pressing `Ctrl+Shift+P` and writing: `ROS: Install ROS Dependencies for this workspace`
5. (optional, but recommended) Build your workspace (in regular way by terminal or using Build Task)
6. Using vscode commands (`Ctrl+Shift+P`) run (it ensures proper autocompletion support):
    - `ROS: Update C++ properties`
    - `ROS: Update Python Path`
7. For better support of C++ completion generate `compile_commands.json`
```
catkin_make  -DCMAKE_EXPORT_COMPILE_COMMANDS=1
```
8. Restart vscode, it should ask you about using newly generated `compile_commands.json`
