# Ball & Beam

![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![LabView](https://img.shields.io/badge/LabView-FFDB00?style=flat-square&logo=labview&logoColor=black)
![PID](https://img.shields.io/badge/Control-PID-00599C?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green)

PID control on Arduino with LabView to stabilize a ball on a beam.

[![Hackster](https://img.shields.io/badge/View_on-Hackster-2E9FE6)](https://www.hackster.io/karem_benchikha/ball-and-beam-601d7a)

## Overview

A ping pong ball rolls on a beam whose pitch is controlled by a servo connected to an Arduino. A distance sensor measures ball position, and a PID controller keeps it stable at the target position.

Developed at INSAT (Spring 2019).

## How It Works

A lever arm connects the servo gear to the beam. As the servo rotates by angle `theta`, the beam angle `alpha` changes, causing gravity to roll the ball. The PID controller adjusts the servo to maintain the desired ball position.

## Bill of Materials

### Mechanical
- Cardboard box (base: 40x20 cm)
- 2x Support (20 cm)
- 2x Beam (34 cm)
- Servo motor horn (5 cm)
- Lever horn (10 cm)
- Ping pong ball

### Electrical
- Arduino (Nano)
- Servo motor
- Sharp IR distance sensor
- Breadboard & jumper cables
