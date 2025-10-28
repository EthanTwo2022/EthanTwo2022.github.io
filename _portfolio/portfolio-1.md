---
title: "Geotri-VIO: 全景视觉惯性里程计"
collection: portfolio
permalink: /portfolio/geotri-vio
excerpt: "一个基于几何一致性多棱镜投影的、用于全景相机的视觉-惯性里程计系统。<br/><img src='/images/geotrivio.png'>"
date: 2025-07-21
header:
  teaser: "/images/geotrivio.png" # (!!!) 这是一个占位符
---

## 项目概览

Geotri-VIO 是一个为多棱镜全景相机（panoramic camera）设计的实时视觉惯性里程计（VIO）系统。

传统的鱼眼或针孔相机模型难以精确描述这类具有复杂折射的（catadioptric）全景相机。我们的工作提出了一种**几何一致性的多棱镜投影模型**，能够准确地处理来自全景相机的视觉信息，并将其与 IMU 数据紧密耦合。

## 核心贡献
* 提出了一种新颖的、几何一致的多棱镜投影模型。
* 将该模型集成到一个基于优化的紧耦合 VIO 框架中。
* 实验证明，Geotri-VIO 在精度和鲁棒性上均优于现有的方法。

## 相关链接
* **[论文 PDF](/files/geotri-vio.pdf)**
* **[期刊页面](https://link.springer.com/article/10.1186/s43020-025-00171-y)**

---