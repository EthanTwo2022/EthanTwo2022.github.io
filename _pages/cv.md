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
* **M.Eng. in Computer Technology**, Sun Yat-sen University, 2024 - Present
  * Member of [RAPID Lab](http://lab.sysu-robotics.com/)
  * Supervisor: Professor [Hui Cheng](https://cse.sysu.edu.cn/teacher/ChengHui)
* **B.Eng. in Industrial Intelligence**, Northeastern University, 2020 - 2024
  * Member of [ACTION Lab](https://space.bilibili.com/434847356)
  * Advisor: Professor Dehong Cong

Research Experience
======
* **2023 - Present: Graduate Research Assistant**
  * RAPID Lab, Sun Yat-sen University
  * Research focus: Sensor calibration, Visual-Inertial Odometry, SLAM
  * Supervisor: Professor Hui Cheng

* **2021 - 2023: Undergraduate Researcher**
  * ACTION Lab, Northeastern University
  * Research focus: 3D perception for robotics
  * Advisor: Professor Dehong Cong
  
Skills
======
* **Programming Languages:** C/C++, Python, MATLAB
* **Robotics & Vision:**
  * ROS/ROS2
  * OpenCV, PCL
  * SLAM systems (VINS, LIO-SAM, etc.)
* **Deep Learning:** PyTorch, TensorFlow
* **Tools:** Git, Docker, LaTeX

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
