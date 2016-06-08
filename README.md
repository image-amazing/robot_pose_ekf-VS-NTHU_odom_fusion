# robot_pose_ekf VS NTHU_odom_fusion

## ROS robot_pose_ekf (ekf with odom and imu data in Odroid)
  * "feedback_wheel_angularVel" topic contains angular velocity of two wheels.

![](https://github.com/piliwilliam0306/robot_pose_ekf-VS-NTHU_odom_fusion/blob/master/9PlWL8sO3dqDf2gr-51E4B.png)



## NTHU_odom_fusion (fusion in PIC MCU)
  * Sending angular velocity of two wheels to do sensor fusion in PIC MCU.
  * Sending fused orientation from PIC MCU to Odroid.
  * PIC MCU can send command to Mega board to rotate the robot when the calibration is necessary.

![](https://github.com/piliwilliam0306/robot_pose_ekf-VS-NTHU_odom_fusion/blob/master/fusion.png)
