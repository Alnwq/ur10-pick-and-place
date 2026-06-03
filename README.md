# UR10 Pick and Place Simulation
A URScript program for simulating a pick and place operation using a Universal Robots UR10 cobot

## Overview
This project demonstrates basic robot programming using URScript the native programming language for UR. The robot moves between a home position, a pick location and a place location, simulating an object handling workflow common in industrial automation.

## What it does
1. Moves to home position
2. Moves to pick position (simulating object detection and approach)
3. Pauses to simulate gripper closing
4. Moves to place position
5. Pauses to simulate gripper release
6. Returns to home

## How to run
1. Download URSim from Universal Robots Academy
2. Open URScript editor
3. Load `pick_and_place.urscript`
4. Enable Simulation mode
5. Run the program

## Technologies
- URScript (Universal Robots native language)
- UR10 robot model
- PolyScope 5

## Related
Built after completing Universal Robots Academy UR20/30 e-Learning 
