# dji_ecust

## motivation

modified version of dji_sdk_demo, the demo_flight_control demo

the demo is based on gps data for controlling, but i want to modified it to gps-denied environment.

## dependency

dji Onboard-sdk-3.4 and Onboard-sdk_ros

you can see as reference.

## usage

use this sample we need some hardware and software configuration. 
first is hardware. we need two computer, the firsts run ros and the second runs the dji simulator, a remote control is required for you will see the `sdk.launch` is ok however the `rosrun dji_ecust dji_demo` may encounter some error such as `obtain control failed!` etc.





