# The way I build rockets

## Design phase

### OpenRocket

To get an initial idea, you can use [OpenRocket](https://openrocket.info/).

This simulator allows you to define parts, dimensions and used materials, and in return it will calculate stability, velocity, forces...

The image below shows one of my first designs, I named it PizzaPower V3.1 (V1 and V2 were almost entirely made out of pizza box cardboard).

<img width="1919" height="1080" alt="image" src="https://github.com/user-attachments/assets/fbfed3fa-f341-4bbb-8c13-934e87352bfc" />

The most important things here are to get an idea of what build you are going for and then choose the right material and make sure it is stable enough.

### Parachute design (optional)

This is where it all started for me, I wanted a way to test my parachutes.

First you would use calculations to decide on the needed drag coefficient and size to get a certain landing speed.

Below, an example is shown, for this design, we would need a chute with a diameter of at least 20 cm. The used tool is the custom HTML script DragCalc_maxq.html

<img width="296" height="721" alt="image" src="https://github.com/user-attachments/assets/c06a94e9-9e76-4587-859f-4db0381441ea" />

Next, you could use a tool like [OpenChute](https://github.com/ElvinC/openchute) to design the parachute.

<img width="1546" height="1156" alt="image" src="https://github.com/user-attachments/assets/a867443d-41e2-4732-bd5a-41a3a12ddef4" />

Want to learn more or need inspiration? Parachute Recovery Systems Design Manual by Theo W. Knacke

### Motor design (optional)

If you ever decide to build your own motors, take all the necessary precautions and safety measures, do not do this without properly informing yourself beforehand.

The only source of knowledge that I trust until now is: [Mr. Nakka website](https://www.nakka-rocketry.net/)

A useful tool for motor design is [OpenMotor](https://github.com/reilleya/openMotor). It allows you to define the propellant, motor dimensions and nozzle. This can give you a primary idea of the thrust curve.

<img width="1301" height="878" alt="image" src="https://github.com/user-attachments/assets/25ed67b2-51c2-45e5-b808-285b8c0701cc" />

Never trust the trust curve alone, especially as a beginner, you will not reach the quality that the simulation assumes. Air bubbles, moisture, etc. can affect the performance of your grain. I strongly advise testing performance on a thrust stand.

### CAD

While not necessary, it can be very useful to confirm dimensions and reiterate on your design, especially for more complex builds.

The SolidWorks models for PizzaPower V3.1 can be found in SolidModels and the corresponding STL files in STLs.

This design was made to be fully 3D printed, PETG was used and proved sufficient to withstand the forces delivered by a Klima D9-5 motor.


## Learned lessons

Don't make your body tube too tight, my first cardboard builds relied on drag for chute deploy, but the packed parachute fit too snug and could not deploy.

Hot glue, cardboard, tape and a 3D printer are very handy for beginner builds.

The PFAFF 1222E is a solid sewing machine.

A simple aluminium launch rod and fitting launch logs with a 1 mm difference max were sufficient for B and D motor flights.

Casting propellant in 1.6 cm tubes can be very frustrating, after about 10 cooked batches I decided to upgrade to 2.5 cm.

Paper nose cones are very simple for beginner builds, just draw a circle, cut until the midpoint and make it pointy.
