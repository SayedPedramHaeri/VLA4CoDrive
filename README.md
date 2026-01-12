<div align="center">
  <img src="Images/VLA4CoDrivee.png" width="350"/>
  
  ## Vision–Language–Action Dataset for Cooperative Autonomous Driving
  
[![paper](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/abs/2510.26641)
[![Documentation](https://img.shields.io/badge/Documentation-Available-blue.svg)](https://carla.readthedocs.io/en/latest/start_quickstart/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

</div>

<p align="justify">
<b>VLA4CoDrive</b> is a large-scale <b>cooperative Vision–Language–Action (VLA)</b> dataset designed to support autonomous driving under multi-vehicle cooperation. This work has been accepted to the <b>IEEE/CVF Winter Conference on Applications of Computer Vision (WACV) 2026</b>.
</p>

---

## 🔍 Overview
<p align="justify">
We introduce VLA4CoDrive, a cooperative Vision–Language–Action dataset with synchronized multi-vehicle sensing across diverse driving environments, providing multi-view visual streams, contextual text (caption, context, description, reasoning), and future trajectory actions for training and evaluating VLA driving models.

<div align="center">
  <img src="Images/VLA.jpg" width="90%"/>
</div>

---

## 📌 Dataset
<p align="justify">
<b>VLA4CoDrive</b> is organized into three tightly aligned modalities:
<b>Vision</b>, <b>Language</b>, and <b>Action</b>, each captured under the following settings.
</p>




<table border="0" cellspacing="0" cellpadding="0">
<tr>
<td width="50%" valign="top">

- 🤝 **Cooperative Multi-Vehicle Setup**  
  Synchronized sensing from multiple vehicles within the same driving episode

- 👁️ **Multi-View & Multi-Modal Perception**  
  RGB (front/rear/left/right), LiDAR, semantic LiDAR, optical flow, GNSS, IMU

- 🧠 **Structured Vision–Language Grounding**  
  Clip-level annotations including **Context, Caption, Description, and Reasoning**

- 🎯 **Action & Trajectory Supervision**  
  Low-level controls (steer/throttle/brake) + 30-step future trajectories

</td>
<td width="50%" valign="top">

- 🌦️ **Controlled Diversity**  
  8 CARLA towns × 8 weather conditions with frame-aligned replay

- 📏 **Large-Scale Dataset**  
  - ~10M vision samples  
  - ~150K language annotations  
  - ~1M action records  
  - ~300–360 hours of driving data  

- 📦 **Standard Annotation Formats**  
  COCO, PASCAL VOC, KITTI (2D & 3D)

</td>
</tr>
</table>

### VLA4CoDrive -- Vision

<p align="center">
  <img src="Images/Sensors.gif" width="100%" />
</p>


<p align="center">
  <img src="Images/scenarios.gif" width="100%" />
</p>
