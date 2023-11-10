# ros2_spot_arm_status

This small ROS 2 package listens to the `joint_states` topic (type [`sensor_msgs/msg/JointState`](https://github.com/ros2/common_interfaces/blob/rolling/sensor_msgs/msg/JointState.msg)) and publishes two status topics `arm_stowed` and `gripper_open` of type [`std_msgs/msg/Bool`](https://github.com/ros2/common_interfaces/blob/rolling/std_msgs/msg/Bool.msg).