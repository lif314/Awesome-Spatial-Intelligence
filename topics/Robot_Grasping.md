# Robot Grasping

> **Grasping** focuses on the "stable holding" of an object, ensuring that the robot can securely grasp it without slipping or damaging it.

**Plane Grasping**

- [Plane Grasping](#Plane-Grasping)

**6DoF Grasping**

- [Point Cloud](#Point-Cloud)
- [TSDF](#TSDF)
- [NeRF](#NeRF)
- [3DGS](#3DGS)

## Plane Grasping

- [``CNN``] **GG-CNN**: Closing the Loop for Robotic Grasping: A Real-time, Generative Grasp Synthesis Approach, *RSS 2018*.  [[Paper](https://arxiv.org/abs/1804.05172)] [[Code](https://github.com/dougsm/ggcnn)] [[ROS_Franka Code](https://github.com/dougsm/mvp_grasp)] [[ Kinva Mico Arm Code](https://github.com/dougsm/ggcnn_kinova_grasping)] ![Stars](https://img.shields.io/github/stars/dougsm/ggcnn?style=social)
- [``CNN``] **GR-CNN**: Antipodal Robotic Grasping using Generative Residual Convolutional Neural Network, *IROS 2020*. [[Paper](https://arxiv.org/abs/1909.04810)] [[Code](https://github.com/skumra/robotic-grasping)] ![Stars](https://img.shields.io/github/stars/skumra/robotic-grasping?style=social)
- [Benchmark: Robotic Grasping on Cornell Grasp Dataset](https://paperswithcode.com/sota/robotic-grasping-on-cornell-grasp-dataset-1)
- [Benchmark: Robotic Grasping on Jacquard dataset](https://paperswithcode.com/sota/robotic-grasping-on-jacquard-dataset)
- [``Diffusion Dataset``] **LGD**: Language-driven Grasp Detection, *CVPR 2024*. [[Paper](https://arxiv.org/abs/2406.09489)] [[Website](https://airvlab.github.io/grasp-anything/)] [[Code](https://github.com/Fsoft-AIC/LGD)] ![Stars](https://img.shields.io/github/stars/Fsoft-AIC/LGD?style=social)
- [Benchmark: Grasp-Anything Dataset](https://paperswithcode.com/dataset/grasp-anything)

## Point Cloud

- **GPD**: Grasp Pose Detection in Point Clouds, *IJRR 2017*. [[Paper](https://arxiv.org/abs/1706.09911)] [[Code (C++)](https://github.com/atenpas/gpd)]  ![Stars](https://img.shields.io/github/stars/atenpas/gpd?style=social)

- **MVP-Grasp**: Multi-Viewpoint Picking, *ICRA 2019*. [[Paper](https://arxiv.org/abs/1809.08564)] [[Code](https://github.com/dougsm/mvp_grasp)] [[Panda Camera Mount.stl](https://github.com/dougsm/mvp_grasp/tree/master/cad)]  ![Stars](https://img.shields.io/github/stars/dougsm/mvp_grasp?style=social)
- **PointNetGPD**: Detecting Grasp Configurations from Point Sets, *ICRA 2019*. [[Paper](https://arxiv.org/abs/1809.06267)] [[Website](https://lianghongzhuo.github.io/PointNetGPD/)] [[Code](https://github.com/lianghongzhuo/PointNetGPD)]  ![Stars](https://img.shields.io/github/stars/lianghongzhuo/PointNetGPD?style=social)
- **6-DOF GraspNet**: Variational Grasp Generation for Object Manipulation, *ICCV 2019*. [[Paper](https://arxiv.org/abs/1905.10520)] [[Code (tf)](https://github.com/NVlabs/6dof-graspnet)] [[Code (pytorch)](https://github.com/jsll/pytorch_6dof-graspnet)] ![Stars](https://img.shields.io/github/stars/NVlabs/6dof-graspnet?style=social)
- **GraspNet-1Billion**: A Large-Scale Benchmark for General Object Grasping, *CVPR 2020*. [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fang_GraspNet-1Billion_A_Large-Scale_Benchmark_for_General_Object_Grasping_CVPR_2020_paper.pdf)] [[Website](https://graspnet.net/)] [[Code](https://github.com/graspnet/graspnet-baseline)] ![Stars](https://img.shields.io/github/stars/graspnet/graspnet-baseline?style=social)
- **Contact-GraspNet**: Efficient 6-DoF Grasp Generation in Cluttered Scenes, *ICRA 2021*. [[Paper](https://arxiv.org/abs/2103.14127)] [[Website](https://research.nvidia.com/publication/2021-03_contact-graspnet-efficient-6-dof-grasp-generation-cluttered-scenes)] [[Code](https://github.com/NVlabs/contact_graspnet)] [[Code (pytorch)](https://github.com/elchun/contact_graspnet_pytorch)] ![Stars](https://img.shields.io/github/stars/NVlabs/contact_graspnet?style=social)
- **Graspness**: Graspness Discovery in Clutters for Fast and Accurate Grasp Detection, *ICCV 2021*. [[Paper](https://arxiv.org/abs/2406.11142)] [[Code](https://github.com/graspnet/anygrasp_sdk)] [[Code (unofficial)](https://github.com/rhett-chen/graspness_implementation)] ![Stars](https://img.shields.io/github/stars/rhett-chen/graspness_implementation?style=social)

## TSDF

- :fire: **VGN**: Volumetric Grasping Network: Real-time 6 DOF Grasp Detection in Clutter, *CoRL 2020*. [[Paper](https://arxiv.org/abs/2101.01132)] [[Code](https://github.com/ethz-asl/vgn)]
- 

## NeRF

- **LERF-TOGO**: Language Embedded Radiance Fields for Zero-Shot Task-Oriented Grasping, *CoRL 2023 (Best Paper Finalist)*. [[Paper](https://arxiv.org/abs/2309.07970)] [[Website](https://lerftogo.github.io/desktop.html)] [[Code](https://github.com/lerftogo/lerftogo)]
- **F3RM**: Distilled Feature Fields Enable Few-Shot Language-Guided Manipulation, *[CoRL 2023 (Best Paper)](https://www.corl2023.org/)*. [[Paper](https://arxiv.org/abs/2308.07931)] [[Website](https://f3rm.github.io/)] [[Code](https://github.com/f3rm/f3rm)]
- **SparseDFF**: Sparse-View Feature Distillation for One-Shot Dexterous Manipulation, *ICLR 2024*. [[Paper](https://arxiv.org/abs/2310.16838)] [[Website](https://helloqxwang.github.io/SparseDFF/)] [[Code](https://github.com/helloqxwang/SparseDFF)]
- Learning Generalizable Feature Fields for Mobile Manipulation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2403.07563)] [[Website](https://geff-b1.github.io/)]
- **D$^3$Fields**: Dynamic 3D Descriptor Fields for Zero-Shot Generalizable Rearrangement, *CoRL 2024 (Oral)*. [[Paper](https://openreview.net/forum?id=Uaaj4MaVIQ)] [[Website](https://robopil.github.io/d3fields/)] [[Code](https://github.com/WangYixuan12/d3fields)]
- **GenDP**: 3D Semantic Fields for Category-Level Generalizable Diffusion Policy, *CoRL 2024*. [[Paper](https://arxiv.org/abs/2410.17488)] [[Website](https://robopil.github.io/GenDP/)] [[Code](https://github.com/WangYixuan12/gendp)]
- :fire: **NeuGraspNet**: Learning Any-View 6DoF Robotic Grasping in Cluttered Scenes via Neural Surface Rendering, *RSS 2024*. [[Paper](https://arxiv.org/abs/2306.07392)] [[Website](https://sites.google.com/view/neugraspnet)] [[Code](https://github.com/pearl-robot-lab/neugraspnet)]

- **GNFactor**: "GNFactor: Multi-Task Real Robot Learning with Generalizable Neural Feature Fields", *CoRL 2023 Oral*. [[Paper/PDF](https://arxiv.org/abs/2308.16891)] [[Code](https://github.com/YanjieZe/GNFactor)] [[Website](https://yanjieze.com/GNFactor/)]


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
* **CLIP-Fields**: Open-label semantic navigation with pre-trained VLMs and language models, *RSS 2023*. [[Paper](https://arxiv.org/abs/2210.05663)] [[Code](https://github.com/notmahi/clip-fields)] [[Website](https://mahis.life/clip-fields/)]

---

## 3DGS

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



 

