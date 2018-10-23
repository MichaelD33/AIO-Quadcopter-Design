

# AIO Quadcopter Circuit Board Design File Directory:

### non-functional prototypes
	- Original PCB iterations for testing and design prototyping
	- Used for early code devlopment

### Version 0.3
	- First working revision of the PCB - removes the 5v buck/boost converter to decrease the overall weight of the quadcopter but due to the component placement the center of gravity has been significantly offset causing issues with balance.

### Version 0.4
	- Fixed center of gravity
	- 5V regulator (decreased efficiency due to the 3.3V regulator being powered by the 5V reg.)
	
### Version 0.4.1
	- Added flyback diode and reverse polarity protection mosfet.
	- 5V regulator and output pads (3.3V regulator still powered via 5V line)
