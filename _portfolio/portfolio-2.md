---
title: "Robocon 2022: Lagori (同创辉煌)"
collection: portfolio
permalink: /portfolio/robocon-2022
excerpt: "National Runner-up (First Prize) in the ROBOCON 2022 China National Contest. Responsible for the visual perception algorithms for the logistic robots. [Demo](/portfolio/robocon-2022)<br/><img src='/images/robocon2022.png' alt='Robocon 2022 Teaser'>"
date: 2022-08-01
header:
  teaser: "/images/robocon2022.png"
---

## Award: National Runner-up (First Prize)
### ROBOCON 2022 China National Contest

## Project Details
This project involved designing two logistic robots (R1 and R2) to autonomously perform tasks including ball recognition, grasping, and throwing, as well as cylinder identification and stacking in a complex environment.

## My Role
I was primarily responsible for the visual perception algorithms for both robots.

1.  **Object Detection (YOLO + ONNX):**
    Trained a YOLO neural network for ball detection. To ensure real-time performance in C++, the model was converted to ONNX format and deployed locally using the ONNX Runtime.

2.  **Point Cloud Processing (PCL):**
    Utilized the Point Cloud Library (PCL) to process data from depth cameras. By implementing segmentation and clustering algorithms, I successfully solved for the pose, size, and relative position of cylinders in complex environments, guiding the robotic arm for grasping.

## Demo

<video style="width: 100%; max-width: 640px; height: auto;" controls preload="metadata">
  <source src="/images/robocon2022-demo.mp4" type="video/mp4">
  Sorry, your browser does not support the HTML5 video tag.
</video>