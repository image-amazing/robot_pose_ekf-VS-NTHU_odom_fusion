# robot_pose_ekf VS NTHU_odom_fusion

## ROS robot_pose_ekf (ekf with odom and imu data in Odroid)
  * "feedback_wheel_angularVel" topic contains angular velocity of two wheels.

![](https://github.com/piliwilliam0306/robot_pose_ekf-VS-NTHU_odom_fusion/blob/master/9PlWL8sO3dqDf2gr-51E4B.png)



## NTHU_odom_fusion (publishing orientation from mega board)
  * Sending angular velocity of two wheel to do sensor fusion in PIC MCU.
  * Sending fused orientation from PIC MCU to Odroid.

![](https://github.com/piliwilliam0306/robot_pose_ekf-VS-NTHU_odom_fusion/blob/master/fusion.png)
