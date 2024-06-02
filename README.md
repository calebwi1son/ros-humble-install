# ros2_humble_install
Requirements:
- Ubuntu 22.04
- 6 gb storage

GIT INSTALL:
```
cd && git clone https://github.com/Marine-Robotics-Club/ros2_humble_install.git
```
```
cd ~/ros2_humble_install && chmod +x ros2_humble_install && ./ros2_humble_install
```
follow installation steps and enjoy ^_^
```
nano +124 ~/.bashrc
```
Place this command in empty line: use right click
```
source /opt/ros/humble/setup.bash
```
ctrl+s >> ctrl+x

close terminal open new one

test

```
ros2 run demo_nodes_cpp talker
```
open second terminal
```
ros2 run demo_nodes_cpp listener

```
example: [INFO] [talker]: Publishing: 'Hello World: X'
open third terminal 
```
ros2 topic list

```
see the topics?? good work



NOTE: this will install ros2-humble-desktop
