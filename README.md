## About
This repository contains basic settings and recommendations for setting up workspace to make work with ROS easy. 


## Setup Workspace to work with vscode

1. Just clone it into your workspace
    ```bash
    git clone https://github.com/pktiuk/vscode_ros_config.git .vscode
    ```
2. Open workspace using vscode/codium
3. Install recommended plugins
4. (not required if you have installed all dependencies) Install ROS dependencies by pressing `Ctrl+Shift+P` and writing: `ROS: Install ROS Dependencies for this workspace`
5. (optional, but recommended) Build your workspace (in regular way by terminal or using Build Task)
6. Using vscode commands (`Ctrl+Shift+P`) run (it ensures proper autocompletion support):
    - `ROS: Update C++ properties`
    - `ROS: Update Python Path`