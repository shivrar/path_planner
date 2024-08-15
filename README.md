# Path & Trajectory planner.
Given desired waypoints generate a path & trajectory from the current position to the desired endpoint through the various waypoints.

This module can be split into 2 modules: A path planner and a trajectory planner.

## Path Planner
Path planning is the process of determining a feasible route or sequence of movements for an agent (e.g., a robot, autonomous vehicle) to travel from a starting point to a destination while avoiding obstacles. The primary focus is on finding a geometric path in the environment that the agent should follow. This process typically doesn't consider the timing or dynamics of the movement. Path planning answers the question: "What path should the agent take?"

## Trajecotry Planner
Trajectory planning, on the other hand, involves determining the time-dependent path that the agent will follow, taking into account its dynamics and kinematics (e.g., velocity, acceleration, and physical constraints). It not only decides the spatial path but also specifies how the agent will move along this path over time. Trajectory planning answers the question: "How should the agent move along the path?"
