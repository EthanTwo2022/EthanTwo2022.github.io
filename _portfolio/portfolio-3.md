---
title: "Robocon 2023: Volleyball Challenge (排球挑战赛)"
collection: portfolio
permalink: /portfolio/robocon-2023
excerpt: "National First Prize (Spark Award) in the ROBOCON 2023 China National Contest. Responsible for the volleyball's target detection and trajectory prediction algorithms. [Demo](/portfolio/robocon-2023)<br/><img src='/images/robocon2023.png' alt='Robocon 2023 Teaser'>"
date: 2023-08-01
header:
  teaser: "/images/robocon2023.png"
---

## Award: National First Prize (Spark Award, Special Award)
### ROBOCON 2023 China National Contest

## Project Details
The task was to design a fully autonomous volleyball robot capable of performing target detection, trajectory prediction, and receiving tasks.

## My Role
I was primarily responsible for the robot's visual perception and prediction algorithms:

1.  **Spatio-temporal Data Fusion:**
    Fused binocular depth information from an Intel Realsense D455 with pixel-level data from YOLOv5 to calculate the precise 3D spatio-temporal sequence (X, Y, Z, t) of the volleyball.

2.  **Trajectory Prediction:**
    Utilized the acquired spatio-temporal sequence to perform real-time trajectory fitting and prediction using the Least Squares method, assisting the robot's decision-making system in receiving the ball.

## Demo

<video style="width: 100%; max-width: 640px; height: auto;" controls preload="metadata">
  <source src="/images/robocon2023-demo.mp4" type="video/mp4">
  Sorry, your browser does not support the HTML5 video tag.
</video>