
# 🤖 ROS 2 Learning Hub & Resources

> A structured, step-by-step roadmap and curated resource guide for students and beginners learning ROS 2 (Robot Operating System 2) from foundations to hands-on implementation.

---

## 📌 Overview

This repository serves as a practical learning guide for ROS 2. It organizes theoretical concepts, recommended books, courses, video tutorials, and working code examples into a progressive roadmap.

Whether you are starting from zero or transitioning from ROS 1, this repository will guide you through building robust robotic applications using **Python** and **C++**.

---

## 🗺️ Learning Roadmap
1_foundations:
  linux: ["IPC", "systemd", "POSIX threads", "Bash scripting"]
  cpp: ["C++17/20", "Smart Pointers", "RAII", "Multithreading", "CMake"]
  python: ["OOP", "asyncio", "NumPy", "PyTest"]
  git: ["Feature Branching", "Rebase", "Submodules", "GitHub Actions"]

2_middleware_containerization:
  ros2: ["Nodes", "Topics", "Services", "Actions", "Lifecycle Nodes", "colcon"]
  docker: ["Multi-stage builds", "Docker Compose", "X11/Wayland Forwarding", "nvidia-docker"]

3_simulation:
  gazebo: ["URDF/Xacro", "SDF", "Sensor Plugins", "Physics Engines"]
  isaac_sim: ["NVIDIA Omniverse", "USD Assets", "Synthetic Data Generation (SDG)", "Isaac ROS"]

4_perception_slam:
  computer_vision: ["OpenCV (C++)", "Camera Calibration", "Feature Detection", "Point Cloud Library (PCL)"]
  slam: ["Cartographer", "ORB-SLAM3", "Nav2 SLAM Toolbox", "Occupancy Grid Mapping"]

5_control_motion_planning:
  control: ["ros2_control", "Closed-loop PID", "State-Space Models", "Kinematics/Dynamics"]
  motion_planning: ["Nav2 (Costmaps, Planners, Controllers)", "MoveIt 2", "Sampling-based algorithms (RRT*, PRM)"]

6_embedded_edge_ai:
  jetson: ["JetPack SDK", "TensorRT Optimization", "DeepStream Pipeline"]
  hardware_interfaces: ["GPIO", "UART", "I2C", "SPI", "CAN Bus Protocol"]