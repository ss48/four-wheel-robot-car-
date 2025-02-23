
![Screens![car](https://github.com/user-attachments/assets/8a10ff29-2975-4ad6-af17-d9807cd7507a)

h![car](https://github.com/user-attachments/assets/421d1374-6244-4f82-8bbd-cc3289567d6c)
ot from 2025-02-23 15-47-19](https://github.com/user-attachments/assets/feaf1294-1754-46cf-bc66-3fcbafde0d87)

![Screenshot from 2025-02-23 15-47-11](https://github.com/user-attachments/assets/2a341810-1ac4-4f23-bae7-52cd0b61c755)


update the package name and the address
roslaunch test_urdf car.launch
rosrun tf view_frames 

rosrun rqt_image_view rqt_image_view

move the robot using: 

rostopic pub /diff_drive_controller/cmd_vel geometry_msgs/Twist "linear: x: 0.5 y: 0.0 z: 0.0 angular: x: 0.0 y: 0.0 z: 0.0" -r 10
