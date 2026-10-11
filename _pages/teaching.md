---
layout: default
permalink: /teaching/
title: Teaching
description: Aerial Robotics (AENGM0073) at the University of Bristol, with interactive labs that run in the browser.
nav: true
nav_order: 3
---

# Aerial Robotics (AENGM0073)

_[University of Bristol](https://www.bris.ac.uk/unit-programme-catalogue/UnitDetails.jsa?ayrCode=27%2F28&unitCode=AENGM0073)_

Aerial Robotics is a team-taught unit on the fundamentals of flight dynamics, control and avionics
in the context of aerial robotics systems and applications.
Alongside the legal requirements for drone (UAV) operations, students use software simulation tools for flight planning and algorithm development,
including flight dynamics, sensor and control models, and are introduced to state-of-the-art approaches in autonomous navigation and bio-inspiration.
By the end of the unit, students can plan a typical UAV operation in selected airspaces, explain feedback control for UAVs and its role in flight dynamics
and guidance, apply a route-planning algorithm in simulation, and carry out a design trade-off study for a new aerial robotics platform.

Topics across the unit include:

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

- **[Simulation Lab](/teaching/simulation-lab/){:target="_blank" rel="noopener"}**: a companion to the aerial robotics simulators and PX4 lecture,
  exploring the integrator and physics step size, sensor models against ground truth (GPS, IMU bias and Kalman fusion),
  and the sim-to-real gap with domain randomisation.
- **[Multirotor Control Lab](/teaching/multirotor-lab/){:target="_blank" rel="noopener"}**: a companion to the multirotor modelling and control lecture,
  covering altitude PID control with thrust limits and disturbances, cascaded position and tilt control of a planar drone,
  and how control allocation maps thrust and torque commands to a quadrotor's four motors, including saturation.

Both labs run entirely in the browser with nothing to install, and work best in Chrome, Edge or Firefox on a laptop.
