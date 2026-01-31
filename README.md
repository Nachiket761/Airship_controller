## Project Structure

uav_control/
├── config/       # PID gains and vehicle parameters
├── firmware/     # Low-level code for the microcontroller
├── src/          # High-level control logic (C++/Python)
│   ├── control/  # Attitude and Position controllers
│   ├── planning/ # Pathfinding and mission logic
│   └── utils/    # Math libraries and loggers
└── simulation/   # Gazebo/SITL environments