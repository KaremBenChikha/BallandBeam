# BallandBeam
PID control on Arduino with LabView to stabilize a ball on a beam.

Introduction

The BallandBeam project was developed at the National Institue in Applied Science and Technology (INSAT) on Spring 2019.

Visit my personal portfolio: https://karembenchikha.me 

Check the Project on Hackster: https://www.hackster.io/karem_benchikha/ball-and-beam-601d7a


This was a school project. The assignment was to construct a ball and beam control system.


A ping pong ball sits on top of the beam rolling forward and backward according to the pitch of the beam. The pitch is controlled by a servo that is connected to an Arduino. The position of the ball is measured by a distance sensor mounted at the end of the beam.


A PID controller is used to control the position of the ball on the beam.


Physical Setup

A ball is placed on a beam, see figure below, where it is allowed to roll with 1 degree of freedom along the length of the beam. A lever arm is attached to the beam at one end and a servo gear at the other. As the servo gear turns by an angle theta, the lever changes the angle of the beam by alpha.

When the angle is changed from the horizontal position, gravity causes the ball to roll along the beam. A controller will be designed for this system so that the ball's position can be manipulated.

Mechanical Part

A simple card box can do the job.
Base support  (40 cm x 20 cm)
2 x Support (20 cm)
2 x Beam (34 cm)
Servo motor horn (5 cm)
Lever horn (10 cm)
Ping pong ball



Electrical Part

You will need:
Arduino (Nano)
Servo motor
Sharp sensor
Cables and jumper
Breadboard
