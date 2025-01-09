# Awesome-Spatial-Intelligence [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)


## 🏠 About
This repo contains a curative list of **Spatial Intelligence for Robotics**, inspired by [Awesome-Implicit-NeRF-Robotics](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics)  and [awesome-Implicit-NeRF-SLAM](https://github.com/DoongLi/awesome-Implicit-NeRF-SLAM).

This is an active repository, you can watch for following the latest advances. If you find this repository useful, please consider STARing ⭐ this list. Feel free to share this list with others!

- [[awesome-NeRF](https://github.com/yenchenlin/awesome-NeRF)] [[Awesome-Implicit-NeRF-Robotics](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics)] [[awesome-NeRF-and-3DGS-SLAM](https://github.com/DoongLi/awesome-NeRF-and-3DGS-SLAM)]

- [[awesome-3D-gaussian-splatting](https://github.com/MrNeRF/awesome-3D-gaussian-splatting)] [[Awesome 3D Gaussian Splatting for Robotics](https://github.com/dtc111111/awesome-3dgs-for-robotics)] [[Awesome-Robotics-3D](https://github.com/zubair-irshad/Awesome-Robotics-3D)]
- [[Awesome-LLM-Robotics](https://github.com/GT-RIPL/Awesome-LLM-Robotics)] [[Awesome-Embodied-Agent-with-LLMs](https://github.com/zchoi/Awesome-Embodied-Agent-with-LLMs)]  [[Awesome-vision-language-action-models](https://github.com/DelinQu/awesome-vision-language-action-model)]
-  [[Awesome-Robotics-Foundation-Models](https://github.com/robotics-survey/Awesome-Robotics-Foundation-Models)]  [[Awesome-Generalist-Robots-via-Foundation-Models](https://github.com/JeffreyYH/Awesome-Generalist-Robots-via-Foundation-Models)]

- [[Awesome Video4Robot](https://github.com/jmwang0117/Video4Robot)] [[Awesome-Video-Robotic-Papers](https://github.com/H-Freax/Awesome-Video-Robotic-Papers)] [[awesome-dust3r](https://github.com/ruili3/awesome-dust3r)]
- [[Awesome_Manipulation](https://github.com/curieuxjy/Awesome_Manipulation)] [[Awesome-Robotics-Manipulation](https://github.com/BaiShuanghao/Awesome-Robotics-Manipulation)] [[awesome-robot-descriptions](https://github.com/robot-descriptions/awesome-robot-descriptions)]
- [[Awesome_Quadrupedal_Robots](https://github.com/curieuxjy/Awesome_Quadrupedal_Robots)] [[awesome-humanoid-learning](https://github.com/jonyzhang2023/awesome-humanoid-learning)] [[awesome-humanoid-robot-learning](https://github.com/YanjieZe/awesome-humanoid-robot-learning)]
- [[Awesome Touch](https://github.com/linchangyi1/Awesome-Touch)] [[Awesome-embodied-world-model-papers](https://github.com/QinengWang-Aiden/Awesome-embodied-world-model-papers)] [[coderonion/awesome-llm-and-aigc](https://github.com/coderonion/awesome-llm-and-aigc)]

---
# Idea

- 2024/12/24: 在目前透明物体的数据集中加上Tactile，主要是Tactile可以很好的用于滑动检测，很契合的点 :+1:
- 2024/12/24: 使用Gaussian Ray Tracing进行透明物体重建，主要用于机械臂的透明物体抓取
  - 2024/12/25：测试Gaussian Ray Tracing, 效果还行
- 2024/12/24: Single RGB-D的点云补全研究，比如SSD，用于单帧机械臂物体抓取

- 2024/12/25: 利用SplatFormer进行泛化的透明物体重建

- 2025/01/05：将[Semantic Diffusion Policy](https://github.com/WangYixuan12/gendp)与[3D Diffusion Policy](https://github.com/YanjieZe/3D-Diffusion-Policy)进行结合，实现3D语义diffusion policy的泛化

## Overview

- Robot
  - Mobile Robot
  - Humanoid Robot
  - Manipulation Robot
  - Locomotion Robot
- Perception
  - Spatial Perception
    - Scene Representation
    - SLAM
    - Scene Segmentation
  - Tactile Perception
  - Auditory Perception

---

- Scene Understanding
  - Scene Representation: Points, NeRF, 3DGS
  - Segmentation
  - Multimodal Grouding
- Data Introduction
  - Video Learning

- **Large Robot Models**
  - [Large Manipulation Model](./topics/Large_Manipulation_Model.md)
    - [LLM/VLM Guidance](https://github.com/lif314/Awesome-Spatial-Intelligence/blob/main/topics/Large_Manipulation_Model.md#LLM/VLM-Guidance)
    - [Structured Instructions](#Structured-Instructions)
    - [Vision-Language-Action](#Vision-Language-Action)
  - [Large Navigation Model](./topics/Large_Navigation_Model.md)
    - [Vision-Language-Action](#Vision-Language-Action)
- **Specific Object Manipulation**
  - [Transparent Object Manipulation](./topics/Transparent_Object_Manipulation.md)
    - [Survey](#Survey)
    - [Datasets](#Datasets)
  
    - [Robotic Grasping-Manipulation](#Robotic-Grasping-Manipulation)
    - [Visual Tactile](#Visual-Tactile)
    - [Pose Estimation](#Pose-Estimation)
    - [Simulation](#Simulation)
    - [Depth Completion](#Depth-Completion)
    - [3D Reconstruction](#3D-Reconstruction)
    - [Segmentation](#Segmentation)
    - [Perception](#Perception)
  - [Deformable Object Manipulation](./topics/Deformable_Object_Manipulation.md)
    - [Robotic Grasping-Manipulation](#Robotic-Grasping-Manipulation)
  - [Articulated Object Manipulation](./topics/Articulated_Object_Manipulation.md)
    - [Pose Estimation](#Pose-Estimation)
- **Spatial Intelligence**
  - [Scene Representation](./topics/Scene_Representation.md)
    - [3D Gaussian Splatting](#3D-Gaussian-Splatting)
  - [Easy 3D](./topics/Easy_3D.md)
    - [Zero Shot 3D Reconstruction](#Zero-Shot-3D-Reconstruction)
    - [Single View 3D Reconstruction](#Single-View-3D-Reconstruction)
    - [Sparse View Reconstruction](#Sparse-View-Reconstruction)
  
    - [Point Cloud Completion](#Point-Cloud-Completion)
  - [Spatial Understanding](./topics/Spatial_Understanding.md)
    - [3D Imagination](#3D-Imagination)
    - [3D Understanding](#3D-Understanding)
    - [Task-Adaptive 3D Part Segmentation](#Task-Adaptive-3D-Part-Segmentation)
- [Vision Tactile Manipulation](./topics/Vision_Tactile_Manipulation.md)
  - [Grasping and Manipulation](#Grasping-and-Manipulation)
  - [Representation and Perception](#Representation-and-Perception)
- [Mobile Manipulation](./topics/Mobile_Manipulation.md)
  - [Survey](#Survey)
  - [Benchmark and Hardware](#Benchmark-and-Hardware)
- [Dataset and Hardware](./topics/Dataset_and_Hardware.md)
- [Classic Manipulation](./topics/Classic_Manipulation.md)
  - [Point Cloud Grasping](#Point-Cloud-Grasping)
  - [3DGS/NeRF Manipulation](#3DGS/NeRF-Manipulation)
- [SLAM](./topics/SLAM.md)


- [Object Pose Estimation](./topics/Object_Pose_Estimation.md)
