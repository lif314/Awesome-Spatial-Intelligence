# Classic Manipulation

- [Point Cloud Manipulation](#Point-Cloud-Manipulation)
- [NeRF Manipulation](#NeRF-Manipulation)
- [3DGS Manipulation](#3DGS-Manipulation)



## Point Cloud Manipulation

- **MVP-Grasp**: Multi-Viewpoint Picking, *ICRA 2019*. [[Paper](https://arxiv.org/abs/1809.08564)] [[Code](https://github.com/dougsm/mvp_grasp)] [[Panda Camera Mount.stl](https://github.com/dougsm/mvp_grasp/tree/master/cad)]

- **GPD**: Grasp Pose Detection in Point Clouds, *IJRR 2017*. [[Paper](https://arxiv.org/abs/1706.09911)] [[Code (C++)](https://github.com/atenpas/gpd)]
- **PointNetGPD**: Detecting Grasp Configurations from Point Sets, *ICRA 2019*. [[Paper](https://arxiv.org/abs/1809.06267)] [[Website](https://lianghongzhuo.github.io/PointNetGPD/)] [[Code](https://github.com/lianghongzhuo/PointNetGPD)]
- **6-DOF GraspNet**: Variational Grasp Generation for Object Manipulation, *ICCV 2019*. [[Paper](https://arxiv.org/abs/1905.10520)] [[Code (tf)](https://github.com/NVlabs/6dof-graspnet)] [[Code (pytorch)](https://github.com/jsll/pytorch_6dof-graspnet)]
- **GraspNet-1Billion**: A Large-Scale Benchmark for General Object Grasping, *CVPR 2020*. [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fang_GraspNet-1Billion_A_Large-Scale_Benchmark_for_General_Object_Grasping_CVPR_2020_paper.pdf)] [[Website](https://graspnet.net/)] [[Code](https://github.com/graspnet/graspnet-baseline)]
- **Contact-GraspNet**: Efficient 6-DoF Grasp Generation in Cluttered Scenes, *ICRA 2021*. [[Paper](https://arxiv.org/abs/2103.14127)] [[Website](https://research.nvidia.com/publication/2021-03_contact-graspnet-efficient-6-dof-grasp-generation-cluttered-scenes)] [[Code](https://github.com/NVlabs/contact_graspnet)] [[Code (pytorch)](https://github.com/elchun/contact_graspnet_pytorch)]
- **Graspness**: Graspness Discovery in Clutters for Fast and Accurate Grasp Detection, *ICCV 2021*. [[Paper](https://arxiv.org/abs/2406.11142)] [[Code](https://github.com/graspnet/anygrasp_sdk)] [[Code (unofficial)](https://github.com/rhett-chen/graspness_implementation)]



## TSDF

- :fire: **VGN**: Volumetric Grasping Network: Real-time 6 DOF Grasp Detection in Clutter, *CoRL 2020*. [[Paper](https://arxiv.org/abs/2101.01132)] [[Code](https://github.com/ethz-asl/vgn)]




## NeRF Manipulation

- **LERF-TOGO**: Language Embedded Radiance Fields for Zero-Shot Task-Oriented Grasping, *CoRL 2023 (Best Paper Finalist)*. [[Paper](https://arxiv.org/abs/2309.07970)] [[Website](https://lerftogo.github.io/desktop.html)] [[Code](https://github.com/lerftogo/lerftogo)]
- **F3RM**: Distilled Feature Fields Enable Few-Shot Language-Guided Manipulation, *[CoRL 2023 (Best Paper)](https://www.corl2023.org/)*. [[Paper](https://arxiv.org/abs/2308.07931)] [[Website](https://f3rm.github.io/)] [[Code](https://github.com/f3rm/f3rm)]
- **SparseDFF**: Sparse-View Feature Distillation for One-Shot Dexterous Manipulation, *ICLR 2024*. [[Paper](https://arxiv.org/abs/2310.16838)] [[Website](https://helloqxwang.github.io/SparseDFF/)] [[Code](https://github.com/helloqxwang/SparseDFF)]
- Learning Generalizable Feature Fields for Mobile Manipulation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2403.07563)] [[Website](https://geff-b1.github.io/)]
- **D$^3$Fields**: Dynamic 3D Descriptor Fields for Zero-Shot Generalizable Rearrangement, *CoRL 2024 (Oral)*. [[Paper](https://openreview.net/forum?id=Uaaj4MaVIQ)] [[Website](https://robopil.github.io/d3fields/)] [[Code](https://github.com/WangYixuan12/d3fields)]
- **GenDP**: 3D Semantic Fields for Category-Level Generalizable Diffusion Policy, *CoRL 2024*. [[Paper](https://arxiv.org/abs/2410.17488)] [[Website](https://robopil.github.io/GenDP/)] [[Code](https://github.com/WangYixuan12/gendp)]
- **NeuGraspNet**: Learning Any-View 6DoF Robotic Grasping in Cluttered Scenes via Neural Surface Rendering, *RSS 2024*. [[Paper](https://arxiv.org/abs/2306.07392)] [[Website](https://sites.google.com/view/neugraspnet)] [[Code](https://github.com/pearl-robot-lab/neugraspnet)]

---

## 3DGS Manipulation

* **GraspSplats**: Efficient Manipulation with 3D Feature Splatting, *CoRL, 2024*. [[Paper](https://arxiv.org/pdf/2409.02084)] [[Website](https://graspsplats.github.io/)] [[Code](https://github.com/jimazeyu/GraspSplats)]
* **ManiGaussian**: Dynamic Gaussian Splatting for Multi-task Robotic Manipulation, *ECCV, 2024*. [[Paper](https://arxiv.org/abs/2403.08321)] [[Website](https://guanxinglu.github.io/ManiGaussian/)] [[Code](https://github.com/GuanxingLu/ManiGaussian)]
* **Physically Embodied Gaussian Splatting**: A Visually Learnt and Physically Grounded 3D Representation for Robotics, *CoRL, 2024*. [[Paper](https://openreview.net/forum?id=AEq0onGrN2)] [[Website](https://embodied-gaussians.github.io/)]
* **RL-GSBridge**: 3D Gaussian Splatting Based Real2Sim2Real Method for Robotic Manipulation Learning, *submitted to ICRA, 2025*. [[Paper](https://arxiv.org/abs/2409.20291)]
* **GaussianGrasper**: 3D Language Gaussian Splatting for Open-vocabulary Robotic Grasping, *RA-L, 2024*. [[Paper](https://arxiv.org/pdf/2403.09637)] [[Website](https://mrsecant.github.io/GaussianGrasper/)] [[Code](https://github.com/MrSecant/GaussianGrasper)]
* **Splat-MOVER**: Multi-Stage, Open-Vocabulary Robotic Manipulation via Editable Gaussian Splatting, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2405.04378)] [[Website](https://splatmover.github.io/)] [[Code](https://github.com/StanfordMSL/Splat-MOVER)]
* **GLOVER**: Generalizable Open-Vocabulary Affordance Reasoning for Task-Oriented Grasping, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2411.12286)] [[Website](https://teleema.github.io/projects/GLOVER/)]
* **G3Flow**: Generative 3D Semantic Flow for Pose-aware and Generalizable Object Manipulation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2411.18369)] [[Website](https://tianxingchen.github.io/G3Flow/)] [[Code](https://github.com/TianxingChen/G3Flow)]
* **Click to Grasp**: Zero-Shot Precise Manipulation via Visual Diffusion Descriptors, *IROS 2024*. [[Paper](https://arxiv.org/abs/2403.14526)] [[Website](https://tsagkas.github.io/click2grasp/)] [[Code](https://github.com/tsagkas/click2grasp)]
* **MSGField**: A Unified Scene Representation Integrating Motion, Semantics, and Geometry for Robotic Manipulation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2410.15730)] [[Website](https://shengyu724.github.io/MSGField.github.io/)] [[Code](https://github.com/ShengYu724/MSGField)]
* **ShapeGrasp**: Zero-Shot Task-Oriented Grasping with Large Language Models through Geometric Decomposition, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2403.18062)] [[Website](https://shapegrasp.github.io/)]
* **Robo-ABC**: Affordance Generalization Beyond Categories via Semantic Correspondence for Robot Manipulation, *ECCV 2024*. [[Paper](https://arxiv.org/abs/2401.07487)] [[Website](https://tea-lab.github.io/Robo-ABC/)] [[Code](https://github.com/TEA-Lab/Robo-ABC)]
* **Robot See Robot Do**: Imitating Articulated Object Manipulation with Monocular 4D Reconstruction, *CoRL 2024 (Oral)*. [[Paper](https://arxiv.org/abs/2409.18121)] [[Website](https://robot-see-robot-do.github.io/)] [[Code](https://github.com/kerrj/rsrd)]
* **SplatSim**: Zero-Shot Sim2Real Transfer of RGB Manipulation Policies Using Gaussian Splatting, *CoRL 2024*. [[Paper](https://arxiv.org/abs/2409.10161)] [[Website](https://splatsim.github.io/)] [[Code](https://github.com/qureshinomaan/SplatSim)]



 