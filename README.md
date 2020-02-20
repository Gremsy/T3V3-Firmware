# T3V3-Firmware
Firmware for T3V3

# What's new?

## Control gimbal in the follow mode
- Gimbal allows control in follow mode by using remote  control or gSDK

## Control gimbal with LightBridge 2 with DJI's Remote Control.
- In Single mode
  + C1 button switch mode (LOCK -> FOLLOW -> MAPPING)
  + C2 button switch control between TILT and PAN axis.
  + C2 button press hold > 2 seconds. Turn off Gimbal.
- In Dual Mode
  + C1 button switch mode (LOCK  FOLLOW  MAPPING)
  + C2 button press hold > 2 seconds. Turn off Gimbal.
- Refer to: https://www.youtube.com/watch?v=p9fpLAZofRc&t=7s

## Control gimbal with Herelink with Pixhawk Flight Controller.
Use S.Bus signal output from the Herelink for simultaneous control of Autopilot, Gimbal and camera as well.
- In Single mode
  + Scroll wheel controls the TILT or PAN axis (Channel 10)
  + Top button (Right) controls the Gimbal mode including 3 states (Toggle PAN or TILT and Reset Position) (Channel 9)
  + C button controls zoom in for camera (Channel 14)
  + D button controls zoom out for camera (Channel 14)
  + Trigger Camera (Channel 7)

## Go to home position when switching the gimbal mode automatically.

## Control gimbal with gSDK.
- Gremsy SDK to meet the requirements of those building solutions for
various industrial applications.

## Control gimbal with Pixhawk.
- Automated aiming of the camera at a Region of Interset or manual control
through MAVLink message.

## Detect errors when initialization.
- Gimbal will dectect automatically when initialization and pop-up error on the
new gTune with troubleshooting guide.

## Start-up at random position.
