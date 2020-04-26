# Single Axis Test Jig Design

<img src="https://github.com/MichaelD33/AIO-Quadcopter-Design/blob/master/test%20jig/single%20axis%20test%20jig/Single%20Axis%20Jig%20Assembly.jpg" width="100%" height="100%">

---

This testing jig is designed to allow the quadcopter to move freely along a singular axis of rotation. 
This setup configuration allows for the user to test the quadcopter's behavior and tune the PID controller without the
quadcopter flying away. Addionally, given that the motion is restricted to a singular axis, PID tuning is simplified by only focusing
on the singular axis of rotation (as opposed to the legacy test jig design, which allows for movement on all axes when properly configured).

---

__Dependancies:__

- This jig requires two of each 3D printed component, one set for each arm of the quadcopter. 

- Two bearings are also required for the device to be to rotate freely along the axis of rotation. The test jig is designed to work with [20x37 mm bearings](https://www.mcmaster.com/5972k168).

- Mounting the quadcopter circuit board to the jig requires the 3D printed [AIO frame](https://github.com/MichaelD33/AIO-Quadcopter-Design/blob/master/3D%20printed%20frame/AIO%20Frame%20Refined.stl).

- Finally, of course, the [AIO quadcopter circuit board](https://github.com/MichaelD33/AIO-Quadcopter-Design/tree/master/circuitry/version%200.4.1) is required— this is the main control board for the quadcopter.

---

__Program Changes:__

- This setup utilizes a custom control program to test and tune the quadcopter. This program may be found in the [SingleAxisController](https://github.com/MichaelD33/SingleAxisController/) repository.

Read more about the specific changes on the single axis controller repository.

