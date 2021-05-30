---
title: alpha base
layout: page
permalink: /base/alpha/
---
# Settings
## Mechanical Settings
### TotalForce [-100~100]
```
Total power of the motor.
For some reason it's possible to go negative, which will invert FFB
```
### WheelSpeed [0~100]
```
The maximal speed of the wheelbase in percent.
If the speed requested from the game is above the percentage value, it will be cut.
Otherwise, no change will happen
```
### WheelDamper [0~100]
```
This setting dampens the wheel rotation.
This can be a usefull tool to stop oscilation.
```
### FilterFrequency [0~100]
```
This Adjust how much of the FFB the game sends is cut off / trimed
0 = Set for Automatic Filtering
1-100 = Sets Manual Filtering
1 = 100% Filter (ON)
100 = 0% Filter (OFF)
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
### Suspension [Soft, Normal, Hard]
```
```
### Response [Stable, Wild]
```
The stable mode is closer to the original output of the game.
In the wild mode, the affected output details will be increased.
```

## Game Force
### ConstantForce [0~200] 
```
Linear scaling of the signals coming from game.
Rule of thumb is, leave at 100
```
### PeriodForce [0~200]
```
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