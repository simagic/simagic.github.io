---
title: alpha base
layout: page
permalink: /base/alpha/
parent: Simagic Wheelbase
---
# Settings
<img src="/assets/images/alpha_manager_setting.jpg" alt="Alpha Manager"/>


<a href="/assets/pdf/Alpha_Base_Manual.pdf" target="_blank">Official alpha Base Manual<a/>

## Mechanical Settings
### TotalForce [-100~100]
```
Total power of the force feedback.
Negative values invert the FFB which is important for games like rFactor 2
```

### WheelInertia [0~100]
```
The weight of the wheel.
Higher means heavier wheel and equals more stability.
But it may also diminish the road and vehicle information.
0 equals original weight of steering wheel
```

### WheelDamper [0~100]
```
This setting dampens the wheel rotation.
This can be a usefull tool to stop oscilation.
```

### SmoothLevel [0~10]
```
This Adjust how much of the FFB the game sends is cut off / trimed
Higher value means smoother feel but also might lose some details
0 equals to no filtering at all

1-9 = Sets Manual Filtering
10 = 100% Filter (ON)
0 = 0% Filter (OFF)
```
### WheelSpring [0~100]
```
This setting is used to center the wheel.
The bigger the number, the harder the centering force.
Can easily be set to very low numbers, because usually the game takes care of this.
A real car centers the wheel only when driving and because of the force on the wheels.
```
### WheelFriction [0~100]
```
This setting adds some friction to the turning action of the wheel.
The more friction the harder to turn the wheel.
Can usually be very low, since this is normaly taken care of from the game FFB
```

## Game Effect
### GameSpring [0~200]
```
```
### GameInertia [0~200]
```
```
### GameDamper [0~200]
```
```
### GameFriction [0~200]
```
```

## Vehicle Setting
### WheelSpeed [0~100]
```
The maximal speed of the wheelbase in percent.
If the speed requested from the game is above the percentage value, it will be cut.
Otherwise, no change will happen
```
### Suspension [0~9]
```
Lower values can provide cleaner / smoother output.
Higher values are closer to the original FFB provided by the game but may introduce unwanted noise.
```

## Buttons
### ReadBase
```
Read configuration from permanent memory on base
```  
### WriteStorage
```
Write configuration to permanent memory on base
```  
### SaveAs
```
Save the configuration for future as a file
```  
### Dropdown
```
Load saved configuration file
```  


# System State

<img src="/assets/images/alpha_manager_system_state.jpg" alt="Alpha Manager System States"/>

### Normal
Everything is good to go, let's race
### ROMErr (ROM Error)
Firmware error.
Try flashing a new (or old) Firmware.
[alpha Firmware](/base/alpha_firmware/)
### LosingPhase
### OverCur (Over Current)
If this occurs with together with over voltage and out of angle you'll need to physically reset the base.
### OverVol (Over Voltage)
See over current
### OverSpeed
### TestCur
### OutOfAng (Out of Angle / Angle over Limit)
See over current
### AssErr