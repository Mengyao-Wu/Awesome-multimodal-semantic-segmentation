# Awesome-multimodal-semantic-segmentation
Resources for multimodal semantic segmentation

# 🧠 Multimodal Semantic Segmentation: Datasets & Resources Overview

This repository provides a curated list of **datasets** and **literature** for multimodal semantic segmentation across **RGB-D**, **RGB-Thermal**, **RGB-Event**, **RGB-LiDAR**, **Audio-Visual**, **Medical**, and **Remote Sensing** domains.

---

## 📁 1. Multimodal Datasets by Modality

### 1.1 RGB + Depth (RGB-D)

| Dataset | Paper Title | Venue | Year | Link |
|---------|-------------|-------|------|------|
| NYU Depth V2 | Indoor Segmentation and Support Inference from RGBD Images | ECCV | 2012 | [Link](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html) |
| SUN RGB-D | SUN RGB-D: A RGB-D Scene Understanding Benchmark Suite | CVPR | 2015 | [Link](https://rgbd.cs.princeton.edu/) |
| Stanford2D3D | 2D-3D-S: A Large-Scale Indoor Dataset for 3D Semantic Segmentation | CVPR | 2017 | [Link](http://buildingparser.stanford.edu/dataset.html) |
| ScanNetV2 | ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes | CVPR | 2017 | [Link](http://www.scan-net.org/) |
| Cityscapes (Stereo) | The Cityscapes Dataset for Semantic Urban Scene Understanding | CVPR | 2016 | [Link](https://www.cityscapes-dataset.com/) |
| SYNTHIA2Cityscapes&SELMA2Cityscapes | Source-Free Domain Adaptation for RGB-D Semantic Segmentation with Vision Transformers | WACV | 2023 | [Link](https://arxiv.org/abs/2305.14269) |
| NYUDv2 | Self-Enhanced Feature Fusion for RGB-D Semantic Segmentation | IEEE SPL | 2024 | [Link](https://ieeexplore.ieee.org/document/10706844/) |
| NYU Depth V2&SUN-RGBD | DFormer: Rethinking RGBD Representation Learning for Semantic Segmentation | ICLR | 2024 | [Link](https://github.com/VCIP-RGBD/DFormer) |
| NYUDv2&SUN-RGBD&SID | ShapeConv: Shape-aware Convolutional Layer  for Indoor RGB-D Semantic Segmentation | ICCV | 2021 | [Link](https://ieeexplore.ieee.org/document/9710391/) |
| GTA→Cityscapes&Synthia→Cityscapes | RGB-D Domain adaptive semantic segmentation with cross-modality feature recalibration | Information Fusion | 2025 | [Link](https://linkinghub.elsevier.com/retrieve/pii/S1566253525001903) |
| ScanNet&Cityscapes | RFBNet: Deep Multimodal Networks with Residual Fusion Blocks for RGB-D Semantic Segmentation | arXiv | 2019 | [Link](http://arxiv.org/abs/1907.00135) |
| NYU Depth V2&SUN-RGBD | PrimKD: Primary Modality Guided Multimodal Fusion for RGB-D Semantic Segmentation | ACM MM | 2024 | [Link](https://dl.acm.org/doi/10.1145/3664647.3681253) |
| NYU Depth V2&SUN-RGBD&SID | Pixel Difference Convolutional Network for RGB-D Semantic Segmentation | TSCVT | 2021 | [Link](https://ieeexplore.ieee.org/document/10185116/) |
| NYUv2 & SUNRGB-D&Cityscapes | Efficient RGB-D Semantic Segmentation for Indoor Scene Analysis | arXiv | 2021 | [Link](http://arxiv.org/abs/2011.06961) |
| NYU Depth V2&SUN-RGBD | Dual-modal non-local context guided multi-stage fusion for indoor RGB-D semantic segmentation | Expert Systems With Applications | 2024 | [Link](https://linkinghub.elsevier.com/retrieve/pii/S0957417424014659) |
| NYU DepthV2&SUNRGBD | DFormerv2: Geometry Self-Attention for RGBD Semantic Segmentation | arXiv | 2025 | [Link](https://github.com/VCIPRGBD/DFormer) |
| NYUv2&SUN RGBD&KITTI | Depth-Adapted CNNs for RGB-D Semantic Segmentation | arXiv | 2022 | [Link](http://arxiv.org/abs/2206.03939) |
| NYU Depth V2&SOP | Cross-Modal Transformer for RGB-D semantic segmentation of production workshop objects | Pattern Recognition | 2023 | [Link](https://github.com/FutureIAI/CMFormer) |
| NYU Depth V2&SUN-RGBD | Automatic Network Architecture Search for RGB-D Semantic Segmentation | ACM MM | 2023 | [Link](https://dl.acm.org/doi/10.1145/3581783.3612288) |
| NYU Depth V2&SUN-RGBD&Cityscapes | Attention-based fusion network for RGB-D semantic segmentation | Neurocomputing | 2024 | [Link](https://linkinghub.elsevier.com/retrieve/pii/S0925231224011421) |
| NYUV2&SUN-RGBD | AsymFormer: Asymmetrical Cross-Modal Representation Learning for Mobile Platform Real-Time RGB-D Semantic Segmentation | CVPR | 2024 | [Link](https://github.com/Fourier7754/AsymFormer) |
| NYUV2&SUN-RGBD | Application of Multi-modal Fusion Attention Mechanism in Semantic Segmentation | CVPR | 2022 | [Link](https://link.springer.com/10.1007/978-3-031-26293-7_23) |


---

### 1.2 RGB + Thermal (RGB-T)

| Dataset | Paper Title | Venue | Year | Link |
|---------|-------------|-------|------|------|
| KAIST Multispectral | Multispectral Pedestrian Detection: Benchmark Dataset and Baseline | CVPRW | 2015 | [Link](https://soonminhwang.github.io/rgbt-ped-detection/) |
| LLVIP | LLVIP: A Visible-Thermal Paired Dataset for Low-Light Vision | ECCV | 2022 | [Link](https://github.com/wyf0912/LLVIP) |
| PST900 | PST900: RGB-Thermal Dataset for Segmentation | IJCAI | 2021 | [Link](https://github.com/Vanint/PST900_RGBT) |
| MFNet | MS-IRTNet: Multistage information interaction network for RGB-T semantic segmentation | Information Sciences	 | 2021 | [Link](https://github.com/poisonzzw/MS-IRTNet) |
| MFNet | UTFNet: Uncertainty-Guided Trustworthy Fusion Network for RGB-Thermal Semantic Segmentation | IEEE | 2023 | [Link](https://github.com/KustTeamWQW/UTFNet) |
| MFNet&PST900 | Region-adaptive and context-complementary cross modulation for RGB-T semantic segmentation | Pattern Recognition | 2024 | [Link](https://linkinghub.elsevier.com/retrieve/pii/S0031320323007896) |
| MFNet&PST900 | RGB-T Semantic Segmentation With Location, Activation, and Sharpening | TCSVT | 2023 | [Link](https://github.com/MathLee/LASNet) |
| MVSeg | Multispectral Video Semantic Segmentation: A Benchmark Dataset and Baseline | CVPR | 2023 | [Link](https://ieeexplore.ieee.org/document/10203299/) |
| MFNet&PST900 | MMSMCNet: Modal Memory Sharing and Morphological Complementary Networks for RGB-T Urban Scene Semantic Segmentation | IEEE | 2023 | [Link](https://github.com/2021nihao/MMSMCNet) |
| MFNet&PST900 | Mitigating Modality Discrepancies for RGB-T Semantic Segmentation | IEEE | 2024 | [Link](https://ieeexplore.ieee.org/document/10008228/) |
| MFNet&PST900 | GMNet: Graded-Feature Multilabel-Learning Network for RGB-Thermal Urban Scene Semantic Segmentation |  | 2023 | [Link](https://ieeexplore.ieee.org/document/9531449/) |
| MFNet | FEANet: Feature-Enhanced Attention Network for RGB-Thermal Real-time Semantic Segmentation | IEEE | 2021 | [Link](https://ieeexplore.ieee.org/document/9636084/) |
| MFNet&PST900 | Complementarity-aware cross-modal feature fusion network for RGB-T semantic segmentation | Pattern Recognition | 2022 | [Link](https://linkinghub.elsevier.com/retrieve/pii/S0031320322003624) |
| MFNet | ABMDRNet: Adaptive-weighted Bi-directional Modality Difference Reduction Network for RGB-T Semantic Segmentation | CVPR | 2021 | [Link](https://ieeexplore.ieee.org/document/9578077/) |
| NYU Depth V2 | Prompting Multi-Modal Image Segmentation with Semantic Grouping | AAAI | 2024 | [Link](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html) |
| MFNet&PST900 | A Feature Divide-and-Conquer Network for RGB-T Semantic Segmentation | TCSVT | 2023 | [Link](https://ieeexplore.ieee.org/document/9987529/) |
| MFNet&PST900&FMB | AGFNet: Adaptive Gated Fusion Network for RGB-T Semantic Segmentation | ITS | 2023 | [Link](https://ieeexplore.ieee.org/document/10858005/) |
| MFNet | CCAFFMNet: Dual-spectral semantic segmentation network with channel-coordinate attention feature fusion module | Neurocomputing | 2022 | [Link](https://linkinghub.elsevier.com/retrieve/pii/S0925231221017331) |
| MFNet&PST900 | Channel and Spatial Relation-Propagation Network for RGB-Thermal Semantic Segmentation | arXiv | 2023 | [Link](http://arxiv.org/abs/2308.12534) |
| MFNet&PST900 | Variational Probabilistic Fusion Network for RGB-T Semantic Segmentation | Journal of Class Files | 2023 | [Link](http://arxiv.org/abs/2307.08536) |
| MFNet&PST900&FMB | Unveiling the Potential of Segment Anything Model 2 for RGB-Thermal Semantic Segmentation with Language Guidance | arXiv | 2025 | [Link](http://arxiv.org/abs/2503.02581) |
| MFNet&PST900 | SGFNet: Semantic-Guided Fusion Network for RGB-Thermal Semantic Segmentation | TCSVT | 2023 | [Link](https://github.com/kw717/SGFNet) |
| MFNet&PST900 | A Feature Divide-and-Conquer Network for RGB-T Semantic Segmentation |  | 2023 | [Link](https://ieeexplore.ieee.org/document/9987529/) |
| MFNet&PST900 | SFAF-MA: Spatial Feature Aggregation and Fusion With Modality Adaptation for RGB-Thermal Semantic Segmentation | TIM | 2023 | [Link](https://github.com/hexunjie/SFAF-MA) |
| MFNet&PST900 | SemanticRT: A Large-Scale Dataset and Method for Robust Semantic Segmentation in Multispectral Images | ACM MM | 2023 | [Link](https://dl.acm.org/doi/10.1145/3581783.3611738) |
| MFNet&PST900 | RGB-T Semantic Segmentation With Location, Activation, and Sharpening | TCSVT | 2023 | [Link](https://github.com/MathLee/LASNet) |
| MFNet | RFIENet: RGB-thermal feature interactive enhancement network for semantic segmentation of insulator in backlight scenes | Measurement | 2022 | [Link](https://linkinghub.elsevier.com/retrieve/pii/S0263224122013732) |
| MFNet&PST900 | Resolving semantic conflicts in RGB-T semantic segmentation | Pattern Recognition | 2025 | [Link](https://linkinghub.elsevier.com/retrieve/pii/S0031320325000585) |
| MFNet&PST900 | Residual spatial fusion network for RGB-thermal semantic segmentation | Neurocomputing | 2024 | [Link](https://linkinghub.elsevier.com/retrieve/pii/S0925231224006842) |
| MFNet&PST900 | RegSeg: An End-to-End Network for Multimodal RGB-Thermal Registration and Semantic Segmentation | TIP | 2024 | [Link](https://ieeexplore.ieee.org/document/10766355/) |
| MFNet&PST900 | Prompting Multi-Modal Image Segmentation with Semantic Grouping | AAAI | 2024 | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/27981) |
| MFNet&PST900 | PEAFusion: Parameter-efficient Adaptation for RGB-Thermal fusion-based semantic segmentation | Information Fusion | 2025 | [Link](https://linkinghub.elsevier.com/retrieve/pii/S1566253525001034) |
| MFNet&PST900 | Open-RGBT: Open-vocabulary RGB-T Zero-shot Semantic Segmentation in Open-world Environments | arXiv | 2023 | [Link](https://OpenRGBT.github.io) |
| MFNet&PST900 | MMSMCNet: Modal Memory Sharing and Morphological Complementary Networks for RGB-T Urban Scene Semantic Segmentation | TCSVT  | 2023 | [Link](https://ieeexplore.ieee.org/document/10123009/) |
| MFNet&PST900 | MiLNet: Multiplex Interactive Learning Network for RGB-T Semantic Segmentation | TIP | 2025 | [Link](https://github.com/Jinfupku/MiLNet) |
| SUNRGBD&PST900 | MEFNET: Multi-expert fusion network for RGB-Thermal semantic segmentationMEFNET: Multi-expert fusion network for RGB-Thermal semantic segmentation | EAAI | 2023 | [Link](https://linkinghub.elsevier.com/retrieve/pii/S0952197623008229) |
| MFNet&PST900 | Mask-guided modality difference reduction network for RGB-T semantic segmentation | Neurocomputing | 2023 | [Link](https://linkinghub.elsevier.com/retrieve/pii/S0925231222015314) |
| MFNet&PST900 | GMNet: Graded-Feature Multilabel-Learning Network for RGB-Thermal Urban Scene Semantic Segmentation | TIP | 2021 | [Link](https://ieeexplore.ieee.org/document/9531449/) |
| MFNet&PST900 | Glass Segmentation with RGB-Thermal Image Pairs | TIP | 2023 | [Link](http://arxiv.org/abs/2204.05453) |
| MFNet&PST900 | GCNet: Grid-like context-aware network for RGB-thermal semantic segmentation | Neurocomputing | 2022 | [Link](https://linkinghub.elsevier.com/retrieve/pii/S0925231222009006) |
| RGBT-TL&RGBT-TS | Dual-Space Graph-Based Interaction Network for RGB-Thermal Semantic Segmentation in Electric Power Scene | TCSVT | 2023 | [Link](https: //github.com/hhujiang/DSGBINet) |
| PST900&ACDC&NightCity | Dual-branch deep cross-modal interaction network for semantic segmentation with thermal images | EAAI | 2024 | [Link](https://linkinghub.elsevier.com/retrieve/pii/S0952197624009783) |
| MFNet | Cross-level interaction fusion network-based RGB-T semantic segmentation for distant targets | Pattern Recognition | 2025 | [Link](https://linkinghub.elsevier.com/retrieve/pii/S0031320324009695) |
| MFNet&PST900 | Context-Aware Interaction Network for RGB-T Semantic Segmentation | TMM | 2024 | [Link](https://ieeexplore.ieee.org/document/10379106/) |
| MFNet&PST900&KP | Complementary Random Masking for RGB-Thermal Semantic Segmentation | ICRA | 2024 | [Link](https://ieeexplore.ieee.org/document/10611200/) |
| MFNet&PST900 | Channel and Spatial Relation-Propagation Network for RGB-Thermal Semantic Segmentation | arXiv | 2023 | [Link](http://arxiv.org/abs/2308.12534) |
| MFNet&PST900&FMB | C⁴Net: Excavating Cross-Modal Context- and Content-Complementarity for RGB-T Semantic Segmentation | TCSVT | 2025 | [Link](https://ieeexplore.ieee.org/document/10734373/) |
| MFNet | ABMDRNet: Adaptive-weighted Bi-directional Modality Difference Reduction Network for RGB-T Semantic Segmentation | CVPR | 2021 | [Link](https://ieeexplore.ieee.org/document/9578077/) |
| MFNet | A RGB-Thermal Image Segmentation Method Based on Parameter Sharing and Attention Fusion for Safe Autonomous Driving | TIP | 2024 | [Link](https://ieeexplore.ieee.org/document/10337777/) |

---

### 1.3 RGB + Event Camera

| Dataset | Paper Title | Venue | Year | Link |
|---------|-------------|-------|------|------|
| DSEC | The DSEC Dataset for Event-based Stereo Visual Odometry | RA-L + ICRA | 2021 | [Link](https://dsec.ifi.uzh.ch/) |
| ESS | ESS: Learning Event-based Semantic Segmentation from Still Images | CVPR | 2021 | [Link](https://github.com/lyuchenyang/ESS) |
| DDD17 | Driving Dataset for Event Cameras (DDD17) | arXiv | 2017 | [Link](https://github.com/uzh-rpg/rpg_davis_data) |
| DSEC | SAM-Event-Adapter: Adapting Segment Anything Model for Event-RGB Semantic Segmentation | ICRA | 2024 | [Link](https://ieeexplore.ieee.org/document/10611127/) |
| DSEC | SAM-Event-Adapter: Adapting Segment Anything Model for Event-RGB Semantic Segmentation | ICRA | 2024 | [Link](https://ieeexplore.ieee.org/document/10611127/) |
| DSEC&DDD17 | Rethinking RGB-Event Semantic Segmentation with a Novel Bidirectional Motion-enhanced Event Representation | arXiv | 2025 | [Link](http://arxiv.org/abs/2505.01548) |

---

### 1.4 RGB + LiDAR

| Dataset | Paper Title | Venue | Year | Link |
|---------|-------------|-------|------|------|
| SemanticKITTI | SemanticKITTI: A Dataset for Semantic Scene Understanding of LiDAR Sequences | ICCV | 2019 | [Link](http://www.semantic-kitti.org/) |
| A2D2 | Audi A2D2: AEV Autonomous Driving Dataset | Dataset Release | 2020 | [Link](https://www.a2d2.audi/) |
| nuScenes | nuScenes: A Multimodal Dataset for Autonomous Driving | CVPR | 2020 | [Link](https://www.nuscenes.org/) |

---

### 1.5 RGB + Audio

| Dataset | Paper Title | Venue | Year | Link |
|---------|-------------|-------|------|------|
| AVSBench | Unveiling and Mitigating Bias in Audio-Visual Segmentation | ECCV | 2022 | [Link](https://github.com/OpenGVLab/AVSBench) |
| MUSIC-AVS | MUSIC: A Multimodal Dataset for Sound Source Localization | ECCV | 2018 | [Link](https://zenodo.org/record/3402610) |

---

### 1.6 RGB + N (Multiple Modalities)

| Dataset | Paper Title | Venue | Year | Link |
|---------|-------------|-------|------|------|
| ArbitraryModalSeg | Delivering Arbitrary-Modal Semantic Segmentation | CVPR | 2023 | [Link](https://arxiv.org/pdf/2303.01480) |
| Multimodal Material Segmentation | Segmenting Materials from Local Appearance and Global Context | CVPR | 2022 | [Link](https://openaccess.thecvf.com/content/CVPR2022/papers/Liang_Multimodal_Material_Segmentation_CVPR_2022_paper.pdf) |
| SYN-UDTIRI&KITTI Road&Cityscapes&KITTI Semantics&MFNet&FMB&ZJU | RoadFormer+: Delivering RGB-X Scene Parsing through Scale-Aware Information Decoupling and Advanced Heterogeneous Feature Fusion | TIV | 2024 | [Link](https://ieeexplore.ieee.org/document/10643711/) |
| MFNet&PST900&NYU Depth V2&SUN-RGBD V1 | On Exploring Shape and Semantic Enhancements for RGB-X Semantic Segmentation | TIV | 2024 | [Link](https://ieeexplore.ieee.org/document/10185113/) |
| NYU Depth V2&SUN-RGBD&PST900&FMB&DDD17 | CPAL: Cross-prompting Adapter with LoRAs for RGB+X Semantic Segmentation | TCSVT | 2021 | [Link](https://ieeexplore.ieee.org/document/10857375/) |

---

### 1.7 Medical Multimodal Datasets

| Dataset | Paper Title | Venue | Year | Link |
|---------|-------------|-------|------|------|
| BraTS | The Multimodal Brain Tumor Image Segmentation Benchmark | IEEE TMI | 2015 | [Link](https://doi.org/10.1109/TMI.2014.2377694) |
| AMOS | AMOS: Abdominal Multi-organ Benchmark | MICCAI | 2022 | [Link](https://amos22.grand-challenge.org/) |
| CHAOS | Combined Healthy Abdominal Organ Segmentation | arXiv | 2019 | [Link](https://arxiv.org/abs/1911.11320) |
| MM-WHS | Whole Heart Segmentation Benchmark | MedIA | 2019 | [Link](https://doi.org/10.1016/j.media.2019.01.012) |
| SegTHOR | Segmentation of Thoracic Organs at Risk | arXiv | 2019 | [Link](https://arxiv.org/abs/1902.09063) |

---

### 1.8 Remote Sensing Multimodal Datasets

| Dataset | Paper Title | Venue | Year | Link |
|---------|-------------|-------|------|------|
| ISPRS Vaihingen / Potsdam | ISPRS Urban Object Classification Benchmark | ISPRS Annals | 2012 | [Link](https://www2.isprs.org/commissions/comm2/wg4/benchmark/semantic-labeling/) |
| LoveDA | LoveDA: Remote Sensing Domain Adaptive Segmentation | NeurIPS (Datasets Track) | 2021 | [Link](https://github.com/Junjue-Wang/LoveDA) |
| DASE2021 | Towards Cross-Modality Domain Adaptation for RS | IGARSS | 2021 | [Link](https://github.com/Junjue-Wang/DASE2021) |
| Houston2018 | GRSS Data Fusion: Hyperspectral + LiDAR | JSTARS | 2018 | [Link](https://www.grss-ieee.org/community/technical-committees/data-fusion/) |

---

## 🔀 2. Method Design: Architectures, Training

### 2.1 Architecture Design

#### 2.1.1 Modality Interaction Design

| Paper Title | Venue | Year | Modality | Link |
|-------------|-------|------|----------|------|
| DFORMER: Rethinking RGBD Representation Learning | CVPR | 2022 | RGB-D | [arXiv](https://arxiv.org/abs/2111.15645) |
| StitchFusion: Weaving Any Visual Modalities | CVPR | 2023 | RGB+N | [arXiv](https://arxiv.org/abs/2304.14302) |

#### 2.1.2 Modality-Invariant Representation

| Paper Title | Venue | Year | Modality | Link |
|-------------|-------|------|----------|------|
| DMR: Decomposed Multi-Modality Representations | NeurIPS | 2022 | RGB + Event | [arXiv](https://arxiv.org/abs/2211.08410) |
| Multi-interactive Feature Learning Benchmark | IJCV | 2021 | RGB-T | [Springer](https://link.springer.com/article/10.1007/s11263-021-01474-9) |

#### 2.1.3 Prompt-Based Learning

| Paper Title | Venue | Year | Modality | Link |
|-------------|-------|------|----------|------|
| SDSTrack: Self-Distillation Symmetric Adapter | CVPR | 2023 | Multi-modal | [arXiv](https://arxiv.org/abs/2303.01977) |
| Visual Prompt for Multi-Modal Tracking | NeurIPS | 2022 | RGB-T | [arXiv](https://arxiv.org/abs/2210.10904) |
| X-Prompt: Cross-modal Prompt for VOS | CVPR | 2023 | Video + Prompt | [arXiv](https://arxiv.org/abs/2304.04223) |
| UniDSeg: Unified Prompt for 3D Segmentation | CVPR | 2024 | RGB + 3D | [arXiv](https://arxiv.org/abs/2311.00277) |
| Dual-Prompt Learning for Efficient Segmentation | ECCV | 2022 | RGB-T | [arXiv](https://arxiv.org/abs/2207.10983) |

---

### 2.2 Training Strategies

| Paper Title | Venue | Year | Method Type | Link |
|-------------|-------|------|-------------|------|
| Complementary Random Masking for RGB-T | ECCV | 2022 | Data Augmentation | [arXiv](https://arxiv.org/abs/2303.17386) |
| Rethinking Reverse Distillation for Multimodal Anomaly Detection | CVPR | 2023 | Knowledge Distillation | [arXiv](https://arxiv.org/abs/2303.02515) |
| Cross-Modal Contrastive Pretraining for Medical Fusion | MICCAI | 2023 | Self-supervised | [Springer](https://link.springer.com/chapter/10.1007/978-3-031-43893-3_28) |
| Modality Dropout for Robust Fusion | TMI | 2022 | Modality Robustness | [IEEE](https://ieeexplore.ieee.org/document/9733185) |
| Joint Feature Regularization for Multi-Stream Fusion | TPAMI | 2023 | Feature Fusion | [IEEE](https://ieeexplore.ieee.org/document/10014115) |

---

 ---

## 🔀 3. Modality-Specific Fusion Techniques

### 3.1 RGB + Audio (Audio-Visual Semantic Segmentation)

| Paper Title | Venue | Year | Fusion Type | Link |
|-------------|-------|------|-------------|------|
| Can Textual Semantics Mitigate Sounding Object Segmentation Preference? | ECCV | 2022 | Audio-Guided Attention | [arXiv](https://arxiv.org/abs/2207.11230) |
| Unveiling and Mitigating Bias in Audio-Visual Segmentation | ECCV | 2022 | Audio-Visual Masking | [GitHub](https://github.com/OpenGVLab/AVSBench) |
| AudioScope: Spatial Audio Segmentation with Unsupervised Clustering | NeurIPS | 2023 | Cross-modal Fusion | [arXiv](https://arxiv.org/abs/2305.01521) |

#### 💡 Notes:
- Typical fusion involves **spectrogram encoding** of audio features (e.g., log-Mel), followed by late or attention-based integration into visual streams.
- Spatial alignment of audio and image cues is key in noisy environments or under occlusion.

---

### 3.2 RGB + Event (Event-based Semantic Segmentation)

| Paper Title | Venue | Year | Fusion Type | Link |
|-------------|-------|------|-------------|------|
| ESS: Learning Event-based Semantic Segmentation from Still Images | CVPR | 2021 | Event Frame Encoding | [GitHub](https://github.com/lyuchenyang/ESS) |
| Combining Events and Frames via Recurrent Asynchronous Networks | ECCV | 2020 | RNN + Fusion | [arXiv](https://arxiv.org/abs/2003.07547) |
| EV-SegNet: Asynchronous Event Segmentation Network | ICCV | 2023 | Hybrid Stream Fusion | [arXiv](https://arxiv.org/abs/2303.13684) |

#### 💡 Notes:
- Event cameras output sparse, high-frequency signals. Fusion methods include **event frame accumulation**, **voxelization**, and **cross-attention with RGB**.
- Event-based fusion is especially beneficial in **HDR** or **fast-motion scenes** where RGB degrades.

---
## 🔄 4. Adaptation Challenges in Multimodal Learning

### 4.1 Modality Adaptation Segmentation

| Paper Title | Venue | Year | Key Idea | Link |
|-------------|-------|------|----------|------|
| Achieving Cross Modal Generalization with Multimodal Unified Representation | NeurIPS | 2022 | Unified Representation for Modal Transfer | [arXiv](https://arxiv.org/abs/2209.15113) |
| Unsupervised Modality Adaptation with Text-to-Image Diffusion | ICCV | 2023 | Diffusion-guided Modality Synthesis | [arXiv](https://arxiv.org/abs/2303.08752) |
| Modality-Aware Knowledge Distillation for RGB-Thermal Tasks | ECCV | 2022 | Cross-modal Teacher-Student Training | [arXiv](https://arxiv.org/abs/2203.01970) |

#### 💡 Notes:
- The goal is to transfer knowledge between different modalities (e.g. RGB→TIR).


---

### 4.2 Missing Modalities

| Paper Title | Venue | Year | Key Idea | Link |
|-------------|-------|------|----------|------|
| Centering the Value of Every Modality: Efficient Modality-Agnostic Segmentation | CVPR | 2023 | Conditional Prompt Fusion | [arXiv](https://arxiv.org/abs/2304.04277) |
| Learning Modality-Agnostic Representation for Semantic Segmentation | NeurIPS | 2022 | Random Modality Dropout + Alignment | [arXiv](https://arxiv.org/abs/2211.11656) |
| Robust Multimodal Learning with Missing Modalities | ICLR | 2023 | Adapter-based Modality Plug-and-Play | [arXiv](https://arxiv.org/abs/2302.03286) |

#### 💡 Notes:
- The design goal is to ensure that the model can effectively predict even if a mode is missing.
---

### 4.3 Cross-Domain & Cross-Modal Domain Adaptation

| Paper Title | Venue | Year | Key Idea | Link |
|-------------|-------|------|----------|------|
| Cross-Domain and Cross-Modal Knowledge Distillation for 3D Segmentation | CVPR | 2022 | KD from Source RGB-LiDAR to Target | [arXiv](https://arxiv.org/abs/2203.05906) |
| Sparse-to-Dense Feature Matching in Cross-Modal Domain Adaptation | ECCV | 2022 | Multi-Level Alignment for RGB-LiDAR | [arXiv](https://arxiv.org/abs/2208.01952) |
| VFM-DA: Vision Foundation Models for Cross-Modal DA | ICCV | 2023 | Foundation Model Pretraining + Adaptation | [arXiv](https://arxiv.org/abs/2304.04513) |
| Towards Source-Free Domain Adaptive Semantic Segmentation Via Importance-Aware and Prototype-Contrast Learning | IEEE | 2024 | Importance-Aware + Prototype-Contrast | [arXiv](https://arxiv.org/abs/2306.01598) |

#### 💡 Notes:
- There is both **modality change** and **domain change** (e.g., RGB-D from indoor→outdoor).






## 📢 Contributions

Pull requests are welcome to expand this resource with new datasets, benchmarks, and literature. Feel free to fork this repo and help build a community resource.

---

## 📄 License

Open for academic and educational use. Please cite original datasets and papers when using any content listed here.
