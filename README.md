# robotic-mining
The Utah Robotic Mining Project

##These packages must be installed in order for catkin_make to run correctly
sudo apt-get install ros-kinetic-find-object-2d
sudo apt-get install libusb-1.0-0 libusb-1.0-0-dev
sudo apt-get install ros-kinetic-joystick-drivers
sudo apt-get install ros-kinetic-realsense-camera
sudo apt-get install libopenni2-dev
sudo apt-get install ros-kinetic-rtabmap-ros
sudo apt-get install libgsl0-dev
rosdep install amcl
rosdep install base_local_planner
rosdep install carrot_planner
rosdep install global_planner
rosdep install gmapping
rosdep install slam_gmapping
rosdep install move_base
rosdep install navfn
rosdep install robot_pose_ekf
rosdep install robot_localization
rosdep install rtabmap_ros

Install Phidgets
Get the phidget libraries from http://www.phidgets.com/downloads/libraries/libphidget.tar.gz
Unzip the archive and go into it.
Run: ./configure
make
sudo make install

* joystick: http://wiki.ros.org/joy/Tutorials/ConfiguringALinuxJoystick

