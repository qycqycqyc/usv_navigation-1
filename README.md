# usv_navigation

This branch currently provides manual control with gui (gui:=true) or joystick (usv_teleop) and automatic heading control.

usv_teleop provides direct control of sail and rudder joint angles.

On the branch usv_navigation of usv_sim_lsa:

```
        roslaunch usv_sim sailboat_scenario0.launch parse:=true
        roslaunch usv_sim sailboat_scenario0.launch parse:=false
        roslaunch usv_teleop sony_dualshock3.launch
```