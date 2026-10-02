<h1 align="center">Nixon Edward Winata</h1>

<p align="center">
  <strong>Robotics Engineer</strong><br>
  Autonomous systems · Perception · Simulation · Industrial robotics
</p>

Hi, I'm Nixon. I build robotics software for navigation, perception, simulation, and industrial automation. My work spans ROS/ROS 2, LiDAR calibration, computer vision, path planning, and robot simulation.

I enjoy the parts of robotics where software meets imperfect sensors and real system constraints: transforming point clouds, debugging robot behavior, and making autonomy easier to inspect.

## What I build

- **Autonomous navigation:** global and local path planning, frontier exploration, Nav2 goal handling, and recovery behavior.
- **LiDAR and point clouds:** multi-sensor calibration with NDT and GICP, frame transforms, and aligned point-cloud pipelines.
- **Perception:** camera detection, ground-plane projection, semantic landmark tracking, and language-guided navigation.
- **Simulation and tools:** URDF robots, Gazebo/RViz environments, ROS GUIs, system monitoring, and repeatable deployment.

## Robotics stack

**Core**

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white)

**Robotics and perception**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Point Cloud Library](https://img.shields.io/badge/Point_Cloud_Library-1E88E5?style=flat-square&logoColor=white)

**Simulation and interfaces**

![Gazebo](https://img.shields.io/badge/Gazebo-F58113?style=flat-square&logo=gazebo&logoColor=white)
![RViz](https://img.shields.io/badge/RViz-22314E?style=flat-square&logo=ros&logoColor=white)
![Qt](https://img.shields.io/badge/Qt-41CD52?style=flat-square&logo=qt&logoColor=white)

**Engineering tools**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)

## Featured work

### [Factory AMR Protocol Lab](https://github.com/Nixon080304/factory-amr-protocol-lab)

**Problem:** A factory robot needs to carry a part between stations while proving navigation, station identity, and PLC transfer completion.

**My work:** Built the ROS 2 coordination state machine, camera marker gates, MQTT replay-safe mission interface, Modbus handshakes, and correlated protocol traces with deterministic failure tests.

**Stack:** ROS 2 Humble, C++, Python, Nav2, Gazebo, RViz, MQTT, DDS, Modbus TCP, OpenCV, Docker

**Result:** A locally verified simulation mission completed in 72.6 simulated seconds. All 12/12 deterministic scenarios matched: four real Gazebo cases, seven protocol cases with a navigation driver, and one DDS experiment. Version 1 supports one part and one fixed route.

### [Semantic Exploration and Language-Guided Navigation](https://github.com/Nixon080304/FYP)

**Problem:** A mobile robot needs to explore an unknown environment, build a persistent semantic map, and navigate to an object named by a person.

**My work:** Built ROS 2 packages for frontier detection and selection, YOLO object detection, ground-plane projection, semantic landmark tracking, and language-command handling through Nav2.

**Stack:** ROS 2, Python, Nav2, YOLO, OpenCV, Gazebo, RViz

**Result:** A simulation workspace that explores frontiers, tracks supported objects, and converts commands such as `go to the chair` into navigation goals.

### [Dynamic Pathfinding Visualizer](https://github.com/Nixon080304/EE3180)

**Problem:** Comparing global and local planning behavior is difficult when the map and algorithm state are hidden.

**My work:** Implemented grid-based A* and a teaching-oriented Dynamic Window Approach, then connected both planners to an interactive map interface.

**Stack:** Python, PyQt5, NumPy, A*, DWA

**Result:** A 50 × 50 visualizer that animates paths and replans when the user adds obstacles.

## Experience highlights

**Robotics Software Engineer Intern · AIDRIVERS**

- Developed ROS tools for multi-LiDAR calibration with NDT and GICP, point-cloud alignment, and sensor configuration.
- Connected industrial PLC hardware to ROS through Modbus and built Qt tools for configuration and status monitoring.

**Robotics Simulation Developer · Foodlink-System**

- Built a URDF-based restaurant robot simulation with differential drive, LiDAR, IMU, depth cameras, and realistic operating scenarios.
- Developed modern C++ and Qt tooling, packaged the system with Docker, and tested robot behavior around docking, low battery, and crowded environments.

Professional projects described here are experience summaries; their source code is private.

## GitHub at a glance

My public work currently centers on robotics, path planning, computer vision, and machine-learning experiments.

<table>
  <tr>
    <td>
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Nixon080304&amp;show_icons=true&amp;hide_rank=true&amp;hide_border=true&amp;theme=github_dark">
        <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=Nixon080304&amp;show_icons=true&amp;hide_rank=true&amp;hide_border=true&amp;theme=default">
        <img alt="Nixon's GitHub statistics" src="https://github-readme-stats.vercel.app/api?username=Nixon080304&amp;show_icons=true&amp;hide_rank=true&amp;hide_border=true&amp;theme=default">
      </picture>
    </td>
    <td>
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Nixon080304&amp;layout=compact&amp;hide_border=true&amp;theme=github_dark">
        <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Nixon080304&amp;layout=compact&amp;hide_border=true&amp;theme=default">
        <img alt="Nixon's most-used public repository languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nixon080304&amp;layout=compact&amp;hide_border=true&amp;theme=default">
      </picture>
    </td>
  </tr>
</table>

## Current focus

I am currently focused on making robot navigation and perception systems easier to test, inspect, and improve.

## Contact

Email: [nixonedwardwinata2004@gmail.com](mailto:nixonedwardwinata2004@gmail.com)
