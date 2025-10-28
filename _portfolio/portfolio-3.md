---
title: "Robocon 2023: 沙排之王 (King of Beach Volleyball)"
collection: portfolio
permalink: /portfolio/robocon-2023
excerpt: "全国大学生机器人大赛（ROBOCON2023）全国一等奖、星火奖。负责排球机器人的目标检测与轨迹预测算法。[Demo](/portfolio/robocon-2023) <br/><img src='/images/robocon2023.png'>"
date: 2023-08-01
header:
  teaser: "/images/robocon2023.png" # (!!!) 推荐！把你的 GIF 放在这里
---

## 奖项：全国一等奖 (星火奖, 特别颁发)

## 项目内容
本项目旨在设计一台全自动排球机器人，完成排球的目标检测、轨迹预测与接球任务。

## 承担工作
我主要负责机器人的视觉感知与预测算法部分：

1.  **时空数据融合:**
    利用 Intel Realsense D455 的双目深度信息与 YOLOv5 的像素信息相融合，计算排球的精确三维时空序列 (X, Y, Z, t)。

2.  **轨迹预测算法:**
    通过获取的时空序列，使用最小二乘法（Least Squares）对排球的飞行轨迹进行实时拟合与预测，辅助机器人决策系统完成接球动作。

## 演示 (Demo)

<video style="width: 100%; max-width: 640px; height: auto;" controls preload="metadata">
  <source src="/images/robocon2023-demo.mp4" type="video/mp4">
  抱歉，你的浏览器不支持 HTML5 video 标签。
</video>