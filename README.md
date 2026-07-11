# Robot Dog Design

## Overview

The initial mechanical design of a simple quadruped robot dog created in Tinkercad. The design focuses on the basic mechanical principles needed for a robot to stand, balance, and perform simple walking movements.

---

# 1. Body and Frame

The robot has a rectangular body that serves as the main chassis. It provides space for electronic components such as the battery, controller, and wiring while keeping the structure lightweight and stable.

---

# 2. Leg Design

The robot has four identical legs, each made of an upper leg, lower leg, and rounded foot. The legs are evenly positioned to provide good balance and support.

---

# 3. Joints and Degrees of Freedom

Each leg has two joints:

- Hip joint
- Knee joint

This gives the robot 8 Degrees of Freedom (2 per leg), allowing basic walking movements.

---

# 4. Sensor Placement

Two ultrasonic sensors are mounted at the front of the robot as its "eyes." They are used to detect obstacles and measure distance.

---

# 5. Motor Selection

Servo motors are used for all joints because they are accurate, easy to control, and provide enough torque for a small robot.

**Recommended Motor:** MG996R Servo Motor

---

# 6. Preliminary Torque Calculation

Assumptions:

- Robot mass = 2 kg
- Load per leg = 0.5 kg
- Leg length = 0.10 m

Force:

F = 0.5 × 9.81 = 4.905 N

Torque:

T = 4.905 × 0.10 = **0.49 N·m**

A servo with at least **0.5 N·m** torque is recommended.

---

# 7. Stability and Center of Gravity

The center of gravity should remain near the middle of the body. Heavy components should be placed inside the chassis to improve balance during movement.

---

# 8. Proposed Walking Method

A **crawl gait** is recommended, where one leg moves at a time while the other three remain on the ground. This provides good stability.

---

# 9. Expected Mechanical Challenges

Possible challenges include:

- Limited motor torque
- Joint wear
- Balance on uneven ground
- Battery weight
- Foot slippage
