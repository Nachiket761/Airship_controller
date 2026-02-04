## Project Structure

```text
uav_control/
├── config/       # PID gains and vehicle parameters
├── firmware/     # Low-level code for the microcontroller
├── src/          # High-level control logic (C++/Python)
│   ├── control/  # Attitude and Position controllers
│   ├── planning/ # Pathfinding and mission logic
│   └── utils/    # Math libraries and loggers
└── simulation/   # Gazebo/SITL environments

<img width="1920" height="1080" alt="Rate Controller" src="https://github.com/user-attachments/assets/9b9b4e2d-3af3-4c8d-80a0-3a2694ff1269" />
