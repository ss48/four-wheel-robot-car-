update the package name and the address
roslaunch test_urdf car.launch
rosrun tf view_frames 

rosrun rqt_image_view rqt_image_view

move the robot using: 

rostopic pub /diff_drive_controller/cmd_vel geometry_msgs/Twist "linear: x: 0.5 y: 0.0 z: 0.0 angular: x: 0.0 y: 0.0 z: 0.0" -r 10
