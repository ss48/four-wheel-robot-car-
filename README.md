
![car](https://github.com/user-attachments/assets/64381d53-e23c-43a0-bb9c-76747654522a)

![Screenshot from 2025-02-23 15-47-11](https://github.com/user-attachments/assets/357aca10-bb22-41ba-a351-5dee697b717b)

![Screenshot from 2025-02-23 15-47-19](https://github.com/user-attachments/assets/db0d1678-a6d1-4357-a22e-c2c5e02cbd65)

update the package name and the address
launch the package:

roslaunch test_urdf car.launch
view the frames:

rosrun tf view_frames 

rosrun rqt_image_view rqt_image_view

move the robot using: 

rostopic pub /diff_drive_controller/cmd_vel geometry_msgs/Twist "linear: x: 0.5 y: 0.0 z: 0.0 angular: x: 0.0 y: 0.0 z: 0.0" -r 10
