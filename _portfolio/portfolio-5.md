---
title: "MT Real2Sim Tutorial: 仿真-真机统一算法框架"
collection: portfolio
permalink: /portfolio/mt-real2sim
excerpt: "An open-source Real2Sim framework built on Isaac Sim 5.1 + ROS1 Noetic. Simulation and real-robot deployment share the same interfaces and algorithm code — zero modifications needed.<br/><img src='/images/mt_r2s.gif' width='66%'>"
date: 2026-06-01
header:
  teaser: "/images/mt_r2s.gif"
---

## Overview / 项目概览

**MT Real2Sim Tutorial** is an open-source, unified simulation ↔ real-robot algorithm framework built on **Isaac Sim 5.1** and **ROS1 Noetic**. The simulation and physical deployment share the same ROS1 interfaces and algorithm code, requiring zero modifications for real-world deployment.

MT Real2Sim Tutorial 是一个开源的仿真-真机统一算法框架，基于 **Isaac Sim 5.1** 和 **ROS1 Noetic** 构建。仿真与真机使用相同的 ROS1 接口和算法代码，实现零修改部署。

This project was developed during my internship at [Manifold Tech Ltd. (留形科技)](https://manifoldtech.cn), where I served as the **project lead**.

<p align="center">
  <img src="/images/mt_r2s.gif" alt="Real2Sim Tutorial — Isaac Sim + ROS1 navigation demo" width="100%">
</p>

## Key Features / 主要特性

- **Real2Sim / 真实到仿真:** Import 3D-scanned real-world environments (from Manifold Tech hardware such as Q9000, Pocket 2 Pro, Odin 1) directly into Isaac Sim as simulation scenes.
- **Sim2Real / 仿真到真机:** Replace the simulation bridge with a real robot driver; all navigation algorithms and demo code remain unchanged.
- **Docker-based / Docker 容器化:** Dual-container orchestration (Isaac Sim + ROS Noetic) with one-click launch via `start.sh`.
- **Full Sensor Suite / 全传感器支持:** RTX LiDAR, Camera, and IMU simulation with configurable intrinsics/extrinsics.
- **RL Locomotion / 强化学习运动控制:** Unitree Go2 quadruped robot with RL-based locomotion policy.
- **Autonomous Navigation / 自主导航:** Terrain analysis, local planning, and path following algorithms (C++).

## Architecture / 系统架构

The framework uses a TCP bridge to decouple the Isaac Sim simulation from the ROS1 algorithm stack, enabling seamless switching between simulation and real-robot deployment:

- **Isaac Sim container:** RL policy, sensor suite, TCP bridge server
- **ROS Noetic container:** sim_bridge, navigation algorithms (C++), demo scripts, RViz

## Links / 相关链接

- **[GitHub Repository](https://github.com/ManifoldTechLtd/MT-Real2Sim-Tutorial)**
- **[Manifold Tech (留形科技)](https://manifoldtech.cn)**
