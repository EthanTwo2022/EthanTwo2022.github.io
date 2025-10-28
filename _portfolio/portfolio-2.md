---
title: "Robocon 2022: 同创辉煌 (Co-create Brilliance)"
collection: portfolio
permalink: /portfolio/robocon-2022
excerpt: "全国大学生机器人大赛（ROBOCON2022）全国亚军。负责 R1、R2 物流搬运机器人的视觉感知算法。[Demo](/portfolio/robocon-2022) <br/><img src='/images/robocon2022.png'>"
date: 2022-08-01
header:
  teaser: "/images/robocon2022.png" # (!!!) 推荐！把你的 GIF 放在这里
---

## 奖项：全国一等奖（亚军）

## 项目内容
设计 R1、R2 两台模拟物流搬运机器人，完成场地内球类目标的识别、抓取、投掷以及圆柱块的识别与堆叠。

## 承担工作
我主要负责两台机器人的视觉感知算法：

1.  **目标识别 (YOLO + ONNX):**
    使用 YOLO 神经网络训练球类目标识别模型。为保证 C++ 端的实时性，将模型转换为 ONNX 格式，并使用 ONNX Runtime 在机器人本地完成高效部署。

2.  **点云处理 (PCL):**
    使用 PCL (Point Cloud Library) 点云库处理深度相机数据。通过分割、聚类等算法，完成对复杂环境中圆柱体物块的位姿、尺寸和相对位置求解，引导机械臂进行抓取。

## 演示 (Demo)



<video style="width: 100%; max-width: 640px; height: auto;" controls preload="metadata">
  <source src="/images/robocon2022-demo.mp4" type="video/mp4">
  抱歉，你的浏览器不支持 HTML5 video 标签。
</video>