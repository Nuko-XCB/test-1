[Sweep-Robot](https://github.com/quboyue/Sweep-Robot-Team36)



<img width="350" height="350" src="https://github.com/GANTIAN-hub405/picutre/blob/main/sweep-robot.jpg"/></div>

 

# About the project

The sweep-robot is a simple, small Robot.It scans a memory map to carry out sweeping movements in accessible areas.



## Software

- Opencv 4.5.1
- Python GPIO
- result

## Hardware 
- Raspberry Pi 4 Model B
- Radar
- 3D drift
- 
### Schematics:

## Roadmap


# Getting Started



# algorithm 
 - ICP
 - MCL
   It is an algorithm that calculates the position of a robot in a known map. The principle of this algorithm is to simulate a group of particles that have the same movement as    the robot. Each particle is given a certain probability by comparing the      sensor data of robot with the simulated sensor data of the particles. After several iterations,    the particles will converge to a position, which is the exact position of the    robot in the map.

 - Floodfill
 - DFS 
 - DWA
   This is an algorithm that plans out specific action strategies for the robot in a part of map after obtaining the information of destination.
   The principle is to sample several groups of velocities and simulate the motion trajectory of the robot in a certain time at these velocities. Then an evaluation function is    used to score these trajectories to exclude collision trajectories and select the speed corresponding to the optimal trajectory to drive the robot.


# Contributing
# License
# Contact
