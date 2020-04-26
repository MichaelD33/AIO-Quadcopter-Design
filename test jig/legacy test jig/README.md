# Legacy Test Jig

---

<img src="https://github.com/MichaelD33/AIO-Quadcopter-Design/blob/master/test%20jig/legacy%20test%20jig/Legacy%20Test%20Jig%20Rendering.png" width="100%" height="100%">

### Warning: This is an archived design. No further work will be done with this design. Compatibility with future AIO designs is not ensured.

*These designs are provided as reference. The use of these designs is not recommended to anyone attempting this project on their own.*

### Design update: 

The use of the [Single Axis Test Jig](https://github.com/MichaelD33/AIO-Quadcopter-Design/tree/master/test%20jig/single%20axis%20test%20jig) 
design is highly recommended for new users attempting to follow this project.

---

__Purpose:__

The creation of this test jig is described in an article I published on the [Ultimaker website](https://ultimaker.com/learn/how-the-tools-we-use-influence-the-designs-we-make)— 
see: "__Tools in testing__".


The quadcopter uses information from the sensors to calculate how fast to spin the motors in order to move to 
a certain location. This process is handled by an algorithm known as a PID controller. Before the quadcopter can fly, this controller needs to be configured through laborious testing, and figuring out where 
to start can be fairly daunting. Furthermore, the guess-and-check method usually causes the quadcopter to go crashing into the 
wall. This caused me to wonder, how might I control and analyze the movement of the quadcopter without it flying away and 
crashing into the wall?

Introducing, the testing jig. This contraption allows the user to test the quadcopter without worrying that the device will break
from colliding with the wall. 

[See an example of this test jig in action](http://delaney.nyc/wp-content/uploads/2020/04/PIDTestJig3.gif)


