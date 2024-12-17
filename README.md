# Awesome-Spatial-Intelligence [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)


## 🏠 About
This repo contains a curative list of **Spatial Intelligence for Robotics**, inspired by [Awesome-Implicit-NeRF-Robotics](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics)  and [awesome-Implicit-NeRF-SLAM](https://github.com/DoongLi/awesome-Implicit-NeRF-SLAM).

This is an active repository, you can watch for following the latest advances. If you find this repository useful, please consider STARing ⭐ this list. Feel free to share this list with others!

- [[awesome-NeRF](https://github.com/yenchenlin/awesome-NeRF)] [[Awesome-Implicit-NeRF-Robotics](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics)] [[awesome-NeRF-and-3DGS-SLAM](https://github.com/DoongLi/awesome-NeRF-and-3DGS-SLAM)]

- [[awesome-3D-gaussian-splatting](https://github.com/MrNeRF/awesome-3D-gaussian-splatting)] [[Awesome 3D Gaussian Splatting for Robotics](https://github.com/dtc111111/awesome-3dgs-for-robotics)] [[Awesome-Robotics-3D](https://github.com/zubair-irshad/Awesome-Robotics-3D)]
- [[Awesome-LLM-Robotics](https://github.com/GT-RIPL/Awesome-LLM-Robotics)] [[Awesome-Embodied-Agent-with-LLMs](https://github.com/zchoi/Awesome-Embodied-Agent-with-LLMs)]  [[Awesome-vision-language-action-models](https://github.com/DelinQu/awesome-vision-language-action-model)]
-  [[Awesome-Robotics-Foundation-Models](https://github.com/robotics-survey/Awesome-Robotics-Foundation-Models)]  [[Awesome-Generalist-Robots-via-Foundation-Models](https://github.com/JeffreyYH/Awesome-Generalist-Robots-via-Foundation-Models)]

- [[Awesome Video4Robot](https://github.com/jmwang0117/Video4Robot)] [[Awesome-Video-Robotic-Papers](https://github.com/H-Freax/Awesome-Video-Robotic-Papers)]
- [[Awesome_Manipulation](https://github.com/curieuxjy/Awesome_Manipulation)] [[Awesome-Robotics-Manipulation](https://github.com/BaiShuanghao/Awesome-Robotics-Manipulation)] [[awesome-robot-descriptions](https://github.com/robot-descriptions/awesome-robot-descriptions)]
- [[Awesome Touch](https://github.com/linchangyi1/Awesome-Touch)] [[Awesome_Quadrupedal_Robots](https://github.com/curieuxjy/Awesome_Quadrupedal_Robots)] [[awesome-humanoid-learning](https://github.com/jonyzhang2023/awesome-humanoid-learning)] [[awesome-humanoid-robot-learning](https://github.com/YanjieZe/awesome-humanoid-robot-learning)]

---
## Overview

- [Vision-Language-Action Models](#Vision-Language-Action-Models)
  - [Video Generation For Robotics](Video-Generation-For-Robotics)

- [Spatial Intelligence](#Spatial-Intelligence)
  - [3D Imagination](#3D-Imagination)
  - [3D Understanding](#3D-Understanding)
  - [Task-Adaptive 3D Part Segmentation](Task-Adaptive-3D-Part-Segmentation)
  - [Zero Shot 3D Reconstruction](#Zero-Shot-3D-Reconstruction)
  - [Single View 3D Reconstruction](#Single-View-3D-Reconstruction)
- [3DGS/NeRF Manipulation](#3DGS/NeRF-Manipulation)
- [Scene Representation](Scene-Representation)
- [Object Pose Estimation](#object-pose-estimation)
- [Perception](#perception)
- [Manipulation/RL](#manipulationrl)
- [Object Reconstruction](#object-reconstruction)
- [Physics](#physics)
- [Planning/Navigation](#planningnavigation)

---

## Vision-Language-Action Models

- **RT-1**: Robotics Transformer for Real-World Control at Scale, *arXiv 2022*. [[Paper](https://arxiv.org/abs/2212.06817)] [[Website](https://robotics-transformer1.github.io/)] [[Code](https://github.com/google-research/robotics_transformer)] [[Robotics at Google](https://deepmind.google/discover/blog/)]
- **Open X-Embodiment**: Robotic Learning Datasets and RT-X Models, *arXiv 2023*. [[Paper](https://arxiv.org/abs/2310.08864)] [[Website](https://robotics-transformer-x.github.io/)] [[Code](https://github.com/google-deepmind/open_x_embodiment)] [[Dataset](https://docs.google.com/spreadsheets/d/1rPBD77tk60AEIGZrGSODwyyzs5FgCU9Uz3h-3_t2A9g/edit#gid=0)] [[Google]]
- **PaLM-E**: An Embodied Multimodal Language Model, *arXiv 2023*. [[Paper](https://arxiv.org/abs/2303.03378)] [[Website](https://palm-e.github.io/)] [[Robotics at Google](https://deepmind.google/discover/blog/)]
- **VQ-BeT**: Behavior Generation with Latent Actions, *ICML 2024 Spotlight*. [[Paper](https://arxiv.org/abs/2403.03181)] [[Website](https://sjlee.cc/vq-bet/)] [[Code](https://github.com/jayLEE0301/vq_bet_official)]
- **RT-2**: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control, *arXiv 2023*. [[Paper](https://arxiv.org/abs/2307.15818)] [[Website](https://robotics-transformer2.github.io/)] [[Unofficial Code](https://github.com/kyegomez/RT-2)] [[Google DeepMind](https://deepmind.google/discover/blog/)]
- **Diffusion Policy**: Visuomotor Policy Learning via Action Diffusion, *RSS 2023*. [[Paper](https://arxiv.org/abs/2303.04137)] [[Website](https://diffusion-policy.cs.columbia.edu/)] [[Code](https://github.com/real-stanford/diffusion_policy)] [[REAL-Stanford](https://github.com/real-stanford)]
- **ALOHA**: Learning Fine-Grained Bimanual Manipulation with Low-Cost Hardware, *RSS 2023*. [[Paper](https://arxiv.org/abs/2304.13705)] [[Code](https://github.com/tonyzhaozh/aloha)] [[Website](https://tonyzhaozh.github.io/aloha/)]
- **ACT**: Action Chunking with Transformers, *RSS 2023*. [[Paper](https://arxiv.org/abs/2304.13705)] [[Code](https://github.com/tonyzhaozh/aloha)] [[Website](https://tonyzhaozh.github.io/aloha/)]
- **LIBERO**: Benchmarking Knowledge Transfer for Lifelong Robot Learning, *NeurIPS 2023*. [[Paper](https://arxiv.org/abs/2306.03310)] [[Website](https://libero-project.github.io/main.html)] [[Code](https://github.com/Lifelong-Robot-Learning/LIBERO)]
- **UniSim**: Learning Interactive Real-World Simulators, *ICLR 2024 (Outstanding Paper Award)*. [[Paper](https://arxiv.org/abs/2310.06114)] [[Website](https://universal-simulator.github.io/unisim/)] [[Google DeepMind](https://deepmind.google/discover/blog/)]
- **ALOHA 2**: An Enhanced Low-Cost Hardware for Bimanual Teleoperation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2405.02292)] [[Code](https://github.com/tonyzhaozh/aloha/tree/main/aloha2)] [[Website](https://aloha-2.github.io/)]  [[Google DeepMind](https://deepmind.google/discover/blog/)]
- **Octo**: An Open-Source Generalist Robot Policy, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2405.12213)] [[Website](https://octo-models.github.io/)] [[Code](https://github.com/octo-models/octo)] [UC Berkeley]
- **OpenVLA**: An Open-Source Vision-Language-Action Model, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2406.09246)] [[Code](https://github.com/openvla/openvla)] [[Website](https://openvla.github.io/)] [Stanford University]
- **HPT**: Scaling Proprioceptive-Visual Learning with Heterogeneous Pre-trained Transformers, *NeurIPS 2024*. [[Paper](https://arxiv.org/abs/2409.20537)] [[Website](https://liruiw.github.io/hpt/)] [[Code](https://github.com/liruiw/HPT)] [[Kaiming He, MIT ](https://people.csail.mit.edu/kaiming/)]
- **RDT-1B**: a Diffusion Foundation Model for Bimanual Manipulation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2410.07864)] [[Code](https://github.com/thu-ml/RoboticsDiffusionTransformer)] [[Website](https://rdt-robotics.github.io/rdt-robotics/)] [[Jun Zhu, THU](https://scholar.google.com/citations?hl=en&user=axsP38wAAAAJ&view_op=list_works&sortby=pubdate)]
- **GR-1**: Unleashing Large-Scale Video Generative Pre-training for Visual Robot Manipulation, *ICLR 2024*. [[Paper](https://arxiv.org/abs/2312.13139)] [[Website](https://gr1-manipulation.github.io/)] [[Code](https://github.com/bytedance/GR-1)] [ByteDance Research]
- **SimplerEnv**: Simulated Manipulation Policy Evaluation Environments for Real Robot Setups, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2405.05941)] [[Website](https://simpler-env.github.io/)] [[Code](https://github.com/simpler-env/SimplerEnv)]
- **π0**: A Vision-Language-Action Flow Model for General Robot Control, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2410.24164)] [[Website](https://www.physicalintelligence.company/blog/pi0)] [[Physical Intelligence](https://www.physicalintelligence.company/)]
- **Scaling Up and Distilling Down**: Language-Guided Robot Skill Acquisition, *CoRL 2023*. [[Paper](https://openreview.net/forum?id=3uwj8QZROL)] [[Website](https://www.cs.columbia.edu/~huy/scalingup/)] [[Code](https://github.com/real-stanford/scalingup)]
- "Data Scaling Laws in Imitation Learning for Robotic Manipulation", *arXiv 2024*. [[Paper](https://arxiv.org/abs/2410.18647)] [[Website](https://data-scaling-laws.github.io/)] [[Code](https://github.com/Fanqi-Lin/Data-Scaling-Laws)] ``8 A100``
- **3D-VLA**: A 3D Vision-Language-Action Generative World Model, *ICML 2024*. [[Paper](https://arxiv.org/abs/2403.09631)] [[Code](https://github.com/UMass-Foundation-Model/3D-VLA)] [[Website](https://vis-www.cs.umass.edu/3dvla/)] [[UMass Foundation Model](https://github.com/UMass-Foundation-Model)]
- A Joint Modeling of Vision-Language-Action for Target-oriented Grasping in Clutter, *ICRA 2023*. [[Paper](https://arxiv.org/abs/2302.12610)] [[Code](https://github.com/xukechun/Vision-Language-Grasping)]
- **CogACT**: A Foundational Vision-Language-Action Model for Synergizing Cognition and Action in Robotic Manipulation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2411.19650)] [[Website](https://cogact.github.io/)] [[Code](https://github.com/microsoft/CogACT)]
- **BYOVLA**: Bring Your Own Vision-Language-Action Model, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2410.01971)] [[Website](https://aasherh.github.io/byovla/)] [[Code](https://github.com/irom-princeton/byovla)]
- **VLMPC**: Vision-Language Model Predictive Control for Robotic Manipulation, *RSS 2024*. [[Paper](https://arxiv.org/abs/2407.09829)] [[Code](https://github.com/PPjmchen/VLMPC)] [[Ran Song, Shandong University](https://faculty.sdu.edu.cn/songran/en/index/1023305/list/index.htm)]
- **3D Diffusion Policy**: Generalizable Visuomotor Policy Learning via Simple 3D Representations, *RSS 2024*. [[Paper](https://arxiv.org/abs/2403.03954)] [[Website](https://3d-diffusion-policy.github.io/)] [[Code](https://github.com/YanjieZe/3D-Diffusion-Policy)]
- **iDP3**: Generalizable Humanoid Manipulation with Improved 3D Diffusion Policies, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2410.10803)] [[Website](https://humanoid-manipulation.github.io/)] [[Code](https://github.com/YanjieZe/Improved-3D-Diffusion-Policy)]
- **NaVILA**: Legged Robot Vision-Language-Action Model for Navigation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2412.04453)] [[Website](https://navila-bot.github.io/)] [[Code (Low Level)](https://github.com/yang-zj1026/legged-loco)] [[Code (VLN-CE-Isaac)](https://github.com/yang-zj1026/VLN-CE-Isaac)] [UC San Diego]

---

### Video Generation For Robotics

- **VLP**: Video Language Planning, *arXiv 2023*. [[Paper](https://arxiv.org/abs/2310.10625)] [[Website](https://video-language-planning.github.io/)] [[Code](https://github.com/video-language-planning/vlp_code)]  [[Google DeepMind](https://deepmind.google/discover/blog/)]
- **AVDC**: Learning to Act from Actionless Videos through Dense Correspondences, *arXiv 2023*. [[Paper](https://arxiv.org/abs/2310.08576)] [[Website](https://flow-diffusion.github.io/)] [[Code](https://github.com/flow-diffusion/AVDC)]

- **ATM**: Any-point Trajectory Modeling for Policy Learning, *RSS 2024*. [[Paper](https://arxiv.org/abs/2401.00025)] [[Website](https://xingyu-lin.github.io/atm/)] [[Code](https://github.com/Large-Trajectory-Model/ATM)] [UC Berkeley]
- **Track2Act**: Predicting Point Tracks from Internet Videos enables Generalizable Robot Manipulation, *ECCV 2024*. [[Paper](https://arxiv.org/abs/2405.01527)] [[Website](https://homangab.github.io/track2act/)] [[Code](https://github.com/homangab/Track-2-Act/)] [CMU]
- **Dreamitate**: Real-World Visuomotor Policy Learning via Video Generation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2406.16862)] [[Website](https://dreamitate.cs.columbia.edu/)] [[Code](https://github.com/cvlab-columbia/dreamitate)] [Columbia University]
- **ARDuP**: Active Region Video Diffusion for Universal Policies, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2406.13301)]
- **This&That**: Language-Gesture Controlled Video Generation for Robot Planning, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2407.05530?context=cs)] [[Website](https://cfeng16.github.io/this-and-that/)] [[Code](https://github.com/cfeng16/this-and-that)]
- **Im2Flow2Act**: Flow as the Cross-Domain Manipulation Interface, *CoRL 2024*. [[Paper](https://arxiv.org/abs/2407.15208)] [[Website](https://im-flow-act.github.io/)] [[Code](https://github.com/real-stanford/im2Flow2Act)]  [[REAL-Stanford](https://github.com/real-stanford)]
- **CLOVER**: Closed-Loop Visuomotor Control with Generative Expectation for Robotic Manipulation, *NeurIPS 2024*. [[Paper](https://arxiv.org/abs/2409.09016)] [[Code](https://github.com/OpenDriveLab/CLOVER)] [[OpenDriveLab](https://github.com/OpenDriveLab)]
- **Gen2Act**: Human Video Generation in Novel Scenarios enables Generalizable Robot Manipulation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2409.16283)] [[Website](https://homangab.github.io/gen2act/)] [[Google DeepMind](https://deepmind.google/discover/blog/)]
- **DynaMo**: In-Domain Dynamics Pretraining for Visuo-Motor Control, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2409.12192)] [[Website](https://dynamo-ssl.github.io/)] [[Code](https://github.com/jeffacce/dynamo_ssl)]
- **GR-2**: A Generative Video-Language-Action Model with Web-Scale Knowledge for Robot Manipulation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2410.06158)] [[Website](https://gr2-manipulation.github.io/)] [Robotics Research Team, ByteDance Research]
- **VLM See, Robot Do**: Human Demo Video to Robot Action Plan via Vision Language Model, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2410.08792)] [[Website](https://ai4ce.github.io/SeeDo/)] [[Code](https://github.com/ai4ce/SeeDo)]
- Towards Synergistic, Generalized, and Efficient Dual-System for Robotic Manipulation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2410.08001)] [[Website](https://opendrivelab.com/RoboDual/)]
- **LAPA**: Latent Action Pretraining from Videos, *CoRL 2024*. [[Paper](https://arxiv.org/abs/2410.11758)] [[Website](https://latentactionpretraining.github.io/)] [[Code](https://github.com/LatentActionPretraining/LAPA)]
- Differentiable Robot Rendering, *CoRL 2024*. [[Paper](https://arxiv.org/abs/2410.13851)] [[Website](https://drrobot.cs.columbia.edu/)] [[Code](https://github.com/cvlab-columbia/drrobot)] [[cvlab-columbia](https://github.com/cvlab-columbia)]
- **OKAMI**: Teaching Humanoid Robots Manipulation Skills through Single Video Imitation, *CoRL 2024*. [[Paper](https://arxiv.org/abs/2410.11792)] [[Website](https://ut-austin-rpl.github.io/OKAMI/)]
- **Robots Pre-train Robots**: Manipulation-Centric Robotic Representation from Large-Scale Robot Datasets, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2410.22325)] [[Website](https://robots-pretrain-robots.github.io/)] [[Code](https://github.com/luccachiang/robots-pretrain-robots)]
- **VideoAgent**: Self-Improving Video Generation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2410.10076)] [[Code](https://github.com/Video-as-Agent/VideoAgent)]
- **IGOR**: Image-GOal Representations are the Atomic Control Units for Foundation Models in Embodied AI, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2411.00785)] [[Website](https://www.microsoft.com/en-us/research/project/igor-image-goal-representations/)]
- **VidMan**: Exploiting Implicit Dynamics from Video Diffusion Model for Effective Robot Manipulation, *NeurIPS 2024*. [[Paper](https://arxiv.org/abs/2411.09153)]
- Grounding Video Models to Actions through Goal Conditioned Exploration, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2411.07223)] [[Website](https://video-to-action.github.io/)] [[Code](https://github.com/video-to-action/video-to-action-release)]
- 

---

## Spatial Intelligence

### 3D Imagination

- **ReconFusion**: 3D Reconstruction with Diffusion Priors, *CVPR, 2024*. [[Paper](https://arxiv.org/abs/2312.02981)] [[Website](https://reconfusion.github.io/)] [[Code (unofficial)](https://github.com/maxgillett/tinysplat)]
- **ZeroNVS**: Zero-Shot 360-Degree View Synthesis from a Single Real Image, *CVPR, 2024*. [[Paper](https://arxiv.org/abs/2310.17994)] [[Website](https://kylesargent.github.io/zeronvs/)] [[Code](https://github.com/kylesargent/zeronvs)]
- **Text2Room**: Extracting Textured 3D Meshes from 2D Text-to-Image Models, *ICCV (oral), 2023*. [[Paper](https://arxiv.org/abs/2303.11989)] [[Website](https://lukashoel.github.io/text-to-room/)] [[Code](https://github.com/lukasHoel/text2room)]
- **WonderJourney**: Going from Anywhere to Everywhere, *CVPR, 2024*. [[Paper](https://arxiv.org/pdf/2312.03884)] [[Website](https://kovenyu.com/wonderjourney/)] [[Code](https://github.com/KovenYu/WonderJourney)]

---

### 3D Understanding

- **LERF**: Language Embedded Radiance Fields, *ICCV 2023 (Oral)*. [[Paper](https://arxiv.org/abs/2303.09553)] [[Website](https://www.lerf.io/)] [[Code](https://github.com/kerrj/lerf)]
- **LEGS**: Incrementally Building Room-Scale Language-Embedded Gaussian Splats (LEGS) with a Mobile Robot, *IROS 2024 (Oral)*. [[Paper](https://arxiv.org/abs/2409.18108)] [[Website](https://berkeleyautomation.github.io/LEGS/)] [[Code](https://github.com/BerkeleyAutomation/L3GS)]
- **OpenGaussian**: Towards Point-Level 3D Gaussian-based Open Vocabulary Understanding, *NeurIPS 2024*. [[Paper](https://arxiv.org/abs/2406.02058)] [[Website](https://3d-aigc.github.io/OpenGaussian/)] [[Code](https://github.com/yanmin-wu/OpenGaussian)]
- **FlashSplat**: 2D to 3D Gaussian Splatting Segmentation Solved Optimally, *ECCV 2024*. [[Paper](https://arxiv.org/abs/2409.08270)] [[Code](https://github.com/florinshen/FlashSplat)]
- :fire: Gradient-Driven 3D Segmentation and Affordance Transfer in Gaussian Splatting Using 2D Masks, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2409.11681)] [[Website](https://jojijoseph.github.io/3dgs-segmentation/)] [[Code](https://github.com/JojiJoseph/3dgs-gradient-segmentation)]
- :fire: Gradient-Weighted Feature Back-Projection: A Fast Alternative to Feature Distillation in 3D Gaussian Splatting, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2411.15193)] [[Website](https://jojijoseph.github.io/3dgs-backprojection/)] [[Code](https://github.com/JojiJoseph/3dgs-gradient-backprojection)]
- :fire:**OOAL**: One-Shot Open Affordance Learning with Foundation Models, *CVPR 2024*. [[Paper](https://arxiv.org/abs/2311.17776)] [[Website](https://reagan1311.github.io/ooal/)] [[Code](https://github.com/Reagan1311/OOAL)]
- **NeRF2Physics**: Physical Property Understanding from Language-Embedded Feature Fields, *CVPR 2024*. [[Paper](https://arxiv.org/abs/2404.04242)] [[Website](https://ajzhai.github.io/NeRF2Physics/)] [[Code](https://github.com/ajzhai/NeRF2Physics)]
- 

### Task-Adaptive 3D Part Segmentation

- **PartSTAD**: 2D-to-3D Part Segmentation Task Adaptation, *ECCV 2024*. [[Paper](https://arxiv.org/abs/2401.05906)] [[Website](https://partstad.github.io/)] [[Code](https://github.com/KAIST-Visual-AI-Group/PartSTAD/)]
- **SAMPart3D**: Segment Any Part in 3D Objects, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2411.07184v2)] [[Website](https://yhyang-myron.github.io/SAMPart3D-website/)] [[Code](https://github.com/Pointcept/SAMPart3D)]
- :fire: **GARField**: Group Anything with Radiance Fields, *CVPR 2024*.  [[Paper](https://arxiv.org/abs/2401.09419)] [[Website](https://www.garfield.studio/)] [[Code](https://github.com/chungmin99/garfield)]
- Open-Vocabulary Part-Based Grasping, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2406.05951)]

### Zero Shot 3D Reconstruction

- **DUSt3R**: Geometric 3D Vision Made Easy, *CVPR 2024* [[Paper](https://arxiv.org/abs/2312.14132)] [[Website](https://europe.naverlabs.com/research/publications/dust3r-geometric-3d-vision-made-easy/)] [[Code](https://github.com/naver/dust3r)]
- **MASt3R**: Grounding Image Matching in 3D with MASt3R, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2406.09756)] [[Website](https://europe.naverlabs.com/blog/mast3r-matching-and-stereo-3d-reconstruction/)] [[Code](https://github.com/naver/mast3r)]
- **Splatt3R**: Zero-shot Gaussian Splatting from Uncalibrated Image Pairs, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2408.13912)] [[Website](https://splatt3r.active.vision/)] [[Code](https://github.com/btsmart/splatt3r)]
- **Spann3R**: 3D Reconstruction with Spatial Memory, *3DV 2025*. [[Paper](https://arxiv.org/abs/2408.16061)] [[Website](https://hengyiwang.github.io/projects/spanner)] [[Code](https://github.com/HengyiWang/spann3r)]
- **MonST3R**: A Simple Approach for Estimating Geometry in the Presence of Motion, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2410.03825)] [[Website](https://monst3r-project.github.io/)] [[Code](https://github.com/Junyi42/monst3r)]
- **No Pose, No Problem**: Surprisingly Simple 3D Gaussian Splats from Sparse Unposed Images, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2410.24207)] [[Website](https://noposplat.github.io/)] [[Code](https://github.com/cvg/NoPoSplat)]
- **ZeroGS**: Training 3D Gaussian Splatting from Unposed Images, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2411.15779)] [[Website](https://aibluefisher.github.io/ZeroGS/)] [[Code](https://github.com/aibluefisher/ZeroGS)]
- **SelfSplat**: Pose-Free and 3D Prior-Free Generalizable 3D Gaussian Splatting, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2411.17190)] [[Website](https://gynjn.github.io/selfsplat/)] [[Code](https://github.com/Gynjn/selfsplat)]
- **Large Spatial Model**: End-to-end Unposed Images to Semantic 3D, *NeurIPS 2024*. [[Paper](https://arxiv.org/abs/2410.18956)] [[Website](https://largespatialmodel.github.io/)]
- **DiffusionGS**: Baking Gaussian Splatting into Diffusion Denoiser for Fast and Scalable Single-stage Image-to-3D Generation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2411.14384v2)] [[Website](https://caiyuanhao1998.github.io/project/DiffusionGS/)] [[Code](https://github.com/caiyuanhao1998/Open-DiffusionGS)]
- 

---

### Single View 3D Reconstruction

- "Learning to Recover 3D Scene Shape from a Single Image", *CVPR 2021*. [[Paper](https://arxiv.org/abs/2012.09365)] [[Code](https://github.com/aim-uofa/AdelaiDepth)] 
- **pixelNeRF**: Neural Radiance Fields from One or Few Images, *CVPR 2021*. [[Paper](https://arxiv.org/abs/2012.02190)] [[Website](https://alexyu.net/pixelnerf/)] [[Code](https://github.com/sxyu/pixel-nerf)]
- **Behind the Scenes**: Density Fields for Single View Reconstruction, *CVPR 2023*. [[Paper](https://arxiv.org/abs/2301.07668)] [[Website](https://fwmb.github.io/bts/)] [[Code](https://github.com/Brummi/BehindTheScenes)]
- **Know Your Neighbors**: Improving Single-View Reconstruction via Spatial Vision-Language Reasoning, *CVPR 2024*. [[Paper](https://arxiv.org/abs/2404.03658)] [[Website](https://ruili3.github.io/kyn/)] [[Code](https://github.com/ruili3/Know-Your-Neighbors)]

- **Zero-1-to-3**: Zero-shot One Image to 3D Object, *ICCV 2023*. [[Paper](https://arxiv.org/abs/2303.11328)] [[Website](https://zero123.cs.columbia.edu/)] [[Code](https://github.com/cvlab-columbia/zero123)]

- **RealFusion**: 360° Reconstruction of Any Object from a Single Image, *CVPR 2023*. [[Paper](https://arxiv.org/abs/2302.10663)] [[Website](https://lukemelas.github.io/realfusion/)] [[Code](https://github.com/lukemelas/realfusion)]

- **One-2-3-45**: Any Single Image to 3D Mesh in 45 Seconds without Per-Shape Optimization, *NeurIPS 2023*. [[Paper](https://arxiv.org/abs/2306.16928)] [[Website](https://one-2-3-45.github.io/)] [[Code](https://github.com/One-2-3-45/One-2-3-45)] [[Demo](https://huggingface.co/spaces/One-2-3-45/One-2-3-45)]

- **One-2-3-45++**: Fast Single Image to 3D Objects with Consistent Multi-View Generation and 3D Diffusion, *CVPR 2024*. [[Paper](https://arxiv.org/abs/2311.07885)] [[Website](https://sudo-ai-3d.github.io/One2345plus_page/)] [[Code](https://github.com/SUDO-AI-3D/One2345plus)] [[Demo](https://www.sudo.ai/3dgen)]

- **Wonder3D**: Single Image to 3D using Cross-Domain Diffusion, *CVPR 2024*. [[Paper](https://arxiv.org/abs/2310.15008)] [[Project](https://www.xxlong.site/Wonder3D/)] [[Code](https://github.com/xxlong0/Wonder3D)] [[Demo](https://huggingface.co/spaces/flamehaze1115/Wonder3D-demo)]

- **ImageDream**: Image-Prompt Multi-view Diffusion for 3D Generation, *arXiv 2023*. [[Paper](https://arxiv.org/abs/2312.02201)] [[Website](https://image-dream.github.io/)] [[Code](https://github.com/bytedance/ImageDream)]

- :+1:**LRM**: Large Reconstruction Model for Single Image to 3D, *ICLR 2024*. [[Paper](https://arxiv.org/abs/2311.04400)] [[Website](https://yiconghong.me/LRM/)] [[Code](https://github.com/3DTopia/OpenLRM)] [[Demo](https://huggingface.co/spaces/zxhezexin/OpenLRM)]

- **DMV3D**: Denoising Multi-View Diffusion using 3D Large Reconstruction Model, *ICLR 2024 spotlight*. [[Paper](https://arxiv.org/abs/2311.09217)] [[Website](https://justimyhxu.github.io/projects/dmv3d/)]

- **TripoSR**: Fast 3D Object Reconstruction from a Single Image , *arXiv 2024*. [[Paper](https://arxiv.org/abs/2403.02151)] [[Code](https://github.com/VAST-AI-Research/TripoSR)]

- **Triplane Meets Gaussian Splatting**: Fast and Generalizable Single-View 3D Reconstruction with Transformers , *CVPR 2024*. [[Paper](https://arxiv.org/abs/2312.09147)] [[Website](https://zouzx.github.io/TriplaneGaussian/)] [[Code](https://github.com/VAST-AI-Research/TriplaneGaussian)]

- **AGG**: Amortized Generative 3D Gaussians for Single Image to 3D , *TMLR 2024*. [[Paper](https://arxiv.org/abs/2401.04099)] [[Website](https://ir1d.github.io/AGG/)]

- **LN3Diff**: Scalable Latent Neural Fields Diffusion for Speedy 3D Generation , *ECCV 2024*. [[Paper](https://arxiv.org/pdf/2403.12019.pdf)] [[Website](https://nirvanalan.github.io/projects/ln3diff/)] [[Code](https://github.com/NIRVANALAN/LN3Diff)]

- **NViST**: In the Wild New View Synthesis from a Single Image with Transformers , *CVPR 2024*. [[Paper](https://arxiv.org/abs/2312.08568)] [[Website](https://wbjang.github.io/nvist_webpage/)] [[Code](https://github.com/wbjang/nvist_official)]

- **Splatter Image**: Ultra-Fast Single-View 3D Reconstruction , *CVPR 2024*. [[Paper](https://arxiv.org/abs/2312.13150)] [[Website](https://szymanowiczs.github.io/splatter-image.html)] [[Code](https://github.com/szymanowiczs/splatter-image)]

- **pixelSplat**: 3D Gaussian Splats from Image Pairs for Scalable Generalizable 3D Reconstruction , *CVPR 2024*. [[Paper](https://arxiv.org/abs/2312.12337)] [[Website](https://davidcharatan.com/pixelsplat/)] [[Code](https://github.com/dcharatan/pixelsplat)]

- **SSR**: Single-view 3D Scene Reconstruction with High-fidelity Shape and Texture, *3DV 2024*. [[Paper](http://arxiv.org/abs/2311.00457)] [[Website](https://dali-jack.github.io/SSR/)] [[Code](https://github.com/DaLi-Jack/SSR-code)]

- "Dynamic Scene Reconstruction from Single Landscape Image Using 4D Gaussian in the Wild", *arXiv 2024*. [[Paper](https://openreview.net/forum?id=HrwrydyPBD)] [[Website](https://cvsp-lab.github.io/3D_MRM_page/)]

- **GRM**: Large Gaussian Reconstruction Model for Efficient 3D Reconstruction and Generation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2403.14621)] [[Website](https://justimyhxu.github.io/projects/grm/)] [[Code](https://github.com/justimyhxu/grm)] [[Demo](https://huggingface.co/spaces/GRM-demo/GRM)]

- **LGM**: Large Multi-View Gaussian Model for High-Resolution 3D Content Creation, *ECCV 2024 (Oral)*. [[Paper](https://arxiv.org/abs/2402.05054)] [[Website](https://me.kiui.moe/lgm/)] [[Code](https://github.com/3DTopia/LGM)] [[Demo](https://huggingface.co/spaces/ashawkey/LGM)]

- :fire: **TRELLIS**: Structured 3D Latents for Scalable and Versatile 3D Generation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2412.01506)] [[Website](https://trellis3d.github.io/)] [[Code](https://github.com/Microsoft/TRELLIS)] [[Demo](https://huggingface.co/spaces/JeffreyXiang/TRELLIS)]

- **MIDI**: Multi-Instance Diffusion for Single Image to 3D Scene Generation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2412.03558)] [[Website](https://huanngzh.github.io/MIDI-Page/)] [[Code](https://github.com/huanngzh/MIDI)]

----
## 3DGS/NeRF Manipulation

- **LERF-TOGO**: Language Embedded Radiance Fields for Zero-Shot Task-Oriented Grasping, *CoRL 2023 (Best Paper Finalist)*. [[Paper](https://arxiv.org/abs/2309.07970)] [[Website](https://lerftogo.github.io/desktop.html)] [[Code](https://github.com/lerftogo/lerftogo)]
- **F3RM**: Distilled Feature Fields Enable Few-Shot Language-Guided Manipulation, *[CoRL 2023 (Best Paper)](https://www.corl2023.org/)*. [[Paper](https://arxiv.org/abs/2308.07931)] [[Website](https://f3rm.github.io/)] [[Code](https://github.com/f3rm/f3rm)]
- **SparseDFF**: Sparse-View Feature Distillation for One-Shot Dexterous Manipulation, *ICLR 2024*. [[Paper](https://arxiv.org/abs/2310.16838)] [[Website](https://helloqxwang.github.io/SparseDFF/)] [[Code](https://github.com/helloqxwang/SparseDFF)]
- Learning Generalizable Feature Fields for Mobile Manipulation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2403.07563)] [[Website](https://geff-b1.github.io/)]
- **D$^3$Fields**: Dynamic 3D Descriptor Fields for Zero-Shot Generalizable Rearrangement, *CoRL 2024 (Oral)*. [[Paper](https://openreview.net/forum?id=Uaaj4MaVIQ)] [[Website](https://robopil.github.io/d3fields/)] [[Code](https://github.com/WangYixuan12/d3fields)]

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
* **NeuGraspNet**: Learning Any-View 6DoF Robotic Grasping in Cluttered Scenes via Neural Surface Rendering, *RSS 2024*. [[Paper](https://arxiv.org/abs/2306.07392)] [[Website](https://sites.google.com/view/neugraspnet)] [[Code](https://github.com/pearl-robot-lab/neugraspnet)]
* 

---

## Scene Representation

### 3D Gaussian Splatting

- Sparse Voxels Rasterization: Real-time High-fidelity Radiance Field Rendering, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2412.04459)] [[Author](https://sunset1995.github.io/)]

----

## Object Pose Estimation

* **BundleSDF**: "Neural 6-DoF Tracking and 3D Reconstruction of Unknown Objects", *CVPR, 2023*. [[Paper](https://arxiv.org/pdf/2303.14158.pdf)] [[Webpage](https://bundlesdf.github.io/)] 

* **ShAPO**: "Implicit Representations for Multi Object Shape Appearance and Pose Optimization", *ECCV, 2022*. [[Paper](https://arxiv.org/pdf/2207.13691.pdf)] [[Pytorch Code](https://github.com/zubair-irshad/shapo)] [[Webpage](https://zubair-irshad.github.io/projects/ShAPO.html)] [[Video](https://youtu.be/LMg7NDcLDcA)] 

* **NCF**: "Neural Correspondence Field for Object Pose Estimation", *ECCV, 2022*. [[Paper](https://arxiv.org/pdf/2208.00113.pdf)] [[Pytorch Code]( https://github.com/LinHuang17/NCF-code)] [[Webpage](https://linhuang17.github.io/NCF/)]

* **Neural-Sim**: "Learning to Generate Training Data with NeRF", *ECCV 2022*.  [[Paper](https://arxiv.org/pdf/2207.11368.pdf)] [[Pytorch Code](https://github.com/gyhandy/Neural-Sim-NeRF)] [[Webpage](https://fylwen.github.io/disp6d.html)]

* **DISP6D**: "Disentangled Implicit Shape and Pose Learning for Scalable 6D Pose Estimation", *ECCV 2022*.  [[Paper](https://arxiv.org/pdf/2107.12549.pdf)] [[Pytorch Code](https://github.com/fylwen/DISP-6D)] [[Webpage](https://nerf2nerf.github.io/)] [[Video](https://youtu.be/GTBfCB2A7sI)]

* **SNAKE**: "SNAKE: Shape-aware Neural 3D Keypoint Field", *NeurIPS, 2022*. [[Paper](https://arxiv.org/abs/2206.01724.pdf)] [[Pytorch Code](https://github.com/zhongcl-thu/SNAKE)]

* **NeRF-RPN**: "A general framework for object detection in NeRFs", *CVPR 2023*. [[Paper](https://arxiv.org/abs/2211.11646)] [[Video](https://youtu.be/M8_4Ih1CJjE)]

* **NeRF-MAE**: "Masked AutoEncoders for Self-Supervised 3D Representation Learning for Neural Radiance Fields", *ECCV 2024*. [[Paper](https://arxiv.org/abs/2404.01300)] [[Webpage](https://nerf-mae.github.io/)] [[Pytorch Code](https://github.com/zubair-irshad/NeRF-MAE)]

* **nerf2nerf**: "Pairwise Registration of Neural Radiance Fields", *arXiv*.  [[Paper](https://arxiv.org/pdf/2211.01600.pdf)] [[Pytorch Code]( https://github.com/nerf2nerf/nerf2nerf)] [[Webpage](https://nerf2nerf.github.io/)] [[Dataset](https://drive.google.com/drive/folders/1jNpwAv1T1ntjIHUMJ1wABePA2Z8_nRRQ)]

* **iNeRF**: "Inverting Neural Radiance Fields for Pose Estimation", *IROS, 2021*. [[Paper](https://arxiv.org/pdf/2012.05877.pdf)] [[Pytorch Code](https://github.com/yenchenlin/iNeRF-public)] [[Website](https://yenchenlin.me/inerf/)] [[Dataset](https://github.com/BerkeleyAutomation/dex-nerf-datasets)]

* **NeRF-Pose**: "A First-Reconstruct-Then-Regress Approach for Weakly-supervised 6D Object Pose Estimation", *arXiv*. [[Paper](https://arxiv.org/pdf/2203.04802.pdf)]

* **PixTrack**: "Precise 6DoF Object Pose Tracking using NeRF Templates and Feature-metric Alignment", *arXiv*. [[Paper](https://arxiv.org/pdf/2209.03910.pdf)] [[Pytorch Code](https://github.com/GiantAI/pixtrack)]

* "Parallel Inversion of Neural Radiance Fields for Robust Pose Estimation", *arXiv*. [[Paper](https://arxiv.org/abs/2210.10108v1)] [[Website](https://pnerfp.github.io/)]

* **NARF22**: "Neural Articulated Radiance Fields for Configuration-Aware Rendering", *IROS, 2022*. [[Paper](https://arxiv.org/pdf/2210.01166.pdf)] [[Website](https://progress.eecs.umich.edu/projects/narf/)]

* **FroDO**: "From Detections to 3D Objects", *CVPR, 2020*. [[Paper](https://arxiv.org/pdf/2005.05125.pdf)] 

* **SDFEst**: "Categorical Pose and Shape Estimation of Objects From RGB-D Using Signed Distance Fields", *RA-L, 2022*. [[Paper](https://arxiv.org/pdf/2207.04880.pdf)] [[Pytorch Code](https://arxiv.org/pdf/2207.04880.pdf)]

* **SSC-6D**: "Self-Supervised Category-Level 6D Object Pose Estimation with Deep Implicit Shape Representation", *AAAI, 2022*. [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/20104)] [[Pytorch Code](https://github.com/swords123/SSC-6D)]

* **Style2NeRF**: "An Unsupervised One-Shot NeRF for Semantic 3D Reconstruction", *BMVC, 2022*. [[Paper](https://bmvc2022.mpi-inf.mpg.de/0104.pdf)] 

* "Shape, Pose, and Appearance from a Single Image via Bootstrapped Radiance Field Inversion", *CVPR, 2023*. [[Paper](https://arxiv.org/pdf/2211.11674.pdf)] [[Code](https://github.com/google-research/nerf-from-image)]

* **TexPose**: "Neural Texture Learning for Self-Supervised 6D Object Pose Estimation", *CVPR 2023*. [[Paper](https://arxiv.org/pdf/2212.12902.pdf)][[Code](https://github.com/HanzhiC/TexPose)]

* **Canonical Fields**: "Self-Supervised Learning of Pose-Canonicalized Neural Fields", *arXiv*. [[Paper](https://arxiv.org/pdf/2212.02493.pdf)]
  
* **NeRF-Det**: "Learning Geometry-Aware Volumetric Representation for Multi-View 3D Object Detection", *arXiv*. [[Paper](https://arxiv.org/abs/2307.14620)] [[Page] https://chenfengxu714.github.io/nerfdet/] [[Code] https://github.com/facebookresearch/NeRF-Det]

* **One-step NeRF**: "Marrying NeRF with Feature Matching for One-step Pose Estimation", *ICRA, 2024*. [[Paper](https://arxiv.org/pdf/2404.00891)] [[Short Video](https://www.youtube.com/watch?v=70fgUobOFWo)] [[Website&Code] Coming]

---
## Perception
* **iSDF**: "Real-Time Neural Signed Distance Fields for Robot Perception", *RSS, 2022*. [[Paper](https://arxiv.org/abs/2204.02296)] [[Pytorch Code](https://github.com/facebookresearch/iSDF)] [[Website](https://joeaortiz.github.io/iSDF/)]

---
## Manipulation/RL

* **GNFactor**: "GNFactor: Multi-Task Real Robot Learning with Generalizable Neural Feature Fields", *CoRL 2023 Oral Presentation*. [[Paper/PDF](https://arxiv.org/abs/2308.16891)] [[Code](https://github.com/YanjieZe/GNFactor)] [[Website](https://yanjieze.com/GNFactor/)]


* **D<sup>3</sup>Fields**: "D<sup>3</sup>Fields: Dynamic 3D Descriptor Fields for Zero-Shot Generalizable Robotic Manipulation", *arXiv*. [[Paper](https://arxiv.org/abs/2309.16118)] [[Webpage](https://robopil.github.io/d3fields/)] [[Code](https://github.com/WangYixuan12/d3fields)] [[Video](https://youtu.be/yNkIOwAO3GA)]

* **SNeRL**: "Semantic-aware Neural Radiance Fields for Reinforcement Learning", *ICML, 2023*. [[Paper](https://arxiv.org/pdf/2301.11520.pdf)] [[Webpage](https://sjlee.cc/snerl/)]

* **Ditto**: "Building Digital Twins of Articulated Objects from Interaction", *CVPR, 2022*. [[Paper](https://arxiv.org/abs/2202.08227)] [[Pytorch Code](https://github.com/UT-Austin-RPL/Ditto)] [[Website](https://ut-austin-rpl.github.io/Ditto/)]

* **Relational-NDF**: "SE(3)-Equivariant Relational Rearrangement with Neural Descriptor Fields", *CORL 2022*. [[Paper](https://arxiv.org/pdf/2211.09786.pdf)] [[Pytorch Code](https://github.com/anthonysimeonov/relational_ndf)] [[Website](https://anthonysimeonov.github.io/r-ndf/)]

* **Neural Descriptor Fields**: "SE(3)-Equivariant Object Representations for Manipulation", *arXiv*. [[Paper](https://arxiv.org/abs/2112.05124)] [[Pytorch Code](https://github.com/anthonysimeonov/ndf_robot)] [[Website](https://yilundu.github.io/ndf/)]

* **Evo-NeRF**: "Evolving NeRF for Sequential Robot Grasping of Transparent Objects", *CORL 2022*. [[Paper](https://openreview.net/pdf?id=Bxr45keYrf)]  [[Website](https://sites.google.com/view/evo-nerf)]

* **NeRF-RL**: "Reinforcement Learning with Neural Radiance Fields", *arXiv*. [[Paper](https://dannydriess.github.io/papers/22-driess-NeRF-RL-preprint.pdf)]  [[Website](https://dannydriess.github.io/nerf-rl/)]

* **Neural Motion Fields**: "Encoding Grasp Trajectories as Implicit Value Functions", *RSS 2022*. [[Paper](https://arxiv.org/pdf/2206.14854.pdf)]  [[Video](https://youtu.be/B-pEhT1pi-Q)]

* **Grasping Field**: "Learning Implicit Representations for Human Grasps", *3DV 2020*. [[Paper](https://arxiv.org/pdf/2008.04451.pdf)] [[Pytorch Code](https://github.com/korrawe/grasping_field)] [[Video](https://youtu.be/J8x5i1FCgTQ)]

* **Dex-NeRF**: "Using a Neural Radiance Field to Grasp Transparent Objects", *CORL, 2021*. [[Paper](https://arxiv.org/abs/2110.14217)]  [[Website](https://sites.google.com/view/dex-nerf)]

* **NeRF-Supervision**: "Learning Dense Object Descriptors from Neural Radiance Fields", *ICRA, 2022*. [[Paper](https://arxiv.org/abs/2203.01913)] [[Pytorch Code](https://github.com/yenchenlin/nerf-supervision-public)] [[Website](https://yenchenlin.me/nerf-supervision/)]

* **GIGA**: "Synergies Between Affordance and Geometry: 6-DoF Grasp Detection via Implicit Representations", *RSS, 2021*. [[Paper](https://arxiv.org/abs/2104.01542)] [[Pytorch Code](https://github.com/UT-Austin-RPL/GIGA)] [[Website](https://sites.google.com/view/rpl-giga2021)]

* **NeuralGrasps**: "Learning Implicit Representations for Grasps of Multiple Robotic Hands", *CORL, 2022*. [[Paper](https://arxiv.org/abs/2207.02959)] [[Website](https://irvlutd.github.io/NeuralGrasps/)]

* "Real-time Mapping of Physical Scene Properties with an Autonomous Robot Experimenter", *CORL, 2022*. [[Paper](https://arxiv.org/abs/2210.17325)] [[Website](https://ihaughton.github.io/RobE/)]

* **ObjectFolder**: "A Dataset of Objects with Implicit Visual, Auditory, and Tactile Representations"", *CORL, 2021*. [[Paper](https://arxiv.org/pdf/2109.07991.pdf)] [[Pytorch Code](https://github.com/rhgao/ObjectFolder)] [[Website](https://ai.stanford.edu/~rhgao/objectfolder/)]

* **ObjectFolder 2.0**: "A Multisensory Object Dataset for Sim2Real Transfer"", *CVPR, 2022*. [[Paper](https://arxiv.org/pdf/2204.02389.pdf)] [[Pytorch Code](https://github.com/rhgao/ObjectFolder)] [[Website](https://ai.stanford.edu/~rhgao/objectfolder2.0/)]

* "Template-Based Category-Agnostic Instance Detection for Robotic Manipulation"", *RA-L, 2022*. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9935113)] 

* **NeRF2Real**: "Sim2real Transfer of Vision-guided Bipedal Motion Skills using Neural Radiance Fields"", *arXiv*. [[Paper](https://arxiv.org/pdf/2210.04932.pdf)] [[Website](https://sites.google.com/view/nerf2real/home)]

* **NeRF-Frenemy**: "Co-Opting Adversarial Learning for Autonomy-Directed Co-Design", *RSS Workshop, 2022*. [[Paper](https://imrss2022.github.io/contributions/lewis.pdf)] [[Website](https://progress.eecs.umich.edu/projects/nerf-frenemy/)]

* **CLA-NeRF**: "Category-Level Articulated Neural Radiance Field", *ICRA, 2022*. [[Paper](https://arxiv.org/pdf/2202.00181.pdf)] [[Website](https://weichengtseng.github.io/project_website/icra22/index.html)]

* **VIRDO**: "Visio-tactile Implicit Representations of Deformable Objects", *ICRA, 2022*. [[Paper](https://arxiv.org/pdf/2202.00868.pdf)] [[Website](https://www.mmintlab.com/research/virdo-visio-tactile-implicit-representations-of-deformable-objects/)]

* **VIRDO++:**: "Real-World, Visuo-Tactile Dynamics and Perception of Deformable Objects", *CORL, 2022*. [[Paper](https://arxiv.org/pdf/2210.03701.pdf)] [[Website](https://www.mmintlab.com/virdopp/)]

* **SceneCollisionNet**: "Object Rearrangement Using Learned Implicit Collision Functions", *ICRA, 2021*. [[Paper](https://arxiv.org/pdf/2011.10726.pdf)] [[Website](https://research.nvidia.com/publication/2021-03_object-rearrangement-using-learned-implicit-collision-functions)]

* "RGB-D Local Implicit Function for Depth Completion of Transparent Objects", *CVPR, 2021*. [[Paper](https://arxiv.org/pdf/2104.00622.pdf)] [[Website](https://research.nvidia.com/publication/2021-03_rgb-d-local-implicit-function-depth-completion-transparent-objects)]

* "Learning Models as Functionals of Signed-Distance Fields for Manipulation Planning", *CORL, 2021*. [[Paper](https://openreview.net/pdf?id=FS30JeiGG3h)] [[Video](https://youtu.be/ga8Wlkss7co)]

* **ContactNets**: "Learning Discontinuous Contact Dynamics with Smooth, Implicit Representations", *CORL, 2020*. [[Paper](https://arxiv.org/pdf/2009.11193.pdf)] [[Pytorch Code](https://github.com/DAIRLab/contact-nets)]

* "Learning Implicit Priors for Motion Optimization", *IROS, 2022*. [[Paper](https://arxiv.org/pdf/2204.05369.pdf)] [[Website](https://sites.google.com/view/implicit-priors)]

* **MIRA**: "Mental Imagery for Robotic Affordances", *CORL, 2022*. [[Paper](https://arxiv.org/pdf/2212.06088.pdf)] [[Website](http://yenchenlin.me/mira/)]

* **NiFR**: "Neural Fields for Robotic Object Manipulation from a Single Image", *ICRA, 2023*. [[Paper](https://arxiv.org/pdf/2210.12126.pdf)]

* **NIFT**: "Neural Interaction Field and Template for Object Manipulation", *ICRA, 2023*. [[Paper](https://arxiv.org/pdf/2210.10992.pdf)]

* "Learning 6-DoF Task-oriented Grasp Detection via Implicit Estimation and Visual Affordance", "IROS, 2022". [[Paper](https://arxiv.org/pdf/2210.08537.pdf)]

* **GraspNeRF**: "Multiview-based 6-DoF Grasp Detection for Transparent and Specular Objects Using Generalizable NeRF", *ICRA, 2023*. [[Paper](https://arxiv.org/pdf/2210.06575v1.pdf)]

* **Touching a NeRF**: "Leveraging Neural Radiance Fields for Tactile Sensory Data Generation ", *CORL, 2022*. [[Paper](https://openreview.net/pdf?id=No3mbanRlZJ)]

* **SE(3)-DiffusionFields**: "Learning smooth cost functions for joint grasp and motion optimization through diffusion", *ICRA, 2023*. [[Paper](https://arxiv.org/pdf/2209.03855.pdf)] [[Pytorch Code](https://github.com/TheCamusean/grasp_diffusion)]

* **Equivariant Descriptor Fields**: "SE(3)-Equivariant Energy-Based Models for End-to-End Visual Robotic Manipulation Learning ", *ICLR, 2023*. [[Paper](https://openreview.net/pdf?id=dnjZSPGmY5O)] 

* **KP-NERF**: "Dynamical Scene Representation and Control with Keypoint-Conditioned Neural Radiance Field", *CASE, 2022*. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9926555)]

* **ACID**: "Action-Conditional Implicit Visual Dynamics for Deformable Object Manipulation", *RSS, 2022*. [[Paper](https://arxiv.org/pdf/2203.06856.pdf)] [[Pytorch Code](https://github.com/NVlabs/ACID)]

* **TRITON**: "Neural Neural Textures Make Sim2Real Consistent", *CORL, 2022*. [[Paper](https://arxiv.org/pdf/2206.13500.pdf)] [[Website](https://tritonpaper.github.io/)] [[Pytorch Code](https://github.com/TritonPaper/TRITON)]

* "Perceiving Unseen 3D Objects by Poking the Objects", *ICRA, 2023*. [[Paper](https://arxiv.org/pdf/2302.13375.pdf)] [[Website](https://zju3dv.github.io/poking_perception/)] [[Pytorch Code](https://github.com/zju3dv/poking_perception)]

* "Feature-Realistic Neural Fusion for Real-Time, Open Set Scene Understanding", *ICRA, 2023*. [[Paper](https://arxiv.org/pdf/2210.03043.pdf)] [[Website](https://makezur.github.io/FeatureRealisticFusion/)]

* **CGF**: "Learning Continuous Grasping Function with a Dexterous Hand from Human Demonstrations", *arXiv*. [[Paper](https://arxiv.org/pdf/2203.06856.pdf)] [[Website](https://jianglongye.com/cgf/)]

* **NGDF**: "Neural Grasp Distance Fields for Robot Manipulation", *arXiv*. [[Paper](https://arxiv.org/pdf/2211.02647.pdf)] [[Website](https://sites.google.com/view/neural-grasp-distance-fields?pli=1)] [[Pytorch Code](https://github.com/facebookresearch/NGDF/)] 

* **NCF**: "Neural Contact Fields: Tracking Extrinsic Contact with Tactile Sensing", *arXiv*. [[Paper](https://arxiv.org/pdf/2210.09297.pdf)] [[Pytorch Code](https://github.com/carolinahiguera/NCF)] 

* **SPARTN**: "NeRF in the Palm of Your Hand: Corrective Augmentation for Robotics via Novel-View Synthesis", *arXiv*. [[Paper](https://arxiv.org/pdf/2301.08556.pdf)] 

* "RGB-Only Reconstruction of Tabletop Scenes for Collision-Free Manipulator Control", *arXiv*. [[Paper](https://arxiv.org/pdf/2210.11668v1.pdf)] [[Website](https://sites.google.com/nvidia.com/ngp-mpc/)]
  
* "Grasp Transfer based on Self-Aligning Implicit Representations of Local Surfaces", *RAL, 2023*. [[Paper](https://arxiv.org/pdf/2308.07807)] [[Code](https://github.com/Fzaero/Grasp-Transfer)] [[Website](https://fzaero.github.io/GraspTransfer/)]

* "A Real2Sim2Real Method for Robust Object Grasping with Neural Surface Reconstruction", *arXiv*. [[Paper](https://arxiv.org/pdf/2210.02685.pdf)] [[Video](https://www.youtube.com/watch?v=TkvAKLsxkSc)]

* **EndoNeRF**: "Neural Rendering for Stereo 3D Reconstruction of Deformable Tissues in Robotic Surgery", *MICCAI, 2022*. [[Paper](https://arxiv.org/pdf/2206.15255.pdf)] [[Pytorch Code](https://github.com/med-air/EndoNeRF)]

* **NFMP**: "Neural Field Movement Primitives for Joint Modelling of Scenes and Motions", *IROS, 2023*. [[Paper](https://arxiv.org/pdf/2308.05040)] [[Code](https://github.com/Fzaero/Neural-Field-Movement-Primitives)] [[Website](https://fzaero.github.io/NFMP/)]

---
## Object Reconstruction

* **NTO3D**: "Neural Target Object 3D Reconstruction with Segment Anything", *CVPR, 2024*. [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Wei_NTO3D_Neural_Target_Object_3D_Reconstruction_with_Segment_Anything_CVPR_2024_paper.pdf)] [[Code](https://github.com/ucwxb/NTO3D)]

* "Self-supervised Neural Articulated Shape and Appearance Models", *CVPR, 2022*. [[Paper](https://arxiv.org/pdf/2205.08525.pdf)] [[Website](https://weify627.github.io/nasam/)]

* **NeuS**: "Learning Neural Implicit Surfacesby Volume Rendering for Multi-view Reconstruction", *Neurips, 2021*. [[Paper](https://arxiv.org/pdf/2106.10689.pdf)] [[Website](https://lingjie0206.github.io/papers/NeuS/)]

* **VolSDF**: "Volume Rendering of Neural Implicit Surfaces", *Neurips, 2021*. [[Paper](https://arxiv.org/pdf/2106.12052.pdf)] [[Pytorch Code](https://github.com/lioryariv/volsdf)]

* **UNISURF**: "Unifying Neural Implicit Surfaces and Radiance Fields for Multi-View Reconstruction", *ICCV, 2021*. [[Paper](https://arxiv.org/pdf/2104.10078.pdf)] [[Website](https://moechsle.github.io/unisurf/)] [[Pytorch Code](https://github.com/autonomousvision/unisurf)]

* **ObjectSDF**: "Object-Compositional Neural Implicit Surfaces", *ECCV, 2022*. [[Paper](https://arxiv.org/pdf/2207.09686.pdf)] [[Website](https://wuqianyi.top/objectsdf/)] [[Pytorch Code](https://github.com/QianyiWu/objsdf)]

* **IDR**: "Multiview Neural Surface Reconstruction by Disentangling Geometry and Appearance", *Neurips, 2020*. [[Paper](https://arxiv.org/pdf/2003.09852.pdf)] [[Website](https://lioryariv.github.io/idr/)] [[Pytorch Code](https://github.com/lioryariv/idr)]

* **DVR**: "Differentiable Volumetric Rendering: Learning Implicit 3D Representations without 3D Supervision", *CVPR, 2020*. [[Paper](https://arxiv.org/pdf/1912.07372.pdf)] [[Pytorch Code](https://github.com/autonomousvision/differentiable_volumetric_rendering)]

* **A-SDF**: "Learning Disentangled Signed Distance Functions for Articulated Shape Representation", *ICCV, 2021*. [[Paper](https://arxiv.org/pdf/2104.07645.pdf)] [[Pytorch Code](https://github.com/JitengMu/A-SDF)]

* **CodeNeRF**: "Disentangled Neural Radiance Fields for Object Categories", *ICCV, 2021*. [[Paper](https://arxiv.org/pdf/2109.01750.pdf)] [[Pytorch Code](https://github.com/wbjang/code-nerf)]

* **DeepSDF**: " Learning Continuous Signed Distance Functions for Shape Representation", *CVPR, 2019*. [[Paper](
https://arxiv.org/pdf/1901.05103.pdf)] [[Pytorch Code](https://github.com/facebookresearch/DeepSDF)]

* **Occupancy networks**: " Learning 3d reconstruction in function space", *CVPR, 2019*. [[Paper](https://arxiv.org/pdf/1812.03828.pdf)] [[Website](https://avg.is.mpg.de/publications/occupancy-networks)]

---
## Physics

* "Inferring Hybrid Neural Fluid Fields from Videos", *Neurips, 2023*. [[Paper](https://arxiv.org/pdf/2312.06561.pdf)] [[Pytorch Code](https://github.com/y-zheng18/HyFluid)] [[Website](https://kovenyu.com/hyfluid/)]

* **DANOs**: "Differentiable Physics Simulation of Dynamics-Augmented Neural Objects", *arXiv*. [[Paper](https://arxiv.org/abs/2210.09420)] [[Video](https://youtu.be/Md0PM-wv_Xg)]

* **PAC-NeRF**: "Physics Augmented Continuum Neural Radiance Fields for Geometry-Agnostic System Identification", *ICLR, 23*. [[Paper](https://openreview.net/pdf?id=tVkrbkz42vc)] [[Website](https://sites.google.com/view/PAC-NeRF)] [[Video](https://youtu.be/Md0PM-wv_Xg)] [[Pytorch Code](https://github.com/xuan-li/PAC-NeRF)]

* **NeuPhysics**: "Editable Neural Geometry and Physics from Monocular Videos", *Neurips, 2022*. [[Paper](https://arxiv.org/abs/2210.12352)] [[Pytorch Code](https://github.com/gaoalexander/neuphysics)] [[Website](https://ylqiao.net/publication/2022nerf/)]

* **NeRF-ysics**: "A Differentiable Pipeline for Enriching NeRF-Represented Objects with Dynamical Properties", *ICRA Workshop, 2022*. [[Paper](https://neural-implicit-workshop.stanford.edu/assets/pdf/lecleach.pdf)]

* "Neural Implicit Representations for Physical Parameter Inference from a Single Video", *WACV, 2023*. [[Paper](https://arxiv.org/pdf/2204.14030.pdf)] [[Pytorch Code](https://github.com/florianHofherr/PhysParamInference)] [[Website](https://florianhofherr.github.io/phys-param-inference/)]

* **NeuroFluid**: "Fluid Dynamics Grounding with Particle-Driven Neural Radiance Fields", *ICML, 2022*. [[Paper](https://proceedings.mlr.press/v162/guan22a/guan22a.pdf)] [[Pytorch Code](https://github.com/syguan96/NeuroFluid)]

* "Physics Informed Neural Fields for Smoke Reconstruction with Sparse Data", *SIGGRAPH, 2022*. [[Paper](https://rachelcmy.github.io/pinf_smoke/data/paper.pdf)] [[Pytorch Code](https://github.com/RachelCmy/pinf_smoke)][[Website](https://rachelcmy.github.io/pinf_smoke/)] 

---
## Planning/Navigation
* **NeRFlow**: "Neural Radiance Flow for 4D View Synthesis and Video Processing", *ICCV, 2021*. [[Paper](https://arxiv.org/abs/2012.09790)] [[Pytorch Code](https://github.com/yilundu/nerflow)] [[Website](https://yilundu.github.io/nerflow/)] 

* **NeRF-Navigation**: "Vision-Only Robot Navigation in a Neural Radiance World", *ICRA, 2022*. [[Paper](https://mikh3x4.github.io/nerf-navigation/assets/NeRF_Navigation.pdf)] [[Pytorch Code](https://github.com/mikh3x4/nerf-navigation)] [[Website](https://mikh3x4.github.io/nerf-navigation/)] 

* **RNR-Map**: "Renderable Neural Radiance Map for Visual Navigation", *CVPR, 2023*. [[Paper](https://arxiv.org/pdf/2303.00304.pdf)] [[Website](https://obin-hero.github.io/RNRmap/)] 

* "Uncertainty Guided Policy for Active Robotic 3D Reconstruction using Neural Radiance Fields", *RAL, 2022*. [[Paper (https://arxiv.org/pdf/2209.08409.pdf)] [[Website](https://www.vis.xyz/pub/robotic-3d-scan-with-nerf/)] 

* **NeRF-dy**: "3D Neural Scene Representations for Visuomotor Control", *CORL, 2021*. [[Paper](https://arxiv.org/abs/2107.04004)] [[Website](https://3d-representation-learning.github.io/nerf-dy/)] 

* **CompNeRFdyn**: "Learning Multi-Object Dynamics with Compositional Neural Radiance Fields", *arXiv*. [[Paper](https://arxiv.org/pdf/2202.11855.pdf)] [[Website](https://dannydriess.github.io/compnerfdyn/)] 

* **PIFO**: "Deep Visual Constraints: Neural Implicit Models for Manipulation Planning from Visual Input", *arXiv*. [[Paper](https://arxiv.org/pdf/2112.04812.pdf)] [[Website](https://sites.google.com/view/deep-visual-constraints)] 

* "Learning Continuous Environment Fields via Implicit Functions", *ICLR, 2022*. [[Paper](https://arxiv.org/pdf/2111.13997.pdf)] [[Website](https://research.nvidia.com/publication/2022-04_learning-continuous-environment-fields-implicit-functions)] 

* "Learning Barrier Functions with Memory for Robust Safe Navigation", *RA-L, 2021*. [[Paper](https://arxiv.org/pdf/2011.01899.pdf)]

* **RedSDF**: "Regularized Deep Signed Distance Fields for Reactive Motion Generation", *IROS, 2022*. [[Paper](https://arxiv.org/abs/2203.04739)] [[Website](https://irosalab.com/2022/02/28/redsdf/)] 

* **AutoNeRF**: "Training Implicit Scene Representations with Autonomous Agents", *arxiv*. [[Paper](https://arxiv.org/pdf/2304.11241.pdf)] [[Website](https://pierremarza.github.io/projects/autonerf/)]

* **ESDF**: "Sampling-free obstacle gradients and reactive planning in Neural Radiance Fields", *arXiv*. [[Paper](https://arxiv.org/abs/2205.01389)]

* **CLIP-Fields**: "Open-label semantic navigation with pre-trained VLMs and language models", *arxiv*. [[Paper](https://arxiv.org/abs/2210.05663)] [[Pytorch Code and Tutorials](https://github.com/notmahi/clip-fields)] [[Website](https://mahis.life/clip-fields/)]

* **Voxfield**: Non-Projective Signed Distance Fields for Online Planning and 3D Reconstruction", *IROS, 2022*. [[Paper](https://www.ipb.uni-bonn.de/wp-content/papercite-data/pdf/pan2022iros.pdf)] [[Pytorch Code](https://github.com/VIS4ROB-lab/voxfield)]

* **Voxblox**: Incremental 3D Euclidean Signed Distance Fields for On-Board MAV Planning, *IROS, 2017*. [[Paper](https://arxiv.org/pdf/1611.03631.pdf)]

* **NFOMP**: Neural Field for Optimal Motion Planner of Differential Drive Robots With Nonholonomic Constraints", *RA-L, 2022*. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9851532)] [[Video](https://youtu.be/beEfEOmxJfM)]

* **CATNIPS**: Collision Avoidance Through Neural Implicit Probabilistic Scenes", *arXiv*. [[Paper](https://arxiv.org/pdf/2302.12931.pdf)] 

* **MeSLAM**: Memory Efficient SLAM based on Neural Fields, *IEEE SMC, 2022*. [[Paper](https://arxiv.org/pdf/2209.09357.pdf)] 

* **NTFields**: "Neural Time Fields for Physics-Informed Robot Motion Planning", *ICLR, 2023*. [[Paper](https://arxiv.org/pdf/2210.00120.pdf)]

* "Real-time Semantic 3D Reconstruction for High-Touch Surface Recognition for Robotic Disinfection", *IROS, 2022*. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9981300)] 

* **NeurAR**: "Neural Uncertainty for Autonomous 3D Reconstruction", *RA-L, 2023*. [[Paper](https://arxiv.org/pdf/2207.10985.pdf)] 

* **IR-MCL**: "Implicit Representation-Based Online Global Localization", *RA-L, 2023*. [[Paper](https://arxiv.org/pdf/2210.03113.pdf)] [[Pytorch Code](https://github.com/PRBonn/ir-mcl)] 

* **360Roam**: "Real-Time Indoor Roaming Using Geometry-Aware 360◦ Radiance Fields", *arXiv*. [[Paper](https://arxiv.org/pdf/2208.02705.pdf)] [[Pytorch Code](https://github.com/PRBonn/ir-mcl)] 

* "Learning Deep SDF Maps Online for Robot Navigation and Exploration", *arXiv*. [[Paper](https://arxiv.org/pdf/2207.10782.pdf)]

* **DroNeRF**: Real-time Multi-agent Drone Pose Optimization for Computing Neural Radiance Fields. [[Paper](https://arxiv.org/pdf/2303.04322.pdf)]

* "Enforcing safety for vision-based controllers via Control Barrier Functions and Neural Radiance Fields", *arXiv*. [[Paper](https://arxiv.org/pdf/2209.12266.pdf)]

* "Full-Body Visual Self-Modeling of Robot Morphologies", *arXiv*. [[Paper](https://arxiv.org/abs/2205.01389)] [[Website](https://huajianup.github.io/research/360Roam/)]

* "Efficient View Path Planning for Autonomous Implicit Reconstruction", *arxiv*. [[Paper](https://arxiv.org/abs/2210.05129)]

* "Multi-Object Navigation with dynamically learned neural implicit representations", *arxiv*. [[Paper](https://arxiv.org/pdf/2209.13159.pdf)] [[Website](https://small-zeng.github.io/EVPP/)]
