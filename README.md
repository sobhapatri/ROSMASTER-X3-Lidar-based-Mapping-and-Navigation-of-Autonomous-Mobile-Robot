# ROSMASTER-X3-Lidar-based-Mapping-and-Navigation-of-Autonomous-Mobile-Robot

## 📌 Overview
This project demonstrates the deployment of an autonomous mobile robot system capable of performing real-time SLAM, indoor navigation, obstacle avoidance, and 3D environment reconstruction. Built using the ROSMASTER-X3 platform and ROS (Robot Operating System), the system wasn deployed and tested within dynamic indoor environments and designed to meet critical needs in warehouse and automation environments.

---

## 🛠️ Problem Being Solved
Many mobile robots lack well-tested and integrated indoor navigation stacks, which limits their safe deployment in environments like warehouses, labs, and testbeds. Without accurate mapping and robust obstacle avoidance, such robots face difficulties navigating in GPS-denied or cluttered spaces.

---

## ✅ Solution Overview
We deployed a complete LIDAR and vision-based autonomous navigation stack using ROS on a mobile robot. The system is capable of generating both 2D and 3D maps, dynamically planning routes, and avoiding static and dynamic obstacles using sensor fusion and costmaps. The robot was tested for single-point and multi-point navigation along with obstacle avoidance within a closed environment.

---

## 🧠 Technical Approach
- **SLAM**: Used GMapping for 2D LIDAR-based mapping and RTAB-Map with stereo camera for 3D RGB-D mapping.
- **Navigation**: ROS Navigation Stack (Nav2 for ROS2) enabled real-time path planning to dynamic waypoints.
- **Sensor Fusion**: Integrated LIDAR, IMU, and wheel encoders for accurate localization and mapping.
- **Visualization**: Monitored robot state, SLAM map, and goals via RViz2 and Gazebo.
- **Hardware Platform**: 
  - ROSMASTER-X3 robot
  - Jetson Orin Nano
  - 2D LIDAR sensor
  - Depth camera
  - Ubuntu 20.04, ROS2

---

## 📊 Key Results
- 📍 Successfully mapped a multi-room indoor space using GMapping and RTAB.
- 🚗 Demonstrated reliable single-point and multi-point autonomous navigation.
- 🔁 Real-time replanning and obstacle avoidance with dynamic costmap updates.
- 🧩 Integrated hardware, SLAM, sensor fusion, path planning, and feedback visualization in a unified system.

---


