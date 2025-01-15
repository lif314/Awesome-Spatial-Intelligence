# Easy 3D

- [Zero Shot 3D Reconstruction](#Zero-Shot-3D-Reconstruction)
- [Single View 3D Reconstruction](#Single-View-3D-Reconstruction)
- [Sparse View Reconstruction](#Sparse-View-Reconstruction)

- [Binocular Vision](#Binocular-Vision)

- [Point Cloud Completion](#Point-Cloud-Completion)

- [Metric Depth](#Metric-Depth)

---

## Zero Shot 3D Reconstruction

- **DUSt3R**: Geometric 3D Vision Made Easy, *CVPR 2024* [[Paper](https://arxiv.org/abs/2312.14132)] [[Website](https://europe.naverlabs.com/research/publications/dust3r-geometric-3d-vision-made-easy/)] [[Code](https://github.com/naver/dust3r)]
- **MASt3R**: Grounding Image Matching in 3D with MASt3R, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2406.09756)] [[Website](https://europe.naverlabs.com/blog/mast3r-matching-and-stereo-3d-reconstruction/)] [[Code](https://github.com/naver/mast3r)]
- **Splatt3R**: Zero-shot Gaussian Splatting from Uncalibrated Image Pairs, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2408.13912)] [[Website](https://splatt3r.active.vision/)] [[Code](https://github.com/btsmart/splatt3r)]
- **Spann3R**: 3D Reconstruction with Spatial Memory, *3DV 2025*. [[Paper](https://arxiv.org/abs/2408.16061)] [[Website](https://hengyiwang.github.io/projects/spanner)] [[Code](https://github.com/HengyiWang/spann3r)]
- **MonST3R**: A Simple Approach for Estimating Geometry in the Presence of Motion, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2410.03825)] [[Website](https://monst3r-project.github.io/)] [[Code](https://github.com/Junyi42/monst3r)]
- **No Pose, No Problem**: Surprisingly Simple 3D Gaussian Splats from Sparse Unposed Images, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2410.24207)] [[Website](https://noposplat.github.io/)] [[Code](https://github.com/cvg/NoPoSplat)]
- **ZeroGS**: Training 3D Gaussian Splatting from Unposed Images, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2411.15779)] [[Website](https://aibluefisher.github.io/ZeroGS/)] [[Code](https://github.com/aibluefisher/ZeroGS)]
- **SelfSplat**: Pose-Free and 3D Prior-Free Generalizable 3D Gaussian Splatting, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2411.17190)] [[Website](https://gynjn.github.io/selfsplat/)] [[Code](https://github.com/Gynjn/selfsplat)]
- :fire: **Large Spatial Model**: End-to-end Unposed Images to Semantic 3D, *NeurIPS 2024*. [[Paper](https://arxiv.org/abs/2410.18956)] [[Website](https://largespatialmodel.github.io/)] [[Code](https://github.com/NVlabs/LSM)]
- **DiffusionGS**: Baking Gaussian Splatting into Diffusion Denoiser for Fast and Scalable Single-stage Image-to-3D Generation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2411.14384v2)] [[Website](https://caiyuanhao1998.github.io/project/DiffusionGS/)] [[Code](https://github.com/caiyuanhao1998/Open-DiffusionGS)]
- **MV-DUSt3R+**: Single-Stage Scene Reconstruction from Sparse Views In 2 Seconds, *arXiv 2024.12*. [[Paper](https://arxiv.org/abs/2412.06974)] [[Website](https://mv-dust3rp.github.io/)] [[Code](https://github.com/facebookresearch/mvdust3r)]

---

## Single View 3D Reconstruction

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

- **Splatter Image**: Ultra-Fast Single-View 3D Reconstruction , *CVPR 2024*. [[Paper](https://arxiv.org/abs/2312.13150)] [[Website](https://szymanowiczs.github.io/splatter-image.html)] [[Code](https://github.com/szymanowiczs/splatter-image)] ``1 V100``

- **pixelSplat**: 3D Gaussian Splats from Image Pairs for Scalable Generalizable 3D Reconstruction , *CVPR 2024*. [[Paper](https://arxiv.org/abs/2312.12337)] [[Website](https://davidcharatan.com/pixelsplat/)] [[Code](https://github.com/dcharatan/pixelsplat)] ``1 A100``

- **SSR**: Single-view 3D Scene Reconstruction with High-fidelity Shape and Texture, *3DV 2024*. [[Paper](http://arxiv.org/abs/2311.00457)] [[Website](https://dali-jack.github.io/SSR/)] [[Code](https://github.com/DaLi-Jack/SSR-code)]

- "Dynamic Scene Reconstruction from Single Landscape Image Using 4D Gaussian in the Wild", *arXiv 2024*. [[Paper](https://openreview.net/forum?id=HrwrydyPBD)] [[Website](https://cvsp-lab.github.io/3D_MRM_page/)]

- **GRM**: Large Gaussian Reconstruction Model for Efficient 3D Reconstruction and Generation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2403.14621)] [[Website](https://justimyhxu.github.io/projects/grm/)] [[Code](https://github.com/justimyhxu/grm)] [[Demo](https://huggingface.co/spaces/GRM-demo/GRM)]

- **LGM**: Large Multi-View Gaussian Model for High-Resolution 3D Content Creation, *ECCV 2024 (Oral)*. [[Paper](https://arxiv.org/abs/2402.05054)] [[Website](https://me.kiui.moe/lgm/)] [[Code](https://github.com/3DTopia/LGM)] [[Demo](https://huggingface.co/spaces/ashawkey/LGM)]

- :fire: **TRELLIS**: Structured 3D Latents for Scalable and Versatile 3D Generation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2412.01506)] [[Website](https://trellis3d.github.io/)] [[Code](https://github.com/Microsoft/TRELLIS)] [[Demo](https://huggingface.co/spaces/JeffreyXiang/TRELLIS)]

- **MIDI**: Multi-Instance Diffusion for Single Image to 3D Scene Generation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2412.03558)] [[Website](https://huanngzh.github.io/MIDI-Page/)] [[Code](https://github.com/huanngzh/MIDI)]

- **DeepPriorAssembly**: Zero-Shot Scene Reconstruction from Single Images with Deep Prior Assembly, *NeurIPS 2024*. [[Paper](https://arxiv.org/abs/2410.15971)] [[Website](https://junshengzhou.github.io/DeepPriorAssembly/)] [[Code](https://github.com/junshengzhou/DeepPriorAssembly)]

- **DreamUp3D**: Object-Centric Generative Models for Single-View 3D Scene Understanding and Real-to-Sim Transfer, *R-AL 2024*. [[Paper](https://arxiv.org/abs/2402.16308)]

- **SPAR3D**: Stable Point-Aware Reconstruction of 3D Objects from Single Images, *arXiv 2025.01*. [[Paper](https://arxiv.org/abs/2501.04689)] [[Website](https://spar3d.github.io/)] [[Code](https://github.com/Stability-AI/stable-point-aware-3d)] [[Demo](https://huggingface.co/spaces/stabilityai/stable-point-aware-3d)]

---

## Sparse View Reconstruction

- **InfiniCube**: Unbounded and Controllable Dynamic 3D Driving Scene Generation with World-Guided Video Models, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2412.03934)] [[Website](https://research.nvidia.com/labs/toronto-ai/infinicube/)]
- **XCube**: Large-Scale 3D Generative Modeling using Sparse Voxel Hierarchies, *CVPR 2024*. [[Paper](https://arxiv.org/abs/2312.03806)] [[Website](https://research.nvidia.com/labs/toronto-ai/xcube/)] [[Code](https://github.com/nv-tlabs/XCube)] [[NVIDIA Toronto AI Lab](https://research.nvidia.com/labs/toronto-ai/)]
- **fVDB**: A Deep-Learning Framework for Sparse, Large-Scale, and High-Performance Spatial Intelligence, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2407.01781)] [[Website](https://research.nvidia.com/labs/prl/publication/williams2024fvdb/)] [[NVIDIA Toronto AI Lab](https://research.nvidia.com/labs/toronto-ai/)]

- **SCube**: Instant Large-Scale Scene Reconstruction using VoxSplats, *NeurIPS 2024*. [[Paper](https://arxiv.org/abs/2410.20030)] [[Code](https://github.com/nv-tlabs/SCube)] [[Website](https://research.nvidia.com/labs/toronto-ai/scube/)]
- **MVSplat**: Efficient 3D Gaussian Splatting from Sparse Multi-View Images, *ECCV2024*. [[Paper](https://arxiv.org/abs/2403.14627)] [[Code](https://github.com/donydchen/mvsplat)] [[Website](https://donydchen.github.io/mvsplat/)] ``1 A100``
- **MVSGaussian**: Fast Generalizable Gaussian Splatting Reconstruction from Multi-View Stereo, *ECCV 2024*. [[Paper](https://arxiv.org/abs/2405.12218)] [[Website](https://mvsgaussian.github.io/)] [[Code](https://github.com/TQTQliu/MVSGaussian)]
- **MVSplat360**: Feed-Forward 360 Scene Synthesis from Sparse Views, *NeurIPS 2024*. [[Paper](https://arxiv.org/abs/2411.04924)] [[Website](https://donydchen.github.io/mvsplat360/)] [[Code](https://github.com/donydchen/mvsplat360)] ``8 A100``
- **DepthSplat**: Connecting Gaussian Splatting and Depth, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2410.13862)] [[Website](https://haofeixu.github.io/depthsplat/)] [[Code](https://github.com/cvg/depthsplat)] ``8 A100``
- **SplatFormer**: Point Transformer for Robust 3D Gaussian Splatting, *arXiv 2024.11*. [[Paper](https://arxiv.org/abs/2411.06390)] [[Website](https://sergeyprokudin.github.io/splatformer/)] [[Code](https://github.com/ChenYutongTHU/SplatFormer)]



---

## Binocular Vision

- :fire:**Binocular3DGS**: Binocular-Guided 3D Gaussian Splatting with View Consistency for Sparse View Synthesis, *NeurIPS 2024*. [[Paper](https://arxiv.org/abs/2410.18822)] [[Website](https://hanl2010.github.io/Binocular3DGS/)] [[Code](https://github.com/hanl2010/Binocular3DGS)]
- **ZoomGS**: Dual-Camera Smooth Zoom on Mobile Phones, *ECCV 2024*. [[Paper](https://arxiv.org/abs/2404.04908)] [[Website](https://dualcamerasmoothzoom.github.io/)] [[Code](https://github.com/ZcsrenlongZ/ZoomGS)]



---

## Point Cloud Completion

- **SDS**: Point-Cloud Completion with Pretrained Text-to-image Diffusion Models, *NeurIPS 2023*. [[Paper](https://arxiv.org/abs/2306.10533)] [[Website](https://sds-complete.github.io/)] [[Code](https://github.com/NVlabs/sds-complete)]

## Metric Depth

- **ZoeDepth**: Zero-shot Transfer by Combining Relative and Metric Depth, *arXiv 2023*. [[Paper](https://arxiv.org/abs/2302.12288)] [[Code](https://github.com/isl-org/ZoeDepth)]
- **Metric3D**: Towards Zero-shot Metric 3D Prediction from A Single Image, *ICCV 2023*. [[Paper](https://arxiv.org/abs/2307.10984)] [[Code](https://github.com/YvanYin/Metric3D)] [[Website](https://jugghm.github.io/Metric3Dv2/)]

- **UniDepth**: Universal Monocular Metric Depth Estimation, *CVPR 2024*. [[Paper](https://arxiv.org/abs/2403.18913)] [[Code](https://github.com/lpiccinelli-eth/UniDepth)] [[Website](https://lpiccinelli-eth.github.io/pub/unidepth/)]
- **PatchFusion**: An End-to-End Tile-Based Framework for High-Resolution Monocular Metric Depth Estimation, *CVPR 2024*. [[Paper](https://arxiv.org/abs/2312.02284)] [[Website](https://zhyever.github.io/patchfusion/)] [[Code](https://github.com/zhyever/PatchFusion)]

- **Depth Pro**: Sharp Monocular Metric Depth in Less Than a Second, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2410.02073)] [[Code](https://github.com/apple/ml-depth-pro)]
- **Depth Anything V2**: A More Capable Foundation Model for Monocular Depth Estimation, *NeurIPS 2024*. [[Paper](https://arxiv.org/abs/2406.09414)] [[Website](https://depth-anything-v2.github.io/)] [[Code](https://github.com/DepthAnything/Depth-Anything-V2)]
- Prompting Depth Anything for 4K Resolution Accurate Metric Depth Estimation, *arXiv 2024*. [[Paper](https://arxiv.org/abs/2412.14015)] [[Website](https://promptda.github.io/)] [[Code](https://github.com/DepthAnything/PromptDA)]
