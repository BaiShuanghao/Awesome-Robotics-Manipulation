# Awesome-Robotics-Manipulation

## ✨ About

This repo contains a curated list of **Robot Manipulation** papers at the intersection of robotics and deep learning..

This repository will be continuously updated, and we warmly welcome contributions from the community. If you have papers, projects, or resources that are not yet included, please feel free to submit them via a pull request, open an issue for discussion or [email](baishuanghao@stu.xjtu.edu.cn) us to add papers! 

<!-- ******* 0-Content Table ******* -->
## 🏠 Table of Contents
- [📝 Awesome Papers](#-awesome-papers)
  - [📄 Survey](#-survey)
  - [🦾 Grasp](#-grasp)
    - [2D Grasp Detection](#2d-grasp-detection)
    - [6-DoF Grasp](#6-dof-grasp)
    - [Grasp in Cluttered Scenes](#grasp-in-cluttered-scenes)
    - [Grasp with 3D Techniques](#grasp-with-3d-techniques)
    - [Language-Driven Grasp](#language-driven-grasp)
    - [Grasp for Transparent Objects](#grasp-for-transparent-objects)
    - [Dexterous Grasp](#dexterous-grasp)
    - [Bimanual Grasp](#bimanual-grasp)
  - [🤖 Manipulation](#-manipulation)
    - [Representation Learning with Auxiliary Tasks](#representation-learning-with-auxiliary-tasks)
    - [Visual Imitation Learning](#visual-imitation-learning)
    - [Learning from Demonstrations](#learning-from-demonstrations)
    - [Latent Action Learning](#latent-action-learning)
    - [World Model](#world-model)
    - [Asynchronous Action Learning](#asynchronous-action-learning)
    - [Diffusion Policy Learning](#diffusion-policy-learning)
    - [Other Policies](#other-policies)
    - [Vision Language Action Models](#vision-language-action-models)
    - [Reinforcement Learning](#reinforcement-learning)
    - [Motion, Tranjectory and Flow](#motion-tranjectory-and-flow)
    - [Data Collection, Selection and Augmentation](#data-collection-selection-and-augmentation)
    - [Affordance Learning](#affordance-learning)
    - [3D Representation for Manipulation](#3d-representation-for-manipulation)
    - [3D Representation Policy Learning](#3d-representation-policy-learning)
    - [High-level Planner](#high-level-planner)
    - [Generalization](#generalization)
    - [Generalist](#generalist)
    - [Human-Robot Interaction and Collaboration](#human-robot-interaction-and-collaboration)
    - [Humanoid Manipulation](#humanoid-manipulation)
    - [Quadrupedal Manipulation](#quadrupedal-manipulation)
    - [Mobile Manipulation](#mobile-manipulation)
    - [Tactile-based Manipulation](#tactile-based-manipulation)
    - [Dexterous Manipulation](#dexterous-manipulation)
    - [Other Applications](#other-applications)
- [📊 Awesome Simulators, Benchmarks and Dataset](#-awesome-simulators-benchmarks-and-dataset)
  - [Grasp Datasets](#grasp-datasets)
  - [Manipulation Simulators and Benchmarks](#manipulation-simulators-and-benchmarks)
  - [Cross-Embodiment Simulators and Benchmarks](#cross-embodiment-simulators-and-benchmarks)
  - [Trajectory Datasets](#trajectory-datasets)
  - [Embodied QA and Affordance Datasets](#embodied-qa-and-affordance-datasets)
- [🛠️ Awesome-techniques](#-awesome-techniques)



<!-- ******* 1-Papers ******* -->
## 📝 Awesome Papers

<!-- ******* 1.1-Survey ******* -->
## 📄 Survey
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**The Developments and Challenges towards Dexterous and Embodied Robotic Manipulation: A Survey**](https://arxiv.org/abs/2507.11840) | arXiv | 2025-07-16 | - | Dexterous Manipulation |
| [**Vision Language Action Models in Robotic Manipulation: A Systematic Review**](https://arxiv.org/abs/2507.10672) | arXiv | 2025-07-14 | - | VLA Models |
| [**A Survey on Vision-Language-Action Models: An Action Tokenization Perspective**](https://arxiv.org/abs/2507.01925) | arXiv | 2025-07-02 | - | VLA Models |
| [**Parallels Between VLA Model Post-Training and Human Motor Learning: Progress, Challenges, and Trends**](https://arxiv.org/abs/2506.20966) | arXiv | 2025-05-26 | ![Star](https://img.shields.io/github/stars/AoqunJin/Awesome-VLA-Post-Training?style=social&label=Star) [Github](https://github.com/AoqunJin/Awesome-VLA-Post-Training) | VLA Models |
| [**Vision-Language-Action Models: Concepts, Progress, Applications and Challenges**](https://arxiv.org/abs/2505.04769) | arXiv | 2025-05-07 | - | VLA Models |
| [**A Survey of Robotic Navigation and Manipulation with Physics Simulators in the Era of Embodied AI**](https://arxiv.org/abs/2505.01458) | arXiv | 2025-05-01 | - | Navigation and Manipulation |
| [**Diffusion Models for Robotic Manipulation: A Survey**](https://arxiv.org/abs/2504.08438) | arXiv | 2025-04-11 | - | DP for Manipulation |
| [**Multimodal Fusion and Vision-Language Models: A Survey for Robot Vision**](https://arxiv.org/abs/2504.02477) | arXiv | 2025-04-03 | ![Star](https://img.shields.io/github/stars/Xiaofeng-Han-Res/MF-RV?style=social&label=Star) [Github](https://github.com/Xiaofeng-Han-Res/MF-RV) | Robot Vision |
| [**Generative Artificial Intelligence in Robotic Manipulation: A Survey**](https://arxiv.org/abs/2503.03464) | arXiv | 2025-03-05 | ![Star](https://img.shields.io/github/stars/GAI4Manipulation/AwesomeGAIManipulation?style=social&label=Star) [Github](https://github.com/GAI4Manipulation/AwesomeGAIManipulation) | Manipulation |
| [**Humanoid Locomotion and Manipulation: Current Progress and Challenges in Control, Planning, and Learning**](https://arxiv.org/abs/2501.02116) | arXiv | 2025-01-03 | - | Humanoid Manipulation |
| [**A Survey of Embodied Learning for Object-Centric Robotic Manipulation**](https://arxiv.org/abs/2408.11537) | arXiv | 2024-08-21 | ![Star](https://img.shields.io/github/stars/RayYoh/OCRM_survey?style=social&label=Star) [Github](https://github.com/RayYoh/OCRM_survey) | Manipulation |
| [**Aligning Cyber Space with Physical World: A Comprehensive Survey on Embodied AI**](https://arxiv.org/abs/2407.06886) | arXiv | 2024-07-09 | ![Star](https://img.shields.io/github/stars/HCPLab-SYSU/Embodied_AI_Paper_List?style=social&label=Star) [Github](https://github.com/HCPLab-SYSU/Embodied_AI_Paper_List) | Embodied Agent |
| [**A Survey on Vision-Language-Action Models for Embodied AI**](https://arxiv.org/abs/2405.14093) | arXiv | 2024-05-23 | - | VLA Models |
| [**Survey of Learning-based Approaches for Robotic In-Hand Manipulation**](https://arxiv.org/abs/2401.07915) | arXiv | 2024-01-15 | - | In-hand Manipulation |
| [**Language-conditioned Learning for Robotic Manipulation: A Survey**](https://arxiv.org/abs/2312.10807) | arXiv | 2023-12-17 | ![Star](https://img.shields.io/github/stars/hk-zh/language-conditioned-robot-manipulation-models?style=social&label=Star) [Github](https://github.com/hk-zh/language-conditioned-robot-manipulation-models) | Manipulation |
| [**Deep Learning Approaches to Grasp Synthesis: A Review**](https://arxiv.org/abs/2207.02556) | T-RO 2023 | 2023-07-06 | [Project](https://rhys-newbury.github.io/projects/6dof/) | Grasp |
| [**Teleoperation of Humanoid Robots: A Survey**](https://arxiv.org/abs/2301.04317) | T-RO 2024 | 2023-01-11 | [Project](https://humanoid-teleoperation.github.io/)

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


<!-- ******* 1.2-Grasp ******* -->
## 🦾 Grasp

<!-- ******* 1.2.1-2D Grasp Detection ******* -->
### 2D Grasp Detection
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**RoboGrasp: A Universal Grasping Policy for Robust Robotic Control**](https://arxiv.org/abs/2502.03072) | arXiv | 2025-02-05 | - | |
| [**HMT-Grasp: A Hybrid Mamba-Transformer Approach for Robot Grasping in Cluttered Environments**](https://arxiv.org/abs/2410.03522) | arXiv | 2024-10-04 | - | |
| [LLGD: **Lightweight Language-driven Grasp Detection using Conditional Consistency Model**](https://arxiv.org/abs/2407.17967) | IROS 2024 | 2024-07-25 | ![Star](https://img.shields.io/github/stars/Fsoft-AIC/Lightweight-Language-driven-Grasp-Detection?style=social&label=Star) [Github](https://github.com/Fsoft-AIC/Lightweight-Language-driven-Grasp-Detection) | |
| [grasp_det_seg_cnn: **End-to-end Trainable Deep Neural Network for Robotic Grasp Detection and Semantic Segmentation from RGB**](https://arxiv.org/abs/2107.05287) | ICRA 2021 | 2021-07-12 | ![Star](https://img.shields.io/github/stars/stefan-ainetter/grasp_det_seg_cnn?style=social&label=Star) [Github](https://github.com/stefan-ainetter/grasp_det_seg_cnn) |  |
| [GR-ConvNet: **Antipodal Robotic Grasping using Generative Residual Convolutional Neural Network**](https://arxiv.org/abs/1909.04810) | IROS 2020 | 2019-09-11 | ![Star](https://img.shields.io/github/stars/skumra/robotic-grasping?style=social&label=Star)  [Github](https://github.com/skumra/robotic-grasping) |  |
| [**Closing the Loop for Robotic Grasping: A Real-time, Generative Grasp Synthesis Approach**](https://arxiv.org/abs/1804.05172) | RSS 2018 | 2018-04-14 | ![Star](https://img.shields.io/github/stars/dougsm/ggcnn?style=social&label=Star)  [Github](https://github.com/dougsm/ggcnn) |  |
| [**Robotic Grasp Detection using Deep Convolutional Neural Networks**](https://arxiv.org/abs/1611.08036) | IROS 2017 | 2016-11-24 | ![Star](https://img.shields.io/github/stars/tnikolla/robot-grasp-detection?style=social&label=Star)  [Github](https://github.com/tnikolla/robot-grasp-detection) |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.2.2-6-DoF Grasp ******* -->
### 6-DoF Grasp
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**MISCGrasp: Leveraging Multiple Integrated Scales and Contrastive Learning for Enhanced Volumetric Grasping**](https://arxiv.org/abs/2507.02672) | arXiv | 2025-07-02 | [Project](https://miscgrasp.github.io/) |  |
| [**GraspMolmo: Generalizable Task-Oriented Grasping via Large-Scale Synthetic Data Generation**](https://arxiv.org/abs/2505.13441) | arXiv | 2025-05-16 | ![Star](https://img.shields.io/github/stars/abhaybd/GraspMolmo?style=social&label=Star) [Github](https://github.com/abhaybd/GraspMolmo) |  |
| [**Exploiting Radiance Fields for Grasp Generation on Novel Synthetic Views**](https://arxiv.org/abs/2505.11467) | RSSW 2025 | 2025-05-16 | ![Star](https://img.shields.io/github/stars/Ali-Rashidi/GtG2?style=social&label=Star) [Github](https://github.com/Ali-Rashidi/GtG2) |  |
| [**Grasp the Graph (GtG) 2.0: Ensemble of GNNs for High-Precision Grasp Pose Detection in Clutter**](https://arxiv.org/abs/2505.02664) | arXiv | 2025-05-05 | ![Star](https://img.shields.io/github/stars/Ali-Rashidi/GtG2?style=social&label=Star) [Github](https://github.com/Ali-Rashidi/GtG2) |  |
| [**PCF-Grasp: Converting Point Completion to Geometry Feature to Enhance 6-DoF Grasp**](https://arxiv.org/abs/2504.16320) | arXiv | 2025-04-22 | ![Star](https://img.shields.io/github/stars/ChengYaofeng/PCF-Grasp?style=social&label=Star) [Github](https://github.com/ChengYaofeng/PCF-Grasp) |  |
| [**Real-to-Sim Grasp: Rethinking the Gap between Simulation and Real World in Grasp Detection**](https://arxiv.org/abs/2410.06521) | CoRL 2024 | 2024-10-09 | [Project](https://isee-laboratory.github.io/R2SGrasp/) | Real2Sim |
| [**OrbitGrasp: SE(3)-Equivariant Grasp Learning**](https://arxiv.org/abs/2407.03531) | CoRL 2024 | 2024-07-03 | [Project](https://orbitgrasp.github.io/) | Equivariance |
| [**EquiGraspFlow: SE(3)-Equivariant 6-DoF Grasp Pose Generative Flows**](https://openreview.net/pdf?id=5lSkn5v4LK) | CoRL 2024 | 2024-09-06 | ![Star](https://img.shields.io/github/stars/bdlim99/EquiGraspFlow?style=social&label=Star) [Github](https://github.com/bdlim99/EquiGraspFlow) | Equivariance |
| [EconomicGrasp: **An Economic Framework for 6-DoF Grasp Detection**](https://arxiv.org/abs/2407.08366) | ECCV 2024 | 2024-07-11 | ![Star](https://img.shields.io/github/stars/iSEE-Laboratory/EconomicGrasp?style=social&label=Star) [Github](https://github.com/iSEE-Laboratory/EconomicGrasp) | Scene-level |
| [**Generalizing 6-DoF Grasp Detection via Domain Prior Knowledge**](https://arxiv.org/abs/2404.01727) | CVPR 2024 | 2024-04-02 | ![Star](https://img.shields.io/github/stars/mahaoxiang822/Generalizing-Grasp?style=social&label=Star) [Github](https://github.com/mahaoxiang822/Generalizing-Grasp) | Generalization |
| [FlexLoG: **Rethinking 6-Dof Grasp Detection: A Flexible Framework for High-Quality Grasping**](https://arxiv.org/abs/2403.15054) | PR 2025 | 2024-03-22 | - | Target-oriented |
| [**AnyGrasp: Robust and Efficient Grasp Perception in Spatial and Temporal Domains**](https://arxiv.org/abs/2212.08333) | T-RO 2023 | 2022-12-16 | ![Star](https://img.shields.io/github/stars/graspnet/anygrasp_sdk?style=social&label=Star) [Github](https://github.com/graspnet/anygrasp_sdk) | |
| [**6-DOF GraspNet: Variational Grasp Generation for Object Manipulation**](https://arxiv.org/abs/1905.10520) | ICCV 2019 | 2019-05-25 | ![Star](https://img.shields.io/github/stars/NVlabs/6dof-graspnet?style=social&label=Star) [Github](https://github.com/NVlabs/6dof-graspnet) | VAE |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.2.3-Grasp in Cluttered Scenes ******* -->
### Grasp in Cluttered Scenes
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**ClutterDexGrasp: A Sim-to-Real System for General Dexterous Grasping in Cluttered Scenes**](https://arxiv.org/abs/2506.14317) | arXiv | 2025-05-17 | [Project](https://clutterdexgrasp.github.io/) | |
| [HGGD: **Efficient Heatmap-Guided 6-Dof Grasp Detection in Cluttered Scenes**](https://arxiv.org/abs/2403.18546) | RA-L 2023 | 2024-03-27 | ![Star](https://img.shields.io/github/stars/THU-VCLab/HGGD?style=social&label=Star) [Github](https://github.com/THU-VCLab/HGGD) | Scene-level |
| [**Contact-GraspNet: Efficient 6-DoF Grasp Generation in Cluttered Scenes**](https://arxiv.org/abs/2103.14127) | ICRA 2021 | 2021-03-25 | ![Star](https://img.shields.io/github/stars/NVlabs/contact_graspnet?style=social&label=Star) [Github](https://github.com/NVlabs/contact_graspnet) | |
| [**GraspNet-1Billion: A Large-Scale Benchmark for General Object Grasping**](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fang_GraspNet-1Billion_A_Large-Scale_Benchmark_for_General_Object_Grasping_CVPR_2020_paper.pdf) | CVPR 2020 | 2020-08-05 | ![Star](https://img.shields.io/github/stars/graspnet/graspnet-baseline?style=social&label=Star) [Github](https://github.com/graspnet/graspnet-baseline) | Scene-level |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.2.4-Grasp with 3D Techniques ******* -->
### Grasp with 3D Techniques
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**ZeroGrasp: Zero-Shot Shape Reconstruction Enabled Robotic Grasping**](https://arxiv.org/abs/2504.10857) | CVPR 2025 | 2025-04-15 | [Project](https://sh8.io/#/zerograsp) |  |
| _SDF_|
| [IGD: **Implicit Grasp Diffusion: Bridging the Gap between Dense Prediction and Sampling-based Grasping**](https://openreview.net/pdf?id=VUhlMfEekm) | CoRL 2024 | 2024-09-05 | ![Star](https://img.shields.io/github/stars/mousecpn/Implicit-Grasp-Diffusion?style=social&label=Star) [Github](https://github.com/mousecpn/Implicit-Grasp-Diffusion) |  |
| [NeuGraspNet: **Learning Any-View 6DoF Robotic Grasping in Cluttered Scenes via Neural Surface Rendering**](https://arxiv.org/abs/2306.07392) | RSS 2024 | 2023-06-12 | - | |
| _NeRF_ |
| [LERF-TOGO: **Language Embedded Radiance Fields for Zero-Shot Task-Oriented Grasping**](https://arxiv.org/abs/2309.07970) | CoRL 2023 | 2023-09-14 | ![Star](https://img.shields.io/github/stars/lerftogo/lerftogo?style=social&label=Star) [Github](https://github.com/lerftogo/lerftogo) | LERF |
| [**GraspNeRF: Multiview-based 6-DoF Grasp Detection for Transparent and Specular Objects Using Generalizable NeRF**](https://arxiv.org/abs/2210.06575) | ICRA 2023 | 2022-10-12 | ![Star](https://img.shields.io/github/stars/PKU-EPIC/GraspNeRF?style=social&label=Star) [Github](https://github.com/PKU-EPIC/GraspNeRF) | |
| _3D Gaussian Splatting (3DGS)_ |
| [**SparseGrasp: Robotic Grasping via 3D Semantic Gaussian Splatting from Sparse Multi-View RGB Images**](https://arxiv.org/abs/2412.02140) | arXiv | 2024-12-03 | - | |
| [**GraspSplats: Efficient Manipulation with 3D Feature Splatting**](https://arxiv.org/abs/2409.02084) | CoRL 2024 | 2024-09-03 | ![Star](https://img.shields.io/github/stars/jimazeyu/GraspSplats?style=social&label=Star) [Github](https://github.com/jimazeyu/GraspSplats) | |
| [**GaussianGrasper: 3D Language Gaussian Splatting for Open-vocabulary Robotic Grasping**](https://arxiv.org/abs/2403.09637) | RA-L 2024 | 2024-03-14 | ![Star](https://img.shields.io/github/stars/MrSecant/GaussianGrasper?style=social&label=Star) [Github](https://github.com/MrSecant/GaussianGrasper) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.2.5-Language-Driven Grasp ******* -->
### Language-Driven Grasp
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**FineGrasp: Towards Robust Grasping for Delicate Objects**](https://arxiv.org/abs/2507.05978) | arXiv | 2025-07-08 | ![Star](https://img.shields.io/github/stars/HorizonRobotics/robo_orchard_lab?style=social&label=Star) [Github](https://github.com/HorizonRobotics/robo_orchard_lab/tree/master/projects/finegrasp_graspnet1b) | |
| [**MapleGrasp: Mask-guided Feature Pooling for Language-driven Efficient Robotic Grasping**](https://arxiv.org/abs/2506.06535) | arXiv | 2025-06-06 | - | |
| [**GraspCorrect: Robotic Grasp Correction via Vision-Language Model-Guided Feedback***](https://arxiv.org/abs/2503.15035) | arXiv | 2025-03-19 | - | |
| [**Free-form language-based robotic reasoning and grasping**](https://arxiv.org/abs/2503.13082) | arXiv | 2025-03-17 | [Project](https://tev-fbk.github.io/FreeGrasp/) | |
| [**AffordGrasp: In-Context Affordance Reasoning for Open-Vocabulary Task-Oriented Grasping in Clutter**](https://arxiv.org/abs/2503.00778) | arXiv | 2025-03-02 | [Project](https://eqcy.github.io/affordgrasp/) | |
| [**RoboReflect: Robotic Reflective Reasoning for Grasping Ambiguous-Condition Objects**](https://arxiv.org/abs/2501.09307) | arXiv | 2025-01-16 | - | |
| [**Attribute-Based Robotic Grasping with Data-Efficient Adaptation**](https://arxiv.org/abs/2501.02149) | T-RO 2024 | 2024-12-12 | [Project](https://sites.google.com/umn.edu/attributes-grasping) | |
| [**RTAGrasp: Learning Task-Oriented Grasping from Human Videos via Retrieval, Transfer, and Alignment**](https://arxiv.org/abs/2409.16033) | ICRA 2025 | 2024-09-24 | [Project](https://sites.google.com/view/rtagrasp/home) | LfD |
| [LGrasp6D: **Language-Driven 6-DoF Grasp Detection Using Negative Prompt Guidance**](https://arxiv.org/abs/2407.13842) | ECCV 2024 | 2024-07-18 | ![Star](https://img.shields.io/github/stars/Fsoft-AIC/Language-Driven-6-DoF-Grasp-Detection-Using-Negative-Prompt-Guidance?style=social&label=Star) [Github](https://github.com/Fsoft-AIC/Language-Driven-6-DoF-Grasp-Detection-Using-Negative-Prompt-Guidance) | |
| [Reasoning Grasping: **Reasoning Grasping via Multimodal Large Language Model**](https://arxiv.org/abs/2402.06798) | CoRL 2024 | 2024-02-09 | [Project](https://reasoning-grasping.github.io/) | LLMs |
| [**ThinkGrasp: A Vision-Language System for Strategic Part Grasping in Clutter**](https://arxiv.org/abs/2407.11298) | CoRL 2024 | 2024-07-16 | ![Star](https://img.shields.io/github/stars/H-Freax/ThinkGrasp?style=social&label=Star) [Github](https://github.com/H-Freax/ThinkGrasp) | MLLMs |
| [OWG: **Towards Open-World Grasping with Large Vision-Language Models**](https://arxiv.org/abs/2406.18722) | CoRL 2024 | 2024-06-26 | [Project](https://gtziafas.github.io/OWG_project/) | MLLMs |
| [**RT-Grasp: Reasoning Tuning Robotic Grasping via Multi-modal Large Language Model**](https://arxiv.org/abs/2411.05212) | IROS 2024 | 2024-11-07 | [Project](https://sites.google.com/view/rt-grasp) | Tunning MLLMs |
| [**VL-Grasp: a 6-Dof Interactive Grasp Policy for Language-Oriented Objects in Cluttered Indoor Scenes**](https://arxiv.org/abs/2308.00640) | IROS 2023 | 2023-08-01 | ![Star](https://img.shields.io/github/stars/luyh20/VL-Grasp?style=social&label=Star) [Github](https://github.com/luyh20/VL-Grasp) | |
| [**GraspGPT: Leveraging Semantic Knowledge from a Large Language Model for Task-Oriented Grasping**](https://arxiv.org/abs/2307.13204) | RA-L 2023 | 2023-07-25 | ![Star](https://img.shields.io/github/stars/mkt1412/GraspGPT_public?style=social&label=Star) [Github](https://github.com/mkt1412/GraspGPT_public) | |
| [**A Joint Modeling of Vision-Language-Action for Target-oriented Grasping in Clutter**](https://arxiv.org/abs/2302.12610) | ICRA 2023 | 2023-02-24 | ![Star](https://img.shields.io/github/stars/xukechun/Vision-Language-Grasping?style=social&label=Star) [Github](https://github.com/xukechun/Vision-Language-Grasping) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.2.6-Grasp for Transparent Objects ******* -->
### Grasp for Transparent Objects
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**DCIRNet: Depth Completion with Iterative Refinement for Dexterous Grasping of Transparent and Reflective Objects**](https://arxiv.org/abs/2506.09491) | arXiv | 2025-06-11 | - | |
| [**SR3D: Unleashing Single-view 3D Reconstruction for Transparent and Specular Object Grasping**](https://arxiv.org/abs/2505.24305) | arXiv | 2025-05-30 | [Project](https://sites.google.com/view/sr3dtech/) | |
| [**FuseGrasp: Radar-Camera Fusion for Robotic Grasping of Transparent Objects**](https://arxiv.org/abs/2502.20037) | arXiv | 2025-02-27 | - | |
| [**TranSplat: Surface Embedding-guided 3D Gaussian Splatting for Transparent Object Manipulation**](https://arxiv.org/abs/2502.07840) | arXiv | 2025-02-11 | - | |
| [**T<sup>2</sup>SQNet: A Recognition Model for Manipulating Partially Observed Transparent Tableware Objects**](https://openreview.net/pdf?id=M0JtsLuhEE) | CoRL 2024 | 2024-09-06 | ![Star](https://img.shields.io/github/stars/seungyeon-k/T2SQNet-public?style=social&label=Star) [Github](https://github.com/seungyeon-k/T2SQNet-public) | |
| [**ASGrasp: Generalizable Transparent Object Reconstruction and Grasping from RGB-D Active Stereo Camera**](https://arxiv.org/abs/2405.05648) | ICRA 2024 | 2024-05-09 | ![Star](https://img.shields.io/github/stars/jun7-shi/ASGrasp?style=social&label=Star) [Github](https://github.com/jun7-shi/ASGrasp) | |
| [**Dex-NeRF: Using a Neural Radiance Field to Grasp Transparent Objects**](https://arxiv.org/abs/2110.14217) | CoRL 2021 | 2021-10-27 | ![Star](https://img.shields.io/github/stars/BerkeleyAutomation/dex-nerf-datasets?style=social&label=Star) [Github](https://github.com/BerkeleyAutomation/dex-nerf-datasets) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.2.7-Dexterous Grasp ******* -->
### Dexterous Grasp
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**You Only Estimate Once: Unified, One-stage, Real-Time Category-level Articulated Object 6D Pose Estimation for Robotic Grasping**](https://arxiv.org/abs/2506.05719) | ICRA 2025 | 2025-06-06 | [Project](https://shanehuanghz.github.io/YOEO/) |  |
| [**Grasp What You Want: Embodied Dexterous Grasping System Driven by Your Voice**](https://arxiv.org/abs/2412.10694) | arXiv | 2024-12-14 | [Project](https://isee-laboratory.github.io/R2SGrasp/) | Real2Sim |
| [**UniGraspTransformer: Simplified Policy Distillation for Scalable Dexterous Robotic Grasping**](https://arxiv.org/abs/2412.02699) | arXiv | 2024-12-03 | ![Star](https://img.shields.io/github/stars/microsoft/UniGraspTransformer?style=social&label=Star) [Github](https://github.com/microsoft/UniGraspTransformer) | |
| [**D(R, O) Grasp: A Unified Representation of Robot and Object Interaction for Cross-Embodiment Dexterous Grasping**](https://arxiv.org/abs/2410.01702) | CoRLW 2024 | 2024-10-02 | ![Star](https://img.shields.io/github/stars/zhenyuwei2003/DRO-Grasp?style=social&label=Star) [Github](https://github.com/zhenyuwei2003/DRO-Grasp) |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


<!-- ******* 1.2.8-Bimanual Grasp ******* -->
### Bimanual Grasp
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**COMBO-Grasp: Learning Constraint-Based Manipulation for Bimanual Occluded Grasping**](https://arxiv.org/abs/2502.08054) | arXiv | 2025-02-12 | [Project](https://combo-grasp.github.io/) | |
| [**Learning Ambidextrous Robot Grasping Policies**](https://www.science.org/doi/10.1126/scirobotics.aau4984?ijkey=IogH9u4mOL70s&keytype=ref&siteid=robotics) | SR 2019 | 2029-01-30 | - | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>



<!-- ******* 1.3-Manipulation ******* -->
## 🤖 Manipulation

<!-- ******* 1.3.1-Representation Learning with Auxiliary Tasks ******* -->
### Representation Learning with Auxiliary Tasks
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Contrastive Learning (Alignment)_ |
| [Σ-agent: **Contrastive Imitation Learning for Language-guided Multi-Task Robotic Manipulation**](https://arxiv.org/abs/2406.09738) | CoRL 2024 | 2024-06-14 | [Project](https://teleema.github.io/projects/Sigma_Agent/) | IL, RepL, Poliy Head, Alignment |
| [**Vid2Robot: End-to-end Video-conditioned Policy Learning with Cross-Attention Transformers**](https://arxiv.org/abs/2403.12943) | RSS 2024 | 2024-03-19 | [Project](https://vid2robot.github.io/) | IL, RepL, LfD, E-D, Poliy Head, Language Goal, Alignment |
| [**R3M: A Universal Visual Representation for Robot Manipulation**](https://arxiv.org/abs/2203.12601) | CoRL 2022 | 2022-03-23 | ![Star](https://img.shields.io/github/stars/facebookresearch/r3m?style=social&label=Star) [Github](https://github.com/facebookresearch/r3m) | IL, RepL, LfD, Alignment, Language Goal, Poliy Head |
| [HULC: **What Matters in Language Conditioned Robotic Imitation Learning over Unstructured Data**](https://arxiv.org/abs/2204.06252) | RA-L 2022 | 2022-04-13 | ![Star](https://img.shields.io/github/stars/lukashermann/hulc?style=social&label=Star) [Github](https://github.com/lukashermann/hulc) | IL, RepL, Alignment, Language Goal, Poliy Head |
| [**BC-Z: Zero-Shot Task Generalization with Robotic Imitation Learning**](https://arxiv.org/abs/2202.02005) | CoRL 2021 | 2022-02-04 | ![Star](https://img.shields.io/github/stars/google-research/tensor2robot?style=social&label=Star) [Github](https://github.com/google-research/tensor2robot/tree/master/research/bcz) | IL, RepL, Language Goal, Alignment, Poliy Head |
| _Masked Reconstruction_ |
| [STP: **Spatiotemporal Predictive Pre-training for Robotic Motor Control**](https://arxiv.org/abs/2403.05304) | arXiv | 2024-03-08 | - | IL, RepL, Masked Construction, Image Prediction, Poliy Head  |
| [**MUTEX: Learning Unified Policies from Multimodal Task Specifications**](https://arxiv.org/abs/2309.14320) | CoRL 2023 | 2023-09-25 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/mutex?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/mutex) | IL, RepL, Multimodal, E-D, Masked Construction, TP |
| [**Robot Learning with Sensorimotor Pre-training**](https://arxiv.org/abs/2306.10007) | CoRL 2023 | 2023-06-16 | [Project](https://robotic-pretrained-transformer.github.io/) | |
| [Voltron: **Language-Driven Representation Learning for Robotics**](https://arxiv.org/abs/2302.12766) | RSS 2023 | 2023-02-24 | ![Star](https://img.shields.io/github/stars/siddk/voltron-robotics?style=social&label=Star) [Github](https://github.com/siddk/voltron-robotics) | IL, RepL, Masked Construction, Both Goals, Poliy Head |
| [MVP: **Real-World Robot Learning with Masked Visual Pre-training**](https://arxiv.org/abs/2210.03109) | CoRL 2022 | 2022-10-06 | ![Star](https://img.shields.io/github/stars/ir413/mvp?style=social&label=Star) [Github](https://github.com/ir413/mvp) | IL, RepL, Masked Construction, Image Goal, Poliy Head |
| _Text Goal Generation_ |
| [**Gondola: Grounded Vision Language Planning for Generalizable Robotic Manipulation**](https://arxiv.org/abs/2506.11261) | arXiv | 2025-06-12 | [Project](https://cshizhe.github.io/projects/robot_gondola.html) | |
| [**RACER: Rich Language-Guided Failure Recovery Policies for Imitation Learning**](https://arxiv.org/abs/2409.14674) | ICRA 2025 | 2024-09-23 | ![Star](https://img.shields.io/github/stars/sled-group/RACER?style=social&label=Star) [Github](https://github.com/sled-group/RACER) | IL, RepL, Human Intervention Generation, Poliy Head, Language Goal |
| [**EmbodiedGPT: Vision-Language Pre-Training via Embodied Chain of Thought**](https://arxiv.org/abs/2305.15021) | NeurIPS 2023 | 2023-05-24 | ![Star](https://img.shields.io/github/stars/EmbodiedGPT/EmbodiedGPT_Pytorch?style=social&label=Star) [Github](https://github.com/EmbodiedGPT/EmbodiedGPT_Pytorch) |  |
| [COTPC: **Chain-of-Thought Predictive Control**](https://arxiv.org/abs/2304.00776) | ICML 2024 | 2023-04-03 | ![Star](https://img.shields.io/github/stars/SeanJia/CoTPC?style=social&label=Star) [Github](https://github.com/SeanJia/CoTPC) | IL, RepL, CoT  |
| _Visual Goal Generation_ |
| [**VIRT: Vision Instructed Transformer for Robotic Manipulation**](https://arxiv.org/abs/2410.07169) | arXiv | 2024-10-09 | ![Star](https://img.shields.io/github/stars/Lizhuoling/VIRT?style=social&label=Star) [Github](https://github.com/Lizhuoling/VIRT) |  |
| [**KOI: Accelerating Online Imitation Learning via Hybrid Key-state Guidance**](https://www.arxiv.org/abs/2408.02912) | CoRL 2024 | 2024-08-06 | ![Star](https://img.shields.io/github/stars/GeWu-Lab/Keystate_Online_Imitation?style=social&label=Star) [Github](https://github.com/GeWu-Lab/Keystate_Online_Imitation) | Online IL, Motion Key States |
| [GENIMA: **Generative Image as Action Models**](https://arxiv.org/abs/2407.07875) | CoRL 2024 | 2024-07-10 | ![Star](https://img.shields.io/github/stars/MohitShridhar/genima?style=social&label=Star)  [Github](https://github.com/MohitShridhar/genima) | diffusion, draw joint-actions |
| [ATM: **Any-point Trajectory Modeling for Policy Learning**](https://arxiv.org/abs/2401.00025) | RSS 2024 | 2023-12-28 | ![Star](https://img.shields.io/github/stars/Large-Trajectory-Model/any-point-trajectory-modeling?style=social&label=Star) [Github](https://github.com/Large-Trajectory-Model/any-point-trajectory-modeling) | IL, RepL, Point Trajectories Generation |
| [MPI: **Learning Manipulation by Predicting Interaction**](https://www.arxiv.org/abs/2406.00439) | RSS 2024 | 2024-06-01 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/MPI?style=social&label=Star) [Github](https://github.com/OpenDriveLab/MPI) | IL, RepL, Interaction-oriented Prediction, Both Goals, Poliy Head |
| [OCI: **Object-Centric Instruction Augmentation for Robotic Manipulation**](https://arxiv.org/abs/2401.02814) | ICRA 2024 | 2024-01-05 | [Project](https://oci-robotics.github.io/) |  IL, RepL, Object-Centric Information Generation, Poliy Head, Language Goal |
| [HOPMan: **Towards Generalizable Zero-Shot Manipulation via Translating Human Interaction Plans**](https://arxiv.org/abs/2312.00775) | ICRA 2024 | 2023-12-01 | [Project](https://homangab.github.io/hopman/) | IL, RepL, LfD, Image Goal, E-D, TP, Human-Plan Generation |
| [**CALAMARI: Contact-Aware and Language conditioned spatial Action MApping for contact-RIch manipulation**](https://openreview.net/pdf?id=Nii0_rRJwN) | CoRL 2023 | 2023-08-30 | [Project](https://www.mmintlab.com/research/calamari/) | RepL, Language Goal, Contact Goal Generation |
| _Image / Video Prediction_ |
| [**Generalist Bimanual Manipulation via Foundation Video Diffusion Models**](https://arxiv.org/abs/2507.12898) | arXiv | 2025-07-17 | - |  |
| [**RwoR: Generating Robot Demonstrations from Human Hand Collection for Policy Learning without Robot**](https://arxiv.org/abs/2507.03930) | arXiv | 2025-07-05 | - |  |
| [**RoboEnvision: A Long-Horizon Video Generation Model for Multi-Task Robot Manipulation**](https://arxiv.org/abs/2506.22007) | arXiv | 2025-06-27 | [Project](https://rwor.github.io/) |  |
| [**Self-Adapting Improvement Loops for Robotic Learning**](https://arxiv.org/abs/2506.06658) | arXiv | 2025-06-07 | [Project](https://diffusion-supervision.github.io/sail/) |  |
| [**ORV: 4D Occupancy-centric Robot Video Generation**](https://arxiv.org/abs/2506.03079) | arXiv | 2025-06-03 | ![Star](https://img.shields.io/github/stars/OrangeSodahub/ORV?style=social&label=Star) [Github](https://github.com/OrangeSodahub/ORV) |  |
| [**Learning Video Generation for Robotic Manipulation with Collaborative Trajectory Control**](https://arxiv.org/abs/2506.01943) | arXiv | 2025-06-02 | ![Star](https://img.shields.io/github/stars/KwaiVGI/RoboMaster?style=social&label=Star) [Github](https://github.com/KwaiVGI/RoboMaster) |  |
| [**GEVRM: Goal-Expressive Video Generation Model For Robust Visual Manipulation**](https://arxiv.org/abs/2502.09268) | ICLR 2025 | 2025-02-13 | - |  |
| [Seer: **Predictive Inverse Dynamics Models are Scalable Learners for Robotic Manipulation**](https://arxiv.org/abs/2412.15109) | ICLR 2025 | 2024-12-19 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/Seer?style=social&label=Star) [Github](https://github.com/OpenRobotLab/Seer/) |  |
| [**Video Prediction Policy: A Generalist Robot Policy with Predictive Visual Representations**](https://arxiv.org/abs/2412.14803) | ICML 2025 | 2024-12-19 | [Project](https://video-prediction-policy.github.io/) |  |
| [**GHIL-Glue: Hierarchical Control with Filtered Subgoal Images**](https://arxiv.org/abs/2410.20018) | arXiv | 2024-10-26 | [Project](https://ghil-glue.github.io/) |  |
| [**FoAM: Foresight-Augmented Multi-Task Imitation Policy for Robotic Manipulation**](https://arxiv.org/abs/2409.19528) | arXiv | 2024-09-29 | [Project](https://projfoam.github.io/) |  |
| [**VideoAgent: Self-Improving Video Generation**](https://arxiv.org/abs/2410.10076) | arXiv | 2024-10-14 | ![Star](https://img.shields.io/github/stars/video-as-agent/videoagent?style=social&label=Star) [Github](https://github.com/video-as-agent/videoagent) |  |
| [**GR-MG: Leveraging Partially Annotated Data via Multi-Modal Goal Conditioned Policy**](https://arxiv.org/abs/2408.14368) | RA-L 2025 | 2024-08-26 | ![Star](https://img.shields.io/github/stars/bytedance/GR-MG?style=social&label=Star) [Github](https://github.com/bytedance/GR-MG) | IL, RepL, Image Prediction, Text State Prediction, Partially labeled data, TP |
| [**GR-2: A Generative Video-Language-Action Model with Web-Scale Knowledge for Robot Manipulation**](https://arxiv.org/abs/2410.06158) | arXiv | 2024-10-08 | [Project](https://gr2-manipulation.github.io/) | IL, RepL, Image Prediction, TP |
| [**VLMPC: Vision-Language Model Predictive Control for Robotic Manipulation**](https://arxiv.org/abs/2407.09829) | RSS 2024 | 2024-07-13 | ![Star](https://img.shields.io/github/stars/PPjmchen/VLMPC?style=social&label=Star) [Github](https://github.com/PPjmchen/VLMPC) | IL, RepL, Video Prediction, MPC |
| [GR-1: **Unleashing Large-Scale Video Generative Pre-training for Visual Robot Manipulation**](https://arxiv.org/abs/2312.13139) | ICLR 2024 | 2023-12-20 | ![Star](https://img.shields.io/github/stars/bytedance/GR-1?style=social&label=Star) [Github](https://github.com/bytedance/GR-1) | IL, RepL, Image Prediction, TP |
| [SuSIE: **Zero-Shot Robotic Manipulation with Pretrained Image-Editing Diffusion Models**](https://arxiv.org/abs/2310.10639) | ICLR 2024 | 2023-10-16 | ![Star](https://img.shields.io/github/stars/kvablack/susie?style=social&label=Star) [Github](https://github.com/kvablack/susie) |  |
| [VLP: **Video Language Planning**](https://arxiv.org/abs/2310.10625) | ICLR 2024 | 2023-10-16 | [Github](https://github.com/video-language-planning/vlp_code) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.2-Visual Imitation Learning ******* -->
### Visual Imitation Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Behavioral Exploration: Learning to Explore via In-Context Adaptation**](https://arxiv.org/abs/2507.09041) | arXiv | 2025-07-11 | - |  |
| [**Is an object-centric representation beneficial for robotic manipulation ?**](https://arxiv.org/abs/2506.19408) | arXiv | 2025-06-24 | - |  |
| [**Robust Instant Policy: Leveraging Student's t-Regression Model for Robust In-context Imitation Learning of Robot Manipulation**](https://arxiv.org/abs/2506.15157) | arXiv | 2025-06-18 | [Project](https://sites.google.com/view/robustinstantpolicy) |  |
| [**SAIL: Faster-than-Demonstration Execution of Imitation Learning Policies**](https://arxiv.org/abs/2506.11948) | arXiv | 2025-06-13 | [Project](https://demospeedup.github.io/) |  |
| [**DemoSpeedup: Accelerating Visuomotor Policies via Entropy-Guided Demonstration Acceleration**](https://arxiv.org/abs/2506.05064) | arXiv | 2025-06-05 | [Project](https://demospeedup.github.io/) |  |
| [**SEM: Enhancing Spatial Understanding for Robust Robot Manipulation**](https://arxiv.org/abs/2505.16196) | arXiv | 2025-05-22 | - |  |
| [**H2R: A Human-to-Robot Data Augmentation for Robot Pre-training from Videos**](https://arxiv.org/abs/2505.11920) | arXiv | 2025-05-17 | - |  |
| [**L2D2: Robot Learning from 2D Drawings**](https://arxiv.org/abs/2505.12072) | arXiv | 2025-05-17 | [Project](https://collab.me.vt.edu/L2D2/) |  |
| [**Exploring Pose-Guided Imitation Learning for Robotic Precise Insertion**](https://arxiv.org/abs/2505.09424) | arXiv | 2025-05-14 | ![Star](https://img.shields.io/github/stars/sunhan1997/PoseInsert?style=social&label=Star) [Github](https://github.com/sunhan1997/PoseInsert) |  |
| [**Augmented Reality for RObots (ARRO): Pointing Visuomotor Policies Towards Visual Robustness**](https://arxiv.org/abs/2505.08627) | arXiv | 2025-05-13 | [Project](https://augmented-reality-for-robots.github.io/) |  |
| [**RoboGround: Robotic Manipulation with Grounded Vision-Language Priors**](https://arxiv.org/abs/2504.21530) | CVPR 2025 | 2025-04-30 | ![Star](https://img.shields.io/github/stars/ZzZZCHS/RoboGround?style=social&label=Star) [Github](https://github.com/ZzZZCHS/RoboGround) |  |
| [**CIVIL: Causal and Intuitive Visual Imitation Learning**](https://arxiv.org/abs/2504.17959) | arXiv | 2025-04-22 | [Project](https://civil2025.github.io/) |  |
| [**SPECI: Skill Prompts based Hierarchical Continual Imitation Learning for Robot Manipulation**](https://arxiv.org/abs/2504.15561) | arXiv | 2025-04-22 | - |  |
| [**Bi-LAT: Bilateral Control-Based Imitation Learning via Natural Language and Action Chunking with Transformers**](https://arxiv.org/abs/2504.01301) | arXiv | 2025-04-02 | [Project](https://mertcookimg.github.io/bi-lat/) |  |
| [**X-IL: Exploring the Design Space of Imitation Learning Policies**](https://arxiv.org/abs/2502.12330) | arXiv | 2025-02-17 | ![Star](https://img.shields.io/github/stars/ALRhub/X_IL?style=social&label=Star) [Github](https://github.com/ALRhub/X_IL) |  |
| [**Imit Diff: Semantics Guided Diffusion Transformer with Dual Resolution Fusion for Imitation Learning**](https://arxiv.org/abs/2502.09649) | arXiv | 2025-02-11 | - |  |
| [**Rethinking Latent Redundancy in Behavior Cloning: An Information Bottleneck Approach for Robot Manipulation**](https://arxiv.org/abs/2502.02853) | ICML 2025 | 2025-02-05 | ![Star](https://img.shields.io/github/stars/BaiShuanghao/BC-IB?style=social&label=Star) [Github](https://github.com/BaiShuanghao/BC-IB) |  |
| [CLOVER: **Closed-Loop Visuomotor Control with Generative Expectation for Robotic Manipulation**](https://arxiv.org/abs/2409.09016) | NeurIPS 2024 | 2024-09-13 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/CLOVER?style=social&label=Star) [Github](https://github.com/OpenDriveLab/CLOVER) | |
| [MS-Bot: **Play to the Score: Stage-Guided Dynamic Multi-Sensory Fusion for Robotic Manipulation**](https://arxiv.org/abs/2408.01366) | CoRL 2024 | 2024-08-02 | ![Star](https://img.shields.io/github/stars/GeWu-Lab/MS-Bot?style=social&label=Star) [Github](https://github.com/GeWu-Lab/MS-Bot) | IL, RepL, Multimodal, Poliy Head |
| [**Theia: Distilling Diverse Vision Foundation Models for Robot Learning**](https://arxiv.org/abs/2407.20179) | CoRL 2024 | 2024-07-29 | ![Star](https://img.shields.io/github/stars/bdaiinstitute/theia?style=social&label=Star) [Github](https://github.com/bdaiinstitute/theia) | IL, RepL, KD in VLMs, Poliy Head |
| [**BAKU: An Efficient Transformer for Multi-Task Policy Learning**](https://arxiv.org/abs/2406.07539) | NeurIPS 2024 | 2024-06-11 | ![Star](https://img.shields.io/github/stars/siddhanthaldar/BAKU?style=social&label=Star) [Github](https://github.com/siddhanthaldar/BAKU) |  |
| [**MUTEX: Learning Unified Policies from Multimodal Task Specifications**](https://arxiv.org/abs/2309.14320) | CoRL 2023 | 2023-09-25 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/mutex?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/mutex) | IL, RepL, Multimodal, E-D, Masked Construction, TP |
| [**LIV: Language-Image Representations and Rewards for Robotic Control**](https://arxiv.org/abs/2306.00958) | ICML 2023 | 2023-06-01 | ![Star](https://img.shields.io/github/stars/penn-pal-lab/LIV?style=social&label=Star) [Github](https://github.com/penn-pal-lab/LIV) | RepL, LfD, Both Goals, Alignment |
| [**VIMA: General Robot Manipulation with Multimodal Prompts**](https://arxiv.org/abs/2210.03094) | ICML 2023 | 2022-10-06 | ![Star](https://img.shields.io/github/stars/vimalabs/VIMA?style=social&label=Star) [Github](https://github.com/vimalabs/VIMA) | Benchmark, E-D, TP, Multimodal Prompt |
| [ACT: **Learning Fine-Grained Bimanual Manipulation with Low-Cost Hardware**](https://arxiv.org/abs/2304.13705) | RSS 2023 | 2023-04-23 | ![Star](https://img.shields.io/github/stars/tonyzhaozh/aloha?style=social&label=Star) [Github](https://github.com/tonyzhaozh/aloha) | IL, RepL, E-D, TP |
| [ZeST: **Can Foundation Models Perform Zero-Shot Task Specification For Robot Manipulation?**](https://arxiv.org/abs/2204.11134) | L4DC 2022 | 2022-04-23 | [Project](https://sites.google.com/view/zestproject) | Both Goals |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.3-Learning from Human Demonstrations ******* -->
### Learning from Demonstrations
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Token Bottleneck: One Token to Remember Dynamics**](https://arxiv.org/abs/2507.06543) | arXiv | 2025-07-09 | ![Star](https://img.shields.io/github/stars/naver-ai/tobo?style=social&label=Star) [Github](https://github.com/naver-ai/tobo) | |
| [**Vision in Action: Learning Active Perception from Human Demonstrations**](https://arxiv.org/abs/2506.15666) | arXiv | 2025-06-18 | ![Star](https://img.shields.io/github/stars/haoyu-x/vision-in-action?style=social&label=Star) [Github](https://github.com/haoyu-x/vision-in-action) | |
| [**Learning Generalizable Robot Policy with Human Demonstration Video as a Prompt**](https://arxiv.org/abs/2505.20795) | arXiv | 2025-05-27 | - |  |
| [MCR: **Robots Pre-train Robots: Manipulation-Centric Robotic Representation from Large-Scale Robot Datasets**](https://arxiv.org/abs/2410.22325) | ICLR 2025 | 2024-10-29 | ![Star](https://img.shields.io/github/stars/luccachiang/robots-pretrain-robots?style=social&label=Star) [Github](https://github.com/luccachiang/robots-pretrain-robots) | IL, RepL, Alignment, Poliy Head |
| [MPI: **Learning Manipulation by Predicting Interaction**](https://www.arxiv.org/abs/2406.00439) | RSS 2024 | 2024-06-01 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/MPI?style=social&label=Star) [Github](https://github.com/OpenDriveLab/MPI) | IL, RepL, Interaction-oriented Prediction, Both Goals, Poliy Head |
| [VC-1: **Where are we in the search for an Artificial Visual Cortex for Embodied Intelligence?**](https://arxiv.org/abs/2303.18240) | NeurIPS 2023 | 2023-03-31 | ![Star](https://img.shields.io/github/stars/facebookresearch/eai-vc?style=social&label=Star)  [Github](https://github.com/facebookresearch/eai-vc) | |
| [Voltron: **Language-Driven Representation Learning for Robotics**](https://arxiv.org/abs/2302.12766) | RSS 2023 | 2023-02-24 | ![Star](https://img.shields.io/github/stars/siddk/voltron-robotics?style=social&label=Star) [Github](https://github.com/siddk/voltron-robotics) | IL, RepL, Masked Construction, Both Goals, Poliy Head |
| [MVP: **Real-World Robot Learning with Masked Visual Pre-training**](https://arxiv.org/abs/2210.03109) | CoRL 2023 | 2022-10-06 | ![Star](https://img.shields.io/github/stars/ir413/mvp?style=social&label=Star) [Github](https://github.com/ir413/mvp) | IL, RepL, Masked Construction, Image Goal, Poliy Head |
| [**VIP: Towards Universal Visual Reward and Representation via Value-Implicit Pre-Training**](https://arxiv.org/abs/2210.00030) | ICLR 2023 | 2022-08-30 | ![Star](https://img.shields.io/github/stars/facebookresearch/vip?style=social&label=Star) [Github](https://github.com/facebookresearch/vip) | RepL, LfD, Image Goal |
| [**R3M: A Universal Visual Representation for Robot Manipulation**](https://arxiv.org/abs/2203.12601) | CoRL 2022 | 2022-03-23 | ![Star](https://img.shields.io/github/stars/facebookresearch/r3m?style=social&label=Star) [Github](https://github.com/facebookresearch/r3m) | IL, RepL, LfD, Alignment, Language Goal, Poliy Head |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.4-Latent Action Learning ******* -->
### Latent Action Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Latent Action Diffusion for Cross-Embodiment Manipulation**](https://arxiv.org/abs/2506.14608) | arXiv | 2025-06-17 | [Project](https://mimicrobotics.github.io/lad/) | |
| [**STAR: Learning Diverse Robot Skill Abstractions through Rotation-Augmented Vector Quantization**](https://arxiv.org/abs/2506.03863) | ICML 2025 | 2025-06-04 | ![Star](https://img.shields.io/github/stars/JiuTian-VL/STAR?style=social&label=Star) [Github](https://github.com/JiuTian-VL/STAR) | |
| [**CoMo: Learning Continuous Latent Motion from Internet Videos for Scalable Robot Learning**](https://arxiv.org/abs/2505.17006) | arXiv | 2025-05-22 | ![Star](https://img.shields.io/github/stars/clamrobot/clam?style=social&label=Star) [Github](https://github.com/clamrobot/clam) | |
| [**FLARE: Robot Learning with Implicit World Modeling**](https://arxiv.org/abs/2505.15659) | arXiv | 2025-05-21 | [Project](https://research.nvidia.com/labs/gear/flare) | |
| [**DreamGen: Unlocking Generalization in Robot Learning through Neural Trajectories**](https://arxiv.org/abs/2505.12705) | arXiv | 2025-05-19 | [Project](https://research.nvidia.com/labs/gear/dreamgen/) | |
| [**CLAM: Continuous Latent Action Models for Robot Learning from Unlabeled Demonstrations**](https://arxiv.org/abs/2505.04999) | arXiv | 2025-05-08 | ![Star](https://img.shields.io/github/stars/clamrobot/clam?style=social&label=Star) [Github](https://github.com/clamrobot/clam) | |
| [**Moto: Latent Motion Token as the Bridging Language for Robot Manipulation**](https://arxiv.org/abs/2412.04445) | arXiv | 2024-12-05 | ![Star](https://img.shields.io/github/stars/TencentARC/Moto?style=social&label=Star) [Github](https://github.com/TencentARC/Moto) | |
| [**Discrete Policy: Learning Disentangled Action Space for Multi-Task Robotic Manipulation**](https://arxiv.org/abs/2409.18707) | ICRA 2025 | 2024-09-27 | [Project](https://discretepolicy.github.io/) | |
| [**IGOR: Image-GOal Representations Atomic Control Units for Foundation Models in Embodied AI**](https://www.microsoft.com/en-us/research/uploads/prod/2024/10/Project_IGOR_for_arXiv.pdf) | - | 2024 | [Project](https://www.microsoft.com/en-us/research/project/igor-image-goal-representations/) | IL, RepL, Image Prediction, Poliy Head |
| [LAPA: **Latent Action Pretraining from Videos**](https://arxiv.org/abs/2410.11758) | ICLR 2025 | 2024-10-15 | ![Star](https://img.shields.io/github/stars/LatentActionPretraining/LAPA?style=social&label=Star) [Github](https://github.com/LatentActionPretraining/LAPA) | IL, RepL, Alignment, Both Goals, Poliy Head |
| [GRIF: **Goal Representations for Instruction Following: A Semi-Supervised Language Interface to Control**](https://arxiv.org/abs/2307.00117) | CoRL 2023 | 2023-06-30 | ![Star](https://img.shields.io/github/stars/rail-berkeley/grif_release?style=social&label=Star)  [Github](https://github.com/rail-berkeley/grif_release) | IL, RepL, Alignment, Both Goals, Poliy Head, Partially labeled data |
| [**MimicPlay: Long-Horizon Imitation Learning by Watching Human Play**](https://arxiv.org/abs/2302.12422) | CoRL 2023 | 2023-02-24 | ![Star](https://img.shields.io/github/stars/j96w/MimicPlay?style=social&label=Star) [Github](https://github.com/j96w/MimicPlay) | IL, RepL, LfD, Image Goal, Poliy Head |
| [KOAP: **Imitation Learning with Limited Actions via Diffusion Planners and Deep Koopman Controllers**](https://arxiv.org/abs/2410.07584) | arXiv | 2024-10-24 | - | IL, RepL, Image Prediction, Koopman Operator |
| [**Behavior Generation with Latent Actions**](https://arxiv.org/abs/2403.03181) | ICML 2024 | 2024-03-05 | ![Star](https://img.shields.io/github/stars/jayLEE0301/vq_bet_official?style=social&label=Star) [Github](https://github.com/jayLEE0301/vq_bet_official) |  |
| [LAPO: **Learning to Act without Actions**](https://arxiv.org/abs/2312.10812) | ICLR 2024 | 2023-12-17 | ![Star](https://img.shields.io/github/stars/schmidtdominik/LAPO?style=social&label=Star) [Github](https://github.com/schmidtdominik/LAPO) | IL, RepL, Image Prediction, Latent Inverse Dynamics Model |
| [ILPO: **Imitating Latent Policies from Observation**](https://arxiv.org/abs/1805.07914) | ICML 2019 | 2018-05-21 | ![Star](https://img.shields.io/github/stars/ashedwards/ILPO?style=social&label=Star) [Github](https://github.com/ashedwards/ILPO) | IL, RepL, Latent Inverse Dynamics Model |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.5-World Model ******* -->
### World Model
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   |  
|:--------|:--------:|:--------:|:--------:|
| [**World4Omni: A Zero-Shot Framework from Image Generation World Model to Robotic Manipulation**](https://arxiv.org/abs/2506.23919) | arXiv | 2025-06-30| [Project](https://world4omni.github.io/) | |
| [**ParticleFormer: A 3D Point Cloud World Model for Multi-Object, Multi-Material Robotic Manipulation**](https://arxiv.org/abs/2506.23126) | arXiv | 2025-06-29 | [Project](https://particleformer.github.io/) | |
| [**GAF: Gaussian Action Field as a Dvnamic World Model for Robotic Mlanipulation**](https://arxiv.org/abs/2506.14135) | arXiv | 2025-06-17 | - | |
| [**A Smooth Sea Never Made a Skilled SAILOR: Robust Imitation via Learning to Search**](https://arxiv.org/abs/2506.05294) | arXiv | 2025-06-05 | ![Star](https://img.shields.io/github/stars/arnavkj1995/SAILOR?style=social&label=Star) [Github](https://github.com/arnavkj1995/SAILOR) | |
| [**WoMAP: World Models For Embodied Open-Vocabulary Object Localization**](https://arxiv.org/abs/2506.01600) | arXiv | 2025-06-02 | [Project](https://robot-womap.github.io/) | |
| [**OSVI-WM: One-Shot Visual Imitation for Unseen Tasks using World-Model-Guided Trajectory Generation**](https://arxiv.org/abs/2505.20425) | arXiv | 2025-05-26 | - | |
| [**Vid2World: Crafting Video Diffusion Models to Interactive World Models**](https://arxiv.org/abs/2505.14357) | arXiv | 2025-05-20 | [Project](https://knightnemo.github.io/vid2world/) | |
| [**Modeling Unseen Environments with Language-guided Composable Causal Components in Reinforcement Learning**](https://arxiv.org/abs/2505.08361) | ICLR 2025 | 2025-05-13 | [Project](https://www.charonwangg.com/project/wm3c/) | |
| [**ManipDreamer: Boosting Robotic Manipulation World Model with Action Tree and Visual Guidance**](https://arxiv.org/abs/2504.16464) | arXiv | 2025-04-23 | - | |
| [**Unified World Models: Coupling Video and Action Diffusion for Pretraining on Large Robotic Datasets**](https://arxiv.org/abs/2504.02792) | arXiv | 2025-04-03 | ![Star](https://img.shields.io/github/stars/WEIRDLabUW/unified-world-model?style=social&label=Star) [Github](https://github.com/WEIRDLabUW/unified-world-model) | |
| [**Multi-Stage Manipulation with Demonstration-Augmented Reward, Policy, and World Model Learning**](https://arxiv.org/abs/2503.01837) | arXiv | 2025-03-03 | - | |
| [**Generalist World Model Pre-Training for Efficient Reinforcement Learning**](https://arxiv.org/abs/2502.19544) | arXiv | 2025-02-26 | - | |
| [**Learning View-invariant World Models for Visual Robotic Manipulation**](https://openreview.net/forum?id=vJwjWyt4Ed) | ICLR 2025 | 2025-01-23 | ![Star](https://img.shields.io/github/stars/lafmdp/ReViWo?style=social&label=Star) [Github](https://github.com/lafmdp/ReViWo) | |
| [**Cosmos World Foundation Model Platform for Physical AI**](https://arxiv.org/abs/2501.03575) | arXiv | 2025-01-07 | ![Star](https://img.shields.io/github/stars/NVIDIA/Cosmos?style=social&label=Star) [Github](https://github.com/NVIDIA/Cosmos) | |
| [Sirius-Fleet: **Multi-Task Interactive Robot Fleet Learning with Visual World Models**](https://arxiv.org/abs/2410.22689) | CoRL 2024 | 2024-10-30 | [Project](https://ut-austin-rpl.github.io/sirius-fleet/) | |
| [**MOTO: Offline Pre-training to Online Fine-tuning for Model-based Robot Learning**](https://arxiv.org/abs/2401.03306) | CoRL 2023 | 2024-01-06 | [Project](https://sites.google.com/view/mo2o) | |
| [FOWM: **Finetuning Offline World Models in the Real World**](https://arxiv.org/abs/2310.16029) | CoRL 2023 | 2023-10-24 | ![Star](https://img.shields.io/github/stars/fyhMer/fowm?style=social&label=Star) [Github](https://github.com/fyhMer/fowm) | |
| [SWIM: **Structured World Models from Human Videos**](https://arxiv.org/abs/2308.10901) | RSS 2023 | 2023-08-23 | [Project](https://human-world-model.github.io/) | |
| [**Surfer: Progressive Reasoning with World Models for Robotic Manipulation**](https://arxiv.org/abs/2306.11335) | arXiv | 2023-06-20 | ![Star](https://img.shields.io/github/stars/Necolizer/RM-PRT?style=social&label=Star) [Github](https://github.com/Necolizer/RM-PRT) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.6-Asynchronous Action Learning ******* -->
### Asynchronous Action Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**HiBerNAC: Hierarchical Brain-emulated Robotic Neural Agent Collective for Disentangling Complex Manipulation**](https://arxiv.org/abs/2506.08296) | arXiv | 2025-06-09 | - |  |
| [**Fast-in-Slow: A Dual-System Foundation Model Unifying Fast Manipulation within Slow Reasoning**](https://arxiv.org/abs/2506.01953) | arXiv | 2025-06-02 | ![Star](https://img.shields.io/github/stars/CHEN-H01/Fast-in-Slow?style=social&label=Star) [Github](https://github.com/CHEN-H01/Fast-in-Slow) |  |
| [**OpenHelix: A Short Survey, Empirical Analysis, and Open-Source Dual-System VLA Model for Robotic Manipulation**](https://arxiv.org/abs/2505.03912) | arXiv | 2025-05-06 | ![Star](https://img.shields.io/github/stars/OpenHelix-robot/OpenHelix?style=social&label=Star) [Github](https://github.com/OpenHelix-robot/OpenHelix) |  |
| [**PIVOT-R: Primitive-Driven Waypoint-Aware World Model for Robotic Manipulation**](https://arxiv.org/abs/2410.10394) | NeurIPS 2024 | 2024-10-14 | ![Star](https://img.shields.io/github/stars/abliao/PIVOT-R?style=social&label=Star) [Github](http://github.com/abliao/PIVOT-R) | IL, RepL, Image Prediction, Hierarchical, Poliy Head |
| [RoboDual: **Towards Synergistic, Generalized, and Efficient Dual-System for Robotic Manipulation**](https://arxiv.org/abs/2410.08001) | arXiv | 2024-10-10 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/RoboDual?style=social&label=Star) [Github](https://github.com/OpenDriveLab/RoboDual) |  |
| [**HiRT: Enhancing Robotic Control with Hierarchical Robot Transformers**](https://arxiv.org/abs/2410.05273) | CoRL 2024 | 2024-09-12 | - | IL, RepL, Hierarchical, Poliy Head |
| [LCB: **From LLMs to Actions: Latent Codes as Bridges in Hierarchical Robot Control**](https://arxiv.org/abs/2405.04798) | IROS 2024 | 2024-05-08 | [Project](https://fredshentu.github.io/LCB_site/) | |
| [**MResT: Multi-Resolution Sensing for Real-Time Control with Vision-Language Models**](https://arxiv.org/abs/2401.14502) | CoRL 2023 | 2024-01-25 | ![Star](https://img.shields.io/github/stars/iamlab-cmu/mrest-multi-resolution-transformer?style=social&label=Star) [Github](https://github.com/iamlab-cmu/mrest-multi-resolution-transformer) | IL, RepL, Multi-Resolution, Poliy Head |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.7-Diffusion Policy Learning ******* -->
### Diffusion Policy Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Spatial-Temporal Aware Visuomotor Diffusion Policy Learning**](https://arxiv.org/abs/2507.06710) | arXiv | 2025-07-09 | [Project](https://zhenyangliu.github.io/DP4/) | |
| [**Hybrid Diffusion Policies with Projective Geometric Algebra for Efficient Robot Manipulation Learning**](https://arxiv.org/abs/2507.05695) | arXiv | 2025-06-24 | - | |
| [**AnchorDP3: 3D Affordance Guided Sparse Diffusion Policy for Robotic Manipulation**](https://arxiv.org/abs/2506.19269) | CVPRW 2025 | 2025-06-24 | - | |
| [**Block-wise Adaptive Caching for Accelerating Diffusion Policy**](https://arxiv.org/abs/2506.13456) | arXiv | 2025-06-24 | - | |
| [**Canonical Policy: Learning Canonical 3D Representation for Equivariant Policy**](https://arxiv.org/abs/2505.18474) | arXiv | 2025-05-24 | [Project](https://zhangzhiyuanzhang.github.io/cp-website/) | |
| [**3D Equivariant Visuomotor Policy Learning via Spherical Projection**](https://arxiv.org/abs/2505.16969) | arXiv | 2025-05-22 | - | |
| [**Latent Theory of Mind: A Decentralized Diffusion Architecture for Cooperative Manipulation**](https://arxiv.org/abs/2505.09144) | arXiv | 2025-05-14 | [Project](https://stanfordmsl.github.io/LatentToM/) | |
| [**H<sup>3</sup>DP: Triply-Hierarchical Diffusion Policy for Visuomotor Learning**](https://arxiv.org/abs/2505.07819) | arXiv | 2025-05-12 | [Project](https://lyy-iiis.github.io/h3dp/) | |
| [**Demystifying Diffusion Policies: Action Memorization and Simple Lookup Table Alternatives**](https://arxiv.org/abs/2505.05787) | arXiv | 2025-05-09 |  [Project](https://stanfordmsl.github.io/alt/) | |
| [**Latent Diffusion Planning for Imitation Learning**](https://arxiv.org/abs/2504.16925) | arXiv | 2025-04-23 | ![Star](https://img.shields.io/github/stars/amberxie88/latent_diffusion_planning?style=social&label=Star) [Github](https://github.com/amberxie88/latent_diffusion_planning) | |
| [**Spatial-Temporal Graph Diffusion Policy with Kinematic Modeling for Bimanual Robotic Manipulation**](https://arxiv.org/abs/2503.10743) | CVPR 2025 | 2025-03-13 | - | |
| [**CodeDiffuser: Attention-Enhanced Diffusion Policy via VLM-Generated Code for Instruction Ambiguity**](https://arxiv.org/abs/2506.16652) | RSS 2025 | 2025-06-19 | ![Star](https://img.shields.io/github/stars/lyttttt3333/CodeDiffuser?style=social&label=Star) [Github](https://github.com/lyttttt3333/CodeDiffuser) | |
| [**Reactive Diffusion Policy: Slow-Fast Visual-Tactile Policy Learning for Contact-Rich Manipulation**](https://arxiv.org/abs/2503.02881) | RSS 2025 | 2025-03-04 | ![Star](https://img.shields.io/github/stars/xiaoxiaoxh/reactive_diffusion_policy?style=social&label=Star) [Github](https://github.com/xiaoxiaoxh/reactive_diffusion_policy) | |
| [**FRMD: Fast Robot Motion Diffusion with Consistency-Distilled Movement Primitives for Smooth Action Generation**](https://arxiv.org/abs/2503.02048) | arXiv | 2025-03-03 | - | |
| [**S<sup>2</sup>-Diffusion: Generalizing from Instance-level to Category-level Skills in Robot Manipulation**](https://arxiv.org/abs/2502.09389) | arXiv | 2025-02-13 | - | |
| [MoDE: **Efficient Diffusion Transformer Policies with Mixture of Expert Denoisers for Multitask Learning**](https://arxiv.org/abs/2412.12953) | ICLR 2025 | 2024-12-17 | ![Star](https://img.shields.io/github/stars/intuitive-robots/MoDE_Diffusion_Policy?style=social&label=Star) [Github](https://github.com/intuitive-robots/MoDE_Diffusion_Policy) | |
| [**Score and Distribution Matching Policy: Advanced Accelerated Visuomotor Policies via Matched Distillation**](https://arxiv.org/abs/2412.09265?) | arXiv | 2024-12-12 | ![Star](https://img.shields.io/github/stars/BofangJia/SDM-Policy?style=social&label=Star) [Github](https://github.com/BofangJia/SDM-Policy) | |
| [**AffordDP: Generalizable Diffusion Policy with Transferable Affordance**](https://arxiv.org/abs/2412.03142) | arXiv | 2024-12-04 | [Project](https://afforddp.github.io/) | |
| [**Instant Policy: In-Context Imitation Learning via Graph Diffusion**](https://arxiv.org/abs/2411.12633) | ICLR 2025 | 2024-11-19 | ![Star](https://img.shields.io/github/stars/vv19/instant_policy?style=social&label=Star) [Github](https://github.com/vv19/instant_policy) | |
| [STMDP: **Brain-inspired Action Generation with Spiking Transformer Diffusion Policy Model**](https://arxiv.org/abs/2411.09953) | arXiv | 2024-11-15 | - | |
| [MBA: **Motion Before Action: Diffusing Object Motion as Manipulation Condition**](https://arxiv.org/abs/2411.09658) | arXiv | 2024-11-14 | ![Star](https://img.shields.io/github/stars/Selen-Suyue/MBA?style=social&label=Star) [Github](https://github.com/Selen-Suyue/MBA) | |
| [DiT Policy: **Diffusion Transformer Policy**](https://arxiv.org/abs/2410.15959) | arXiv | 2024-10-21 | - | |
| [**CAGE: Causal Attention Enables Data-Efficient Generalizable Robotic Manipulation**](https://arxiv.org/abs/2410.14974) | arXiv | 2024-10-19 | ![Star](https://img.shields.io/github/stars/cage-policy/CAGE?style=social&label=Star) [Github](https://github.com/cage-policy/CAGE) | |
| [**RDT-1B: a Diffusion Foundation Model for Bimanual Manipulation**](https://arxiv.org/abs/2410.07864) | ICLR 2025 | 2024-10-10 | ![Star](https://img.shields.io/github/stars/thu-ml/RoboticsDiffusionTransformer?style=social&label=Star) [Github](https://github.com/thu-ml/RoboticsDiffusionTransformer) | |
| [ScaleDP: **Scaling Diffusion Policy in Transformer to 1 Billion Parameters for Robotic Manipulation**](https://arxiv.org/abs/2409.14411) | ICRA 2025 | 2024-09-22 | [Project](https://scaling-diffusion-policy.github.io/) | |
| [**SDP: Spiking Diffusion Policy for Robotic Manipulation with Learnable Channel-Wise Membrane Thresholds**](https://arxiv.org/abs/2409.11195) | arXiv | 2024-09-17 | - | |
| [DiT-Block Policy: **The Ingredients for Robotic Diffusion Transformers**](https://arxiv.org/abs/2410.10088) | arXiv | 2024-10-14 | ![Star](https://img.shields.io/github/stars/sudeepdasari/dit-policy?style=social&label=Star) [Github](https://github.com/sudeepdasari/dit-policy) | |
| [**GenDP: 3D Semantic Fields for Category-Level Generalizable Diffusion Policy**](https://arxiv.org/abs/2410.17488) | CoRL 2024 | 2024-10-23 | ![Star](https://img.shields.io/github/stars/WangYixuan12/gendp?style=social&label=Star) [Github](https://github.com/WangYixuan12/gendp) |  |
| [**EquiBot: SIM(3)-Equivariant Diffusion Policy for Generalizable and Data Efficient Learning**](https://arxiv.org/abs/2407.01479) | CoRL 2024 | 2024-07-01 | ![Star](https://img.shields.io/github/stars/yjy0625/equibot?style=social&label=Star) [Github](https://github.com/yjy0625/equibot) |  |
| [SDP: **Sparse Diffusion Policy: A Sparse, Reusable, and Flexible Policy for Robot Learning**](https://arxiv.org/abs/2407.01531) | CoRL 2024 | 2024-07-01 | ![Star](https://img.shields.io/github/stars/AnthonyHuo/SDP?style=social&label=Star) [Github](https://github.com/AnthonyHuo/SDP) | MoE |
| [**ManiCM: Real-time 3D Diffusion Policy via Consistency Model for Robotic Manipulation**](https://arxiv.org/abs/2406.01586) | arXiv | 2024-06-03 | ![Star](https://img.shields.io/github/stars/ManiCM-fast/ManiCM?style=social&label=Star) [Github](https://github.com/ManiCM-fast/ManiCM) |  |
| [**RISE: 3D Perception Makes Real-World Robot Imitation Simple and Effective**](https://arxiv.org/abs/2404.12281) | IROS 2024 | 2024-04-18 | ![Star](https://img.shields.io/github/stars/rise-policy/rise?style=social&label=Star) [Project](https://github.com/rise-policy/rise) | |
| [MDT: **Multimodal Diffusion Transformer: Learning Versatile Behavior from Multimodal Goals**](https://arxiv.org/abs/2407.05996) | RSS 2024 | 2024-07-08 | ![Star](https://img.shields.io/github/stars/intuitive-robots/mdt_policy?style=social&label=Star) [Github](https://github.com/intuitive-robots/mdt_policy) | IL, RepL, Masked Construction, DP, Partially labeled data |
| [R&D: **Render and Diffuse: Aligning Image and Action Spaces for Diffusion-based Behaviour Cloning**](https://arxiv.org/abs/2405.18196) | RSS 2024 | 2024-05-28 | ![Star](https://img.shields.io/github/stars/vv19/rendiff?style=social&label=Star) [Github](https://github.com/vv19/rendiff) | |
| [DP3: **3D Diffusion Policy: Generalizable Visuomotor Policy Learning via Simple 3D Representations**](https://arxiv.org/abs/2403.03954) | RSS 2024 | 2024-03-06 | ![Star](https://img.shields.io/github/stars/YanjieZe/3D-Diffusion-Policy?style=social&label=Star) [Github](https://github.com/YanjieZe/3D-Diffusion-Policy) |  |
| [**PlayFusion: Skill Acquisition via Diffusion from Language-Annotated Play**](https://arxiv.org/abs/2312.04549) | CoRL 2023 | 2023-12-07 | [Project](https://play-fusion.github.io/) |  |
| [EquiDiff: **Equivariant Diffusion Policy**](https://arxiv.org/abs/2407.01812) | CoRL 2024 | 2024-07-01 | ![Star](https://img.shields.io/github/stars/pointW/equidiff?style=social&label=Star) [Code](https://github.com/pointW/equidiff) | Equivariance |
| [**StructDiffusion: Language-Guided Creation of Physically-Valid Structures using Unseen Objects**](https://arxiv.org/abs/2211.04604) | RSS 2023 | 2022-11-08 | ![Star](https://img.shields.io/github/stars/StructDiffusion/StructDiffusion?style=social&label=Star) [Github](https://github.com/StructDiffusion/StructDiffusion) |  |
| [BESO: **Goal-Conditioned Imitation Learning using Score-based Diffusion Policies**](https://arxiv.org/abs/2304.02532) | RSS 2023 | 2023-04-05 | ![Star](https://img.shields.io/github/stars/intuitive-robots/beso?style=social&label=Star) [Github](https://github.com/intuitive-robots/beso) |  |
| [**Diffusion Policy: Visuomotor Policy Learning via Action Diffusion**](https://arxiv.org/abs/2303.04137) | RSS 2023 | 2023-03-07 | ![Star](https://img.shields.io/github/stars/real-stanford/diffusion_policy?style=social&label=Star) [Github](https://github.com/real-stanford/diffusion_policy) |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.8-Other Policies ******* -->
### Other Policies
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**MP1: Mean Flow Tames Policy Learning in 1-step for Robotic Manipulation**](https://arxiv.org/abs/2507.10543) | arXiv | 2025-07-14 | ![Star](https://img.shields.io/github/stars/LogSSim/MP1?style=social&label=Star) [Github](https://github.com/LogSSim/MP1) | |
| [**Reinforcement Learning with Action Chunking**](https://arxiv.org/abs/2507.07969) | arXiv | 2025-07-10 | ![Star](https://img.shields.io/github/stars/ColinQiyangLi/qc?style=social&label=Star) [Github](https://github.com/ColinQiyangLi/qc) | |
| [**Wavelet Policy: Lifting Scheme for Policy Learning in Long-Horizon Tasks**](https://arxiv.org/abs/2507.04331) | arXiv | 2025-07-06 | - | |
| [**Chain-of-Action: Trajectory Autoregressive Modeling for Robotic Manipulation**](https://arxiv.org/abs/2506.09990) | arXiv | 2025-06-11 | ![Star](https://img.shields.io/github/stars/zwbx/Chain-of-Action?style=social&label=Star) [Github](https://github.com/zwbx/Chain-of-Action) | |
| [**FreqPolicy: Efficient Flow-based Visuomotor Policy via Frequency Consistency**](https://arxiv.org/abs/2506.08822) | arXiv | 2025-06-10 | - | |
| [**Real-Time Execution of Action Chunking Flow Policies**](https://arxiv.org/abs/2506.07339) | arXiv | 2025-06-09 | [Project](https://www.pi.website/research/real_time_chunking) | |
| [**Rodrigues Network for Learning Robot Actions**](https://arxiv.org/abs/2506.02618) | arXiv | 2025-06-03 | - | |
| [**FreqPolicy: Frequency Autoregressive Visuomotor Policy with Continuous Tokens**](https://arxiv.org/abs/2506.01583) | arXiv | 2025-06-02 | - | |
| [**Streaming Flow Policy: Simplifying diffusionflow-matching policies by treating action trajectories as flow trajectories**](https://arxiv.org/abs/2505.21851) | arXiv | 2025-05-28 | [Project](https://siddancha.github.io/streaming-flow-policy/) | |
| [**Dense Policy: Bidirectional Autoregressive Learning of Actions**](https://arxiv.org/abs/2503.13217) | arXiv | 2025-03-17 | ![Star](https://img.shields.io/github/stars/Selen-Suyue/DensePolicy?style=social&label=Star) [Github](https://github.com/Selen-Suyue/DensePolicy) | |
| [**RoboBERT: An End-to-end Multimodal Robotic Manipulation Model**](https://arxiv.org/abs/2502.07837) | arXiv | 2025-02-11 | ![Star](https://img.shields.io/github/stars/PeterWangsicheng/RoboBERT?style=social&label=Star) [Github](https://github.com/PeterWangsicheng/RoboBERT) | |
| [**EnerVerse: Envisioning Embodied Future Space for Robotics Manipulation**](https://arxiv.org/abs/2501.01895) | arXiv | 2025-01-03 | [Project](https://sites.google.com/view/enerverse) | |
| [**CARP: Visuomotor Policy Learning via Coarse-to-Fine Autoregressive Prediction**](https://arxiv.org/abs/2412.06782) | arXiv | 2024-12-09 | ![Star](https://img.shields.io/github/stars/ZhefeiGong/carp?style=social&label=Star) [Github](https://github.com/ZhefeiGong/carp) | |
| [**FlowPolicy: Enabling Fast and Robust 3D Flow-based Policy via Consistency Flow Matching for Robot Manipulation**](https://arxiv.org/abs/2412.04987) | AAAI 2025 | 2024-12-06 | ![Star](https://img.shields.io/github/stars/zql-kk/FlowPolicy?style=social&label=Star) [Github](https://github.com/zql-kk/FlowPolicy) | |
| [**Autoregressive Action Sequence Learning for Robotic Manipulation**](https://arxiv.org/abs/2410.03132) | arXiv | 2024-10-04 | ![Star](https://img.shields.io/github/stars/mlzxy/arp?style=social&label=Star) [Github](https://github.com/mlzxy/arp) | |
| [**MaIL: Improving Imitation Learning with Selective State Space Models**](https://arxiv.org/abs/2406.08234) | CoRL 2024 | 2024-06-12 | ![Star](https://img.shields.io/github/stars/ALRhub/MaIL?style=social&label=Star) [Github](https://github.com/ALRhub/MaIL) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.9-Vision Language Action Models ******* -->
### Vision Language Action Models
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**EgoVLA: Learning Vision-Language-Action Models from Egocentric Human Videos**](https://arxiv.org/abs/2507.12440) | arXiv | 2025-07-16 | [Project](https://rchalyang.github.io/EgoVLA/) | |
| [**DreamVLA: A Vision-Language-Action Model Dreamed with Comprehensive World Knowledge**](https://arxiv.org/abs/2507.04447) | arXiv | 2025-07-13 | ![Star](https://img.shields.io/github/stars/Zhangwenyao1/DreamVLA?style=social&label=Star) [Github](https://github.com/Zhangwenyao1/DreamVLA) | |
| [**Tactile-VLA: Unlocking Vision-Language-Action Model's Physical Knowledge for Tactile Generalization**](https://arxiv.org/abs/2507.09160) | arXiv | 2025-07-12 | - | |
| [**VOTE: Vision-Language-Action Optimization with Trajectory Ensemble Voting**](https://arxiv.org/abs/2507.05116) | arXiv | 2025-07-07 | ![Star](https://img.shields.io/github/stars/LukeLIN-web/VOTE?style=social&label=Star) [Github](https://github.com/LukeLIN-web/VOTE) | |` 
| [**cVLA: Towards Efficient Camera-Space VLAs**](https://arxiv.org/abs/2507.02190) | arXiv | 2025-07-02 | - | |
| [**MoIRA: Modular Instruction Routing Architecture for Multi-Task Robotics**](https://arxiv.org/abs/2507.01843) | arXiv | 2025-07-02 | - | |
| [**TriVLA: A Unified Triple-System-Based Unified Vision-Language-Action Model for General Robot Control**](https://arxiv.org/abs/2507.01424) | arXiv | 2025-07-01| [Project](https://zhenyangliu.github.io/TriVLA/) | |
| [**VQ-VLA: Improving Vision-Language-Action Models via Scaling Vector-Quantized Action Tokenizers**](https://arxiv.org/abs/2507.01016) | ICCV 2025 | 2025-07-01| ![Star](https://img.shields.io/github/stars/xiaoxiao0406/VQ-VLA?style=social&label=Star) [Github](https://github.com/xiaoxiao0406/VQ-VLA) | |
| [**CronusVLA: Transferring Latent Motion Across Time for Multi-Frame Prediction in Manipulation**](https://arxiv.org/abs/2506.19816) | arXiv | 2025-06-24 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/CronusVLA?style=social&label=Star) [Github](https://github.com/OpenRobotLab/CronusVLA) | |
| [UniVLA: **Unified Vision-Language-Action Model**](https://arxiv.org/abs/2506.19850) | arXiv | 2025-06-24 | ![Star](https://img.shields.io/github/stars/baaivision/UniVLA?style=social&label=Star) [Github](https://github.com/baaivision/UniVLA) | |
| [**RoboMonkey: Scaling Test-Time Sampling and Verification for Vision-Language-Action Models**](https://arxiv.org/abs/2506.17811) | arXiv | 2025-06-21 | [Project](https://robomonkey-vla.github.io/) | |
| [**RLRC: Reinforcement Learning-based Recovery for Compressed Vision-Language-Action Models**](https://arxiv.org/abs/2506.17639) | arXiv | 2025-06-21 | [Project](https://rlrc-vla.github.io/) | |
| [**VLA-OS: Structuring and Dissecting Planning Representations and Paradigms in Vision-Language-Action Models**](https://arxiv.org/abs/2506.17561) | arXiv | 2025-06-21 | ![Star](https://img.shields.io/github/stars/HeegerGao/VLA-OS?style=social&label=Star) [Github](https://github.com/HeegerGao/VLA-OS) | |
| [**ControlVLA: Few-shot Object-centric Adaptation for Pre-trained Vision-Language-Action Models**](https://arxiv.org/abs/2506.16211) | arXiv | 2025-06-19 | ![Star](https://img.shields.io/github/stars/ControlVLA/ControlVLA?style=social&label=Star) [Github](https://github.com/ControlVLA/ControlVLA) | |
| [**CEED-VLA: Consistency Vision-Language-Action Model with Early-Exit Decoding**](https://arxiv.org/abs/2506.13725) | arXiv | 2025-06-16 | ![Star](https://img.shields.io/github/stars/OpenHelix-Team/CEED-VLA?style=social&label=Star) [Github](https://github.com/OpenHelix-Team/CEED-VLA) | |
| [**SP-VLA: A Joint Model Scheduling and Token Pruning Approach for VLA Model Acceleration**](https://arxiv.org/abs/2506.12723) | arXiv | 2025-06-15 | - | |
| [**RationalVLA: A Rational Vision-Language-Action Model with Dual System**](https://arxiv.org/abs/2506.10826) | arXiv | 2025-06-12 | [Project](https://irpn-eai.github.io/rational_vla) | |
| [**EfficientVLA: Training-Free Acceleration and Compression for Vision-Language-Action Models**](https://arxiv.org/abs/2506.10100) | arXiv | 2025-06-11 | - | |
| [**SAFE: Multitask Failure Detection for Vision-Language-Action Models**](https://arxiv.org/abs/2506.09937) | arXiv | 2025-06-11 | [Project](https://vla-safe.github.io/) | |
| [**TGRPO :Fine-tuning Vision-Language-Action Model via Trajectory-wise Group Relative Policy Optimization**](https://arxiv.org/abs/2506.08440) | arXiv | 2025-06-10 | ![Star](https://img.shields.io/github/stars/hahans/TGRPO?style=social&label=Star) [Github](https://github.com/hahans/TGRPO) | |
| [**BridgeVLA: Input-Output Alignment for Efficient 3D Manipulation Learning with Vision-Language Models**](https://arxiv.org/abs/2506.07961) | arXiv | 2025-06-09 | ![Star](https://img.shields.io/github/stars/BridgeVLA/BridgeVLA?style=social&label=Star) [Github](https://github.com/BridgeVLA/BridgeVLA) | |
| [**BitVLA: 1-bit Vision-Language-Action Models for Robotics Manipulation**](https://arxiv.org/abs/2506.07530) | arXiv | 2025-06-09 | ![Star](https://img.shields.io/github/stars/ustcwhy/BitVLA?style=social&label=Star) [Github](https://github.com/ustcwhy/BitVLA) | |
| [**BEAST: Efficient Tokenization of B-Splines Encoded Action Sequences for Imitation Learning**](https://arxiv.org/abs/2506.06072) | arXiv | 2025-06-06 | ![Star](https://img.shields.io/github/stars/intuitive-robots/beast_calvin?style=social&label=Star) [Github](https://github.com/intuitive-robots/beast_calvin) | |
| [**SwitchVLA: Execution-Aware Task Switching for Vision-Language-Action Models**](https://arxiv.org/abs/2506.03574) | arXiv | 2025-06-04 | [Project](https://switchvla.github.io/) | |
| [**SmolVLA: A Vision-Language-Action Model  for Affordable and Efficient Robotics**](https://arxiv.org/abs/2506.01844) | arXiv | 2025-06-02 | ![Star](https://img.shields.io/github/stars/huggingface/lerobot?style=social&label=Star) [Github](https://github.com/huggingface/lerobot) | |
| [**OG-VLA: 3D-Aware Vision Language Action Model via Orthographic Image Generation**](https://arxiv.org/abs/2506.01196) | arXiv | 2025-06-01 | [Project](https://og-vla.github.io/) | |
| [**LoHoVLA: A Unified Vision-Language-Action Model for Long-Horizon Embodied Tasks**](https://arxiv.org/abs/2505.23705) | arXiv | 2025-05-29 | [Project](https://www.pi.website/research/knowledge_insulation) | |
| [**Knowledge Insulating Vision-Language-Action Models: Train Fast, Run Fast, Generalize Better**](https://arxiv.org/abs/2505.23705) | arXiv | 2025-05-29 | [Project](https://www.pi.website/research/knowledge_insulation) | |
| [**Agentic Robot: A Brain-Inspired Framework for Vision-Language-Action Models in Embodied Agents**](https://arxiv.org/abs/2505.23450) | arXiv | 2025-05-29 | - | |
| [**ForceVLA: Enhancing VLA Models with a Force-aware MoE for Contact-rich Manipulation**](https://arxiv.org/abs/2505.22159) | arXiv | 2025-05-28 | [Project](https://sites.google.com/view/forcevla2025) | |
| [ChatVLA-2: **Vision-Language-Action Model with Open-World Embodied Reasoning from Pretrained Knowledge**](https://arxiv.org/abs/2505.21906) | arXiv | 2025-05-28 | [Project](https://chatvla-2.github.io/) | |
| [**Hume: Introducing System-2 Thinking in Visual-Language-Action Model**](https://arxiv.org/abs/2505.21432) | arXiv | 2025-05-27 | ![Star](https://img.shields.io/github/stars/hume-vla/hume?style=social&label=Star) [Github](https://github.com/hume-vla/hume) | |
| [**Think Twice, Act Once: Token-Aware Compression and Action Reuse for Efficient Inference in Vision-Language-Action Models**](https://arxiv.org/abs/2505.21200) | arXiv | 2025-05-27 | - | |
| [**VLA-RL: Towards Masterful and General Robotic Manipulation with Scalable Reinforcement Learning**](https://arxiv.org/abs/2505.18719) | arXiv | 2025-05-24 | ![Star](https://img.shields.io/github/stars/GuanxingLu/vlarl?style=social&label=Star) [Github](https://github.com/GuanxingLu/vlarl) | |
| [**Interactive Post-Training for Vision-Language-Action Models**](https://arxiv.org/abs/2505.17016) | arXiv | 2025-05-22 | ![Star](https://img.shields.io/github/stars/Ariostgx/ript-vla?style=social&label=Star) [Github](https://github.com/Ariostgx/ript-vla) | |
| [**BadVLA: Towards Backdoor Attacks on Vision-Language-Action Models via Objective-Decoupled Optimization**](https://arxiv.org/abs/2505.16640) | arXiv | 2025-05-22 | [Project](https://badvla-project.github.io/) | |
| [**ManipLVM-R1: Reinforcement Learning for Reasoning in Embodied Manipulation with Large Vision-Language Models**](https://arxiv.org/abs/2505.16517) | arXiv | 2025-05-22 | - | |
| [**From Grounding to Manipulation: Case Studies of Foundation Model Integration in Embodied Robotic Systems**](https://arxiv.org/abs/2505.15685) | arXiv | 2025-05-21 | - | |
| [**Saliency-Aware Quantized Imitation Learning for Efficient Robotic Control**](https://arxiv.org/abs/2505.15304) | arXiv | 2025-05-21 | - | |
| [**Incentivizing Multimodal Reasoning in Large Models for Direct Robot Manipulation**](https://arxiv.org/abs/2505.12744) | arXiv | 2025-05-19 | - | |
| [**OneTwoVLA: A Unified Vision-Language-Action Model with Adaptive Reasoning**](https://arxiv.org/abs/2505.11917) | arXiv | 2025-05-17 | ![Star](https://img.shields.io/github/stars/Fanqi-Lin/OneTwoVLA?style=social&label=Star) [Github](https://github.com/Fanqi-Lin/OneTwoVLA) | |
| [**VTLA: Vision-Tactile-Language-Action Model with Preference Learning for Insertion Manipulation**](https://arxiv.org/abs/2505.09577) | arXiv | 2025-05-14 | [Project](https://sites.google.com/view/vtla) | |
| [FSD: **From Seeing to Doing: Bridging Reasoning and Decision for Robotic Manipulation**](https://arxiv.org/abs/2505.08548) | arXiv | 2025-05-13 | [Project](https://embodied-fsd.github.io/) | |
| [ECoT-Lite: **Training Strategies for Efficient Embodied Reasoning**](https://arxiv.org/abs/2505.08243) | arXiv | 2025-05-13 | - | |
| [**UniVLA: Learning to Act Anywhere with Task-centric Latent Actions**](https://www.arxiv.org/abs/2505.06111) | RSS 2025 | 2025-05-09 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/UniVLA?style=social&label=Star) [Github](https://github.com/OpenDriveLab/UniVLA) | |
| [**3D CAVLA: Leveraging Depth and 3D Context to Generalize Vision Language Action Models for Unseen Tasks**](https://arxiv.org/abs/2505.05800) | arXiv | 2025-05-09 | [Project](https://3d-cavla.github.io/) |  |
| [**OpenHelix: A Short Survey, Empirical Analysis, and Open-Source Dual-System VLA Model for Robotic Manipulation**](https://arxiv.org/abs/2505.03912) | arXiv | 2025-05-06 | ![Star](https://img.shields.io/github/stars/OpenHelix-robot/OpenHelix?style=social&label=Star) [Github](https://github.com/OpenHelix-robot/OpenHelix) |  |
| [**GraspVLA: a Grasping Foundation Model Pre-trained on Billion-scale Synthetic Action Data**](https://arxiv.org/abs/2505.03233) | arXiv | 2025-05-06 | ![Star](https://img.shields.io/github/stars/PKU-EPIC/GraspVLA?style=social&label=Star) [Github](https://github.com/PKU-EPIC/GraspVLA) |  |
| [**Interleave-VLA: Enhancing Robot Manipulation with Interleaved Image-Text Instructions**](https://arxiv.org/abs/2505.02152) | arXiv | 2025-05-04 | [Project](https://interleave-vla-anonymous.github.io/Interleave-VLA-Anonymous/) |  |
| [**CrayonRobo: Object-Centric Prompt-Driven Vision-Language-Action Model for Robotic Manipulation**](https://arxiv.org/abs/2505.02166) | arXiv | 2025-05-04 | - |  |
| [**NORA: A Small Open-Sourced Generalist Vision Language Action Model for Embodied Tasks**](https://arxiv.org/abs/2504.19854) | arXiv | 2025-04-28 | ![Star](https://img.shields.io/github/stars/declare-lab/nora?style=social&label=Star) [Github](https://github.com/declare-lab/nora) |  |
| [**π<sub>0.5</sub>: a Vision-Language-Action Model with Open-World Generalization**](https://arxiv.org/abs/2504.16054) | arXiv | 2025-04-22 | [Project](https://www.pi.website/blog/pi05) |  |
| [**A0: An Affordance-Aware Hierarchical Model for General Robotic Manipulation**](https://arxiv.org/abs/2504.12636) | arXiv | 2025-04-17 | ![Star](https://img.shields.io/github/stars/A-embodied/A0?style=social&label=Star) [Github](https://github.com/A-embodied/A0) |  |
| [**CoT-VLA: Visual Chain-of-Thought Reasoning for Vision-Language-Action Models**](https://arxiv.org/abs/2503.22020) | CVPR 2025 | 2025-03-27 | [Project](https://cot-vla.github.io/) |  |
| [**MoLe-VLA: Dynamic Layer-skipping Vision Language Action Model via Mixture-of-Layers for Efficient Robot Manipulation**](https://arxiv.org/abs/2503.20384) | arXiv | 2025-03-26 | ![Star](https://img.shields.io/github/stars/RoyZry98/MoLe-VLA-Pytorch?style=social&label=Star) [Github](https://github.com/RoyZry98/MoLe-VLA-Pytorch/) |  |
| [**Dita: Scaling Diffusion Transformer for Generalist Vision-Language-Action Policy**](https://arxiv.org/abs/2503.19757) | arXiv | 2025-03-25 | ![Star](https://img.shields.io/github/stars/RoboDita/Dita?style=social&label=Star) [Github](https://github.com/RoboDita/Dita) |  |
| [**DataPlatter: Boosting Robotic Manipulation Generalization with Minimal Costly Data**](https://arxiv.org/abs/2503.19516) | arXiv | 2025-03-25 | - |  |
| [**AgiBot World Colosseo: A Large-scale Manipulation Platform for Scalable and Intelligent Embodied Systems**](https://arxiv.org/abs/2503.06669) | - | 2025-03-09 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/AgiBot-World?style=social&label=Star) [Github](https://github.com/OpenDriveLab/AgiBot-World) |  |
| [GO-1: **AgiBot World Colosseo: A Large-scale Manipulation Platform for Scalable and Intelligent Embodied Systems**](https://arxiv.org/abs/2503.06669) | IROS 2025 | 2025-03-09 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/AgiBot-World?style=social&label=Star) [Github](https://github.com/OpenDriveLab/AgiBot-World) |
| [**VLA Model-Expert Collaboration for Bi-directional Manipulation Learning**](https://arxiv.org/abs/2503.04163) | arXiv | 2025-03-06 | [Project](https://aoqunjin.github.io/Expert-VLA/) |  |
| [**DexGraspVLA: A Vision-Language-Action Framework Towards General Dexterous Grasping**](https://arxiv.org/abs/2502.20900) | arXiv | 2025-03-05 | ![Star](https://img.shields.io/github/stars/Psi-Robot/DexGraspVLA?style=social&label=Star) [Github](https://github.com/Psi-Robot/DexGraspVLA) |  |
| [**OTTER: A Vision-Language-Action Model with Text-Aware Visual Feature Extraction**](https://arxiv.org/abs/2503.03734) | ICML 2025 | 2025-03-05 | ![Star](https://img.shields.io/github/stars/Max-Fu/otter?style=social&label=Star) [Github](https://github.com/Max-Fu/otter) |  |
| [**Accelerating Vision-Language-Action Model Integrated with Action Chunking via Parallel Decoding**](https://arxiv.org/abs/2503.02310) | arXiv | 2025-02-28 | - |  |
| [**FLOWER: Democratizing Generalist Robot Policies with Efficient Vision-Language-Action Flow Policies**](https://openreview.net/forum?id=ifo8oWSLSq) | ICLR 2025 | 2025-02-28 | - |  |
| [**RoboBrain: A Unified Brain Model for Robotic Manipulation from Abstract to Concrete**](https://arxiv.org/abs/2502.21257) | CVPR 2025 | 2025-02-28 | [Project](https://superrobobrain.github.io/) |  |
| [OpenVLA-Oft: **Fine-Tuning Vision-Language-Action Models: Optimizing Speed and Success**](https://arxiv.org/abs/2502.19645) | arXiv | 2025-02-27 | ![Star](https://img.shields.io/github/stars/moojink/openvla-oft?style=social&label=Star) [Github](https://github.com/moojink/openvla-oft) |  |
| [**Hi Robot: Open-Ended Instruction Following with Hierarchical Vision-Language-Action Models**](https://arxiv.org/abs/2502.19417) | arXiv | 2025-02-26 | [Project](https://www.pi.website/research/hirobot) |  |
| [**ObjectVLA: End-to-End Open-World Object Manipulation Without Demonstration**](https://arxiv.org/abs/2502.19250) | arXiv | 2025-02-26 | [Project](https://objectvla.github.io/) |  |
| [**ChatVLA: Unified Multimodal Understanding and Robot Control with Vision-Language-Action Model**](https://arxiv.org/abs/2502.14420) | arXiv | 2025-02-20 | [Project](https://chatvla.github.io/) |  |
| [**Magma: A Foundation Model for Multimodal AI Agents**](https://arxiv.org/abs/2502.13130) | CVPR 2025 | 2025-02-18 | ![Star](https://img.shields.io/github/stars/microsoft/Magma?style=social&label=Star) [Github](https://github.com/microsoft/Magma) |  |
| [**DexVLA: Vision-Language Model with Plug-In Diffusion Expert for General Robot Control**](https://arxiv.org/abs/2502.05855) | arXiv | 2025-02-09 | ![Star](https://img.shields.io/github/stars/juruobenruo/DexVLA?style=social&label=Star) [Github](https://github.com/juruobenruo/DexVLA) |  |
| [**HAMSTER: Hierarchical Action Models For Open-World Robot Manipulation**](https://arxiv.org/abs/2502.05485) | ICLR 2025 | 2025-02-08 | [Project](https://hamster-robot.github.io/) |  |
| [**ConRFT: A Reinforced Fine-tuning Method for VLA Models via Consistency Policy**](https://arxiv.org/abs/2502.05450) | RSS 2025 | 2025-02-08 | [Project](https://cccedric.github.io/conrft/) |  |
| [**Probing a Vision-Language-Action Model for Symbolic States and Integration into a Cognitive Architecture**](https://arxiv.org/abs/2502.04558) | arXiv | 2025-02-06 | - |  |
| [RAD: **Action-Free Reasoning for Policy Generalization**](https://arxiv.org/abs/2502.03729) | arXiv | 2025-02-06 | [Project](https://rad-generalization.github.io/) |  |
| [**VLA-Cache: Towards Efficient Vision-Language-Action Model via Adaptive Token Caching in Robotic Manipulation**](https://arxiv.org/abs/2502.02175) | arXiv | 2025-02-04 | - |  |
| [**UP-VLA: A Unified Understanding and Prediction Model for Embodied Agent**](https://arxiv.org/abs/2501.18867) | arXiv | 2025-01-31 | - |  |
| [**SpatialVLA: Exploring Spatial Representations for Visual-Language-Action Model**](https://arxiv.org/abs/2501.15830) | RSS 2025 | 2025-01-27 | ![Star](https://img.shields.io/github/stars/SpatialVLA/SpatialVLA?style=social&label=Star) [Github](https://github.com/SpatialVLA/SpatialVLA) |  |
| [**CogACT: A Foundational Vision-Language-Action Model for Synergizing Cognition and Action in Robotic Manipulation**](https://arxiv.org/abs/2411.19650) | arXiv | 2024-12-29 | ![Star](https://img.shields.io/github/stars/microsoft/CogACT?style=social&label=Star) [Github](https://github.com/microsoft/CogACT) |  |
| [Seer: **Predictive Inverse Dynamics Models are Scalable Learners for Robotic Manipulation**](https://arxiv.org/abs/2412.15109) | ICLR 2025 | 2024-12-19 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/Seer?style=social&label=Star) [Github](https://github.com/OpenRobotLab/Seer/) |  |
| [RoboVLMs: **Towards Generalist Robot Policies: What Matters in Building Vision-Language-Action Models**](https://arxiv.org/abs/2412.14058) | arXiv | 2024-12-18 | ![Star](https://img.shields.io/github/stars/Robot-VLAs/RoboVLMs?style=social&label=Star) [Github](https://github.com/Robot-VLAs/RoboVLMs) |  |
| [**Emma-X: An Embodied Multimodal Action Model with Grounded Chain of Thought and Look-ahead Spatial Reasoning**](https://arxiv.org/abs/2412.11974) | arXiv | 2024-12-16 | ![Star](https://img.shields.io/github/stars/declare-lab/Emma-X?style=social&label=Star) [Github](https://github.com/declare-lab/Emma-X) |  |
| [**VLAS: Vision-Language-Action Model with Speech Instructions for Customized Robot Manipulation**](https://arxiv.org/abs/2502.13508) | ICLR 2025 | 2025-01-25 | ![Star](https://img.shields.io/github/stars/whichwhichgone/VLAS?style=social&label=Star) [Github](https://github.com/whichwhichgone/VLAS) |  |
| [**TraceVLA: Visual Trace Prompting Enhances Spatial-Temporal Awareness for Generalist Robotic Policies**](https://arxiv.org/abs/2412.10345) | ICLR 2025 | 2024-12-13 | ![Star](https://img.shields.io/github/stars/umd-huang-lab/tracevla?style=social&label=Star) [Github](https://github.com/umd-huang-lab/tracevla) |  |
| [**Diffusion-VLA: Scaling Robot Foundation Models via Unified Diffusion and Autoregression**](https://arxiv.org/abs/2412.03293) | ICML 2025 | 2024-12-14 | [Project](https://diffusion-vla.github.io/) |  |
| [**π<sub>0</sub>: A Vision-Language-Action Flow Model for General Robot Control**](https://arxiv.org/abs/2410.24164) | arXiv | 2024-10-31 | [Project](https://www.physicalintelligence.company/blog/pi0) |  |
| [BYOVLA: **Run-time Observation Interventions Make Vision-Language-Action Models More Visually Robust**](https://arxiv.org/abs/2410.01971) | arXiv | 2024-10-02 | ![Star](https://img.shields.io/github/stars/irom-lab/byovla?style=social&label=Star) [Github](https://github.com/irom-lab/byovla) |  |
| [**VLATest: Testing and Evaluating Vision-Language-Action Models for Robotic Manipulation**](https://arxiv.org/abs/2409.12894) | FSE 2025  | 2024-09-19 | ![Star](https://img.shields.io/github/stars/ma-labo/VLATest?style=social&label=Star) [Github](https://github.com/ma-labo/VLATest) |  |
| [**TinyVLA: Towards Fast, Data-Efficient Vision-Language-Action Models for Robotic Manipulation**](https://arxiv.org/abs/2409.12514) | RA-L 2025 | 2024-09-19 | ![Star](https://img.shields.io/github/stars/liyaxuanliyaxuan/TinyVLA?style=social&label=Star) [Github](https://github.com/liyaxuanliyaxuan/TinyVLA) |  |
| [**DeeR-VLA: Dynamic Inference of Multimodal Large Language Models for Efficient Robot Execution**](https://arxiv.org/abs/2411.02359) | NeurIPS 2024 | 2024-11-04 | [Github](https://github.com/yueyang130/DeeR-VLA) |  |
| [**QueST: Self-Supervised Skill Abstractions for Learning Continuous Control**](https://arxiv.org/abs/2407.15840) | NeurIPS 2024 | 2024-07-22 | ![Star](https://img.shields.io/github/stars/pairlab/QueST?style=social&label=Star) [Github](https://github.com/pairlab/QueST) |  |
| [**RoboMamba: Multimodal State Space Model for Efficient Robot Reasoning and Manipulation**](https://arxiv.org/abs/2406.04339) | NeurIPS 2024 | 2024-06-06 | ![Star](https://img.shields.io/github/stars/lmzpai/roboMamba?style=social&label=Star) [Github](https://github.com/lmzpai/roboMamba) |  |
| [DP-VLA: **A Dual Process VLA: Efficient Robotic Manipulation Leveraging VLM**](https://arxiv.org/abs/2410.15549) | CoRL 2024 | 2024-10-21 | - |  |
| [**OpenVLA: An Open-Source Vision-Language-Action Model**](https://arxiv.org/abs/2406.09246) | CoRL 2024 | 2024-06-13 | ![Star](https://img.shields.io/github/stars/openvla/openvla?style=social&label=Star) [Github](https://github.com/openvla/openvla) |  |
| [**LLARVA: Vision-Action Instruction Tuning Enhances Robot Learning**](https://arxiv.org/abs/2406.11815) | CoRL 2024 | 2024-06-17 | ![Star](https://img.shields.io/github/stars/Dantong88/LLARVA?style=social&label=Star) [Github](https://github.com/Dantong88/LLARVA) |  |
| [ECoT: **Robotic Control via Embodied Chain-of-Thought Reasoning**](https://arxiv.org/abs/2407.08693) | CoRL 2024 | 2024-07-11 | ![Star](https://img.shields.io/github/stars/MichalZawalski/embodied-CoT?style=social&label=Star) [Github](https://github.com/MichalZawalski/embodied-CoT/) |  |
| [**3D-VLA: A 3D Vision-Language-Action Generative World Model**](https://arxiv.org/abs/2403.09631) | ICML 2024 | 2024-03-14 | ![Star](https://img.shields.io/github/stars/UMass-Foundation-Model/3D-VLA?style=social&label=Star) [Github](https://github.com/UMass-Foundation-Model/3D-VLA) |  |
| [**Octo: An Open-Source Generalist Robot Policy**](https://arxiv.org/abs/2405.12213) | RSS 2024 | 2024-05-20 | ![Star](https://img.shields.io/github/stars/octo-models/octo?style=social&label=Star)  [Github](https://github.com/octo-models/octo) | |
| [**RT-H: Action Hierarchies Using Language**](https://arxiv.org/abs/2403.01823) | RSS 2024 | 2024-03-04 | [Project](https://rt-hierarchy.github.io/) |  |
| [RoboFlamingo: **Vision-Language Foundation Models as Effective Robot Imitators**](https://arxiv.org/abs/2311.01378) | ICLR 2024 | 2023-11-02 | ![Star](https://img.shields.io/github/stars/RoboFlamingo/RoboFlamingo?style=social&label=Star) [Github](https://github.com/RoboFlamingo/RoboFlamingo) |  |
| [**Open X-Embodiment: Robotic Learning Datasets and RT-X Models**](https://arxiv.org/abs/2310.08864) | ICRA 2024 | 2023-10-13 | ![Star](https://img.shields.io/github/stars/google-deepmind/open_x_embodiment?style=social&label=Star) [Github](https://github.com/google-deepmind/open_x_embodiment) | |
| [MOO: **Open-World Object Manipulation using Pre-trained Vision-Language Models**](https://arxiv.org/abs/2303.00905) | CoRL 2023 | 2023-03-02 | [Project](https://robot-moo.github.io/) |  |
| [**RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control**](https://arxiv.org/abs/2307.15818) | CoRL 2023 | 2023-07-28 | [Project](https://robotics-transformer2.github.io/) |  |
| [**RT-1: Robotics Transformer for Real-World Control at Scale**](https://arxiv.org/abs/2212.06817) | RSS 2023 | 2022-12-13 | ![Star](https://img.shields.io/github/stars/google-research/robotics_transformer?style=social&label=Star) [Github](https://github.com/google-research/robotics_transformer) |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.10-Reinforcement Learning ******* -->
### Reinforcement Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**EXPO: Stable Reinforcement Learning with Expressive Policies**](https://arxiv.org/abs/2507.07986) | arXiv | 2025-07-10 | - |  |
| [**Goal-Oriented Skill Abstraction for Offline Multi-Task Reinforcement Learning**](https://arxiv.org/abs/2507.06628) | ICML 2025 | 2025-07-09 | - |  |
| [**Q-STAC: Q-Guided Stein Variational Model Predictive Actor-Critic**](https://arxiv.org/abs/2507.06625) | arXiv | 2025-07-09 | [Project](https://sites.google.com/view/q-stac#h.mprn6mj2v3sr) |  |
| [**Eye, Robot: Learning to Look to Act with a BC-RL Perception-Action Loop**](https://arxiv.org/abs/2506.10968) | arXiv | 2025-06-12 | [Project](https://www.eyerobot.net/) |  |
| [**Reinforcement Learning via Implicit Imitation Guidance**](https://arxiv.org/abs/2506.07505) | arXiv | 2025-06-09 | - |  |
| [**ReWiND: Language-Guided Rewards Teach Robot Policies without New Demonstrations**](https://arxiv.org/abs/2505.10911) | arXiv | 2025-05-16 | [Project](https://rewind-reward.github.io/) |  |
| [**What Matters for Batch Online Reinforcement Learning in Robotics?**](https://arxiv.org/abs/2505.08078) | arXiv | 2025-05-12 | [Project](https://pd-perry.github.io/batch-online-rl/) |  |
| [**Video-Enhanced Offline Reinforcement Learning: A Model-Based Approach**](https://arxiv.org/abs/2505.06482) | ICML 2025 | 2025-05-10 | ![Star](https://img.shields.io/github/stars/panmt/VeoRL?style=social&label=Star) [Github](https://github.com/panmt/VeoRL) |  |
| [**TREND: Tri-teaching for Robust Preference-based Reinforcement Learning with Demonstrations**](https://arxiv.org/abs/2505.06079) | ICRA 2025 | 2025-05-09 | [Project](https://shuaiyihuang.github.io/publications/TREND/) |  |
| [**Learning from Suboptimal Data in Continuous Control via Auto-Regressive Soft Q-Network**](https://arxiv.org/abs/2502.00288) | arXiv | 2025-02-01 | - |  |
| [**Policy Decorator: Model-Agnostic Online Refinement for Large Policy Model**](https://arxiv.org/abs/2412.13630) | ICLR 2025 | 2024-12-18 | ![Star](https://img.shields.io/github/stars/tongzhoumu/policy_decorator?style=social&label=Star) [Github](https://github.com/tongzhoumu/policy_decorator) |  |
| [**RLDG: Robotic Generalist Policy Distillation via Reinforcement Learning**](https://arxiv.org/abs/2412.09858) | arXiv | 2024-12-13 | [Project](https://generalist-distillation.github.io/) |  |
| [HIL-SERL: **Precise and Dexterous Robotic Manipulation via Human-in-the-Loop Reinforcement Learning**](https://arxiv.org/abs/2410.21845) | arXiv | 2024-10-29 | [Project](https://hil-serl.github.io/) |  |
| [**PointPatchRL - Masked Reconstruction Improves Reinforcement Learning on Point Clouds**](https://arxiv.org/abs/2410.18800) | CoRL 2024 | 2024-10-24 | [Project](https://alrhub.github.io/pprl-website) |  |
| [**SPIRE: Synergistic Planning, Imitation, and Reinforcement for Long-Horizon Manipulation**](https://arxiv.org/abs/2410.18065) | CoRL 2024 | 2024-10-23 | [Project](https://sites.google.com/view/spire-corl-2024) |  |
| [Maniwhere: **Learning to Manipulate Anywhere: A Visual Generalizable Framework For Reinforcement Learning**](https://arxiv.org/abs/2407.15815) | CoRL 2024 | 2024-07-22 | [Project](https://gemcollector.github.io/maniwhere/) |  |
| [PSL: **Plan-Seq-Learn: Language Model Guided RL for Solving Long Horizon Robotics Tasks**](https://arxiv.org/abs/2405.01534) | ICLR 2024 | 2024-05-02 | ![Star](https://img.shields.io/github/stars/mihdalal/planseqlearn?style=social&label=Star) [Github](https://github.com/mihdalal/planseqlearn) | |
| [**TD-MPC2: Scalable, Robust World Models for Continuous Control**](https://arxiv.org/abs/2310.16828) | ICLR 2024 | 2023-10-25 | ![Star](https://img.shields.io/github/stars/nicklashansen/tdmpc2?style=social&label=Star) [Github](https://github.com/nicklashansen/tdmpc2) | |
| [VELAP: **Expansive Latent Planning for Sparse Reward Offline Reinforcement Learning**](https://openreview.net/pdf?id=xQx1O7WXSA) | CoRL 2023 | 2023 | - | |
| [**Q-Transformer: Scalable Offline Reinforcement Learning via Autoregressive Q-Functions**](https://arxiv.org/abs/2309.10150) | CoRL 2023 | 2023-09-18 | [Project](https://qtransformer.github.io/) | |
| [PTR: **Pre-Training for Robots: Offline RL Enables Learning New Tasks from a Handful of Trials**](https://arxiv.org/abs/2210.05178) | RSS 2023 | 2022-10-11 | [Project](https://sites.google.com/view/ptr-final/) |  |
| [TD-MPC: **Temporal Difference Learning for Model Predictive Control**](https://arxiv.org/abs/2203.04955) | ICML 2022 | 2022-03-09 | ![Star](https://img.shields.io/github/stars/nicklashansen/tdmpc?style=social&label=Star) [Github](https://github.com/nicklashansen/tdmpc) |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.11-Motion, Tranjectory and Flow ******* -->
### Motion, Tranjectory and Flow
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Path Planning_|
| [LACO: **Language-Conditioned Path Planning**](https://arxiv.org/abs/2308.16893) | CoRL 2023 | 2024-08-31 | ![Star](https://img.shields.io/github/stars/amberxie88/lapp?style=social&label=Star) [Github](https://github.com/amberxie88/lapp) |  |
| _Motion Planning_|
| [**Prompting with the Future: Open-World Model Predictive Control with Interactive Digital Twins**](https://arxiv.org/abs/2506.13761) | RSS 2025 | 2025-06-16 | ![Star](https://img.shields.io/github/stars/TritiumR/Prompting-with-the-Future?style=social&label=Star) [Github](https://github.com/TritiumR/Prompting-with-the-Future) |  |
| [**A Real-to-Sim-to-Real Approach to Robotic Manipulation with VLM-Generated Iterative Keypoint Rewards**](https://arxiv.org/abs/2502.08643) | ICRA 2025 | 2025-02-12 | ![Star](https://img.shields.io/github/stars/shivanshpatel35/IKER?style=social&label=Star) [Github](https://github.com/shivanshpatel35/IKER) | Motion Planning |
| [**DiffusionSeeder: Seeding Motion Optimization with Diffusion for Rapid Motion Planning**](https://arxiv.org/abs/2410.16727) | CoRL 2024 | 2024-10-22 | [Project](https://diffusion-seeder.github.io/) | Motion Planning  |
| [**ReKep: Spatio-Temporal Reasoning of Relational Keypoint Constraints for Robotic Manipulation**](https://arxiv.org/abs/2409.01652) | CoRL 2024 | 2024-09-03 | ![Star](https://img.shields.io/github/stars/huangwl18/ReKep?style=social&label=Star) [Github](https://github.com/huangwl18/ReKep) | Motion Planning |
| [**CoPa: General Robotic Manipulation through Spatial Constraints of Parts with Foundation Models**](https://arxiv.org/abs/2403.08248) | ICRAW 2024 | 2024-03-13 | ![Star](https://img.shields.io/github/stars/HaoxuHuang/copa?style=social&label=Star) [Github](https://github.com/HaoxuHuang/copa) | Motion Planning |
| [Elastic-DS: **Task Generalization with Stability Guarantees via Elastic Dynamical System Motion Policies**](https://arxiv.org/abs/2309.01884) | CoRL 2023 | 2023-09-05 | ![Star](https://img.shields.io/github/stars/tonylitianyu/Elastic-DS?style=social&label=Star) [Github](https://github.com/tonylitianyu/Elastic-DS) | IL, LfD, Motion |
| _Trajectory Optimization_|
| [**Geometry-aware 4D Video Generation for Robot Manipulation**](https://arxiv.org/abs/2507.01099) | arXiv | 2025-07-01 | ![Star](https://img.shields.io/github/stars/lzylucy/4dgen?style=social&label=Star) [Github](https://github.com/lzylucy/4dgen) |  |
| [**Robotic Manipulation by Imitating Generated Videos Without Physical Demonstrations**](https://arxiv.org/abs/2507.00990) | arXiv | 2025-07-01 | ![Star](https://img.shields.io/github/stars/shivanshpatel35/rigvid?style=social&label=Star) [Github](https://github.com/shivanshpatel35/rigvid) |  |
| [**ORION: Vision-based Manipulation from Single Human Video with Open-World Object Graphs**](https://arxiv.org/abs/2405.20321) | arXiv | 2024-05-30 | [Project](https://ut-austin-rpl.github.io/ORION-release/) |  |
| [PointFlowMatch: **Learning Robotic Manipulation Policies from Point Clouds with Conditional Flow Matching**](https://arxiv.org/abs/2409.07343) | CoRL 2024 | 2024-09-11 | [Project](http://pointflowmatch.cs.uni-freiburg.de/) |  |
| [**RoboTAP: Tracking Arbitrary Points for Few-Shot Visual Imitation**](https://arxiv.org/abs/2308.15975) | ICRA 2024 | 2023-08-30 | ![Star](https://img.shields.io/github/stars/google-deepmind/tapnet?style=social&label=Star) [Github](https://github.com/google-deepmind/tapnet/blob/main/colabs/tapir_clustering.ipynb) |  |
| [**VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models**](https://arxiv.org/abs/2307.05973) | CoRL 2023 | 2023-07-12 | ![Star](https://img.shields.io/github/stars/huangwl18/VoxPoser?style=social&label=Star)  [Github](https://github.com/huangwl18/VoxPoser) | Zero-shot Trajectory Optimization |
| [**LATTE: LAnguage Trajectory TransformEr**](https://arxiv.org/abs/2208.02918) | ICRA 2023 | 2022-08-04 | ![Star](https://img.shields.io/github/stars/arthurfenderbucker/LaTTe-Language-Trajectory-TransformEr?style=social&label=Star)  [Github](https://github.com/arthurfenderbucker/LaTTe-Language-Trajectory-TransformEr) |  |
| _Keypoint-conditioned policy_|
| [**Knowledge-Driven Imitation Learning: Enabling Generalization Across Diverse Conditions**](https://arxiv.org/abs/2506.21057) | arXiv | 2025-06-26 | ![Star](https://img.shields.io/github/stars/mioam/KnowledgeIL?style=social&label=Star) [Github](https://github.com/mioam/KnowledgeIL) |  |
| [**ATK: Automatic Task-driven Keypoint Selection for Robust Policy Learning**](https://arxiv.org/abs/2506.13867) | arXiv | 2025-06-16 | [Project](https://yunchuzhang.github.io/ATK/) |  |
| _Trajectory-conditioned policy_|
| [**Diffusion Trajectory-guided Policy for Long-horizon Robot Manipulation**](https://arxiv.org/abs/2502.10040) | arXiv | 2025-02-14 | - |  |
| [**P3-PO: Prescriptive Point Priors for Visuo-Spatial Generalization of Robot Policies**](https://arxiv.org/abs/2412.06784) | arXiv | 2024-12-09 | ![Star](https://img.shields.io/github/stars/mlevy2525/P3PO?style=social&label=Star) [Github](https://github.com/mlevy2525/P3PO) |  |
| [**Track2Act: Predicting Point Tracks from Internet Videos enables Generalizable Robot Manipulation**](https://arxiv.org/abs/2405.01527) | ECCV 2024 | 2024-05-02 | ![Star](https://img.shields.io/github/stars/homangab/Track-2-Act?style=social&label=Star) [Github](https://github.com/homangab/Track-2-Act) |  |
| [ATM: **Any-point Trajectory Modeling for Policy Learning**](https://arxiv.org/abs/2401.00025) | RSS 2024 | 2023-12-28 | ![Star](https://img.shields.io/github/stars/Large-Trajectory-Model/any-point-trajectory-modeling?style=social&label=Star) [Github](https://github.com/Large-Trajectory-Model/any-point-trajectory-modeling) |  |
| [AWE: **Waypoint-Based Imitation Learning for Robotic Manipulation**](https://arxiv.org/abs/2307.14326) | CoRL 2023 | 2023-07-26 | ![Star](https://img.shields.io/github/stars/lucys0/awe?style=social&label=Star) [Github](https://github.com/lucys0/awe) | IL, Waypoint |
| _Flow-conditioned policy_|
| [**EC-Flow: Enabling Versatile Robotic Manipulation from Action-Unlabeled Videos via Embodiment-Centric Flow**](https://arxiv.org/abs/2507.06224) | ICCV 2025 | 2025-07-08 | ![Star](https://img.shields.io/github/stars/YixiangChen515/EC-Flow?style=social&label=Star) [Github](https://github.com/YixiangChen515/EC-Flow) |  |
| [**VLM-SFD: VLM-Assisted Siamese Flow Diffusion Framework for Dual-Arm Cooperative Manipulation**](https://arxiv.org/abs/2506.13428) | arXiv | 2025-06-16 | [Project](https://sites.google.com/view/vlm-sfd/) |  |
| [**3DFlowAction: Learning Cross-Embodiment Manipulation from 3D Flow World Model**](https://arxiv.org/abs/2506.06199) | arXiv | 2025-06-06 | ![Star](https://img.shields.io/github/stars/Hoyyyaard/3DFlowAction?style=social&label=Star) [Github](https://github.com/Hoyyyaard/3DFlowAction/) |  |
| [**VIP: Vision Instructed Pre-training for Robotic Manipulation**](https://arxiv.org/abs/2410.07169) | arXiv | 2024-10-09 | ![Star](https://img.shields.io/github/stars/Lizhuoling/VIRT?style=social&label=Star) [Github](https://github.com/Lizhuoling/VIRT) |  |
| [**ManiTrend: Bridging Future Generation and Action Prediction with 3D Flow for Robotic Manipulation**](https://arxiv.org/abs/2502.10028) | arXiv | 2024-02-14 | - |  |
| [Im2Flow2Act: **Flow as the Cross-Domain Manipulation Interface**](https://www.arxiv.org/abs/2407.15208) | CoRL 2024 | 2024-07-21 | ![Star](https://img.shields.io/github/stars/real-stanford/im2Flow2Act?style=social&label=Star) [Github](https://github.com/real-stanford/im2Flow2Act) |  |
| [AVDC: **Learning to Act from Actionless Videos through Dense Correspondences**](https://arxiv.org/abs/2310.08576) | ICLR 2024 | 2023-10-12 | ![Star](https://img.shields.io/github/stars/flow-diffusion/AVDC?style=social&label=Star) [Github](https://github.com/flow-diffusion/AVDC) | Optical Flow |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.12-Data Collection, Selection and Augmentation ******* -->
### Data Collection, Selection and Augmentation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Handware_ |
| [**Dexterous Teleoperation of 20-DoF ByteDexter Hand via Human Motion Retargeting**](https://arxiv.org/abs/2507.03227) | arXiv | 2025-07-04 | [Project](https://byte-dexter.github.io/) |  |
| [**DexWrist: A Robotic Wrist for Constrained and Dynamic Manipulation**](https://arxiv.org/abs/2507.01008) | arXiv | 2025-07-01 | [Project](https://dexwrist.csail.mit.edu/) |  |
| [**RAPID Hand: A Robust, Affordable, Perception-Integrated, Dexterous Manipulation Platform for Generalist Robot Autonomy**](https://arxiv.org/abs/2506.07490) | arXiv | 2025-05-09 | [Project](https://rapid-hand.github.io/) | |
| [**Demonstrating Learning from Humans on Open-Source Dexterous Robot Hands**](https://www.roboticsproceedings.org/rss20/p014.pdf) | RSS 2024 | 2024 | 2024-01-01 | |
| _Data Collection_ |
| [**Fast Bilateral Teleoperation and Imitation Learning Using Sensorless Force Control via Accurate Dynamics Model**](https://arxiv.org/abs/2507.06174) | arXiv | 2025-07-08 | - |  |
| [**TypeTele: Releasing Dexterity in Teleoperation by Dexterous Manipulation Types**](https://arxiv.org/abs/2507.01857) | arXiv | 2025-07-02 | [Project](https://isee-laboratory.github.io/TypeTele/) |
| [**CUPID: Curating Data your Robot Loves with Influence Functions**](https://arxiv.org/abs/2506.19121) | arXiv | 2025-06-23 | [Project](https://cupid-curation.github.io/) |  |
| [**Compliant Residual DAgger: Improving Real-World Contact-Rich Manipulation with Human Corrections**](https://arxiv.org/abs/2506.16685) | arXiv | 2025-06-20 | [Project](https://compliant-residual-dagger.github.io/) |  |
| [**mimic-one: a Scalable Model Recipe for General Purpose Robot Dexterity**](https://arxiv.org/abs/2506.11916) | arXiv | 2025-06-13 | [Project](https://mimicrobotics.github.io/mimic-one/) |  |
| [**ExoStart: Efficient learning for dexterous manipulation with sensorized exoskeleton demonstrations**](https://arxiv.org/abs/2506.11775) | arXiv | 2025-06-13 | [Project](https://sites.google.com/view/exostart) |  |  
| [**EgoZero: Robot Learning from Smart Glasses**](https://arxiv.org/abs/2505.20290) | arXiv | 2025-05-26 | [Project](https://egozero-robot.github.io/) |  |  
| [**Guiding Data Collection via Factored Scaling Curves**](https://arxiv.org/abs/2505.07728) | arXiv | 2025-05-12 | [Project](https://factored-data-scaling.github.io/) |  |  
| [**Kaiwu: A Multimodal Manipulation Dataset and Framework for Robot Learning and Human-Robot Interaction**](https://arxiv.org/abs/2503.05231) | arXiv | 2025-03-07 | - |  |  
| [**AVR: Active Vision-Driven Robotic Precision Manipulation with Viewpoint and Focal Length Optimization**](https://arxiv.org/abs/2503.01439) | arXiv | 2025-03-03 | [Project](https://avr-robot.github.io/) |  |  
| [**Physics-Driven Data Generation for Contact-Rich Manipulation via Trajectory Optimization**](https://arxiv.org/abs/2502.20382) | arXiv | 2025-02-27 | [Project](https://lujieyang.github.io/physicsgen/) |  |  
| [**Re<sup>3</sup>Sim: Generating High-Fidelity Simulation Data via 3D-Photorealistic Real-to-Sim for Robotic Manipulation**](https://arxiv.org/abs/2502.08645) | arXiv | 2025-02-12 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/Re3Sim?style=social&label=Star) [Github](https://github.com/OpenRobotLab/Re3Sim) |  |  
| [**ALPHA-α and Bi-ACT Are All You Need: Importance of Position and Force Information/Control for Imitation Learning of Unimanual and Bimanual Robotic Manipulation with Low-Cost System**](https://arxiv.org/abs/2411.09942) | arXiv | 2024-11-15 | [Project](https://mertcookimg.github.io/alpha-biact/) |  |
| [**DexUMI: Using Human Hand as the Universal Manipulation Interface for Dexterous Manipulation**](https://arxiv.org/abs/2505.21864) | RSSW 2025 | 2025-05-28 | ![Star](https://img.shields.io/github/stars/real-stanford/DexUMI?style=social&label=Star) [Github](https://github.com/real-stanford/DexUMI) |  |
| [**SkillMimicGen: Automated Demonstration Generation for Efficient Skill Learning and Deployment**](https://arxiv.org/abs/2410.18907) | CoRL 2024 | 2024-10-24 | [Project](https://skillgen.github.io/) |  |
| [NILS: **Scaling Robot Policy Learning via Zero-Shot Labeling with Foundation Models**](https://arxiv.org/abs/2410.17772) | CoRL 2024 | 2024-10-23 | [Project](https://robottasklabeling.github.io/) |  |
| [SOAR: **Autonomous Improvement of Instruction Following Skills via Foundation Models**](https://arxiv.org/abs/2407.20635) | CoRL 2024 | 2024-07-30 | ![Star](https://img.shields.io/github/stars/rail-berkeley/soar?style=social&label=Star) [Github](https://github.com/rail-berkeley/soar) |  |
| [**Manipulate-Anything: Automating Real-World Robots using Vision-Language Models**](https://arxiv.org/abs/2406.18915) | CoRL 2024 | 2024-06-27 | [Project](https://robot-ma.github.io/) | |
| [**DexCap: Scalable and Portable Mocap Data Collection System for Dexterous Manipulation**](https://arxiv.org/abs/2403.07788) | CoRL 2024 | 2024-03-12 | ![Star](https://img.shields.io/github/stars/j96w/DexCap?style=social&label=Star) [Github](https://github.com/j96w/DexCap) | |
| [**Universal Manipulation Interface: In-The-Wild Robot Teaching Without In-The-Wild Robots**](https://arxiv.org/abs/2402.10329) | RSS 2024 | 2024-02-15 | ![Star](https://img.shields.io/github/stars/real-stanford/universal_manipulation_interface?style=social&label=Star) [Github](https://github.com/real-stanford/universal_manipulation_interface) | |
| [**AirExo: Low-Cost Exoskeletons for Learning Whole-Arm Manipulation in the Wild**](https://arxiv.org/abs/2309.14975) | ICRA 2024 | 2023-09-26 | ![Star](https://img.shields.io/github/stars/AirExo/collector?style=social&label=Star) [Github](https://github.com/AirExo/collector) | |
| [**SPRINT: Scalable Policy Pre-Training via Language Instruction Relabeling**](https://arxiv.org/abs/2306.11886) | ICRA 2024 | 2023-06-20 | ![Star](https://img.shields.io/github/stars/clvrai/sprint?style=social&label=Star) [Github](https://github.com/clvrai/sprint) | |
| [**Scaling Up and Distilling Down: Language-Guided Robot Skill Acquisition**](https://arxiv.org/abs/2307.14535) | CoRL 2023 | 2023-07-26 | ![Star](https://img.shields.io/github/stars/real-stanford/scalingup?style=social&label=Star) [Github](https://github.com/real-stanford/scalingup) |  |
| [**AnyTeleop: A General Vision-Based Dexterous Robot Arm-Hand Teleoperation System**](https://arxiv.org/abs/2307.04577) | RSS 2023 | 2023-07-10 | [Project](https://yzqin.github.io/anyteleop/)  | |
| [DIAL: **Robotic Skill Acquisition via Instruction Augmentation with Vision-Language Models**](https://arxiv.org/abs/2211.11736) | RSS 2023 | 2022-11-21 | [Project](https://instructionaugmentation.github.io/) |  |
| [**RoboCat: A Self-Improving Generalist Agent for Robotic Manipulation**](https://arxiv.org/abs/2306.11706) | TMLR 2023 | 2023-06-20 | ![Star](https://img.shields.io/github/stars/kyegomez/RoboCAT?style=social&label=Star) [Github](https://github.com/kyegomez/RoboCAT) | |
| _Data Selection_ |
| [**Is Diversity All You Need for Scalable Robotic Manipulation?**](https://arxiv.org/abs/2507.06219) | arXiv | 2025-07-08 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/AgiBot-World?style=social&label=Star) [Github](https://github.com/OpenDriveLab/AgiBot-World) |  |
| [**SCIZOR: A Self-Supervised Approach to Data Curation for Large-Scale Imitation Learning**](https://arxiv.org/abs/2505.22626) | arXiv | 2025-05-28 | [Project](https://ut-austin-rpl.github.io/SCIZOR/) |  |
| [**Robot Data Curation with Mutual Information Estimators**](https://arxiv.org/abs/2502.08623) | arXiv | 2025-02-12 | [Project](https://joeyhejna.com/demonstration-info/) |  |
| [**What Matters in Learning from Large-Scale Datasets for Robot Manipulation**](https://openreview.net/forum?id=LqhorpRLIm) | ICLR 2025 | 2025-01-23 | [Project](https://mimiclabs-iclr.github.io/) |  |
| [AMF: **Active Fine-Tuning of Generalist Policies**](https://arxiv.org/abs/2410.05026) | arXiv | 2024-10-07 | - |  |
| [**Re-Mix: Optimizing Data Mixtures for Large Scale Imitation Learning**](https://arxiv.org/abs/2408.14037) | CoRL 2024 | 2024-08-26 | ![Star](https://img.shields.io/github/stars/jhejna/remix?style=social&label=Star) [Github](https://github.com/jhejna/remix) |  |
| [**An Unbiased Look at Datasets for Visuo-Motor Pre-Training**](https://arxiv.org/abs/2310.09289) | CoRL 2023 | 2023-10-13 | ![Star](https://img.shields.io/github/stars/SudeepDasari/data4robotics?style=social&label=Star) [Github](https://github.com/SudeepDasari/data4robotics) | |
| [**Data Quality in Imitation Learning**](https://arxiv.org/abs/2306.02437) | NeurIPS 2023 | 2023-06-04 | - |  |
| _Data Retrieval_ |
| [**STRAP: Robot Sub-Trajectory Retrieval for Augmented Policy Learning**](https://arxiv.org/abs/2412.15182) | ICLR 2025 | 2024-12-19 | [Project](https://weirdlabuw.github.io/strap/) | |
| [**Retrieval-Augmented Embodied Agents**](https://arxiv.org/abs/2404.11699) | CVPR 2024 | 2024-04-17 | - | |
| [**Behavior Retrieval: Few-Shot Imitation Learning by Querying Unlabeled Datasets**](https://arxiv.org/abs/2304.08742) | RSS 2023 | 2023-04-08 | ![Star](https://img.shields.io/github/stars/MaxDu17/BehaviorRetrieval?style=social&label=Star) [Github](https://github.com/MaxDu17/BehaviorRetrieval) | |
| _Data Augmentation_ |
| [**RoboPearls: Editable Video Simulation for Robot Manipulation**](https://arxiv.org/abs/2506.22756) | ICCV 2025| 2025-06-28 | [Project](https://tangtaogo.github.io/RoboPearls/) |  |
| [**RoboEngine: Plug-and-Play Robot Data Augmentation with Semantic Robot Segmentation and Background Generation**](https://arxiv.org/abs/2503.18738) | arXiv | 2025-03-24 | ![Star](https://img.shields.io/github/stars/michaelyuancb/roboengine?style=social&label=Star) [Github](https://github.com/michaelyuancb/roboengine) |  |
| [**Predictive Red Teaming: Breaking Policies Without Breaking Robots**](https://arxiv.org/abs/2502.06575) | arXiv | 2025-02-10 | [Project](https://predictive-red-team.github.io/) |  |
| [**RoCoDA: Counterfactual Data Augmentation for Data-Efficient Robot Learning from Demonstrations**](https://arxiv.org/abs/2411.16959) | arXiv | 2024-11-25 | [Project](https://rocoda.github.io/) |  |
| [**View-Invariant Policy Learning via Zero-Shot Novel View Synthesis**](https://arxiv.org/abs/2409.03685) | CoRL 2024 | 2024-09-05 | ![Star](https://img.shields.io/github/stars/s-tian/VISTA?style=social&label=Star) [Github](https://github.com/s-tian/VISTA) |  |
| [**RoVi-Aug: Robot and Viewpoint Augmentation for Cross-Embodiment Robot Learning**](https://arxiv.org/abs/2409.03403) | CoRL 2024 | 2024-09-05 | [Project](https://rovi-aug.github.io/) |  |
| [**Diffusion Augmented Agents: A Framework for Efficient Exploration and Transfer Learning**](https://arxiv.org/abs/2407.20798) | CoLLAs 2024 | 2024-07-30 | [Project](https://sites.google.com/view/diffusion-augmented-agents/) |  |
| [**Diffusion Meets DAgger: Supercharging Eye-in-hand Imitation Learning**](https://arxiv.org/abs/2402.17768) | RSS 2024 | 2023-02-27 | ![Star](https://img.shields.io/github/stars/ErinZhang1998/dmd_diffusion?style=social&label=Star) [Github](https://github.com/ErinZhang1998/dmd_diffusion) | |
| [ROSIE: **Scaling Robot Learning with Semantically Imagined Experience**](https://arxiv.org/abs/2302.11550) | RSS 2023 | 2023-02-22 | [Project](https://diffusion-rosie.github.io/) |  |
| [**GenAug: Retargeting behaviors to unseen situations via Generative Augmentation**](https://arxiv.org/abs/2302.06671) | RSS 2023 | 2023-02-13 | ![Star](https://img.shields.io/github/stars/genaug/genaug?style=social&label=Star) [Github](https://github.com/genaug/genaug) |  |
| _Evaluation_|
| [**Efficient Evaluation of Multi-Task Robot Policies With Active Experiment Selection**](https://arxiv.org/abs/2502.09829) | arXiv | 2025-02-14 | - |  |
| [**Contrast Sets for Evaluating Language-Guided Robot Policies**](https://arxiv.org/abs/2406.13636) | CoRL 2024 | 2024-06-19 | - |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.13-Affordance Learning ******* -->
### Affordance Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Articulated Object Affordance_ |
| [**ManipGPT: Is Affordance Segmentation by Large Vision Models Enough for Articulated Object Manipulation?**](https://arxiv.org/abs/2412.10050) | arXiv | 2024-12-13 | - | |
| [**UniAff: A Unified Representation of Affordances for Tool Usage and Articulation with Vision-Language Models**](https://arxiv.org/abs/2409.20551) | ICRA 2025 | 2024-09-16 | [Project](https://sites.google.com/view/uni-aff/home) | |
| [**A3VLM: Actionable Articulation-Aware Vision Language Model**](https://arxiv.org/abs/2406.07549) | CoRL 2024 | 2024-06-14 | ![Star](https://img.shields.io/github/stars/changhaonan/A3VLM?style=social&label=Star) [Github](https://github.com/changhaonan/A3VLM) | |
| [**AIC MLLM: Autonomous Interactive Correction MLLM for Robust Robotic Manipulation**](https://arxiv.org/abs/2406.11548) | CoRL 2024 | 2024-06-17 | [Project](https://sites.google.com/view/aic-mllm) | |
| [**SAGE: Bridging Semantic and Actionable Parts for Generalizable Manipulation of Articulated Objects**](https://arxiv.org/abs/2312.01307) | RSS 2024 | 2023-12-03 | ![Star](https://img.shields.io/github/stars/geng-haoran/SAGE?style=social&label=Star) [Github](https://github.com/geng-haoran/SAGE) | |
| [**Kinematic-aware Prompting for Generalizable Articulated Object Manipulation with LLMs**](https://arxiv.org/abs/2311.02847) | ICRA 2024 | 2023-11-06 | ![Star](https://img.shields.io/github/stars/GeWu-Lab/LLM_articulated_object_manipulation?style=social&label=Star) [Github](https://github.com/GeWu-Lab/LLM_articulated_object_manipulation) | |
| [**Ditto: Building Digital Twins of Articulated Objects from Interaction**](https://arxiv.org/abs/2202.08227) | CVPR 2022 | 2022-08-16 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/Ditto?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/Ditto) | |
| _Part-Based Object Affordance_ |
| [**PartInstruct: Part-level Instruction Following for Fine-grained Robot Manipulation**](https://arxiv.org/abs/2505.21652) | RSS 2025 | 2025-05-27 | ![Star](https://img.shields.io/github/stars/SCAI-JHU/PartInstruct?style=social&label=Star)  [Github](https://github.com/SCAI-JHU/PartInstruct) | |
| [3DAPNet: **Language-Conditioned Affordance-Pose Detection in 3D Point Clouds**](https://arxiv.org/abs/2309.10911) | ICRA 2024 | 2023-09-19 | ![Star](https://img.shields.io/github/stars/Fsoft-AIC/Language-Conditioned-Affordance-Pose-Detection-in-3D-Point-Clouds?style=social&label=Star)  [Github](https://github.com/Fsoft-AIC/Language-Conditioned-Affordance-Pose-Detection-in-3D-Point-Clouds) | |
| [CPM: **Composable Part-Based Manipulation**](https://arxiv.org/abs/2405.05876) | CoRL 2023 | 2024-05-09 | [Project](https://cpmcorl2023.github.io/) | |
| [**PartManip: Learning Cross-Category Generalizable Part Manipulation Policy from Point Cloud Observations**](https://arxiv.org/abs/2303.16958) | CVPR 2023 | 2023-03-29 | ![Star](https://img.shields.io/github/stars/PKU-EPIC/PartManip?style=social&label=Star)  [Github](https://github.com/PKU-EPIC/PartManip) | |
| [**GAPartNet: Cross-Category Domain-Generalizable Object Perception and Manipulation via Generalizable and Actionable Parts**](https://arxiv.org/abs/2211.05272) | CVPR 2023 | 2022-11-10 | ![Star](https://img.shields.io/github/stars/PKU-EPIC/GAPartNet?style=social&label=Star) [Github](https://github.com/PKU-EPIC/GAPartNet) | |
| _Spatial Affordance_ |
| [**T-Rex: Task-Adaptive Spatial Representation Extraction for Robotic Manipulation with Vision-Language Models**](https://arxiv.org/abs/2506.19498) | arXiv | 2025-06-24 | - | |
| [**Bridging Perception and Action: Spatially-Grounded Mid-Level Representations for Robot Generalization**](https://arxiv.org/abs/2506.06196) | arXiv | 2025-06-06 | [Project](https://mid-level-moe.github.io/) | |
| [**Robotic Visual Instruction**](https://arxiv.org/abs/2505.00693) | CVPR 2025 | 2025-05-01 | [Project](https://robotic-visual-instruction.github.io/#) | |
| [**RoboSpatial: Teaching Spatial Understanding to 2D and 3D Vision-Language Models for Robotics**](https://arxiv.org/abs/2411.16537) | arXiv | 2024-11-25 | [Project](https://chanh.ee/RoboSpatial/) | |
| [**SpatialBot: Precise Spatial Understanding with Vision Language Models**](https://arxiv.org/abs/2406.13642) | ICRA 2025 | 2024-06-19 | ![Star](https://img.shields.io/github/stars/BAAI-DCAI/SpatialBot?style=social&label=Star)  [Github](https://github.com/BAAI-DCAI/SpatialBot) | |
| [**RoboPoint: A Vision-Language Model for Spatial Affordance Prediction for Robotics**](https://arxiv.org/abs/2406.10721) | CoRL 2024 | 2024-06-15 | ![Star](https://img.shields.io/github/stars/wentaoyuan/RoboPoint?style=social&label=Star) [Github](https://github.com/wentaoyuan/RoboPoint) | |
| [**SpatialVLM: Endowing Vision-Language Models with Spatial Reasoning Capabilities**](https://arxiv.org/abs/2401.12168) | CVPR 2024 | 2024-01-22 | [Project](https://spatial-vlm.github.io/) | |
| _Visual Affordance_|
| [**UAD: Unsupervised Affordance Distillation for Generalization in Robotic Manipulation**](https://arxiv.org/abs/2506.09284) | arXiv | 2025-06-10 | ![Star](https://img.shields.io/github/stars/TangYihe/unsup-affordance?style=social&label=Star) [Github](https://github.com/TangYihe/unsup-affordance) | |
| [**RAM: Retrieval-Based Affordance Transfer for Generalizable Zero-Shot Robotic Manipulation**](https://arxiv.org/abs/2407.04689) | CoRL 2024 | 2024-07-05 | ![Star](https://img.shields.io/github/stars/yxKryptonite/RAM_code?style=social&label=Star) [Github](https://github.com/yxKryptonite/RAM_code) | |
| [**MOKA: Open-World Robotic Manipulation through Mark-Based Visual Prompting**](https://arxiv.org/abs/2403.03174) | RSS 2024 | 2024-03-05 | ![Star](https://img.shields.io/github/stars/moka-manipulation/moka?style=social&label=Star) [Github](https://github.com/moka-manipulation/moka) |  |
| [**SLAP: Spatial-Language Attention Policies**](https://arxiv.org/abs/2304.11235) | CoRL 2023 | 2023-04-21 | ![Star](https://img.shields.io/github/stars/facebookresearch/home-robot?style=social&label=Star)  [Github](https://github.com/facebookresearch/home-robot/tree/main/projects/slap_manipulation) | |
| [**KITE: Keypoint-Conditioned Policies for Semantic Manipulation**](https://arxiv.org/abs/2306.16605) | CoRL 2023 | 2023-06-29 | [Project](https://sites.google.com/view/kite-website/home) | |
| [HULC++: **Grounding Language with Visual Affordances over Unstructured Data**](https://arxiv.org/abs/2210.01911) | ICRA 2023 | 2022-10-04 | ![Star](https://img.shields.io/github/stars/mees/hulc2?style=social&label=Star) [Github](https://github.com/mees/hulc2) | IL, RepL, Language Goal, Poliy Head, Visual Affordance  |
| [**CLIPort: What and Where Pathways for Robotic Manipulation**](https://arxiv.org/abs/2109.12098) | CoRL 2022 | 2021-09-24 | ![Star](https://img.shields.io/github/stars/cliport/cliport?style=social&label=Star) [Github](https://github.com/cliport/cliport) | |
| [VAPO: **Affordance Learning from Play for Sample-Efficient Policy Learning**](https://arxiv.org/abs/2203.00352) | ICRA 2022 | 2022-03-01 | [Project](http://vapo.cs.uni-freiburg.de/) | RepL, RL, Object-Centric |
| [**Transporter Networks: Rearranging the Visual World for Robotic Manipulation**](https://arxiv.org/abs/2010.14406) | CoRL 2020 | 2020-10-27 | ![Star](https://img.shields.io/github/stars/google-research/ravens?style=social&label=Star) [Github](https://github.com/google-research/ravens) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.14-3D Representation for Manipulation ******* -->
### 3D Representation for Manipulation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [RoboSplat: **Novel Demonstration Generation with Gaussian Splatting Enables Robust One-Shot Manipulation**](https://arxiv.org/abs/2504.13175) | RSS 2025 | 2025-04-17 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/robosplat?style=social&label=Star) [Github](https://github.com/OpenRobotLab/robosplat) | |
| [**G3Flow: Generative 3D Semantic Flow for Pose-aware and Generalizable Object Manipulation**](https://arxiv.org/abs/2411.18369) | arXiv | 2024-11-27 | ![Star](https://img.shields.io/github/stars/TianxingChen/G3Flow?style=social&label=Star) [Github](https://github.com/TianxingChen/G3Flow) | |
| [**MSGField: A Unified Scene Representation Integrating Motion, Semantics, and Geometry for Robotic Manipulation**](https://arxiv.org/abs/2410.15730) | arXiv | 2024-10-21 | ![Star](https://img.shields.io/github/stars/ShengYu724/MSGField?style=social&label=Star) [Github](https://github.com/ShengYu724/MSGField) | 2DGS |
| [**Splat-MOVER: Multi-Stage, Open-Vocabulary Robotic Manipulation via Editable Gaussian Splatting**](https://arxiv.org/abs/2405.04378) | CoRL 2024 | 2024-05-07 | ![Star](https://img.shields.io/github/stars/StanfordMSL/Splat-MOVER?style=social&label=Star) [Github](https://github.com/StanfordMSL/Splat-MOVER) | 3DGS |
| [**IMAGINATION POLICY: Using Generative Point Cloud Models for Learning Manipulation Policies**](https://arxiv.org/abs/2406.11740) | CoRL 2024 | 2024-06-17 | [Project](https://haojhuang.github.io/imagine_page/) |  |
| [**Physically Embodied Gaussian Splatting: A Realtime Correctable World Model for Robotics**](https://arxiv.org/abs/2406.10788) | CoRL 2024 | 2024-06-16 | [Project](https://embodied-gaussians.github.io/) | 3DGS |
| [**RiEMann: Near Real-Time SE(3)-Equivariant Robot Manipulation without Point Cloud Segmentation**](https://arxiv.org/abs/2403.19460) | CoRL 2024 | 2024-03-28 | ![Star](https://img.shields.io/github/stars/HeegerGao/RiEMann?style=social&label=Star) [Github](https://github.com/HeegerGao/RiEMann) |  |
| [**RoboEXP: Action-Conditioned Scene Graph via Interactive Exploration for Robotic Manipulation**](https://arxiv.org/abs/2402.15487) | CoRL 2024 | 2024-02-23 | ![Star](https://img.shields.io/github/stars/Jianghanxiao/RoboEXP?style=social&label=Star) [Github](https://github.com/Jianghanxiao/RoboEXP) | 3D reasoning, action-conditioned scene graph (ACSG) task |
| [**D<sup>3</sup>Fields: Dynamic 3D Descriptor Fields for Zero-Shot Generalizable Rearrangement**](https://arxiv.org/abs/2309.16118) | CoRL 2024 | 2023-09-28 | ![Star](https://img.shields.io/github/stars/WangYixuan12/d3fields?style=social&label=Star) [Github](https://github.com/WangYixuan12/d3fields) |  |
| [**Object-Aware Gaussian Splatting for Robotic Manipulation**](https://openreview.net/pdf?id=gdRI43hDgo) | ICRAW 2024 | 2024-04-24 | [Project](https://object-aware-gaussian.github.io/) | 3DGS |
| [F3RM: **Distilled Feature Fields Enable Few-Shot Language-Guided Manipulation**](https://arxiv.org/abs/2308.07931) | CoRL 2023 | 2023-07-27 | ![Star](https://img.shields.io/github/stars/f3rm/f3rm?style=social&label=Star) [Github](https://github.com/f3rm/f3rm) | NeRF |
| [R-NDF: **SE(3)-Equivariant Relational Rearrangement with Neural Descriptor Fields**](https://arxiv.org/abs/2211.09786) | CORL 2022 | 2022-11-17 | ![Star](https://img.shields.io/github/stars/anthonysimeonov/relational_ndf?style=social&label=Star)  [Github](https://github.com/anthonysimeonov/relational_ndf) |  |
| [NDF: **Neural Descriptor Fields: SE(3)-Equivariant Object Representations for Manipulation**](https://arxiv.org/abs/2112.05124) | ICRA 2022 | 2021-12-09 | ![Star](https://img.shields.io/github/stars/anthonysimeonov/ndf_robot?style=social&label=Star) [Github](https://github.com/anthonysimeonov/ndf_robot) |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.15-3D Representation Policy Learning ******* -->
### 3D Representation Policy Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Diffusion Policy (DP)_|
| [**PRISM: Pointcloud Reintegrated Inference via Segmentation and Cross-attention for Manipulation**](https://arxiv.org/abs/2507.04633) | arXiv | 2025-07-07 | ![Star](https://img.shields.io/github/stars/czknuaa/PRISM?style=social&label=Star) [Github](https://github.com/czknuaa/PRISM) |  |
| [PPI: **Gripper Keypose and Object Pointflow as Interfaces for Bimanual Robotic Manipulation**](https://arxiv.org/abs/2504.17784) | RSS 2025 | 2025-04-24 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/PPI?style=social&label=Star) [Github](https://github.com/OpenRobotLab/PPI) |  |
| [**GravMAD: Grounded Spatial Value Maps Guided Action Diffusion for Generalized 3D Manipulation**](https://arxiv.org/abs/2409.20154) | ICLR 2025 | 2024-09-30 | [Project](https://gravmad.github.io/) |  |
| [**3D Diffuser Actor: Policy Diffusion with 3D Scene Representations**](https://arxiv.org/abs/2402.10885) | CoRL 2024 | 2024-02-16 | ![Star](https://img.shields.io/github/stars/nickgkan/3d_diffuser_actor?style=social&label=Star) [Github](https://github.com/nickgkan/3d_diffuser_actor) |  |
| [DP3: **3D Diffusion Policy: Generalizable Visuomotor Policy Learning via Simple 3D Representations**](https://arxiv.org/abs/2403.03954) | RSS 2024 | 2024-03-06 | ![Star](https://img.shields.io/github/stars/YanjieZe/3D-Diffusion-Policy?style=social&label=Star) [Github](https://github.com/YanjieZe/3D-Diffusion-Policy) |  |
| _Reconstruction_ |
| [**CL3R: 3D Reconstruction and Contrastive Learning for Enhanced Robotic Manipulation Representations**](https://arxiv.org/abs/2507.08262) | arXiv | 2025-07-11 | - |  |
| [**EquAct: An SE(3)-Equivariant Multi-Task Transformer for Open-Loop Robotic Manipulation**](https://arxiv.org/abs/2505.21351) | arXiv | 2025-05-27 | - |  |
| [**Lift3D Foundation Policy: Lifting 2D Large-Scale Pretrained Models for Robust 3D Robotic Manipulation**](https://arxiv.org/abs/2411.18623) | arXiv | 2024-11-27 | ![Star](https://img.shields.io/github/stars/PKU-HMI-Lab/LIFT3D?style=social&label=Star) [Github](https://github.com/PKU-HMI-Lab/LIFT3D) |  |
| [**SPA: 3D Spatial-Awareness Enables Effective Embodied Representation**](https://arxiv.org/abs/2410.08208) | ICLR 2025 | 2024-10-10 | ![Star](https://img.shields.io/github/stars/HaoyiZhu/SPA?style=social&label=Star) [Github](https://github.com/HaoyiZhu/SPA) | |
| [**ManiGaussian: Dynamic Gaussian Splatting for Multi-task Robotic Manipulation**](https://arxiv.org/abs/2403.08321) | ECCV 2024 | 2024-03-13 | ![Star](https://img.shields.io/github/stars/GuanxingLu/ManiGaussian?style=social&label=Star) [Github](https://github.com/GuanxingLu/ManiGaussian) | 3DGS, IL, Language Goal, Reconstruction/Prediction |
| [SGRv2: **Leveraging Locality to Boost Sample Efficiency in Robotic Manipulation**](https://arxiv.org/abs/2406.10615) | CoRL 2024 | 2024-06-15 | ![Star](https://img.shields.io/github/stars/TongZhangTHU/sgr?style=social&label=Star) [Github](https://github.com/TongZhangTHU/sgr) |  |
| [**RVT-2: Learning Precise Manipulation from Few Demonstrations**](https://arxiv.org/abs/2406.08545) | RSS 2024 | 2024-01-12 | ![Star](https://img.shields.io/github/stars/nvlabs/rvt?style=social&label=Star) [Github](https://github.com/nvlabs/rvt) |  |
| [**GNFactor: Multi-Task Real Robot Learning with Generalizable Neural Feature Fields**](https://arxiv.org/abs/2308.16891) | CoRL 2023 | 2023-08-31 | ![Star](https://img.shields.io/github/stars/YanjieZe/GNFactor?style=social&label=Star) [Github](https://github.com/YanjieZe/GNFactor) | NeRF, IL, Language Goal, Reconstruction |
| [3D4RL: **Visual Reinforcement Learning with Self-Supervised 3D Representations**](https://arxiv.org/abs/2210.07241) | RA-L 2023 | 2022-10-13 | ![Star](https://img.shields.io/github/stars/YanjieZe/rl3d?style=social&label=Star) [Github](https://github.com/YanjieZe/rl3d) | RL, RepL, Reconstruction, Image Goal |
| [**PolarNet: 3D Point Clouds for Language-Guided Robotic Manipulation**](https://arxiv.org/abs/2309.15596) | CoRL 2023 | 2023-09-27 | ![Star](https://img.shields.io/github/stars/vlc-robot/polarnet?style=social&label=Star) [Github](https://github.com/vlc-robot/polarnet) |  |
| [**M2T2: Multi-Task Masked Transformer for Object-centric Pick and Place**](https://arxiv.org/abs/2311.00926) | CoRL 2023 | 2023-11-02 | ![Star](https://img.shields.io/github/stars/NVlabs/M2T2?style=social&label=Star) [Github](https://github.com/NVlabs/M2T2) |  |
| [PerAct: **Perceiver-Actor: A Multi-Task Transformer for Robotic Manipulation**](https://arxiv.org/abs/2209.05451) | CoRL 2022 | 2022-09-12 | ![Star](https://img.shields.io/github/stars/peract/peract?style=social&label=Star)  [Github](https://github.com/peract/peract) | PerAct |
| _Visual Goal Generation_ |
| [**3D-MVP: 3D Multiview Pretraining for Robotic Manipulation**](https://arxiv.org/abs/2406.18158) | CVPR 2025 | 2024-06-26 | [Project](https://jasonqsy.github.io/3DMVP/) |  |
| [ActAIM2: **Discovering Robotic Interaction Modes with Discrete Representation Learning**](https://arxiv.org/abs/2410.20258) | CoRL 2024 | 2024-10-26 | [Project](https://actaim2.github.io/) |  |
| [**SAM-E: Leveraging Visual Foundation Model with Sequence Imitation for Embodied Manipulation**](https://arxiv.org/abs/2405.19586) | ICML 2024 | 2024-05-30 | ![Star](https://img.shields.io/github/stars/pipixiaqishi1/SAM-E?style=social&label=Star) [Github](https://github.com/pipixiaqishi1/SAM-E) |  |
| [**RVT: Robotic View Transformer for 3D Object Manipulation**](https://arxiv.org/abs/2306.14896) | CoRL 2023 | 2023-06-26 | ![Star](https://img.shields.io/github/stars/nvlabs/rvt?style=social&label=Star) [Github](https://github.com/nvlabs/rvt) |  |
| [GROOT: **Learning Generalizable Manipulation Policies with Object-Centric 3D Representations**](https://arxiv.org/abs/2310.14386) | CoRL 2023 | 2023-10-22 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/GROOT?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/GROOT) | IL, RepL, TP, Object-Centric, PC |
| _3D Policy_ |
| [**FlowRAM: Grounding Flow Matching Policy with Region-Aware Mamba Framework for Robotic Manipulation**](https://arxiv.org/abs/2506.16201) | arXiv | 2025-06-19 | - |  |
| [**EmbodiedMAE: A Unified 3D Multi-Modal Representation for Robot Manipulation**](https://arxiv.org/abs/2505.10105) | arXiv | 2025-05-15 | - |  |
| [**FP3: A 3D Foundation Policy for Robotic Manipulation**](https://arxiv.org/abs/2503.08950) | arXiv | 2025-03-11 | ![Star](https://img.shields.io/github/stars/horipse01/3d-foundation-policy?style=social&label=Star) [Github](https://github.com/horipse01/3d-foundation-policy) |  |
| [**VidBot: Learning Generalizable 3D Actions from In-the-Wild 2D Human Videos for Zero-Shot Robotic Manipulation**](https://arxiv.org/abs/2503.07135) | CVPR 2025 | 2025-03-10 | [Project](https://hanzhic.github.io/vidbot-project/) |  |
| [SPHINX: **What's the Move? Hybrid Imitation Learning via Salient Points**](https://arxiv.org/abs/2412.05426) | ICLR 2025 | 2024-12-06 | ![Star](https://img.shields.io/github/stars/priyasundaresan/sphinx?style=social&label=Star) [Github](https://github.com/priyasundaresan/sphinx) |  |
| [SGR: **A Universalc Semantic-Geometric Representation for Robotic Manipulation**](https://arxiv.org/abs/2306.10474) | CoRL 2023 | 2023-06-18 | ![Star](https://img.shields.io/github/stars/TongZhangTHU/sgr?style=social&label=Star) [Github](https://github.com/TongZhangTHU/sgr) |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.16-Reasoning, Planning and Code Generation ******* -->
### High-level Planner
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Control_|
| [**DEMONSTRATE: Zero-shot Language to Robotic Control via Multi-task Demonstration Learning**](https://arxiv.org/abs/2507.12855) | arXiv | 2025-07-17 | - |  |
| _Task Planning_ |
| [**Imagine, Verify, Execute: Memory-Guided Agentic Exploration with Vision-Language Models**](https://arxiv.org/abs/2505.07815) | arXiv | 2025-05-12 | [Project](https://ive-robot.github.io/) |  |
| [**MALMM: Multi-Agent Large Language Models for Zero-Shot Robotics Manipulation**](https://arxiv.org/abs/2411.17636) | arXiv | 2024-11-26 | [Project](https://malmm1.github.io/) |  |
| [**Socratic Planner: Inquiry-Based Zero-Shot Planning for Embodied Instruction Following**](https://arxiv.org/abs/2404.15190) | arXiv | 2024-04-21 | - | |
| [**Polaris: Open-ended Interactive Robotic Manipulation via Syn2Real Visual Grounding and Large Language Models**](https://arxiv.org/abs/2408.07975) | IROS 2024 | 2024-08-15 | [Project](https://star-uu-wang.github.io/Polaris/) |  |
| [PG-InstructBLIP: **Physically Grounded Vision-Language Models for Robotic Manipulation**](https://arxiv.org/abs/2309.02561) | ICRA 2024 | 2023-09-05 | [Project](https://iliad.stanford.edu/pg-vlm/) |  |
| [**RoCo: Dialectic Multi-Robot Collaboration with Large Language Models**](https://arxiv.org/abs/2307.04738) | ICRA 2024 | 2023-07-10 | ![Star](https://img.shields.io/github/stars/MandiZhao/robot-collab?style=social&label=Star) [Github](https://github.com/MandiZhao/robot-collab) | |
| [**REFLECT: Summarizing Robot Experiences for Failure Explanation and Correction**](https://arxiv.org/abs/2306.15724) | CoRL 2023 | 2023-06-27 | ![Star](https://img.shields.io/github/stars/real-stanford/reflect?style=social&label=Star) [Github](https://github.com/real-stanford/reflect) | |
| [Saycan: **Do As I Can, Not As I Say: Grounding Language in Robotic Affordances**](https://arxiv.org/abs/2204.01691) | CoRL 2023 | 2022-04-04 | ![Star](https://img.shields.io/github/stars/google-research/google-research?style=social&label=Star) [Github](https://github.com/google-research/google-research/tree/master/saycan) | |
| [**LLM+P: Empowering Large Language Models with Optimal Planning Proficiency**](https://arxiv.org/abs/2304.11477) | arXiv | 2023-04-22 | ![Star](https://img.shields.io/github/stars/Cranial-XIX/llm-pddl?style=social&label=Star) [Github](https://github.com/Cranial-XIX/llm-pddl) | |
| [**Inner Monologue: Embodied Reasoning through Planning with Language Models**](https://arxiv.org/abs/2207.05608) | CoRL 2022 | 2022-07-12 | [Project](https://innermonologue.github.io/) | |
| [SHOWTELL: **Teaching Robots with Show and Tell: Using Foundation Models to Synthesize Robot Policies from Language and Visual Demonstrations**](https://openreview.net/pdf?id=G8UcwxNAoD) | CoRL 2024 | 2024-09-06 | [Project](https://robo-showtell.github.io/) |  |
| [GIRAF: **Gesture-Informed Robot Assistance via Foundation Models**](https://arxiv.org/abs/2309.02721) | CoRL 2023 | 2023-09-06 | [Project](https://sites.google.com/view/giraf23) | |
| [**LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models**](https://arxiv.org/abs/2212.04088) | ICCV 2023 | 2022-12-08 | ![Star](https://img.shields.io/github/stars/OSU-NLP-Group/LLM-Planner?style=social&label=Star) [Github](https://github.com/OSU-NLP-Group/LLM-Planner/) |  |
| _Code Generation_ |
| [**Robotic Programmer: Video Instructed Policy Code Generation for Robotic Manipulation**](https://arxiv.org/abs/2501.04268) | arXiv | 2025-01-08 | [Project](https://video2code.github.io/RoboPro-website/) | |
| [**Demo2Code: From Summarizing Demonstrations to Synthesizing Code via Extended Chain-of-Thought**](https://arxiv.org/abs/2305.16744) | NeurIPS 2023 | 2023-05-26 | [Project](https://portal-cornell.github.io/demo2code/) | |
| [**Instruct2Act: Mapping Multi-modality Instructions to Robotic Actions with Large Language Model**](https://arxiv.org/abs/2305.11176) | arXiv | 2023-05-18 | ![Star](https://img.shields.io/github/stars/OpenGVLab/Instruct2Act?style=social&label=Star) [Github](https://github.com/OpenGVLab/Instruct2Act) | LLMs, VLMs, Code Generation |
| [**ProgPrompt: Generating Situated Robot Task Plans using Large Language Models**](https://arxiv.org/abs/2209.11302) | ICRA 2023 | 2022-09-22 | ![Star](https://img.shields.io/github/stars/NVlabs/progprompt-vh?style=social&label=Star) [Github](https://github.com/NVlabs/progprompt-vh) | LLMs, Code Generation |
| [**ChatGPT for Robotics: Design Principles and Model Abilities**](https://arxiv.org/abs/2306.17582) | IEEE Access 2023 | 2023-02-20 | ![Star](https://img.shields.io/github/stars/microsoft/PromptCraft-Robotics?style=social&label=Star) [Github](https://github.com/microsoft/PromptCraft-Robotics) | LLMs, Code Generation |
| [**Code as Policies: Language Model Programs for Embodied Control**](https://arxiv.org/abs/2209.07753) | ICRA 2023 | 2022-09-16 | ![Star](https://img.shields.io/github/stars/google-research/google-research?style=social&label=Star) [Github](https://github.com/google-research/google-research/tree/master/code_as_policies) | LLMs, Code Generation |
| [**TidyBot: Personalized Robot Assistance with Large Language Models**](https://arxiv.org/abs/2305.05658) | Autonomous Robots 2023 | 2023-05-09 | ![Star](https://img.shields.io/github/stars/jimmyyhwu/tidybot?style=social&label=Star) [Github](https://github.com/jimmyyhwu/tidybot) | LLMs, Code Generation |
| [**Statler: State-Maintaining Language Models for Embodied Reasoning**](https://arxiv.org/abs/2306.17840) | ICRA 2024 | 2023-06-30 | ![Star](https://img.shields.io/github/stars/ripl/statler?style=social&label=Star) [Github](https://github.com/ripl/statler) | LLMs, Code Generation |
| [**InterPreT: Interactive Predicate Learning from Language Feedback for Generalizable Task Planning**](https://arxiv.org/abs/2405.19758) | RSS 2024 | 2023-05-30 | ![Star](https://img.shields.io/github/stars/hmz-15/interactive-predicate-learning?style=social&label=Star) [Github](https://github.com/hmz-15/interactive-predicate-learning) | Code Generation, Task Planning, PDDL |
| [**Text2Motion: From Natural Language Instructions to Feasible Plans**](https://arxiv.org/abs/2303.12153) | Autonomous Robots 2023 | 2023-03-21 | [Project](https://sites.google.com/stanford.edu/text2motion) |  |
| _Multimodal Reasoning_ |
| [**RoboBrain 2.0 Technical Report**](https://arxiv.org/abs/2507.02029) | arXiv | 2025-07-02 | ![Star](https://img.shields.io/github/stars/FlagOpen/RoboBrain2.0?style=social&label=Star) [Github](https://github.com/FlagOpen/RoboBrain2.0) |  |
| [**EmbodiedVSR: Dynamic Scene Graph-Guided Chain-of-Thought Reasoning for Visual Spatial Tasks**](https://arxiv.org/abs/2503.11089) | arXiv | 2025-03-14 | - |  |
| [**Can We Detect Failures Without Failure Data? Uncertainty-Aware Runtime Failure Detection for Imitation Learning Policies**](https://arxiv.org/abs/2503.08558) | arXiv | 2025-03-11 | [Project](https://cxu-tri.github.io/FAIL-Detect-Website/) |  |
| [**SoFar: Language-Grounded Orientation Bridges Spatial Reasoning and Object Manipulation**](https://arxiv.org/abs/2502.13143) | arXiv | 2025-02-18 | ![Star](https://img.shields.io/github/stars/qizekun/SoFar?style=social&label=Star) [Github](https://github.com/qizekun/SoFar) |  |
| [**From Foresight to Forethought: VLM-In-the-Loop Policy Steering via Latent Alignment**](https://arxiv.org/abs/2502.01828) | arXiv | 2025-02-03 | - |  |
| [**Code-as-Monitor: Constraint-aware Visual Programming for Reactive and Proactive Robotic Failure Detection**](https://arxiv.org/abs/2412.04455) | CVPR 2025 | 2024-12-05 | [Project](https://zhoues.github.io/Code-as-Monitor/) | VLMs, Failure Detection |
| [**AHA: A Vision-Language-Model for Detecting and Reasoning Over Failures in Robotic Manipulation**](https://arxiv.org/abs/2410.00371) | ICLR 2025 | 2024-10-01 | [Project](https://aha-vlm.github.io/) | VLMs, Failure Detection |
| [λ-Repformer: **Task Success Prediction for Open-Vocabulary Manipulation Based on Multi-Level Aligned Representations**](https://arxiv.org/abs/2410.00436) | CoRL 2024 | 2024-10-01 | [Project](https://lambda-repformer-project-pa-eziy1.kinsta.page/) | RepL, Multi-level, E-D TP, Both Goals |
| [**ManipLLM: Embodied Multimodal Large Language Model for Object-Centric Robotic Manipulation**](https://arxiv.org/abs/2312.16217) | CVPR 2024 | 2023-12-24 | ![Star](https://img.shields.io/github/stars/clorislili/ManipLLM?style=social&label=Star) [Github](https://github.com/clorislili/ManipLLM) |  |
| [**EmbodiedGPT: Vision-Language Pre-Training via Embodied Chain of Thought**](https://arxiv.org/abs/2305.15021) | NeurIPS 2023 | 2023-05-24 | ![Star](https://img.shields.io/github/stars/EmbodiedGPT/EmbodiedGPT_Pytorch?style=social&label=Star) [Github](https://github.com/EmbodiedGPT/EmbodiedGPT_Pytorch) |  |
| [Matcha: **Chat with the Environment: Interactive Multimodal Perception Using Large Language Models**](https://arxiv.org/abs/2303.08268) | IROS 2023 | 2023-03-14 | ![Star](https://img.shields.io/github/stars/xf-zhao/Matcha-agent?style=social&label=Star) [Github](https://github.com/xf-zhao/Matcha-agent) |  |
| [**PaLM-E: An Embodied Multimodal Language Model**](https://arxiv.org/abs/2303.03378) | ICML 2023 | 2023-03-06 | ![Star](https://img.shields.io/github/stars/kyegomez/PALM-E?style=social&label=Star) [Github](https://github.com/kyegomez/PALM-E) |  |
| [**Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language**](https://arxiv.org/abs/2204.00598) | ICLR 2023 | 2022-04-01 | [Project](https://github.com/google-research/google-research/tree/master/socraticmodels) |  |
<!--  
| Reasoning w/o robotics |
| [**Language Models as Zero-Shot Planners: Extracting Actionable Knowledge for Embodied Agents**](https://arxiv.org/abs/2201.07207) | ICML 2022 | 2022-01-18 | [Github](https://github.com/huangwl18/language-planner) | |
| [**Large Language Models as Commonsense Knowledge for Large-Scale Task Planning**](https://arxiv.org/abs/2305.14078) | NeurIPS 2023 | 2023-05-23 | [Github](https://github.com/llm-mcts/llm-mcts) | |
| [**LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models**](https://arxiv.org/abs/2212.04088) | ICCV 2023 | 2022-12-08 | [Github](https://github.com/OSU-NLP-Group/LLM-Planner/) | |
| [**ReAct: Synergizing Reasoning and Acting in Language Models**](https://arxiv.org/abs/2210.03629) | ICLR 2023 | 2022-10-06 | [Github](https://github.com/ysymyth/ReAct) | | 
| [**Reasoning with Language Model is Planning with World Model**](https://arxiv.org/abs/2210.03629) | EMNLP 2023 | 2023-05-24 | [Github](https://github.com/maitrix-org/llm-reasoners) | | 
| [**Dynamic Planning with a LLM**](https://arxiv.org/abs/2308.06391) | arXiv | 2023-08-11 | [Github](https://github.com/itl-ed/llm-dp) | | 
| [**SMART-LLM: Smart Multi-Agent Robot Task Planning using Large Language Models**](https://arxiv.org/abs/2309.10062) | arXiv | 2023-09-18 | [Github](https://github.com/SMARTlab-Purdue/SMART-LLM) | | 
-->

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.17-Generalization ******* -->
### Generalization 
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Generalization with Benchmarks_ |
| [**A Taxonomy for Evaluating Generalist Robot Policies**](https://arxiv.org/abs/2503.01238) | arXiv | 2024-03-03 | [Project](https://stargen-taxonomy.github.io/) |  |
| _Generalization using Data_ |
| [**Mirage: Cross-Embodiment Zero-Shot Policy Transfer with Cross-Painting**](https://arxiv.org/abs/2402.19249) | RSS 2024 | 2024-02-29 | ![Star](https://img.shields.io/github/stars/BerkeleyAutomation/mirage?style=social&label=Star) [Github](https://github.com/BerkeleyAutomation/mirage) |  |
| [**Decomposing the Generalization Gap in Imitation Learning for Visual Robotic Manipulation**](https://arxiv.org/abs/2307.03659) | ICRA 2024 | 2024-02-29 | ![Star](https://img.shields.io/github/stars/RLAgent/factor-world?style=social&label=Star) [Github](https://github.com/RLAgent/factor-world) |  
| _Compositional Generalization_ |
| [**Policy Architectures for Compositional Generalization in Control**](https://arxiv.org/abs/2203.05960) | NeurIPSW 2022 | 2022-03-10 | ![Star](https://img.shields.io/github/stars/facebookresearch/entity-factored-rl?style=social&label=Star) [Github](https://github.com/facebookresearch/entity-factored-rl) | Compositional Generalization |
| [PROGRAMPORT: **Programmatically Grounded, Compositionally Generalizable Robotic Manipulation**](https://arxiv.org/abs/2304.13826) | ICLR 2023 | 2023-04-26 | [Project](https://progport.github.io/) | Compositional Generalization |
| [**Efficient Data Collection for Robotic Manipulation via Compositional Generalization**](https://arxiv.org/abs/2403.05110) | RSS 2024 | 2024-03-08 | [Project](https://iliad.stanford.edu/robot-data-comp/) | Compositional Generalization |
| _Sim2Real or real2real Generalization_ |
| [**Real2Render2Real: Scaling Robot Data Without Dynamics Simulation or Robot Hardware**](https://arxiv.org/abs/2505.09601) | arXiv | 2025-05-14 | [Project](https://real2render2real.com/) |  |
| [**X-Sim: Cross-Embodiment Learning via Real-to-Sim-to-Real**](http://arxiv.org/abs/2505.07096) | arXiv | 2025-05-11 | ![Star](https://img.shields.io/github/stars/portal-cornell/X-Sim?style=social&label=Star) [Github](https://github.com/portal-cornell/X-Sim) |  |
| [**Sim-and-Real Co-Training: A Simple Recipe for Vision-Based Robotic Manipulation**](https://arxiv.org/abs/2405.10020) | arXiv | 2025-03-31 | [Project](https://co-training.github.io/) |  |
| [**Natural Language Can Help Bridge the Sim2Real Gap**](https://arxiv.org/abs/2405.10020) | RSS 2024 | 2024-05-16 | ![Star](https://img.shields.io/github/stars/UT-Austin-RobIn/lang4sim2real?style=social&label=Star) [Github](https://github.com/UT-Austin-RobIn/lang4sim2real) |  |
| [RialTo: **Reconciling Reality through Simulation: A Real-to-Sim-to-Real Approach for Robust Manipulation**](https://arxiv.org/abs/2403.03949) | RSS 2024 | 2024-03-06 | ![Star](https://img.shields.io/github/stars/real-to-sim-to-real/RialToPolicyLearning?style=social&label=Star) [Github](https://github.com/real-to-sim-to-real/RialToPolicyLearning) |  |
| [Domain Randomization: **Sim-to-Real Transfer of Robotic Control with Dynamics Randomization**](https://arxiv.org/abs/1710.06537) | ICRA 2018 | 2017-10-18 |  |  |
| _Disentangled Representation Learning_ |
| [**Zero-Shot Visual Generalization in Robot Manipulation**](https://arxiv.org/abs/2505.11719) | arXiv | 2022-05-16 | [Project](https://sites.google.com/view/vis-gen-robotics/home) |  |
| [**Merging and Disentangling Views in Visual Reinforcement Learning for Robotic Manipulation**](https://arxiv.org/abs/2505.04619) | arXiv | 2025-05-07 | ![Star](https://img.shields.io/github/stars/aalmuzairee/mad?style=social&label=Star) [Github](https://github.com/aalmuzairee/mad) |  |
| [**Disentangled Object-Centric Image Representation for Robotic Manipulation**](https://arxiv.org/abs/2503.11565) | arXiv | 2025-03-14 | - |  |
| _Generalization for Long-horizon and Complex Task_ |
| [**Bootstrapping Imitation Learning for Long-horizon Manipulation via Hierarchical Data Collection Space**](https://arxiv.org/abs/2505.17389) | arXiv | 2025-05-23 | [Project](https://hd-space-robotics.github.io/) | |
| [**RoboHorizon: An LLM-Assisted Multi-View World Model for Long-Horizon Robotic Manipulation**](https://arxiv.org/abs/2501.06605) | arXiv | 2025-01-11 | - | |
| [ManipGen: **Local Policies Enable Zero-shot Long-horizon Manipulation**](https://arxiv.org/abs/2410.22332) | CoRLW 2024 | 2024-10-29 | [Project](https://mihdalal.github.io/manipgen/) | |
| [TBBF: **A Backbone for Long-Horizon Robot Task Understanding**](https://arxiv.org/abs/2408.01334) | RA-L 2025 | 2024-08-02 | [Project](https://sites.google.com/view/therbligsbasedbackbone/home) | |
| [**STAP: Sequencing Task-Agnostic Policies**](https://arxiv.org/abs/2210.12250) | ICRA 2023 | 2022-10-21 | ![Star](https://img.shields.io/github/stars/agiachris/STAP?style=social&label=Star) [Github](https://github.com/agiachris/STAP) |  |
| [BOSS: **Bootstrap Your Own Skills: Learning to Solve New Tasks with Large Language Model Guidance**](https://arxiv.org/abs/2310.10021) | CoRL 2023 | 2023-12-16 | ![Star](https://img.shields.io/github/stars/clvrai/boss?style=social&label=Star) [Github](https://github.com/clvrai/boss) | Skill Bootstrapping |
| [BLADE: **Learning Compositional Behaviors from Demonstration and Language**](https://openreview.net/pdf?id=fR1rCXjCQX) | CoRL 2024 | 2024 | [Project](https://blade-bot.github.io/) | IL, RepL, Poliy Head, Few-Shot Policy Adaptation |
| [PALO: **Policy Adaptation via Language Optimization: Decomposing Tasks for Few-Shot Imitation**](https://arxiv.org/abs/2408.16228) | CoRL 2024 | 2024-08-29 | ![Star](https://img.shields.io/github/stars/vivekmyers/palo?style=social&label=Star) [Github](https://github.com/vivekmyers/palo) | Fine-grained Atom Action |
| _Lifelong Learning_ |
| [**Dynamic Mixture of Progressive Parameter-Efficient Expert Library for Lifelong Robot Learning**](https://arxiv.org/abs/2506.05985) | arXiv | 2025-06-06 | - |  |
| [**Think Small, Act Big: Primitive Prompt Learning for Lifelong Robot Manipulation**](https://arxiv.org/abs/2504.00420) | CVPR 2025 | 2025-04-01 | - |  |
| _Few-shot_ |
| [**Few-Shot Vision-Language Action-Incremental Policy Learning**](https://arxiv.org/abs/2504.15517) | arXiv | 2025-04-22 | ![Star](https://img.shields.io/github/stars/codeshop715/FSAIL?style=social&label=Star) [Github](https://github.com/codeshop715/FSAIL) |  |
| [**You Only Teach Once: Learn One-Shot Bimanual Robotic Manipulation from Video Demonstrations**](https://arxiv.org/abs/2501.14208) | arXiv | 2025-01-24 | ![Star](https://img.shields.io/github/stars/hnuzhy/YOTO?style=social&label=Star) [Github](https://github.com/hnuzhy/YOTO) |  |
| [**Learning Generalizable 3D Manipulation With 10 Demonstrations**](https://arxiv.org/abs/2411.10203) | arXiv | 2024-11-15 | ![Star](https://img.shields.io/github/stars/renyu2016/Generalized-3D-Manipulation?style=social&label=Star) [Github](https://github.com/renyu2016/Generalized-3D-Manipulation) |  |
| _Incremental Learning_ |
| [**iManip: Skill-Incremental Learning for Robotic Manipulation**](https://arxiv.org/abs/2503.07087) | arXiv | 2025-03-10 | - |  |
|  _Test-Time Adaptation_ |
| [**Adapting by Analogy: OOD Generalization of Visuomotor Policies via Functional Correspondence**](https://arxiv.org/abs/2506.12678) | arXiv | 2025-06-15 | - |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.18-Generalization ******* -->
### Generalist
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Generalist with Different Embodiment Types_ |
| [**RoboOS: A Hierarchical Embodied Framework for Cross-Embodiment and Multi-Agent Collaboration**](https://arxiv.org/abs/2505.03673) | arXiv | 2025-05-06 | ![Star](https://img.shields.io/github/stars/FlagOpen/RoboOS?style=social&label=Star) [Github](https://github.com/FlagOpen/RoboOS) | Cross-Embodied |
| [CrossFormer: **Scaling Cross-Embodied Learning: One Policy for Manipulation, Navigation, Locomotion and Aviation**](https://arxiv.org/abs/2408.11812) | CoRL 2024 | 2024-08-21 | ![Star](https://img.shields.io/github/stars/rail-berkeley/crossformer?style=social&label=Star) [Github](https://github.com/rail-berkeley/crossformer) | Cross-Embodied |
| [ARIO: **All Robots in One: A New Standard and Unified Dataset for Versatile, General-Purpose Embodied Agents**](https://arxiv.org/abs/2408.10899) | arXiv | 2024-08-20 | [Project](https://imaei.github.io/project_pages/ario/) | Cross-Embodied |
| [HPT: **Scaling Proprioceptive-Visual Learning with Heterogeneous Pre-trained Transformers**](https://arxiv.org/abs/2409.20537) | NeurIPS 2024 | 2024-09-30 | ![Star](https://img.shields.io/github/stars/liruiw/HPT?style=social&label=Star) [Github](https://github.com/liruiw/HPT) |  |
| _Generalist in Different Embodied Tasks_|
| [LEO: **An Embodied Generalist Agent in 3D World**](https://arxiv.org/abs/2311.12871) | ICML 2024 | 2023-11-18 | ![Star](https://img.shields.io/github/stars/embodied-generalist/embodied-generalist?style=social&label=Star) [Github](https://github.com/embodied-generalist/embodied-generalist) |  |
| _Manipulation Generalist_|
| [**Beyond Sight: Finetuning Generalist Robot Policies with Heterogeneous Sensors via Language Grounding**](https://arxiv.org/abs/2501.04693) | arXiv | 2025-01-08 | ![Star](https://img.shields.io/github/stars/fuse-model/FuSe?style=social&label=Star) [Github](https://github.com/fuse-model/FuSe) |
| [**RLDG: Robotic Generalist Policy Distillation via Reinforcement Learning**](https://arxiv.org/abs/2412.09858) | arXiv | 2024-12-13 | [Project](https://generalist-distillation.github.io/) |  |
| [**RoboMM: All-in-One Multimodal Large Model for Robotic Manipulation**](https://arxiv.org/abs/2412.07215) | arXiv | 2024-12-10 | ![Star](https://img.shields.io/github/stars/RoboUniview/RoboMM?style=social&label=Star) [Github](https://github.com/RoboUniview/RoboMM) |  |
| [**Effective Tuning Strategies for Generalist Robot Manipulation Policies**](https://arxiv.org/abs/2410.01220) | arXiv | 2024-10-02 | - | |
| [**Octo: An Open-Source Generalist Robot Policy**](https://arxiv.org/abs/2405.12213) | RSS 2024 | 2024-05-20 | ![Star](https://img.shields.io/github/stars/octo-models/octo?style=social&label=Star) [Github](https://github.com/octo-models/octo) | |
| [V-GPS: **Steering Your Generalists: Improving Robotic Foundation Models via Value Guidance**](https://arxiv.org/abs/2410.13816) | CoRL 2024 | 2024-10-17 | [Project](https://nakamotoo.github.io/V-GPS/index.html) |  |
| [**Open X-Embodiment: Robotic Learning Datasets and RT-X Models**](https://arxiv.org/abs/2310.08864) | ICRA 2024 | 2023-10-13 | ![Star](https://img.shields.io/github/stars/google-deepmind/open_x_embodiment?style=social&label=Star)  [Github](https://github.com/google-deepmind/open_x_embodiment) | |
| [**RoboAgent: Generalization and Efficiency in Robot Manipulation via Semantic Augmentations and Action Chunking**](https://arxiv.org/abs/2309.01918) | ICRA 2024 | 2023-09-05 | ![Star](https://img.shields.io/github/stars/robopen/roboagent?style=social&label=Star) [Github](https://github.com/robopen/roboagent) | |
| [Maniwhere: **Learning to Manipulate Anywhere: A Visual Generalizable Framework For Reinforcement Learning**](https://arxiv.org/abs/2407.15815) | CoRL 2024 | 2024-07-22 | [Project](https://gemcollector.github.io/maniwhere/) |  |
| [**CAGE: Causal Attention Enables Data-Efficient Generalizable Robotic Manipulation**](https://arxiv.org/abs/2407.15815) | arXiv | 2024-10-19 | [Project](https://cage-policy.github.io/) |  |
| [**Robot Utility Models: General Policies for Zero-Shot Deployment in New Environments**](https://arxiv.org/abs/2409.05865) | arXiv | 2024-09-09 | [Github](https://github.com/haritheja-e/robot-utility-models/) |  |
| More for [VLAs](#vision-language-action-models) |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.19-Human-Robot Interaction and Collaboration ******* -->
### Human-Robot Interaction and Collaboration
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Maximizing Alignment with Minimal Feedback: Efficiently Learning Rewards for Visuomotor Robot Policy Alignment**](https://arxiv.org/abs/2412.04835) | arXiv | 2024-12-06 | [Project](https://sites.google.com/berkeley.edu/rapl) |  |
| [**Vocal Sandbox: Continual Learning and Adaptation for Situated Human-Robot Collaboration**](https://openreview.net/pdf?id=ypaYtV1CoG) | CoRL 2024 | 2024-09-06 | [Project](https://vocal-sandbox.github.io/) |  |
| [**APRICOT: Active Preference Learning and Constraint-Aware Task Planning with LLMs**](https://openreview.net/pdf?id=nQslM6f7dW) | CoRL 2024 | - | [Project](https://portal-cornell.github.io/apricot/) |  |
| [**Text2Interaction: Establishing Safe and Preferable Human-Robot Interaction**](https://arxiv.org/abs/2408.06105) | CoRL 2024 | 2024-08-12 | ![Star](https://img.shields.io/github/stars/JakobThumm/text2interaction?style=social&label=Star) [Github](https://github.com/JakobThumm/text2interaction) |  |
| [**GenH2R: Learning Generalizable Human-to-Robot Handover via Scalable Simulation, Demonstration, and Imitation**](https://arxiv.org/abs/2401.00929) | CVPR 2024 | 2024-01-01  | ![Star](https://img.shields.io/github/stars/chenjy2003/genh2r?style=social&label=Star) [Github](https://github.com/chenjy2003/genh2r)  |
| [KNOWNO: **Robots That Ask For Help: Uncertainty Alignment for Large Language Model Planners**](https://arxiv.org/abs/2307.01928) | CoRL 2023 | 2023-07-04 | [Github](https://github.com/google-research/google-research/tree/master/language_model_uncertainty) | |
| [LILAC: **Yell At Your Robot: Improving On-the-Fly from Language Corrections**](https://arxiv.org/abs/2403.12910) | arXiv | 2024-03-19 | ![Star](https://img.shields.io/github/stars/yay-robot/yay_robot?style=social&label=Star) [Github](https://github.com/yay-robot/yay_robot) | |
| [YAY Robot: **"No, to the Right" -- Online Language Corrections for Robotic Manipulation via Shared Autonomy**](https://arxiv.org/abs/2301.02555) | HRI 2023 | 2023-01-06 | ![Star](https://img.shields.io/github/stars/Stanford-ILIAD/lilac?style=social&label=Star) [Github](https://github.com/Stanford-ILIAD/lilac) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.20-Humanoid Manipulation ******* -->
### Humanoid Manipulation
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Hierarchical Vision-Language Planning for Multi-Step Humanoid Manipulation**](https://arxiv.org/abs/2506.22827) | RSSW 2025 | 2025-06-28 | [Project](https://vlp-humanoid.github.io/) | |
| [**TACT: Humanoid Whole-body Contact Manipulation through Deep Imitation Learning with Tactile Modality**](https://arxiv.org/abs/2506.15146) | RA-L 2025 | 2025-06-18 | -| |
| [**Humanoid Policy ~ Human Policy**](https://arxiv.org/abs/2503.13441) | arXiv | 2025-03-17 | ![Star](https://img.shields.io/github/stars/RogerQi/human-policy?style=social&label=Star) [Github](https://github.com/RogerQi/human-policy) | |
| [**Humanoid-VLA: Towards Universal Humanoid Control with Visual Integration**](https://arxiv.org/abs/2502.14795) | arXiv | 2025-02-20 | -| |
| [**OKAMI: Teaching Humanoid Robots Manipulation Skills through Single Video Imitation**](https://arxiv.org/abs/2410.11792) | CoRL 2024 | 2024-10-15 | [Project](https://ut-austin-rpl.github.io/OKAMI/)  |
| [**Generalizable Humanoid Manipulation with 3D Diffusion Policies**](https://arxiv.org/abs/2410.10803) | arXiv | 2024-10-14  | ![Star](https://img.shields.io/github/stars/YanjieZe/Improved-3D-Diffusion-Policy?style=social&label=Star) [Github](https://github.com/YanjieZe/Improved-3D-Diffusion-Policy)  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

### Quadrupedal Manipulation
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Human2LocoMan: Learning Versatile Quadrupedal Manipulation with Human Pretraining**](https://arxiv.org/abs/2506.16475) | RSS 2025 | 2025-06-19  | ![Star](https://img.shields.io/github/stars/chrisyrniu/Human2LocoMan?style=social&label=Star) [Github](https://github.com/chrisyrniu/Human2LocoMan)  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.21-Mobile Manipulation ******* -->
### Mobile Manipulation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Object-Centric Mobile Manipulation through SAM2-Guided Perception and Imitation Learning**](https://arxiv.org/abs/2507.10899) | arXiv | 2025-07-15 | - |
| [**HoMeR: Learning In-the-Wild Mobile Manipulation via Hybrid Imitation and Whole-Body Control**](https://arxiv.org/abs/2506.01185) | arXiv | 2025-06-01 | ![Star](https://img.shields.io/github/stars/priyasundaresan/homer?style=social&label=Star) [Github](https://github.com/priyasundaresan/homer) |
| [**Robi Butler: Remote Multimodal Interactions with Household Robot Assistant**](https://arxiv.org/abs/2409.20548) | arXiv | 2024-09-30 | [Project](https://robibutler.github.io/) |
| [**TaMMa: Target-driven Multi-subscene Mobile Manipulation**](https://openreview.net/pdf?id=EiqQEsOMZt) | CoRL 2024 | 2024-09-06 | - |
| [**SayPlan: Grounding Large Language Models using 3D Scene Graphs for Scalable Robot Task Planning**](https://arxiv.org/abs/2307.06135) | CoRL 2023 | 2024-07-12 | [Project](https://sayplan.github.io/) |
| [**Mobile ALOHA: Learning Bimanual Mobile Manipulation with Low-Cost Whole-Body Teleoperation**](https://arxiv.org/abs/2401.02117) | CoRL 2024 | 2024-01-04 | ![Star](https://img.shields.io/github/stars/MarkFzp/mobile-aloha?style=social&label=Star) [Github](https://github.com/MarkFzp/mobile-aloha) |
| [**GAMMA: Graspability-Aware Mobile MAnipulation Policy Learning based on Online Grasping Pose Fusion**](https://arxiv.org/abs/2309.15459) | ICRA 2024 | 2023-09-27 | ![Star](https://img.shields.io/github/stars/user432/gamma?style=social&label=Star) [Github](https://github.com/user432/gamma) |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.22-Tactile ******* -->
### Tactile-based Manipulation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Robotic Perception with a Large Tactile-Vision-Language Model for Physical Property Inference**](https://arxiv.org/abs/2506.19303) | arXiv | 2025-06-24 | - |
| [**ViTacFormer: Learning Cross-Modal Representation for Visuo-Tactile Dexterous Manipulation**](https://arxiv.org/abs/2506.15953) | arXiv | 2025-06-19 | - |
| [**Tactile Beyond Pixels: Multisensory Touch Representations for Robot Manipulation**](https://arxiv.org/abs/2506.14754) | arXiv | 20256-06-17 | - |
| [**Touch Begins Where Vision Ends: Generalizable Policies for Contact-rich Manipulation**](https://arxiv.org/abs/2506.13762) | arXiv | 2025-06-16 | ![Star](https://img.shields.io/github/stars/anonvital/anonvital?style=social&label=Star) [Github](https://github.com/anonvital/anonvital) |
| [**FreeTacMan: Robot-free Visuo-Tactile Data Collection System for Contact-rich Manipulation**](https://arxiv.org/abs/2506.01941) | arXiv | 2025-06-02 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/FreeTacMan?style=social&label=Star) [Github](https://github.com/OpenDriveLab/FreeTacMan) |
| [**Feel the Force: Contact-Driven Learning from Humans**](https://arxiv.org/abs/2506.01944) | arXiv | 2025-06-02 | [Project](https://feel-the-force-ftf.github.io/) |
| [**ControlTac: Force- and Position-Controlled Tactile Data Augmentation with a Single Reference Image**](https://arxiv.org/abs/2505.20498) | arXiv | 2025-05-26 | [Project](https://dongyuluo.github.io/controltac/) |
| [**CLTP: Contrastive Language-Tactile Pre-training for 3D Contact Geometry Understanding**](https://arxiv.org/abs/2505.08194) | arXiv | 2025-05-13 | [Project](https://sites.google.com/view/cltp/) |
| [**GelFusion: Enhancing Robotic Manipulation under Visual Constraints via Visuotactile Fusion**](https://arxiv.org/abs/2505.07455) | arXiv | 2025-05-12 | [Project](https://gelfusion.github.io/) |
| [**On the Importance of Tactile Sensing for Imitation Learning: A Case Study on Robotic Match Lighting**](https://arxiv.org/abs/2504.13618) | arXiv | 2025-04-18 | [Project](https://sites.google.com/view/tactile-il) |
| [**Look-to-Touch: A Vision-Enhanced Proximity and Tactile Sensor for Distance and Geometry Perception in Robotic Manipulation**](https://arxiv.org/abs/2504.10280) | arXiv | 2025-04-14 | - |
| [**TLA: Tactile-Language-Action Model for Contact-Rich Manipulation**](https://arxiv.org/abs/2503.08548) | arXiv | 2025-03-11 | [Project](https://sites.google.com/view/tactile-language-action/) |
| [**Digitizing Touch with an Artificial Multimodal Fingertip**](https://scontent-phx1-1.xx.fbcdn.net/v/t39.2365-6/465055681_924267079585273_8047410736294936611_n.pdf?_nc_cat=101&ccb=1-7&_nc_sid=3c67a6&_nc_ohc=eYsIus3g6awQ7kNvgHFzDT0&_nc_zt=14&_nc_ht=scontent-phx1-1.xx&_nc_gid=AMTquwsvbz_wl7RVbIQ8jop&oh=00_AYDMjkNHpucdF6CABQmVEn3awqGbVKQRc0VdZ78K9yxWiQ&oe=6729FC10) | arXiv | 2024-11-04 | ![Star](https://img.shields.io/github/stars/facebookresearch/digit360?style=social&label=Star) [Github](https://github.com/facebookresearch/digit360)  |
| [**Sparsh: Self-supervised touch representations for vision-based tactile sensing**](https://scontent-phx1-1.xx.fbcdn.net/v/t39.2365-6/464969941_1107633400780143_7479102347328147009_n.pdf?_nc_cat=103&ccb=1-7&_nc_sid=3c67a6&_nc_ohc=rIIjx3oS8NoQ7kNvgHoYE_8&_nc_zt=14&_nc_ht=scontent-phx1-1.xx&_nc_gid=Afu6x6FhbEXrGbbgReB-uHE&oh=00_AYBE3smKcto0X7YBse7xJmR7MDXYQdWIdRbYjvpl2wGayQ&oe=6729FA64) | CoRL 2024 | 2024 | ![Star](https://img.shields.io/github/stars/facebookresearch/sparsh?style=social&label=Star) [Github](https://github.com/facebookresearch/sparsh)  |
| [**MimicTouch: Leveraging Multi-modal Human Tactile Demonstrations for Contact-rich Manipulation**](https://arxiv.org/abs/2310.16917) | CoRL 2024 | 2023-10-25 | [Project](https://sites.google.com/view/MimicTouch)  |
| [**Octopi: Object Property Reasoning with Large Tactile-Language Models**](https://arxiv.org/abs/2405.02794) | RSS 2024 | 2024-05-05 | ![Star](https://img.shields.io/github/stars/clear-nus/octopi?style=social&label=Star) [Github](https://github.com/clear-nus/octopi)  |
| [**RoboPack: Learning Tactile-Informed Dynamics Models for Dense Packing**](https://arxiv.org/abs/2407.01418) | RSS 2024 | 2024-07-01 | [Project](https://robo-pack.github.io/)  |
| [RotateIt: **General In-Hand Object Rotation with Vision and Touch**](https://arxiv.org/abs/2309.09979) | CoRL 2023 | 2023-09-18 | [Project](https://haozhi.io/rotateit/)  |
| [T-DEX: **Dexterity from Touch: Self-Supervised Pre-Training of Tactile Representations with Robotic Play**](https://arxiv.org/abs/2303.12076) | CoRL 2023 | 2023-03-21 | ![Star](https://img.shields.io/github/stars/irmakguzey/tactile-dexterity?style=social&label=Star) [Github](https://github.com/irmakguzey/tactile-dexterity)  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.23-Dexterous Manipulation ******* -->
### Dexterous Manipulation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**A Careful Examination of Large Behavior Models for Multitask Dexterous Manipulation**](https://arxiv.org/abs/2507.05331) | arXiv | 2025-07-07 | [Project](https://toyotaresearchinstitute.github.io/lbm1/) |
| [**Object-Focus Actor for Data-efficient Robot Generalization Dexterous Manipulation**](https://arxiv.org/abs/2505.15098) | arXiv | 2025-05-21 | [Project](https://yihanghku.github.io/OFA/) |
| [**DORA: Object Affordance-Guided Reinforcement Learning for Dexterous Robotic Manipulation**](https://arxiv.org/abs/2505.14819) | arXiv | 2025-05-20 | [Project](https://sites.google.com/view/dora-manip) |
| [**MAPLE: Encoding Dexterous Robotic Manipulation Priors Learned From Egocentric Videos**](https://arxiv.org/abs/2504.06084) | arXiv | 2025-04-08 | ![Star](https://img.shields.io/github/stars/algvr/maple?style=social&label=Star) [Code](https://github.com/algvr/maple/) |
| [**CordViP: Correspondence-based Visuomotor Policy for Dexterous Manipulation in Real-World**](https://arxiv.org/abs/2502.08449) | arXiv | 2025-02-12 | [Project](https://aureleopku.github.io/CordViP/) |
| [**Bunny-VisionPro: Real-Time Bimanual Dexterous Teleoperation for Imitation Learning**](https://arxiv.org/abs/2407.03162) | arXiv | 2024-07-03 | ![Star](https://img.shields.io/github/stars/Dingry/BunnyVisionPro?style=social&label=Star) [Github](https://github.com/Dingry/BunnyVisionPro) |
| [**CyberDemo: Augmenting Simulated Human Demonstration for Real-World Dexterous Manipulation**](https://arxiv.org/abs/2402.14795) | CVPR 2024 | 2024-02-22 | ![Star](https://img.shields.io/github/stars/wang59695487/hand_teleop_real_sim_mix_adr?style=social&label=Star) [Github](https://github.com/wang59695487/hand_teleop_real_sim_mix_adr) | |
| [**Dexterous Functional Grasping**](https://arxiv.org/abs/2312.02975) | CoRL 2023 | 2023-12-05 | [Project](https://dexfunc.github.io/)  | |
| [**DEFT: Dexterous Fine-Tuning for Real-World Hand Policies**](https://arxiv.org/abs/2310.19797) | CoRL 2023 | 2023-10-30 | [Project](https://dexterous-finetuning.github.io/)  | |
| [**REBOOT: Reuse Data for Bootstrapping Efficient Real-World Dexterous Manipulation**](https://arxiv.org/abs/2309.03322) | CoRL 2023 | 2023-09-06 | [Project](https://sites.google.com/view/reboot-dexterous)  | |
| [**Sequential Dexterity: Chaining Dexterous Policies for Long-Horizon Manipulation**](https://arxiv.org/abs/2309.00987) | CoRL 2023 | 2023-09-02 | ![Star](https://img.shields.io/github/stars/sequential-dexterity/SeqDex?style=social&label=Star) [Github](https://github.com/sequential-dexterity/SeqDex) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.24-Other Applications ******* -->
### Other Applications
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Deformable Object Manipulation_ |
| [**Learning Efficient Robotic Garment Manipulation with Standardization**](https://arxiv.org/abs/2506.22769) | arXiv | 2025-06-12  | [Project](https://hellohaia.github.io/APS/) |
| _Precise Manipulation_ |
| [**RICE: Reactive Interaction Controller for Cluttered Canopy Environment**](https://arxiv.org/abs/2506.10383) | RA-L 2025 | 2025-06-12  | - |
| [**Find the Fruit: Designing a Zero-Shot Sim2Real Deep RL Planner for Occlusion Aware Plant Manipulation**](https://arxiv.org/abs/2505.16547) | arXiv | 2025-05-22  | - |
| [**FoAR: Force-Aware Reactive Policy for Contact-Rich Robotic Manipulation**](https://arxiv.org/abs/2411.15753) | arXiv | 2024-11-24 | [Project](https://tonyfang.net/FoAR/)  |
| [**ForceMimic: Force-Centric Imitation Learning with Force-Motion Capture System for Contact-Rich Manipulation**](https://arxiv.org/abs/2410.07554) | arXiv | 2024-10-10 | [Project](https://forcemimic.github.io/)  |
| [**Predicting Object Interactions with Behavior Primitives: An Application in Stowing Tasks**](https://arxiv.org/abs/2309.16873) | CoRL 2023 | 2023-09-28 | ![Star](https://img.shields.io/github/stars/haonan16/Stow?style=social&label=Star) [Github](https://github.com/haonan16/Stow)  |
| [VAPORS: **Learning Sequential Acquisition Policies for Robot-Assisted Feeding**](https://arxiv.org/abs/2309.05197) | CoRL 2023 | 2023-09-11  | [Project](https://sites.google.com/view/vaporsbot) |
| [**HANDLOOM: Learned Tracing of One-Dimensional Objects for Inspection and Manipulation**](https://arxiv.org/abs/2303.08975) | CoRL 2023 | 2023-03-15 | [Project](https://github.com/vainaviv/handloom)  |
| [**RoboCook: Long-Horizon Elasto-Plastic Object Manipulation with Diverse Tools**](https://arxiv.org/abs/2306.14447) | CoRL 2023 | 2023-06-26  | ![Star](https://img.shields.io/github/stars/hshi74/robocook?style=social&label=Star) [Github](https://github.com/hshi74/robocook) |
| _Object Rearrangement_ |
| [**PACA: Perspective-Aware Cross-Attention Representation for Zero-Shot Scene Rearrangement**](https://arxiv.org/abs/2410.22059) | WACV 2025 | 2024-10-29  | - |
| [**LGMCTS: Language-Guided Monte-Carlo Tree Search for Executable Semantic Object Rearrangement**](https://arxiv.org/abs/2309.15821) | IROS 2024 | 2023-09-27  | ![Star](https://img.shields.io/github/stars/changhaonan/LGMCTS-D?style=social&label=Star) [Github](https://github.com/changhaonan/LGMCTS-D)  |
| [LLM-GROP: **Task and Motion Planning with Large Language Models for Object Rearrangement**](https://arxiv.org/abs/2303.06247) | IROS 2023 | 2023-03-10 | [Colab](https://colab.research.google.com/drive/1cSqoSc6Gk9KM9p-GwHSIIL5VfZICGW3B?usp=sharing)  |
| [**DALL-E-Bot: Introducing Web-Scale Diffusion Models to Robotics**](https://arxiv.org/abs/2210.02438) | RA-L 2023 | 2022-10-05 | [Project](https://www.robot-learning.uk/)  |
| _Non-prehensile Manipulation_ |
| [**HACMan: Learning Hybrid Actor-Critic Maps for 6D Non-Prehensile Manipulation**](https://arxiv.org/abs/2305.03942) | CoRL 2023 | 2023-05-06  | ![Star](https://img.shields.io/github/stars/HACMan-2023/HACMan?style=social&label=Star) [Github](https://github.com/HACMan-2023/HACMan)  |
| _Tool Manipulation_ |
| [**RobotSmith: Generative Robotic Tool Design for Acquisition of Complex Manipulation Skills**](https://arxiv.org/abs/2506.14763) | arXiv | 2025-06-17 | [Project](https://chunru-lin.github.io/RobotSmith/) | |
| [**Leveraging Language for Accelerated Learning of Tool Manipulation**](https://arxiv.org/abs/2206.13074) | CoRL 2023 | 2022-06-27 | ![Star](https://img.shields.io/github/stars/irom-lab/ATLA?style=social&label=Star) [Github](https://github.com/irom-lab/ATLA) | |
| _Responsible Manipulation_|
| [**Learning Robust Motion Skills via Critical Adversarial Attacks for Humanoid Robots**](https://arxiv.org/abs/2507.08303) | arXiv | 2025-07-11 | - | |
| [**Adversarial Attacks on Robotic Vision Language Action Models**](https://arxiv.org/abs/2506.03350) | arXiv | 2025-06-03 | ![Star](https://img.shields.io/github/stars/eliotjones1/robogcg?style=social&label=Star) [Github](https://github.com/eliotjones1/robogcg) | |
| [**Adversarial Data Collection: Human-Collaborative Perturbations for Efficient and Robust Robotic Imitation Learning**](https://arxiv.org/abs/2503.11646) | arXiv | 2025-03-14 | - | |
| [**How vulnerable is my policy? Adversarial attacks on modern behavior cloning policies**](https://arxiv.org/abs/2502.03698) | arXiv | 2025-02-06 | - | |
| [**Don't Let Your Robot be Harmful: Responsible Robotic Manipulation**](https://arxiv.org/abs/2411.18289) | arXiv | 2024-11-27 | ![Star](https://img.shields.io/github/stars/kodenii/Responsible-Robotic-Manipulation?style=social&label=Star) [Github](https://github.com/kodenii/Responsible-Robotic-Manipulation) | |
| [**TrojanRobot: Backdoor Attacks Against LLM-based Embodied Robots in the Physical World**](https://arxiv.org/abs/2411.11683) | arXiv | 2024-11-18 | [Project](https://trojanrobot.github.io/) | |
| _Medical Science_|
| [**S3D: A Spatial Steerable Surgical Drilling Framework for Robotic Spinal Fixation Procedures**](https://arxiv.org/abs/2507.01779) | IROS 2025 | 2025-07-02 | - | |
| [**SonoGym: High Performance Simulation for Challenging Surgical Tasks with Robotic Ultrasound**](https://arxiv.org/abs/2507.01152) | arXiv | 2025-07-01 | ![Star](https://img.shields.io/github/stars/SonoGym/SonoGym?style=social&label=Star) [Github](https://github.com/SonoGym/SonoGym) | |
| _AI4Science_|
| [**Enhancing Autonomous Manipulator Control with Human-in-loop for Uncertain Assembly Environments**](https://arxiv.org/abs/2507.11006) | CASE 2025 | 2025-07-15 | - | |
| [**CapsDT: Diffusion-Transformer for Capsule Robot Manipulation**](https://arxiv.org/abs/2506.16263) | arXiv | 2025-06-19 | - | |
| [**LabUtopia: High-Fidelity Simulation and Hierarchical Benchmark for Scientific Embodied Agents**](https://arxiv.org/abs/2505.22634) | arXiv | 2025-05-28 | - | |
| [**RoboCulture: A Robotics Platform for Automated Biological Experimentation**](https://arxiv.org/abs/2505.14941) | arXiv | 2025-05-20 | - | |
| _Sports_ |
| [**SpikePingpong: High-Frequency Spike Vision-based Robot Learning for Precise Striking in Table Tennis Game**](https://arxiv.org/abs/2506.06690) | arXiv | 2025-06-07 | - | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


<!-- ******* 2-Benchmarks ******* -->
## 📊 Awesome Simulators, Benchmarks and Dataset

<!-- ******* 2.1-Grasp Datasets ******* -->
### Grasp Datasets
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**MapleGrasp: Mask-guided Feature Pooling for Language-driven Efficient Robotic Grasping**](https://arxiv.org/abs/2506.06535) | arXiv | 2025-06-06 | - | |
| [**GraspClutter6D: A Large-scale Real-world Dataset for Robust Perception and Grasping in Cluttered Scenes**](https://arxiv.org/abs/2504.06866) | arXiv | 2025-04-09 | [Project](https://sites.google.com/view/graspclutter6d) | |
| [**QDGset: A Large Scale Grasping Dataset Generated with Quality-Diversity**](https://arxiv.org/abs/2410.02319) | arXiv | 2024-10-03 | [Project](https://github.com/qdgrasp/qdgrasp.github.io/blob/main/qdg_set.md) | |
| [**Real-to-Sim Grasp: Rethinking the Gap between Simulation and Real World in Grasp Detection**](https://arxiv.org/abs/2410.06521) | CoRL 2024 | 2024-10-09 | [Project](https://isee-laboratory.github.io/R2SGrasp/) | |
| [**DexGraspNet 2.0: Learning Generative Dexterous Grasping in Large-scale Synthetic Cluttered Scenes**](https://openreview.net/attachment?id=5W0iZR9J7h&name=pdf) | CoRL 2024 | 2024 | ![Star](https://img.shields.io/github/stars/PKU-EPIC/DexGraspNet2?style=social&label=Star) [Github](https://github.com/PKU-EPIC/DexGraspNet2)  |
| [Grasp-Anything-6D: **Language-Driven 6-DoF Grasp Detection Using Negative Prompt Guidance**](https://arxiv.org/abs/2407.13842) | ECCV 2024 | 2024-07-18 | ![Star](https://img.shields.io/github/stars/Fsoft-AIC/Language-Driven-6-DoF-Grasp-Detection-Using-Negative-Prompt-Guidance?style=social&label=Star) [Github](https://github.com/Fsoft-AIC/Language-Driven-6-DoF-Grasp-Detection-Using-Negative-Prompt-Guidance) |  |
| [Grasp-Anything++: **Language-driven Grasp Detection**](https://arxiv.org/abs/2406.09489) | CVPR 2024 | 2024-06-13 | ![Star](https://img.shields.io/github/stars/Fsoft-AIC/LGD?style=social&label=Star) [Github](https://github.com/Fsoft-AIC/LGD) |  |
| [**Grasp-Anything: Large-scale Grasp Dataset from Foundation Models**](https://arxiv.org/abs/2309.09818) | ICRA 2024 | 2023-09-18 | ![Star](https://img.shields.io/github/stars/Fsoft-AIC/Grasp-Anything?style=social&label=Star) [Github](https://github.com/Fsoft-AIC/Grasp-Anything) | |
| [**DexGraspNet: A Large-Scale Robotic Dexterous Grasp Dataset for General Objects Based on Simulation**](https://arxiv.org/abs/2210.02697) | ICRA 2023 | 2022-10-06 | ![Star](https://img.shields.io/github/stars/PKU-EPIC/DexGraspNet?style=social&label=Star) [Github](https://github.com/PKU-EPIC/DexGraspNet) | |
| [**GraspNet-1Billion: A Large-Scale Benchmark for General Object Grasping**](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fang_GraspNet-1Billion_A_Large-Scale_Benchmark_for_General_Object_Grasping_CVPR_2020_paper.pdf) | CVPR 2020 | 2020-08-05 | ![Star](https://img.shields.io/github/stars/graspnet/graspnet-baseline?style=social&label=Star) [Github](https://github.com/graspnet/graspnet-baseline) | |
| [**Jacquard: A Large Scale Dataset for Robotic Grasp Detection**](https://arxiv.org/abs/1803.11469) | IROS 2018 | 2018-03-30 | [Project](https://jacquard.liris.cnrs.fr/) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 2.2-Manipulation Simulators and Benchmarks ******* -->
### Manipulation Simulators and Benchmarks
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Manipulation in Home Environment_ |
| [**RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots**](https://arxiv.org/abs/2406.02523) | RSS 2024 | 2024-06-04 | ![Star](https://img.shields.io/github/stars/robocasa/robocasa?style=social&label=Star) [Github](https://github.com/robocasa/robocasa) |  |
| [**ARNOLD: A Benchmark for Language-Grounded Task Learning With Continuous States in Realistic 3D Scenes**](https://arxiv.org/abs/2304.04321) | ICCV 2023 | 2023-04-09 | ![Star](https://img.shields.io/github/stars/arnold-benchmark/arnold?style=social&label=Star) [Github](https://github.com/arnold-benchmark/arnold) | |
| [**HomeRobot: Open-Vocabulary Mobile Manipulation**](https://arxiv.org/abs/2306.11565) | CoRL 2023 | 2023-06-20 | ![Star](https://img.shields.io/github/stars/facebookresearch/home-robot?style=social&label=Star) [Github](https://github.com/facebookresearch/home-robot) | |
| [**ALFRED: A Benchmark for Interpreting Grounded Instructions for Everyday Tasks**](https://arxiv.org/abs/1912.01734) | CVPR 2020 | 2019-12-03 | ![Star](https://img.shields.io/github/stars/askforalfred/alfred?style=social&label=Star) [Github](https://github.com/askforalfred/alfred) | |
| _Manipulation in On-Table Environment_ |
| [**HumanoidGen: Data Generation for Bimanual Dexterous Manipulation via LLM Reasoning**](https://arxiv.org/abs/2507.00833) | arXiv | 2025-07-01 | ![Star](https://img.shields.io/github/stars/TeleHuman/HumanoidGen?style=social&label=Star) [Github](https://github.com/TeleHuman/HumanoidGen) | |
| [**RoboEval: Where Robotic Manipulation Meets Structured and Scalable Evaluation**](https://arxiv.org/abs/2507.00435) | arXiv | 2025-07-01 | ![Star](https://img.shields.io/github/stars/Robo-Eval/RoboEval?style=social&label=Star) [Github](https://github.com/Robo-Eval/RoboEval) | |
| [**RoboTwin 2.0: A Scalable Data Generator and Benchmark with Strong Domain Randomization for Robust Bimanual Robotic Manipulation**](https://arxiv.org/abs/2506.18088) | arXiv | 2025-06-22 | ![Star](https://img.shields.io/github/stars/robotwin-Platform/RoboTwin?style=social&label=Star) [Github](https://github.com/robotwin-Platform/RoboTwin) | |
| [**GENMANIP: LLM-driven Simulation for Generalizable Instruction-Following Manipulation**](https://arxiv.org/abs/2506.10966) | CVPR 2025 | 2025-06-12 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/GenManip?style=social&label=Star) [Github](https://github.com/OpenRobotLab/GenManip) | |
| [INT-ACT: **From Intention to Execution: Probing the Generalization Boundaries of Vision-Language-Action Models**](https://arxiv.org/abs/2506.09930) | arXiv | 2025-06-11 | ![Star](https://img.shields.io/github/stars/ai4ce/INT-ACT?style=social&label=Star) [Github](https://github.com/ai4ce/INT-ACT) | |
| [**MultiNet: An Open-Source Software Toolkit \& Benchmark Suite for the Evaluation and Adaptation of Multimodal Action Models**](https://arxiv.org/abs/2506.09172) | ICMLW 2025 | 2025-06-10 | - | |
| [**RoboCerebra: A Large-scale Benchmark for Long-horizon Robotic Manipulation Evaluation**](https://arxiv.org/abs/2506.06677) | arXiv | 2025-06-07 | [Project](https://robocerebra.github.io/) | |
| [AGNOSTOS: **Exploring the Limits of Vision-Language-Action Manipulations in Cross-task Generalization**](https://arxiv.org/abs/2505.15660) | arXiv | 2025-05-21 | ![Star](https://img.shields.io/github/stars/jiaming-zhou/X-ICM?style=social&label=Star) [Github](https://github.com/jiaming-zhou/X-ICM) | |
| [**RoboTwin: Dual-Arm Robot Benchmark with Generative Digital Twins**](https://arxiv.org/abs/2504.13059) | CVPR 2025 | 2025-04-17 | ![Star](https://img.shields.io/github/stars/TianxingChen/RoboTwin?style=social&label=Star) [Github](https://github.com/TianxingChen/RoboTwin) | |
| [**AutoEval: Autonomous Evaluation of Generalist Robot Manipulation Policies in the Real World**](https://arxiv.org/pdf/2503.24278) | arXiv | 2025-03-31 | ![Star](https://img.shields.io/github/stars/zhouzypaul/auto_eval?style=social&label=Star) [Github](https://github.com/zhouzypaul/auto_eval) | |
| [**MuBlE: MuJoCo and Blender simulation Environment and Benchmark for Task Planning in Robot Manipulation**](https://arxiv.org/abs/2503.02834) | arXiv | 2025-03-03 | ![Star](https://img.shields.io/github/stars/michaal94/MuBlE?style=social&label=Star) [Github](https://github.com/michaal94/MuBlE) | |
| [**FLAME: A Federated Learning Benchmark for Robotic Manipulation**](https://arxiv.org/abs/2503.01729) | arXiv | 2025-03-03 | - | |
| [**VLABench: A Large-Scale Benchmark for Language-Conditioned Robotics Manipulation with Long-Horizon Reasoning Tasks**](https://arxiv.org/abs/2412.18194) | arXiv | 2024-12-24 | ![Star](https://img.shields.io/github/stars/OpenMOSS/VLABench?style=social&label=Star) [Github](https://github.com/OpenMOSS/VLABench) | |
| [Gembench: **Towards Generalizable Vision-Language Robotic Manipulation: A Benchmark and LLM-guided 3D Policy**](https://arxiv.org/abs/2410.01345) | ICRA 2025 | 2024-10-02 | ![Star](https://img.shields.io/github/stars/vlc-robot/robot-3dlotus?style=social&label=Star) [Github](https://github.com/vlc-robot/robot-3dlotus) | |
| [OBSBench: **Point Cloud Matters: Rethinking the Impact of Different Observation Spaces on Robot Learning**](https://arxiv.org/abs/2402.02500) | NeuIPS 2024 | 2024-02-04 | ![Star](https://img.shields.io/github/stars/HaoyiZhu/PointCloudMatters?style=social&label=Star) [Github](https://github.com/HaoyiZhu/PointCloudMatters) |
| [**GenSim2: Scaling Robot Data Generation with Multi-modal and Reasoning LLMs**](https://arxiv.org/abs/2410.03645) | CoRL 2024 | 2024-10-04 | ![Star](https://img.shields.io/github/stars/GenSim2/gensim2?style=social&label=Star) [Github](https://github.com/GenSim2/gensim2) |
| [**LADEV: A Language-Driven Testing and Evaluation Platform for Vision-Language-Action Models in Robotic Manipulation**](https://arxiv.org/abs/2410.05191) | arXiv | 2024-10-07 | - | For VLA |
| [SIMPLER: **Evaluating Real-World Robot Manipulation Policies in Simulation**](https://arxiv.org/abs/2405.05941) | CoRL 2024 | 2024-05-09 | ![Star](https://img.shields.io/github/stars/simpler-env/SimplerEnv?style=social&label=Star) [Github](https://github.com/simpler-env/SimplerEnv) | For VLA |
| [**THE COLOSSEUM: A Benchmark for Evaluating Generalization for Robotic Manipulation**](https://arxiv.org/abs/2402.08191) | RSSW 2024 | 2024-02-13 | ![Star](https://img.shields.io/github/stars/robot-colosseum/robot-colosseum?style=social&label=Star) [Github](https://github.com/robot-colosseum/robot-colosseum) | |
| [**LIBERO: Benchmarking Knowledge Transfer for Lifelong Robot Learning**](https://arxiv.org/abs/2306.03310) | NeurIPS 2023 | 2023-06-05 | ![Star](https://img.shields.io/github/stars/Lifelong-Robot-Learning/LIBERO?style=social&label=Star) [Github](https://github.com/Lifelong-Robot-Learning/LIBERO) | |
| [**VIMA: General Robot Manipulation with Multimodal Prompts**](https://arxiv.org/abs/2210.03094) | ICML 2023 | 2022-10-06 | ![Star](https://img.shields.io/github/stars/vimalabs/VIMA?style=social&label=Star) [Github](https://github.com/vimalabs/VIMA) | |
| [**CALVIN: A Benchmark for Language-Conditioned Policy Learning for Long-Horizon Robot Manipulation Tasks**](https://arxiv.org/abs/2112.03227) | RA-L 2021 | 2021-12-06 | ![Star](https://img.shields.io/github/stars/mees/calvin?style=social&label=Star) [Github](https://github.com/mees/calvin) | |
| [**RLBench: The Robot Learning Benchmark & Learning Environment**](https://arxiv.org/abs/1909.12271) | RA-L 2020 | 2019-09-26 | ![Star](https://img.shields.io/github/stars/stepjam/RLBench?style=social&label=Star) [Github](https://github.com/stepjam/RLBench) | |
| [**KitchenShift: Evaluating Zero-Shot Generalization of Imitation-Based Policy Learning Under Domain Shifts**](https://openreview.net/pdf?id=DdglKo8hBq0) | NeurIPSW 2021 | 2021 | ![Star](https://img.shields.io/github/stars/etaoxing/kitchen-shift?style=social&label=Star) [Github](https://github.com/etaoxing/kitchen-shift) |
| [**Meta-World: A Benchmark and Evaluation for Multi-Task and Meta Reinforcement Learning**](https://arxiv.org/abs/1910.10897) | CoRL 2019 | 2019-10-24 | ![Star](https://img.shields.io/github/stars/Farama-Foundation/Metaworld?style=social&label=Star) [Github](https://github.com/Farama-Foundation/Metaworld) |
| [Franka-Kitchen: **Relay Policy Learning: Solving Long-Horizon Tasks via Imitation and Reinforcement Learning**](https://arxiv.org/abs/1910.11956) | CoRL 2019 | 2019-10-25 | [Project](https://relay-policy-learning.github.io/) |
| [**ClutterGen: A Cluttered Scene Generator for Robot Learning**](https://arxiv.org/abs/2407.05425) | CoRL 2024 | 2024-07-07 | ![Star](https://img.shields.io/github/stars/generalroboticslab/ClutterGen?style=social&label=Star) [Github](https://github.com/generalroboticslab/ClutterGen) |  |
| _Tactile-based Manipulation_ |
| [**ManiFeel: Benchmarking and Understanding Visuotactile Manipulation Policy Learning**](https://arxiv.org/abs/2505.18472) | arXiv | 2025-05-24 | [Project](https://zhengtongxu.github.io/manifeel-website/) | |
| [**TacCompress: A Benchmark for Multi-Point Tactile Data Compression in Dexterous Manipulation**](https://arxiv.org/abs/2505.16289) | arXiv | 2025-05-22 | - | |
| [**Efficient Tactile Simulation with Differentiability for Robotic Manipulation**](https://openreview.net/pdf?id=6BIffCl6gsM) | CoRL 2022 | 2022-09-10 | ![Star](https://img.shields.io/github/stars/eanswer/TactileSimulation?style=social&label=Star) [Github](https://github.com/eanswer/TactileSimulation) | |
| _Functional Manipulation_ |
| [**FMB: a Functional Manipulation Benchmark for Generalizable Robotic Learning**](https://arxiv.org/abs/2401.08553) | IJRR 2024 | 2024-01-16 | ![Star](https://img.shields.io/github/stars/rail-berkeley/fmb?style=social&label=Star) [Github](https://github.com/rail-berkeley/fmb) |
| _Others_ |
| [**Two by Two: Learning Multi-Task Pairwise Objects Assembly for Generalizable Robot Manipulation**](https://arxiv.org/abs/2504.06961) | CVPR 2025 | 2025-04-09 | [Project](https://tea-lab.github.io/TwoByTwo/) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 2.3-Cross-Embodiment Simulators and Benchmarks ******* -->
### Cross-Embodiment Simulators and Benchmarks
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**VIKI-R: Coordinating Embodied Multi-Agent Cooperation via Reinforcement Learning**](https://arxiv.org/abs/2506.09049) | arXiv | 2025-06-10 | ![Star](https://img.shields.io/github/stars/MARS-EAI/VIKI-R?style=social&label=Star) [Github](https://github.com/MARS-EAI/VIKI-R) |
| [**ImagineBench: Evaluating Reinforcement Learning with Large Language Model Rollouts**](https://arxiv.org/abs/2505.10010) | arXiv | 2025-05-15 | ![Star](https://img.shields.io/github/stars/LAMDA-RL/ImagineBench?style=social&label=Star) [Github](https://github.com/LAMDA-RL/ImagineBench) |
| [**AgiBot World Colosseo: A Large-scale Manipulation Platform for Scalable and Intelligent Embodied Systems**](https://arxiv.org/abs/2503.06669) | IROS 2025 | 2025-03-09 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/AgiBot-World?style=social&label=Star) [Github](https://github.com/OpenDriveLab/AgiBot-World) |
| [**RoboVerse: Towards a Unified Platform, Dataset and Benchmark for Scalable and Generalizable Robot Learning**](https://arxiv.org/abs/2504.18904) | RSS 2025 | 2025-04-26 | ![Star](https://img.shields.io/github/stars/RoboVerseOrg/RoboVerse?style=social&label=Star) [Github](https://github.com/RoboVerseOrg/RoboVerse) |
| **GENESIS: A generative world for general-purpose robotics & embodied AI learning** | - | - | ![Star](https://img.shields.io/github/stars/Genesis-Embodied-AI/Genesis?style=social&label=Star) [Github](https://github.com/Genesis-Embodied-AI/Genesis) |
| [**ManiSkill3: GPU Parallelized Robotics Simulation and Rendering for Generalizable Embodied AI**](https://arxiv.org/abs/2410.00425) | arXiv | 2024-10-01 | ![Star](https://img.shields.io/github/stars/haosulab/ManiSkill?style=social&label=Star) [Github](https://github.com/haosulab/ManiSkill) |
| [CortexBench: **Where are we in the search for an Artificial Visual Cortex for Embodied Intelligence?**](https://arxiv.org/abs/2303.18240) | NeurIPS 2023 | 2023-03-31 | ![Star](https://img.shields.io/github/stars/facebookresearch/eai-vc?style=social&label=Star) [Github](https://github.com/facebookresearch/eai-vc) | |
| **Isaac Lab: [Orbit: A Unified Simulation Framework for Interactive Robot Learning Environments](https://arxiv.org/abs/2301.04195)** | RA-L 2023 | 2023-01-10 | ![Star](https://img.shields.io/github/stars/isaac-sim/IsaacLab?style=social&label=Star) [Github](https://github.com/isaac-sim/IsaacLab) |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 2.4-Trajectory Datasets ******* -->
### Trajectory Datasets
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**RoboFAC: A Comprehensive Framework for Robotic Failure Analysis and Correction**](https://arxiv.org/abs/2505.12224) | arXiv | 2024-05-18 | - | |
| [**RoboMIND: Benchmark on Multi-embodiment Intelligence Normative Data for Robot Manipulation**](https://arxiv.org/abs/2412.13877) | arXiv | 2024-12-18 | ![Star](https://img.shields.io/github/stars/x-humanoid-robomind/x-humanoid-robomind.github.io?style=social&label=Star) [Github](https://github.com/x-humanoid-robomind/x-humanoid-robomind.github.io) |
| [ARIO: **All Robots in One: A New Standard and Unified Dataset for Versatile, General-Purpose Embodied Agents**](https://arxiv.org/abs/2408.10899) | arXiv | 2024-08-20 | [Dataset](https://openi.pcl.ac.cn/ARIO/ARIO_Dataset) | |
| [**Open X-Embodiment: Robotic Learning Datasets and RT-X Models**](https://arxiv.org/abs/2310.08864) | ICRA 2024 | 2023-10-13 | ![Star](https://img.shields.io/github/stars/google-deepmind/open_x_embodiment?style=social&label=Star) [Github](https://github.com/google-deepmind/open_x_embodiment) | |
| [**DROID: A Large-Scale In-The-Wild Robot Manipulation Dataset**](https://arxiv.org/abs/2403.12945) | ICRA 2024 | 2024-03-19 | ![Star](https://img.shields.io/github/stars/droid-dataset/droid_policy_learning?style=social&label=Star) [Github](https://github.com/droid-dataset/droid_policy_learning) | |
| [**BridgeData V2: A Dataset for Robot Learning at Scale**](https://arxiv.org/abs/2308.12952) | CoRL 2023 | 2024-08-24 | ![Star](https://img.shields.io/github/stars/rail-berkeley/bridge_data_v2?style=social&label=Star) [Github](https://github.com/rail-berkeley/bridge_data_v2) | |
| [**RH20T: A Comprehensive Robotic Dataset for Learning Diverse Skills in One-Shot**](https://arxiv.org/abs/2307.00595) | RSSW 2023 | 2023-07-02 | [Project](https://rh20t.github.io/) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 2.5-Embodied QA and Affordance Datasets ******* -->
### Embodied QA and Affordance Datasets
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Embodied QA and Affordance Datasets_ |
| [**PAC Bench: Do Foundation Models Understand Prerequisites for Executing Manipulation Policies?**](https://arxiv.org/abs/2506.23725) | arXiv | 2024-06-30 | [Project](https://pacbench.github.io/) | |
| [**Robo2VLM: Visual Question Answering from Large-Scale In-the-Wild Robot Manipulation Datasets**](https://arxiv.org/abs/2505.15517) | arXiv | 2024-05-21 | [Huggingface](https://huggingface.co/datasets/keplerccc/Robo2VLM-1) | |
| [**PointArena: Probing Multimodal Grounding Through Language-Guided Pointing**](https://arxiv.org/abs/2505.09990) | arXiv | 2024-05-15 | ![Star](https://img.shields.io/github/stars/pointarena/pointarena?style=social&label=Star) [Github](https://github.com/pointarena/pointarena) | |
| [**ManipBench: Benchmarking Vision-Language Models for Low-Level Robot Manipulation**](https://arxiv.org/abs/2505.09698) | arXiv | 2024-05-14 | [Project](https://manipbench.github.io/) | |
| [**ManipVQA: Injecting Robotic Affordance and Physically Grounded Information into Multi-Modal Large Language Models**](https://arxiv.org/abs/2403.11289) | IROS 2024 | 2024-03-17 | ![Star](https://img.shields.io/github/stars/SiyuanHuang95/ManipVQA?style=social&label=Star) [Github](https://github.com/SiyuanHuang95/ManipVQA) | |
| [**OpenEQA: Embodied Question Answering in the Era of Foundation Models**](https://open-eqa.github.io/assets/pdfs/paper.pdf) | CVPR 2024 | 2024 | ![Star](https://img.shields.io/github/stars/facebookresearch/open-eqa?style=social&label=Star) [Github](https://github.com/facebookresearch/open-eqa) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>



<!-- ******* 3-Techniques ******* -->
## 🛠️ Awesome Techniques
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| **Awesome-Implicit-NeRF-Robotics: [Neural Fields in Robotics: A Survey](https://arxiv.org/abs/2410.20220)** | - | 2024-10-26 | ![Star](https://img.shields.io/github/stars/zubair-irshad/Awesome-Implicit-NeRF-Robotics?style=social&label=Star) [Github](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics) | |
| **Awesome-Video-Robotic-Papers** | - | 2024 | ![Star](https://img.shields.io/github/stars/H-Freax/Awesome-Video-Robotic-Papers?style=social&label=Star) [Github](https://github.com/H-Freax/Awesome-Video-Robotic-Papers) | |
| **Awesome-Generalist-Robots-via-Foundation-Models: [Neural Fields in Robotics: A Survey](https://arxiv.org/abs/2312.08782)** | - | 2024 | ![Star](https://img.shields.io/github/stars/JeffreyYH/Awesome-Generalist-Robots-via-Foundation-Models?style=social&label=Star) [Github](https://github.com/JeffreyYH/Awesome-Generalist-Robots-via-Foundation-Models) | |
| **Awesome-Robotics-3D** | - | 2024 | ![Star](https://img.shields.io/github/stars/zubair-irshad/Awesome-Robotics-3D?style=social&label=Star) [Github](https://github.com/zubair-irshad/Awesome-Robotics-3D) | |
| **Awesome-Robotics-Foundation-Models: [Foundation Models in Robotics: Applications, Challenges, and the Future](https://arxiv.org/abs/2312.07843)** | - | 2023-12-13 | ![Star](https://img.shields.io/github/stars/robotics-survey/Awesome-Robotics-Foundation-Models?style=social&label=Star) [Github](https://github.com/robotics-survey/Awesome-Robotics-Foundation-Models/tree/main) | |
| **Awesome-LLM-Robotics** | - | 2022 |  ![Star](https://img.shields.io/github/stars/GT-RIPL/Awesome-LLM-Robotics?style=social&label=Star) [Github](https://github.com/GT-RIPL/Awesome-LLM-Robotics) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


 <!-- 
## Large Language Models

## Vision-Language Models

## 3D
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Learning 2D Invariant Affordance Knowledge for 3D Affordance Grounding**](https://arxiv.org/abs/2408.13024) | arXiv | 2024-08-23 | [Github](https://github.com/goxq/MIFAG-code) | |
| [**Mamba3D: Enhancing Local Features for 3D Point Cloud Analysis via State Space Model**](https://arxiv.org/abs/2404.14966) | MM 2024 | 2024-04-23 | [Github](https://github.com/xhanxu/Mamba3D) | |
| [**PointMamba: A Simple State Space Model for Point Cloud Analysis**](https://arxiv.org/abs/2402.10739) | NeuIPS 2024 | 2024-02-16 | [Github](https://github.com/LMD0311/PointMamba) | |
| [**Point Transformer V3: Simpler, Faster, Stronger**](https://arxiv.org/abs/2312.10035) | CVPR 2024 | 2023-12-15 | [Github](https://github.com/Pointcept/PointTransformerV3) | |
| [**Point Transformer V2: Grouped Vector Attention and Partition-based Pooling**](https://arxiv.org/abs/2210.05666) | NeurIPS 2022 | 2022-10-11 | [Github](https://github.com/Pointcept/PointTransformerV2) | |
| [**Point Transformer**](https://arxiv.org/abs/2402.10739) | ICCV 2021 | 2020-12-16 | [Github](https://github.com/POSTECH-CVLab/point-transformer) | |
| [**PointNet++: Deep Hierarchical Feature Learning on Point Sets in a Metric Space**](https://arxiv.org/abs/1706.02413) | NeurIPS 2017  | 2017-06-07 | [Github](https://github.com/charlesq34/pointnet2) | |
| [**PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation**](https://arxiv.org/abs/1612.00593) | CVPR 2017 | 2016-12-02 | [Github](https://github.com/charlesq34/pointnet) | |
| [**LERF: Language Embedded Radiance Fields**](https://arxiv.org/abs/2303.09553) | ICCV 2023 | 2023-03-16 | [Github](https://github.com/kerrj/lerf) | |
| [**3D Gaussian Splatting for Real-Time Radiance Field Rendering**](https://arxiv.org/abs/2308.04079) | TOG 2023 | 2023-08-08 | [Github](https://github.com/graphdeco-inria/gaussian-splatting) | |
| [**LangSplat: 3D Language Gaussian Splatting**](https://arxiv.org/abs/2312.16084) | CVPR 2024 | 2023-12-26 | [Github](https://github.com/minghanqin/LangSplat) | |
--> 


## ✨ Citation

If you find this repository useful, please consider citing this list:
```
@misc{openhelixteam2024roboticsmanipulation,
    title = {Awesome-Robotics-Manipulation},
    author = {CC-BCI Group and OpenHelix Team},
    journal = {GitHub repository},
    url = {https://github.com/BaiShuanghao/Awesome-Robotics-Manipulation},
    year = {2024},
}
```

- [XJTU Cognitive Computing and Brain-Computer Interaction (CC-BCI) Group](https://gr.xjtu.edu.cn/en/web/chenbd/home),  Prof. Badong Chen [[Google Scholar](https://scholar.google.com/citations?user=mq6tPX4AAAAJ&hl=en)].
- [OpenHelix Team](https://github.com/OpenHelix-Team),  Ph.D. Stu. Pengxiang Ding [[Google Scholar](https://scholar.google.com/citations?user=QyBSTzEAAAAJ&hl=en)].

