# Wall-Following Autonomous Robot

An embedded systems project that implements an autonomous robot capable of following walls inside a track, handling 90-degree turns, detecting turn direction, counting turns, and sending the final turn sequence to a PC.

The robot is designed using low-level embedded C with direct register manipulation instead of high-level Arduino APIs.

---

## Project Overview

This project focuses on building a real-time autonomous mobile robot that can navigate a constrained corridor track using ultrasonic sensors and motor control.

The robot follows the wall path, keeps itself centered between the walls using sensor feedback, detects sharp 90-degree turns, classifies each turn as either left or right, stores the turn sequence, and transmits the result to a PC.

Example output:

```text
Turns: 5
Sequence: L, R, R, L, L
