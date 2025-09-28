# 🛠️ URDF for Mars Rover Components

This repository contains URDF (Unified Robot Description Format) files generated from SolidWorks assemblies of major subsystems in our Mars Rover project. These files are essential for simulating and visualizing the robot in ROS-based environments like RViz and Gazebo.

## 🤖 What is URDF?

URDF is an XML-based format used to describe the physical structure, joints, and visual geometry of a robot. It allows roboticists to simulate motion, test control algorithms, and visualize kinematics without needing the physical hardware.

## 🔄 How These Files Were Created

Each URDF file in this repo was exported using the official SolidWorks URDF Exporter plugin. The process involved:
- Assembling and mating CAD components in SolidWorks
- Defining joint types and coordinate systems
- Exporting the structure into URDF format with linked STL meshes

## 📁 What's Inside

- `/meshes`: STL files for each robot part
- `robot.urdf`: The main robot description file
- Optional launch/config files for ROS integration

## 🚀 Use Cases

- Simulate Mars Rover subsystems in Gazebo
- Visualize joint motion in RViz
- Integrate with ROS control packages
- Test kinematics and collision models

---

Feel free to fork, clone, or contribute if you're working on robotic simulation or CAD-to-ROS workflows.
