# AIO Quadcopter Legacy PCB Design Directory:

---

### Warning: This is a directory for archived designs. No further work will be done with these designs. Functionality or compatibility with future AIO designs is not ensured.

*These designs are provided as reference. The use of these designs is not recommended to anyone attempting this project.*

The use of the [AIO Quadcopter version 0.4.1](https://github.com/MichaelD33/AIO-Quadcopter-Design/tree/master/circuitry/version%200.4.1) 
circuit board design is highly recommended for new users attempting to follow this project.

---

## Directory Overview

### non-functional prototypes
	- Original PCB designs.
	- Used for early code development and hardware testing

### Version 0.3
	- First working revision of the PCB - This design removed the 5v buck/boost converter to decrease the overall weight; however, this resulted in the center of gravity being significantly offset from the center of the PCB. This results in a number of issues with the device's balance.

### Version 0.4
	- Fixed center of gravity
	- Replaced the 5V regulator (decreased efficiency due to the 3.3V regulator being powered by the 5V reg.)
	
### Version 0.4.1 (see link above)
	- Added flyback diode and reverse polarity protection mosfet.
	- 5V regulator and output pads (3.3V regulator still powered via 5V line)
