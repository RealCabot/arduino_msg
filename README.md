## Message interface for Arduino

### Why do I need to seperate this from `arduino_node`?

Please refer to ths stupid `rosserial` [bug](https://github.com/ros-drivers/rosserial/issues/239).

### How to build it for Arduino Firmware?
```
rm -r ~/Arduino/libraries/ros_lib
rosrun rosserial_arduino make_libraries.py ~/Arduino/libraries arduino_node