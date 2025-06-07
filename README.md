# 3-Bot Priority-Based Decentralized Planner

## Overview

This project, part of the ED5215 course(Jan-May,2023) at IIT Madras, investigates a priority-based decentralized planner for multi-robot systems.

The primary objectives are-

1. **Path Planning:** Develop sequential path planning for multiple robots.
2. **Collision Avoidance:** Ensure each robot considers the paths of previously planned robots to avoid collisions.

## Summary

For a pre-defined map with specified start and goal locations, we sequentially plan the paths for multiple robots. Each robot waits for the previous robot to complete its path planning before initiating its own. This approach ensures that each robot can account for the paths of previously planned robots, effectively avoiding collisions. The methodology was validated using the Pioneer-3 robot in the Coppeliasim simulation software.



