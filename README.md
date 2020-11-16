crazyflie_ros (modified)
=============

The original code and documentation can be found here: https://github.com/whoenig/crazyflie_ros (ACTLab at USC).

Some files in crazyflie_cpp were edited to support the GTC setpoint. Also, msg types are added to support integration into a reinforcement learning framework. 

## GTC message

```
Header header
uint16 mode
geometry_msgs/Vector3 cmd
```


## State message

```
std_msgs/Header header 
std_msgs/Float32MultiArray state