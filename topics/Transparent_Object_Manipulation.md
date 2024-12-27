# Transparent Object Manipulation

<details>
  <summary>[Challenges and Applications]</summary>

```
- Challenges:
    - Visual Perception and Detection
    - Depth Perception
    - Refraction and Perspective Distortion
    - Grasping and Manipulation
    - Sensor Errors and Uncertainty
- Applications:
    - Medical Robotics
    - Robotic Surgery and Medical Assistance
    - Robotic Cleaning Systems
```
</details>


----



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



---

## Survey

- Robotic Perception of Transparent Objects: A Review, *TAI 2024*. [[Paper](https://ieeexplore.ieee.org/abstract/document/10288041)]



---

## Datasets

- **ClearPose**: Large-scale Transparent Object Dataset and Benchmark, *ECCV 2022*. [[Paper](https://arxiv.org/abs/2203.03890)] [[Code](https://github.com/opipari/ClearPose)]

- **TransCG**: A Large-Scale Real-World Dataset for Transparent Object Depth Completion and A Grasping Baseline, *RAL 2022 & ICRA 2023*. [[Paper](https://arxiv.org/abs/2202.08471)] [[Website](https://graspnet.net/transcg)] [[Code](https://github.com/galaxies99/transcg)] [[Cewu Lu](https://www.mvig.org/)]
- **TRansPose**: Large-Scale Multispectral Dataset for Transparent Object, *IJRR 2023*. [[Paper](https://arxiv.org/abs/2307.05016)] [[Website](https://sites.google.com/view/transpose-dataset)]



---

## Robotic Grasping-Manipulation

- **ClearGrasp**: 3D Shape Estimation of Transparent Objects for Manipulation, *ICRA 2020*. [[Paper](https://arxiv.org/abs/1910.02550)] [[Website](https://sites.google.com/view/cleargrasp)] [[Code](https://github.com/Shreeyak/cleargrasp)]
- **Dex-NeRF**: Using a Neural Radiance field to Grasp Transparent Objects, *CoRL 2021*. [[Paper](https://arxiv.org/abs/2110.14217)] [[Website](https://sites.google.com/view/dex-nerf)] [[Datasets](https://github.com/BerkeleyAutomation/dex-nerf-datasets)] [[Code](https://github.com/BerkeleyAutomation/dex-nerf-datasets/releases/tag/corl2021)] [[Unofficial Code](https://github.com/salykova/instant-DexNerf)]
- **Evo-NeRF**: Evolving NeRF for Sequential Robot Grasping of Transparent Objects, *CoRL 2022*. [[Paper](https://openreview.net/forum?id=Bxr45keYrf)] [[Website](https://sites.google.com/view/evo-nerf)] 
- **GraspNeRF**: Multiview-based 6-DoF Grasp Detection for Transparent and Specular Objects Using Generalizable NeRF, *ICRA 2023*. [[Paper](https://arxiv.org/abs/2210.06575)] [[Website](https://pku-epic.github.io/GraspNeRF/)] [[Code](https://github.com/PKU-EPIC/GraspNeRF)]
- **NFL**: Normal Field Learning for 6-DoF Grasping of Transparent Objects, *R-AL 2024*. [[Paper](https://3d.snu.ac.kr/assets/NFL/NFL_RAL_final.pdf)] [[Website](https://3d.snu.ac.kr/publications/NFL)] [[Code](https://github.com/twjhlee/Normal-Field-Learning)]
- **Residual-NeRF**: Learning Residual NeRFs for Transparent Object Manipulation, *ICRA 2024*. [[Paper](https://arxiv.org/abs/2405.06181v1)] [[Website](https://residual-nerf.github.io/)] [[Code](https://github.com/momentum-robotics-lab/residual-nerf)] [[Data](https://drive.google.com/drive/folders/15r_mLt8MD5-AuYfoWCLy72hD27-tHA2N?usp=sharing)]
- **DREDS**: Domain Randomization-Enhanced Depth Simulation and Restoration for Perceiving and Grasping Specular and Transparent Objects, *ECCV 2020*. [[Paper](https://arxiv.org/abs/2208.03792)] [[Website](https://pku-epic.github.io/DREDS/)] [[Code](https://github.com/PKU-EPIC/DREDS)] [[He Wang, PKU-EPIC](https://hughw19.github.io/)]
- **ASGrasp**: Generalizable Transparent Object Reconstruction and 6-DoF Grasp Detection from RGB-D Active Stereo Camera, *ICRA 2024*. [[Paper](https://arxiv.org/abs/2405.05648)] [[Website](https://pku-epic.github.io/ASGrasp/)] [[Code](https://github.com/jun7-shi/ASGrasp)]
- **TransNet**: Transparent Object Manipulation Through Category-Level Pose Estimation, *ECCVW 2022*. [[Paper](https://arxiv.org/abs/2208.10002)] [[Website](https://progress.eecs.umich.edu/projects/transnet/)]
- D^3RoMa: Disparity Diffusion-based Depth Sensing for Material-Agnostic Robotic Manipulation, *CoRL 2024*. [[Paper](https://arxiv.org/abs/2409.14365)] [[Website](https://pku-epic.github.io/D3RoMa/)] [[Code](https://github.com/songlin/d3roma)]
- 

---

## Visual Tactile

- Visual–Tactile Fusion for Transparent Object Grasping in Complex Backgrounds, *T-RO 2023*. [[Paper](https://arxiv.org/abs/2211.16693)] [[Website](https://sites.google.com/view/visual-tactilefusion)] [[Code](https://github.com/Shoujie1998/Visual-tactile-fusion)] [[Linqi Ye, THU-SHU](https://linqi-ye.github.io/)]
- **TransTouch**: Learning Transparent Objects Depth Sensing Through Sparse Touches, *IROS 2023*. [[Paper](https://arxiv.org/abs/2309.09427)] [[Code](https://github.com/ritsu-a/transtouch)]



---

##  Pose Estimation

- **KeyPose**: Multi-View 3D Labeling and Keypoint Estimation for Transparent Objects, *CVPR 2020*. [[Paper](https://arxiv.org/abs/1912.02805)] [[Website](https://sites.google.com/view/keypose?pli=1)] [[Code](https://github.com/google-research/google-research/tree/master/keypose)]
- **StereoPose**: Category-Level 6D Transparent Object Pose Estimation from Stereo Images via Back-View NOCS, *ICRA 2023*. [[Paper](https://arxiv.org/abs/2211.01644)] [[Webaite](https://appsrv.cse.cuhk.edu.hk/~kaichen/stereopose.html)] [[Code](https://github.com/ck-kai/StereoPose)]



---

## Simulation

- Close the Optical Sensing Domain Gap by Physics-Grounded Active Stereo Sensor Simulation, *T-RO 2023*. [[Paper](https://arxiv.org/abs/2201.11924)] [[Website](https://angli66.github.io/active-sensor-sim/)] [[Code](https://github.com/haosulab/SAPIEN)] [University of California]
- 

---

## Depth Completion

- **Implicit Depth**: RGB-D Local Implicit Function for Depth Completion of Transparent Objects, *CVPR 2021*. [[Paper](https://arxiv.org/abs/2104.00622)] [[Website](https://research.nvidia.com/publication/2021-03_rgb-d-local-implicit-function-depth-completion-transparent-objects)] [[Code](https://github.com/NVlabs/implicit_depth)]

- **FDCT**: Fast Depth Completion for Transparent Objects, *R-AL 2023*. [[Paper](https://arxiv.org/abs/2307.12274)] [[Code](https://github.com/Nonmy/FDCT)]
- **TDCNet**: Transparent Objects Depth Completion with CNN-Transformer Dual-Branch Parallel Network, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2412.14961)] [[Code](https://github.com/XianghuiFan/TDCNet)] [[Website](https://graspnet.net/transcg)] [[Cewu Lu](https://graspnet.net/index.html)]
- **Depth4ToM**: Learning Depth Estimation for Transparent and Mirror Surfaces, *ICCV 2023*. [[Paper](https://arxiv.org/abs/2307.15052)] [[Website](https://cvlab-unibo.github.io/Depth4ToM/)] [[Code](https://github.com/CVLAB-Unibo/Depth4ToM-code)]

- **Seeing Glass**: Joint Point-Cloud and Depth Completion for Transparent Objects, *CoRL 2021*. [[Paper](https://arxiv.org/abs/2110.00087)] [[Website](https://www.pair.toronto.edu/TranspareNet/)] [[Code](https://github.com/pairlab/TranspareNet)]
- **ActiveZero**: Mixed Domain Learning for Active Stereovision with Zero Annotation, *CVPR 2022*. [[Paper](https://arxiv.org/abs/2112.02772)] [[Code](https://github.com/haosulab/ActiveZero)]
- **ActiveZero++**: Mixed Domain Learning Stereo and Confidence-based Depth Completion with Zero Annotation, *TPAMI 2023*. [[Paper](https://ieeexplore.ieee.org/document/10219021)] [[Code](https://github.com/jaycions/activezero2_official)]
- Consistent Depth Prediction for Transparent Object Reconstruction from RGB-D Camera, *ICCV 2023*. [[Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Cai_Consistent_Depth_Prediction_for_Transparent_Object_Reconstruction_from_RGB-D_Camera_ICCV_2023_paper.html)]
- Monocular Depth Estimation for Glass Walls with Context: A New Dataset and Method, *TPAMI 2023*. [[Paper](https://ieeexplore.ieee.org/document/10230851)] [[Code](https://github.com/ViktorLiang/GW-Depth)] 
- **TODE-Trans**: Transparent Object Depth Estimation with Transformer, *ICRA 2023*. [[Paper](https://arxiv.org/abs/2209.08455)] [[Code](https://github.com/yuchendoudou/TODE)]
- **ClearDepth**: Enhanced Stereo Perception of Transparent Objects for Robotic Manipulation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2409.08926)] [[Website](https://sites.google.com/view/cleardepth/)]

---

## 3D Reconstruction

- **DRT**: Differentiable Refraction-Tracing for Mesh Reconstruction of Transparent Objects, *SIGGRAPH Asia 2020*. [[Paper](https://arxiv.org/abs/2009.09144)] [[Website](https://vcc.tech/research/2020/DRT)] [[Code](https://github.com/lvjiahui/DRT)]
- Eikonal Fields for Refractive Novel-View Synthesis, *SIGGRAPH 2022*. [[Paper](https://arxiv.org/abs/2202.00948)] [[Website](https://eikonalfield.mpi-inf.mpg.de/)] [[Code](https://github.com/m-bemana/eikonalfield)]
- Deep Polarization Cues for Single-shot Shape and Subsurface Scattering Estimation, *ECCV 2024*. [[Paper](https://arxiv.org/abs/2407.08149)] [[Code](https://github.com/ligoudaner377/polarized_inverse_scattering)]
- **NeTO**: Neural Reconstruction of Transparent Objects with Self-Occlusion Aware Refraction-Tracing, *ICCV 2023*. [[Paper](https://www.xxlong.site/NeTO/ARXIV_NeTO.pdf)] [[Website](https://www.xxlong.site/NeTO/)] [[Code](https://github.com/xxlong0/NeTO)]
- **NEMTO**: Neural Environment Matting for Novel View and Relighting Synthesis of Transparent Objects, *ICCV 2023*. [[Paper](https://arxiv.org/abs/2303.11963)] [[Website](https://ivrl.github.io/NEMTO/)] [[Code](https://github.com/IVRL/NEMTO)]
- Hybrid Mesh-neural Representation for 3D Transparent Object Reconstruction, *CVMJ 2023*. [[Paper](https://arxiv.org/abs/2203.12613v3)] [[Code](https://github.com/superxjm/HybridTransparentRecon)]
- **TransPIR**: Polarimetric Inverse Rendering for Transparent Shapes Reconstruction, *TOM 2024*. [[Paper](https://arxiv.org/pdf/2208.11836.pdf)] [[Code](https://github.com/shaomq2187/TransPIR)]
- **TransSfP**: Transparent Shape from a Single View Polarization Image, *ICCV 2023*. [[Paper](https://arxiv.org/abs/2204.06331)] [[Code](https://github.com/shaomq2187/TransSfP)]
- **Touch-GS**: Visual-Tactile Supervised 3D Gaussian Splatting, *IROS 2024*. [[Paper](https://arxiv.org/abs/2403.09875)] [[Website](https://arm.stanford.edu/touch-gs)] [[Code](https://github.com/armlabstanford/Touch-GS)]
- **FusionSense**: Bridging Common Sense, Vision, and Touch for Robust Sparse-View Reconstruction, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2410.08282)] [[Website](https://ai4ce.github.io/FusionSense/)] [[Code](https://github.com/ai4ce/FusionSense)]
- **Snap-it, Tap-it, Splat-it**: Tactile-Informed 3D Gaussian Splatting for Reconstructing Challenging Surfaces, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2403.20275)]
- Transparent Object Reconstruction in 3D Gaussian Splatting with RGB-to-TIR Translation, *MLVU Projects (Spring 2024)*. [[Paper](http://viplab.snu.ac.kr/viplab/courses/mlvu_2024_1/projects/07.pdf)] [[Talk](https://www.youtube.com/watch?v=mqFSw7z5JPk)]
- **NU-NeRF**: Neural Reconstruction of Nested Transparent Objects with Uncontrolled Capture Environment, *SIGGRAPH Asia 2024*.  [[Paper](https://drive.google.com/drive/folders/1DP_aQ5GRow-Se4LpImYLjX3mah2__PSh?usp=sharing)] [[Website](http://geometrylearning.com/NU-NeRF/)] [[Code](https://github.com/78ij/NU-NeRF)]

---

##  Segmentation

- **TransCut**: Transparent Object Segmentation from a Light-Field Image, *ICCV 2025*. [[Paper](https://arxiv.org/abs/1511.06853)] [[Website](https://transcut.github.io/)]
- Segmenting Transparent Objects in the Wild, *ECCV 2020*. [[Paper](https://arxiv.org/abs/2003.13948)] [[Code](https://github.com/xieenze/Segment_Transparent_Objects)]
- Deep Polarization Cues for Transparent Object Segmentation, *CVPR 2020*. [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kalra_Deep_Polarization_Cues_for_Transparent_Object_Segmentation_CVPR_2020_paper.pdf)]
- Glass Segmentation with RGB-Thermal Image Pairs, *TIP 2023*. [[Paper](https://arxiv.org/abs/2204.05453)] [[Code](https://github.com/Dong-Huo/RGB-T-Glass-Segmentation)]
- Leveraging RGB-D Data with Cross-Modal Context Mining for Glass Surface Detection, *AAAI 2025*. [[Paper](https://arxiv.org/abs/2206.11250)] [[Code](https://jiaying.link/AAAI25-RGBDGlass/code.zip)] [[Website](https://jiaying.link/AAAI25-RGBDGlass/)]
- Self-supervised Transparent Liquid Segmentation for Robotic Pouring, *ICRA 2022*. [[Paper](https://www.google.com/url?q=https%3A%2F%2Farxiv.org%2Fabs%2F2203.01538&sa=D&sntz=1&usg=AOvVaw3d5pQfrbcL9HH5mwauGDwD)] [[Website](https://sites.google.com/view/transparentliquidpouring)] [[Code](https://github.com/gauthamnarayan/transparent-liquid-segmentation)]

----

## Perception

- **MVTrans**: Multi-view Perception to See Transparent Objects, *ICRA 2023*. [[Paper](https://arxiv.org/abs/2302.11683)] [[Website](https://ac-rad.github.io/MVTrans/)] [[Code](https://github.com/ac-rad/MVTrans)]
- Transparent Object Tracking Benchmark, *ICCV 2021*. [[Paper](https://arxiv.org/abs/2011.10875)] [[Website](https://hengfan2010.github.io/projects/TOTB/)] [[Code](https://drive.google.com/file/d/1IjEVDI5_L9doB2gXMMHIKi4krAkRhx6X/view)]
- A New Dataset and a Distractor-Aware Architecture for Transparent Object Tracking, *IJCV 2024*. [[Paper](https://arxiv.org/abs/2401.03872)] [[Group](https://prints.vicos.si/)]
