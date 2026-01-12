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

<table width="100%" border="0">
<tr>
<td width="50%" valign="top">

<ul>
  <li>🤝 <b>Cooperative Multi-Vehicle Setup</b><br>
      Synchronized sensing from multiple vehicles within the same driving episode</li><br>

  <li>👁️ <b>Multi-View & Multi-Modal Perception</b><br>
      RGB (front/rear/left/right), LiDAR, semantic LiDAR, optical flow, GNSS, IMU</li><br>

  <li>🧠 <b>Structured Vision–Language Grounding</b><br>
      Clip-level annotations including <b>Context, Caption, Description, and Reasoning</b></li><br>

  <li>🎯 <b>Action & Trajectory Supervision</b><br>
      Low-level controls (steer/throttle/brake) + 30-step future trajectories</li>
</ul>

</td>

<td width="50%" valign="top">

<ul>
  <li>🌦️ <b>Controlled Diversity</b><br>
      8 CARLA towns × 8 weather conditions with frame-aligned replay</li><br>

  <li>📏 <b>Large-Scale Dataset</b><br>
      ~10M vision samples · ~150K language annotations · ~1M action records · ~300–360 hours</li><br>

  <li>📦 <b>Standard Annotation Formats</b><br>
      COCO, PASCAL VOC, KITTI (2D & 3D)</li>
</ul>

</td>
</tr>
</table>







<p align="center">
  <img src="Images/scenarios.gif" width="100%" />
</p>
