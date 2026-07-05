---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Software Engineering, Chongqing University, Sep. 2023 - Jun. 2026
  * GPA: 4.11, ranked 4th
* B.E. in Computer Science and Technology, Guangdong University of Technology, Sep. 2019 - Jun. 2023
  * GPA: 3.72, ranked 3rd
  * Recommended for graduate admission without entrance examination

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Research Experience
======
* LIO-DPC: Accurate and Fast LiDAR-Inertial Odometry with Dynamic Pose Chain
  * Proposed a LiDAR-inertial odometry system that integrates filtering and graph optimization through a dynamic pose chain.
  * Supported real-time incremental updates and batch updates for fast and accurate pose estimation.
  * Introduced a loop-quality metric to retain high-quality loop closures and reduce graph optimization cost.
  * Achieved state-of-the-art accuracy while maintaining real-time performance on real-world datasets.

* LIO-HKDT: Fast and Accurate LiDAR-Inertial Odometry With Hash K-D Tree
  * Proposed hkd-Tree, a hybrid data structure combining voxel-based localized search with efficient k-d tree nearest-neighbor search.
  * Designed a voxel distribution mechanism and buffered update strategy for efficient KNN search and incremental point-cloud insertion.
  * Built the LIO-HKDT system, which maintains competitive accuracy while improving runtime efficiency in LiDAR-inertial odometry.

Project Experience
======
* National Key Project: Cooperative Perception for Unmanned Vehicle Swarms, Jan. 2024 - Jul. 2025
  * Developed hardware drivers and simulation plugins for chassis, IMU, and LiDAR.
  * Unified real and simulated interfaces so algorithms validated in simulation could be deployed on vehicles.
  * Designed a cooperative pose estimation algorithm integrating pose estimation, distributed loop closure, pose graph optimization, and dynamic pose chain management.
  * Developed a distributed loop closure module using STD point-cloud descriptors for intra-robot and inter-robot loop closure detection.

* Project Huiyan: Autonomous Perception and Navigation for Unmanned Vehicles, Oct. 2023 - Sep. 2024
  * Built URDF models and Gazebo simulation environments from vehicle parameters.
  * Developed chassis, LiDAR, and IMU drivers and simulation plugins based on ROS-control.
  * Deployed and debugged localization, mapping, and navigation algorithms on unmanned vehicles in offices, industrial parks, and warehouses.

Competition Experience
======
* 20th China Postgraduate Mathematical Contest in Modeling, National Third Prize, 2023
* 22nd National College Students Robocon Competition, National First Prize, 2022 - 2023
  * Responsible for mapping and navigation of a self-developed omnidirectional chassis.
  * Developed motor PID control, motion control, simulation models, sensor drivers, communication, SLAM, and path planning using ROS-control.
* 21st National College Students RoboMaster Competition, National Third Prize, 2021 - 2022
  * Debugged mecanum, omni, and steering-wheel chassis, launcher mechanisms, and gimbal mechanisms.
  * Developed GPIO drivers, ROS-control controllers, CAN communication protocols, and Gazebo simulation models.
* 21st National College Students Robocon Competition, National First Prize, 2021 - 2022
  * Managed team operations, technical training, task planning, documentation, and collaborative development standards.
* 13th Lanqiao Cup National Software Competition, Provincial Second Prize, 2020 - 2021
* 20th China Robotics and AI Competition, Provincial Third Prize, 2020 - 2021
* 10th National College Student Mechanical Design Competition, Provincial Second Prize, 2020 - 2021
* 15th China Collegiate Computing Design Competition, Provincial Second Prize, 2020 - 2021
* 20th National College Students Robocon Competition, National Third Prize, 2020 - 2021

Honors & Awards
======
* First-Class Graduate Scholarship, Chongqing University, 2024 - 2025
* First-Class Graduate Scholarship, Chongqing University, 2023 - 2024
* Outstanding Graduate, Guangdong University of Technology, 2022 - 2023
* Outstanding Undergraduate Thesis, Guangdong University of Technology, 2022 - 2023
* First-Class Excellent Student Scholarship, Guangdong University of Technology, 2021 - 2022
* Second-Class Excellent Student Scholarship, Guangdong University of Technology, 2020 - 2021

Skills
======
* Programming: C/C++, Python
* Robotics and SLAM: LiDAR-inertial odometry, SLAM, ROS, ROS-control, Gazebo
* Machine Learning and Vision: PyTorch, OpenCV
* Embedded and Mechanical Systems: STM32 microcontrollers, motor control, 3D modeling

[//]: # (PDF Version)

[//]: # (======)

[//]: # (* [Download CV]&#40;/assets/CV-YuexinMu.pdf&#41;)
