
# CS561 Artificial Intelligence - Assignment 1: Navigating E-puck Robots in a Webots Arena

## Project Overview

This project implements a Webots simulation of three E-puck robots navigating an arena with obstacles and light sources. The robots are:

1. Torch Bearer: Moves around the arena, avoiding obstacles while emitting light.
2. Dark Knight: Explores the arena while avoiding both obstacles and light.
3. Follower (Bonus): Follows the Torch Bearer while avoiding obstacles.

## File Structure

'''
CS561_assignment_1/
│
├── ReadMe.md
├── Report.pdf
│
└── assignment1/
    ├── controllers/
    │   ├── my_e_puck_controller_dark_knight/
    │   │   └── my_e_puck_controller_dark_knight.py
    │   ├── my_e_puck_controller_follower/
    │   │   └── my_e_puck_controller_follower.py
    │   └── my_e_puck_controller_avoider/
    │       └── my_e_puck_controller_avoider.py
    ├── plugins/
    │   ├── physics/
    │   ├── remote_controls/
    │   └── robot_windows/
    ├── protos/
    │   ├── icons/
    │   └── construction_Lamp.proto
    ├── worlds/
    │   └── world.wbt
    └── libraries/
'''

## Setup and Running the Simulation

1. Ensure you have Webots installed on your system.
2. Open the Webots software.
3. Load the world file located at `assignment1/worlds/world.wbt`.
4. The simulation should start automatically. If not, use the Webots interface to start the simulation.

## Robot Controllers

### Torch Bearer (Avoider)
- File: `my_e_puck_controller_avoider.py`
- Behavior: Moves around the arena avoiding obstacles using proximity sensors.

### Dark Knight
- File: `my_e_puck_controller_dark_knight.py`
- Behavior: Explores the arena while avoiding both obstacles and light sources.

### Follower (Bonus)
- File: `my_e_puck_controller_follower.py`
- Behavior: Follows the Torch Bearer while avoiding obstacles.

## Key Features

- Obstacle avoidance using proximity sensors
- Light detection and avoidance (Dark Knight)
- Light following (Follower)
- Smooth navigation and turning behaviors

## Additional Notes

- The simulation uses a checkered arena with randomly placed wooden box obstacles.
- The background light is disabled to create a dark environment.
- Robot speeds are set lower than maximum for smoother movement.
- Detailed explanations and observations can be found in the accompanying `Report.pdf`.

## Troubleshooting

If you encounter any issues running the simulation:
1. Ensure all controller files are in their respective folders within the `controllers` directory.
2. Check that the world file (`world.wbt`) is properly configured with the correct robot models and controllers.
3. Verify that all required Webots modules and dependencies are installed.

For any further queries, please contact the CS561 TAs.

Citations:
[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/52192604/cdfeca3a-9808-4d1b-8128-638e8c0e1a41/paste.txt
