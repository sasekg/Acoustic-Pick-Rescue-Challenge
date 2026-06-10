# Acoustic Guitar Pick Extraction Challenge

## Overview

The Acoustic Guitar Pick Extraction Challenge is a robotics competition focused on a deceptively simple real-world problem:

> Remove a guitar pick that has been accidentally dropped inside an acoustic guitar as quickly as possible without damaging the instrument.

While a human can often solve the problem by manually shaking and rotating the guitar, the challenge becomes significantly more interesting when strict constraints are imposed on force, vibration, and instrument safety.

The goal is to encourage research in:

- Robotics
- Motion planning
- Reinforcement learning
- Acoustic sensing
- Computer vision
- Fragile object manipulation
- Human-safe automation

---

# Motivation

Many robotics competitions focus on sorting blocks, navigating mazes, or manipulating standardized objects.

This challenge instead focuses on:

- A recognizable real-world problem
- Hidden-state environments
- Delicate object handling
- Sensor-guided manipulation

A successful solution could have applications beyond musical instruments, including:

- Foreign object recovery from machinery
- Aerospace maintenance
- Medical device inspection
- Artifact conservation
- Manufacturing quality control

---

# Problem Statement

A standard guitar pick has been dropped into the body of an acoustic guitar.

The robot must:

1. Detect or infer the location of the pick.
2. Manipulate the guitar using only approved methods.
3. Guide the pick to the sound hole.
4. Extract the pick completely from the instrument.

The guitar must remain undamaged throughout the process.

---

# Competition Format

## Equipment

Competition organizers provide:

- Identical acoustic guitars
- Identical guitar picks
- Standardized starting fixtures

Robots are supplied by competitors.

---

## Test Procedure

1. A pick is dropped into a guitar.
2. The pick location is randomized.
3. The robot begins from a neutral starting position.
4. Timing starts when the robot is activated.
5. Timing stops when the pick exits the guitar body.

---

# Multi-Guitar Challenge

Each team must extract picks from:

- 10 guitars
- Randomized pick locations
- Randomized orientations

Final score is based on total completion time.

---

# Safety Requirements

The guitar is considered a fragile object.

Robots must not:

- Damage the finish
- Damage strings
- Damage tuning machines
- Damage the bridge
- Damage internal bracing
- Damage the neck

The challenge is intentionally designed so that a simple high-energy shaking solution is not acceptable.

---

# Example Constraints

## Maximum Acceleration

A maximum acceleration threshold may be imposed.

## Maximum Angular Velocity

Rotation speeds may be limited.

## Maximum Vibration

Robots may be required to remain below specified vibration levels.

## Neck Torque Limits

Fixtures must prevent excessive loads on the neck.

---

# Scoring

## Base Score

Total elapsed time across all guitars.

## Penalties

### Minor Penalties

- Excessive vibration
- Excessive force
- Temporary tuning deviation

### Major Penalties

- Cosmetic damage
- Finish scratches
- Denting

### Disqualification

- Structural damage
- Neck damage
- Bridge damage
- Cracks
- Broken strings

---

# Technical Approaches

Possible solutions include:

## Controlled Motion Systems

- Multi-axis gimbals
- Gentle orientation changes
- Motion planning algorithms

## Acoustic Localization

- Microphones
- Contact sensors
- Vibration analysis

## Vision Systems

- Cameras through the sound hole
- Endoscopic inspection
- Internal mapping

## Machine Learning

- Reinforcement learning
- Motion optimization
- Pick trajectory prediction

## Hybrid Systems

Combining sensing and motion planning to minimize energy while maximizing extraction speed.

---

# Research Questions

This challenge raises several interesting research problems:

### Hidden Object Localization

Can a robot determine the location of an unseen object using sound and vibration alone?

### Minimal-Energy Manipulation

What is the minimum motion required to move a trapped object through a constrained cavity?

### Safe Manipulation

How can a robot maximize task performance while maintaining strict force and vibration limits?

### Learning-Based Recovery

Can reinforcement learning discover extraction strategies superior to human intuition?

---

# Future Variations

## Different Objects

- Picks
- Screws
- Washers
- Allen keys

## Different Instruments

- Acoustic guitars
- Classical guitars
- Ukuleles
- Mandolins

## Obstacle Variants

- Internal bracing layouts
- Different body shapes
- Different sound hole sizes

---

# Example Competition Names

- Acoustic Guitar Pick Extraction Challenge
- Pick Rescue Robotics Challenge
- Guitar Retrieval Grand Prix
- Hidden Object Recovery Challenge
- Gentle Manipulation Robotics Competition

---

# Mission Statement

The Acoustic Guitar Pick Extraction Challenge promotes robotics research focused on intelligence rather than brute force.

The winning robot should not be the one that shakes the hardest.

The winning robot should be the one that understands the instrument, understands the object, and retrieves it safely using the least amount of energy possible.