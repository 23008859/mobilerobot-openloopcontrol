# MobileRobot-Openloopcontrol
## Aim:

To develop a python control code to move the mobilerobot along the predefined path.

## Equipments Required:
1. RoboMaster EP core
2. Python 3.7

## Procedure

Step1:
<br/>
Use from robomaster import robot

Step2:
<br/>
Choose the x,y,z-axis movement distance(metres).

Step3:
<br/>
Give ep_chassis.move to move straight

'Step4:
<br/>
Give time.sleep() for a break.

'Step5:
<br/>
Give ep_chassis.drive_speed to have a circular movement.
## Program
```python
from robomaster import robot
import time

if __name__ == '__main__':
    ep_robot = robot.Robot()
    ep_robot.initialize(conn_type="ap")

    ep_chassis = ep_robot.chassis
ep_robot robot. Robot()

ep_robot.initialize(conn_type="ap")

ep_chassis ep_robot.chassis

ep_led ep_robot.led

ep_camera ep_robot.camera

print("Video streaming started.....")

ep_camera.start_video_stream(display=True, resolution camera.STREAM_360P)

ep_chassis.move(x=2.5, y=0, z=0, xy_speed=1.5).wait_for_completed() ep_led.set_led(comp = "all", r=255,g=0, b=0, effect="on")

ep_chassis.move(x=0.4, y=0, z=80, xy_speed=1.5).wait_for_completed() ep_led.set_led(comp = "all", r=0,g=255, b=255, effect="on")

ep_chassis.move(x=1, y=0, z=0, xy speed-1.5).wait_for_completed() ep_led.set_led(comp = "all", r=255,g=204, b=0, effect="on")

ep_chassis.move(x=0, y=-1.5, z=0, xy_speed=1.5).wait_for_completed() ep_led.set_led(comp = "all", r=255,g=255, b=0, effect="on")

ep_chassis.move(x=0, y=0, z=60, xy_speed=1.5).wait_for_completed(). ep_led.set_led(comp = "all", r=255,g=0, b=255, effect="on")

ep_chassis.move(x=1.5, y=0, z=0, xy_speed=1.5).wait_for_completed() ep_led.set_led(comp = "all", r=204,g=255,b=255, effect="on")

ep_chassis.move(x=0, y=0, z=43, xy_speed=1.5).wait_for_completed() ep_led.set_led(comp = "all",r=255,g=128, b=128, effect="on")

ep_chassis.move(x=1.4, y=0, z=0, xy_speed=1.5).wait_for_completed() ep_led.set_led(comp "all", r=255,g=128, b=128, effect="on")

ep_chassis.move(x=0, y=0, z=-85, xy_speed=1.5).wait_for_completed() ep_led.set_led(comp = "all", r=255,g=0, b=255, effect="on")

ep_chassis.move(x=-2, y=0, z=0, xy_speed=1.3).wait_for_completed() ep_led.set_led(comp = "all", r=0,g=255, b=255, effect="on")

ep_chassis.move(x=0, y=0, z=-98, xy_speed=1.5).wait_for_completed() ep_led.set_led(comp = "all",r=153,g=51, b=0, effect="on")

ep_chassis.move(x=0.6, y=0, z=0, xy_speed=1.3).wait_for_completed() ep_led.set_led(comp = "all", r=153,g=51, b=153, effect="on")

ep_chassis.move(x=0, y=0, z=0, xy_speed=1.3).wait_for_completed() ep_led.set_led(comp = "all",r=51,g=102,b=255, effect="on")



    
    ep_robot.close()
```

## MobileRobot Movement Image:

![robo](./img/robomaster.png)

Insert image here

![Screenshot 2023-12-31 130717](https://github.com/23008859/mobilerobot-openloopcontrol/assets/139117979/b707a05b-b27d-4bca-8cc9-93fbfd0ec59c)

<br/>
<br/>
<br/>
<br/>

## MobileRobot Movement Video:
https://youtu.be/n_C7r0ElftM
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](https://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)

<br/>
<br/>
<br/>
<br/>

## Result:
Thus the python program code is developed to move the mobilerobot in the predefined path.


<br/>
<br/>

```
Mobile Robotics Laboratory
Department of Artificial Intelligence and Data Science/ Machine Learning
Saveetha Engineering College
```
