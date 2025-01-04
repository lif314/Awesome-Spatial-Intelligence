# Scene Representation

- [3D Gaussian Splatting](#3D-Gaussian-Splatting)
  - [Representation](#Representation)
  - [Acceleration](#Acceleration)
  - [Ray Tracing](#Ray-Tracing)
  - [GS+SDF+Mesh Extraction](#GS+SDF+Mesh-Extraction)
  - [Omnidirectional GS](#Omnidirectional-GS)


## 3D Gaussian Splatting

### Representation

- **3DGS**: 3D Gaussian Splatting for Real-Time Radiance Field Rendering, *SIGGRAPH 2023*. [[Paper](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/3d_gaussian_splatting_low.pdf)] [[Website](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/)] [[Code](https://github.com/graphdeco-inria/gaussian-splatting)]
- **2DGS**: 2D Gaussian Splatting for Geometrically Accurate Radiance Fields, *SIGGRAPH 2024*. [[Paper](https://arxiv.org/abs/2403.17888)] [[Website](https://surfsplatting.github.io/)] [[Code](https://github.com/hbb1/2d-gaussian-splatting)]

- **3D Convex Splatting**: Radiance Field Rendering with 3D Smooth Convexes, *arXiv 2024.11*. [[Paper](https://arxiv.org/abs/2411.14974)] [[Website](https://convexsplatting.github.io/)] [[Code](https://github.com/convexsplatting/convex-splatting)]

- **Sparse Voxels Rasterization**: Real-time High-fidelity Radiance Field Rendering, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2412.04459)] [[Author](https://sunset1995.github.io/)]

- **3DGS-MCMC**: 3D Gaussian Splatting as Markov Chain Monte Carlo, *NeurIPS 2024*. [[Paper](https://arxiv.org/abs/2404.09591)] [[Website](https://ubc-vision.github.io/3dgs-mcmc/)] [[Code](https://github.com/ubc-vision/3dgs-mcmc)]



### Acceleration

- **3DGS-LM**: Faster Gaussian-Splatting Optimization with Levenberg-Marquardt, *arXiv 2024.10*. [[Paper](https://arxiv.org/abs/2409.12892)] [[Website](https://lukashoel.github.io/3DGS-LM/)] [[Code](https://github.com/lukasHoel/3DGS-LM)]
- **Taming 3DGS**: High-Quality Radiance Fields with Limited Resources, *SIGGRAPH Asia 2024*. [[Paper](https://arxiv.org/abs/2406.15643)] [[Website](https://humansensinglab.github.io/taming-3dgs/)] [[Code](https://github.com/humansensinglab/taming-3dgs)]

### Ray Tracing

- **3D Gaussian Ray Tracing**: Fast Tracing of Particle Scenes, *SIGGRAPH Asia 2024*. [[Paper](https://arxiv.org/abs/2407.07090v3)] [[Website](https://gaussiantracer.github.io/)] [[Unofficial Code](https://github.com/fudan-zvg/gaussian-raytracing)]
- **Relightable 3D Gaussians**: Realistic Point Cloud Relighting with BRDF Decomposition and Ray Tracing, *ECCV 2024*. [[Paper](https://arxiv.org/abs/2311.16043)] [[Website](https://nju-3dv.github.io/projects/Relightable3DGaussian/)] [[Code](https://github.com/NJU-3DV/Relightable3DGaussian)]
- **IRGS**: Inter-Reflective Gaussian Splatting with 2D Gaussian Ray Tracing, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2412.15867)] [[Code](https://github.com/fudan-zvg/IRGS)] [[Website](https://fudan-zvg.github.io/IRGS/)]
- **LiDAR-RT**: Gaussian-based Ray Tracing for Dynamic LiDAR Re-simulation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2412.15199)] [[Code](https://github.com/zju3dv/LiDAR-RT)] [[Website](https://zju3dv.github.io/lidar-rt/)]
- **RayGauss**: Volumetric Gaussian-Based Ray Casting for Photorealistic Novel View Synthesis, *WACV 2025*. [[Paper](https://arxiv.org/abs/2408.03356)] [[Website](https://raygauss.github.io/)] [[Code](https://github.com/hugobl1/ray_gauss)] ``Very SLOW!!!``
- **Don't Splat your Gaussians**: Volumetric Ray-Traced Primitives for Modeling and Rendering Scattering and Emissive Media, *ToG 2024*. [[Paper](https://arxiv.org/abs/2405.15425)] [[Website](https://arcanous98.github.io/projectPages/gaussianVolumes.html)]
- Unified Gaussian Primitives for Scene Representation and Rendering, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2406.09733v2)]
- **EnvGS**: Modeling View-Dependent Appearance with Environment Gaussian, *arXiv 2024.12*. [[Paper](https://arxiv.org/abs/2412.15215)] [[Website](https://zju3dv.github.io/envgs/)] [[Code](https://github.com/zju3dv/EnvGS)] [[ZJU3DV](https://github.com/zju3dv)]
- **3DGUT**: Enabling Distorted Cameras and Secondary Rays in Gaussian Splatting, *arXiv 2024.12*. [[Paper](https://arxiv.org/abs/2412.12507)] [[Website](https://research.nvidia.com/labs/toronto-ai/3DGUT/)]
- **DirectL**: Efficient Radiance Fields Rendering for 3D Light Field Displays, *TOG 2024*. [[Paper](https://arxiv.org/abs/2407.14053)] [[Website](https://direct-l.github.io/)]
- **SSS-GS**: Subsurface Scattering for 3D Gaussian Splatting, *arXiv 2024.10*. [[Paper](https://arxiv.org/abs/2408.12282)] [[Website](https://sss.jdihlmann.com/)] [[Code](https://github.com/cgtuebingen/SSS-GS)]

### GS+SDF+Mesh Extraction

- **SuGaR**: Surface-Aligned Gaussian Splatting for Efficient 3D Mesh Reconstruction and High-Quality Mesh Rendering, *CVPR 2024*. [[Paper](https://arxiv.org/abs/2311.12775)] [[Website](https://imagine.enpc.fr/~guedona/sugar/)] [[Code](https://github.com/Anttwo/SuGaR)]
- **GSDF**: 3DGS Meets SDF for Improved Rendering and Reconstruction, *NeurIPS 2024*. [[Paper](https://arxiv.org/abs/2403.16964)] [[Website](https://city-super.github.io/GSDF/)] [[Code](https://github.com/city-super/GSDF)]
- **GS-Pull**: Neural Signed Distance Function Inference through Splatting 3D Gaussians Pulled on Zero-Level Set, *NeurIPS 2024*. [[Paper](https://arxiv.org/abs/2410.14189)] [[Website](https://wen-yuan-zhang.github.io/GS-Pull/)] [[Code](https://github.com/wen-yuan-zhang/GS-Pull)]
- **SplatSDF**: Boosting Neural Implicit SDF via Gaussian Splatting Fusion, *arXiv 2024.11*. [[Paper](https://arxiv.org/abs/2411.15468)] [[Website](https://blarklee.github.io/splatsdf/)] [[Code](https://github.com/BlarkLee/SplatSDF_official)]
- **AGS-Mesh**: Adaptive Gaussian Splatting and Meshing with Geometric Priors for Indoor Room Reconstruction Using Smartphones, *3DV 2025*. [[Paper](https://arxiv.org/abs/2411.19271)] [[Website](https://xuqianren.github.io/ags_mesh_website/)] [[Paper](https://github.com/XuqianRen/AGS_Mesh)]

### Omnidirectional GS

- **ODGS**: 3D Scene Reconstruction from Omnidirectional Images with 3D Gaussian Splatting, *NeurIPS 2024*. [[Paper](https://arxiv.org/abs/2410.20686)] [[Code](https://github.com/esw0116/ODGS)]



### Event GS

- **Event3DGS**: Event-Based 3D Gaussian Splatting for High-Speed Robot Egomotion, *CoRL 2024*. [[Paper](https://arxiv.org/abs/2406.02972)] [[Code](https://github.com/jayhsu0627/Event3DGS)]
- 





### Forward Feed

- **SplatFields**: Neural Gaussian Splats for Sparse 3D and 4D Reconstruction, *ECCV 2024*. [[Paper](https://arxiv.org/abs/2409.11211)] [[Website](https://markomih.github.io/SplatFields/)] [[Code](https://github.com/markomih/SplatFields)]
