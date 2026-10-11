---
layout: page
permalink: /teaching/
title: Teaching
description: Courses we teach, with interactive labs to explore.
nav: true
nav_order: 3
---

Teaching by the Aerial Robotics Group at the University of Bristol.

## Aerial Robotics (AENGM0073)

_University of Bristol · MSc and final-year undergraduate_

The unit teaches fundamental skills in flight dynamics, control and avionics within the context of aerial robotics systems and applications.
Alongside the legal requirements for drone (UAV) operations, students are introduced to software simulation tools for flight planning
and algorithm development, including flight dynamics models, sensor models and control systems.
This is complemented by disruptive technologies such as autonomous navigation and bio-inspiration.
By the end of the unit, students should be able to produce an outline plan for a typical UAV operation in UK airspace,
explain the basis of feedback control for UAVs and its role in flight dynamics and guidance,
apply a typical route planning algorithm in a representative software simulation,
and carry out a design trade-off study for a new aerial robotics platform.

Topics include:

- Introduction to aerial robotics systems and applications
- Legal requirements, risk assessment and ethics of drone operations
- Vision for aerial robots
- Multirotor modelling and control
- Aerial robotics simulators and the PX4 framework
- Drone autonomy, path planning and ground control stations
- Fixed-wing dynamics and control
- Neural-network-based and adaptive control
- Sensors and drone power systems

### Interactive labs

- **[Simulation Lab](/teaching/simulation-lab/)**: a companion to the aerial robotics simulators and PX4 lecture,
  exploring the integrator and physics step size, sensor models against ground truth (GPS, IMU bias and Kalman fusion),
  and the sim-to-real gap with domain randomisation.
- **[Multirotor Control Lab](/teaching/multirotor-lab/)**: a companion to the multirotor modelling and control lecture,
  covering altitude PID control with thrust limits and disturbances, cascaded position and tilt control of a planar drone,
  and how control allocation maps thrust and torque commands to a quadrotor's four motors, including saturation.

Both labs run entirely in the browser with nothing to install, and work best in Chrome, Edge or Firefox on a laptop.
