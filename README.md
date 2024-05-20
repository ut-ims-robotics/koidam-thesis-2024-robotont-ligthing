# Development of light solution software for the educational robot Robotont

This repository contains files created for my bachelor's thesis.
* `robotont-firmware` contains the code I added to control the adressable LEDs for Robotont STM32 microcontroller. The code is in `src/svc/led.c` and `src/svc/led.h`. The added library is in `src/hw/ARGB.c` and `src/hw/ARGB.h`
* `robotont_driver` contains the code I added to the Robodont ROS2 driver. The code is in `src/plugin_led_module.cpp` and `include/robotont_driver/plugin_led_module.hpp`.
* `robotont_msgs` contains the code I added and modified in the Robodont messages ROS2 package. The code is in `msg/LedModuleSegment.msg` and `msg/LedModuleMode.msg`.
* `demo_lighting` contains the demonstration ROS2 package I made for my thesis.
