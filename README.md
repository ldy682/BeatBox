# Beatbox
 
This is an application that uses the Beaglebone Green along with a Red Zen Cape attached on top of it. The host (the vm) and the target (Beaglebone) uses debian 11.8

## Function 

- Continuously play a beat which is outputted from the hardware's headphone jack.
- Joystick controls
  - up/down to increase and decrease volume
  - left/right to increase and decrease tempo
  - press in to change the beat, no-beat -> beat1 -> beat2 -> no-beat -> ...
-These settings can alse be changed on the webpage using this command on the server directory:
    ``` $node server.js```
- Additionally, moving the hardware left/right, up/down and forward/backward, produces different sounds using the accelerometer.

## Required Libraries

