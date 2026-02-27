# Awesome-Robotics-Manipulation

## ✨ About

This repository curates research papers on robot manipulation, featuring a smaller collection of non-learning control methods and a larger body of learning-based approaches.

This repository will be continuously updated, and we warmly welcome contributions from the community. If you have papers, projects, or resources that are not yet included, please feel free to submit them via a pull request, open an issue for discussion or [email](baishuanghao@stu.xjtu.edu.cn) us to add papers! 

## 📢 News

- **[2025/10]** Our paper [Towards a Unified Understanding of Robot Manipulation: A Comprehensive Survey](https://arxiv.org/abs/2510.10903) is on available! 
- **[2025/08]** Major revision of the classification system with a more refined taxonomy; substantial improvements across all sections.
- **[2025/07]** Expanded coverage of *Dexterous*, *Soft Robotic*, *Mobile*, *Quadrupedal*, and *Humanoid Manipulation*; refined the categorization and content for *Awesome Simulators, Benchmarks, and Datasets*，added non-learning-based control methods.  
- **[2025/06]** Introduced new sections on *Grasp in Cluttered Scenes*, *Quadrupedal and Humanoid Manipulation*, and *Learning from Human Demonstrations*. Also improved the classification of the *Applications* section and added a subsection on *Embodied QA Datasets*.  
- **[2025/02]** Added a new section on *Bimanual Grasp*.  
- **[2024/12]** Introduced coverage of *Dexterous Grasp*.  
- **[2024/10]** Repository is now public!

<details>
Stay tuned for updates to this comprehensive survey!

<summary>Summary of Survey</summary>

<img src="imgs/summary.png" alt="summary" 
     style="image-rendering: auto; max-width: 100%; height: auto;">
   
</details>

<!-- ------- 0 - Content Table ------- -->
<h2 id="table-of-contents">🏠 Table of Contents</h2>

- [📝 Awesome Papers](#-awesome-papers)
  - [📄 Survey](#-survey)
  - [Manipulation Tasks](contents/manipulation_tasks.md)
    - [Grasp](contents/manipulation_tasks.md#grasp)
    - [Basic Manipulation](contents/manipulation_tasks.md#basic-manipulation)
    - [Dexterous Manipulation](contents/manipulation_tasks.md#dexterous-manipulation)
    - [Soft Robotic Manipulation](contents/manipulation_tasks.md#soft-robotic-manipulation)
    - [Deformable Object Manipulation](contents/manipulation_tasks.md#deformable-object-manipulation)
    - [Mobile Manipulation](contents/manipulation_tasks.md#mobile-manipulation)
    - [Quadrupedal Manipulation](contents/manipulation_tasks.md#quadrupedal-manipulation)
    - [Humanoid Manipulation](contents/manipulation_tasks.md#humanoid-manipulation)
  - [High-level Planner](contents/high-level_planner.md)
    - [Task Planning](contents/high-level_planner.md#task-planning)
    - [Code Generation](contents/high-level_planner.md#code-generation)
    - [Multimodal Reasoning](contents/high-level_planner.md#multimodal-reasoning)
    - [Motion Planning](contents/high-level_planner.md#motion-planning)
    - [Affordance Learning](contents/high-level_planner.md#affordance-learning)
    - [3D Representation as Planner](contents/high-level_planner.md#3d-representation-as-planner)
  - [Low-level Learning-based Control Methods](contents/low-level_learning-based_control.md)
    - [Learning Strategy](contents/low-level_learning-based_control.md#learning-strategy)
      - [Imitation Learning (IL)](contents/low-level_learning-based_control.md#imitation-learning-il)
      - [Reinforcement Learning (RL)](contents/low-level_learning-based_control.md#reinforcement-learning-rl)
      - [RL and IL](contents/low-level_learning-based_control.md#rl-and-il)
      - [Learning with Auxiliary Tasks](contents/low-level_learning-based_control.md#learning-with-auxiliary-tasks)
    - [Input Modelling](contents/low-level_learning-based_control.md#input-modelling)
      - [Vision Action Models](contents/low-level_learning-based_control.md#vision-action-models)
      - [Vision Language Action Models](contents/low-level_learning-based_control.md#vision-language-action-models)
      - [Tactile-based Action Models](contents/low-level_learning-based_control.md#tactile-based-action-models)
      - [Other Modalities](contents/low-level_learning-based_control.md#other-modalities)
    - [Latent Learning](contents/low-level_learning-based_control.md#latent-learning)
      - [Pretrained Latent Learning](contents/low-level_learning-based_control.md#pretrained-latent-learning)
      - [Latent Action Learning](contents/low-level_learning-based_control.md#latent-action-learning)
    - [Policy Learning](contents/low-level_learning-based_control.md#latent-decode-policy-design)
      - [Diffusion Policy](contents/low-level_learning-based_control.md#diffusion-policy)
      - [Flow Matching Policy](contents/low-level_learning-based_control.md#flow-macthing-policy)
      - [Other Policies](contents/low-level_learning-based_control.md#other-policies)
  - [Bottlenecks](contents/bottlenecks.md)
    - [Data Collection and Utilization](contents/bottlenecks.md#data-collection-and-utilization)
        - [Data Collection](contents/bottlenecks.md#data-collection)
        - [Data Utilization](contents/bottlenecks.md#data-utilization)
    - [Generalization](contents/bottlenecks.md#generalization)
      - [Task Generalization](contents/bottlenecks.md#task-generalization)
      - [Environment Generalization](contents/bottlenecks.md#environment-generalization)
      - [Cross-Embodiment Generalization](contents/bottlenecks.md#cross-embodiment-generalization)
  - [Applications](contents/applications.md)
- [📊 Awesome Simulators, Benchmarks and Datasets](#-awesome-simulators-benchmarks-and-dataset)
  - [Grasp Datasets](#grasp-datasets)
  - [Single-Embodiment Manipulation Simulators and Benchmarks](#single-embodiment-manipulation-simulators-and-benchmarks)
  - [Cross-Embodiment Simulators and Benchmarks](#cross-embodiment-simulators-and-benchmarks)
  - [Other Simulators and Benchmarks](#other-simulators-and-benchmarks)
  - [Trajectory Datasets](#trajectory-datasets)
  - [Embodied QA and Affordance Datasets](#embodied-qa-and-affordance-datasets)
  - [Human and Robotic Video Datasets](#human-and-robotic-video-datasets)
- [🛠️ Awesome Techniques](#-awesome-techniques)
  - [Tutorial](#tutorial)
  - [Github Repo](#github-repo)



<!-- ------- 1 - Papers ------- -->
## 📝 Awesome Papers

<!-- ------- 1.1 - Survey ------- -->
### 📄 Survey
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| _VLA Models_ |
| [**An Anatomy of Vision-Language-Action Models: From Modules to Milestones and Challenges**](https://arxiv.org/abs/2512.11362) | arXiv | 2025-12-12 | ![Star](https://img.shields.io/github/stars/SuyuZ1/VLA-Survey-Anatomy?style=social&label=Star) [Github](https://github.com/SuyuZ1/VLA-Survey-Anatomy) | VLA Models |
| [**A Survey on Efficient Vision-Language-Action Models**](https://arxiv.org/abs/2510.24795) | arXiv | 2025-10-27 | ![Star](https://img.shields.io/github/stars/YuZhaoshu/Efficient-VLAs-Survey?style=social&label=Star) [Github](https://github.com/YuZhaoshu/Efficient-VLAs-Survey) | VLA Models |
| [**Efficient Vision-Language-Action Models for Embodied Manipulation: A Systematic Survey**](https://arxiv.org/abs/2510.17111) | arXiv | 2025-10-20 | - | VLA Models |
| [**Vision-Language-Action Models for Robotics: A Review Towards Real-World Applications**](https://arxiv.org/abs/2510.07077) | IEEE Access 2025 | 2025-10-08 | [Project](https://vla-survey.github.io/) | VLA Models |
| [**Large VLM-based Vision-Language-Action Models for Robotic Manipulation: A Survey**](https://arxiv.org/abs/2508.13073) | arXiv | 2025-08-23 | ![Star](https://img.shields.io/github/stars/JiuTian-VL/Large-VLM-based-VLA-for-Robotic-Manipulation?style=social&label=Star) [Github](https://github.com/JiuTian-VL/Large-VLM-based-VLA-for-Robotic-Manipulation) | VLA Models |
| [**Survey of Vision-Language-Action Models for Embodied Manipulation**](https://arxiv.org/abs/2508.15201) | arXiv | 2025-08-21 | - | VLA Models |
| [**Vision Language Action Models in Robotic Manipulation: A Systematic Review**](https://arxiv.org/abs/2507.10672) | arXiv | 2025-07-14 | - | VLA Models |
| [**A Survey on Vision-Language-Action Models: An Action Tokenization Perspective**](https://arxiv.org/abs/2507.01925) | arXiv | 2025-07-02 | - | VLA Models |
| [**Parallels Between VLA Model Post-Training and Human Motor Learning: Progress, Challenges, and Trends**](https://arxiv.org/abs/2506.20966) | arXiv | 2025-05-26 | ![Star](https://img.shields.io/github/stars/AoqunJin/Awesome-VLA-Post-Training?style=social&label=Star) [Github](https://github.com/AoqunJin/Awesome-VLA-Post-Training) | VLA Models |
| [**Vision-Language-Action Models: Concepts, Progress, Applications and Challenges**](https://arxiv.org/abs/2505.04769) | arXiv | 2025-05-07 | - | VLA Models |
| [**A Survey on Vision-Language-Action Models for Embodied AI**](https://arxiv.org/abs/2405.14093) | arXiv | 2024-05-23 | - | VLA Models |
| _Dexterous Manipulation_ |
| [**The Developments and Challenges towards Dexterous and Embodied Robotic Manipulation: A Survey**](https://arxiv.org/abs/2507.11840) | arXiv | 2025-07-16 | - | Dexterous Manipulation |
| [**Interactive Imitation Learning for Dexterous Robotic Manipulation: Challenges and Perspectives -- A Survey**](https://arxiv.org/abs/2506.00098) | arXiv | 2025-06-30 | - | Dexterous Manipulation |
| [**Dexterous Manipulation through Imitation Learning: A Survey**](https://arxiv.org/abs/2504.03515) | arXiv | 2025-04-04 | - | Dexterous Manipulation |
| _Deformable Object Manipulation (DOM)_ |
| [**T-DOM: A Taxonomy for Robotic Manipulation of Deformable Objects**](https://arxiv.org/abs/2412.20998) | arXiv | 2024-12-30 | [Project](https://sites.google.com/view/t-dom) | DOM |
| [**A Survey on Robotic Manipulation of Deformable Objects: Recent Advances, Open Challenges and New Frontiers**](https://arxiv.org/abs/2312.10419) | arXiv | 2023-12-16 | - | DOM |
| [**Robotic manipulation and sensing of deformable objects in domestic and industrial applications: a survey**](https://uca.hal.science/hal-01816189/document) | IJRR 2018 | 2018-06-13 | - | DOM |
| _Humanoid Manipulation_ |
| [**Humanoid Locomotion and Manipulation: Current Progress and Challenges in Control, Planning, and Learning**](https://arxiv.org/abs/2501.02116) | arXiv | 2025-01-03 | - | Humanoid Manipulation |
| [**Teleoperation of Humanoid Robots: A Survey**](https://arxiv.org/abs/2301.04317) | T-RO 2024 | 2023-01-11 | [Project](https://humanoid-teleoperation.github.io/) | Humanoid |
| _Others_ |
| [**Video Generation Models in Robotics -- Applications, Research Challenges, Future Directions**](https://arxiv.org/abs/2601.07823) | arXiv | 2026-01-12 | - | Video Generation |
| [**Embodied Robot Manipulation in the Era of Foundation Models: Planning and Learning Perspectives**](https://arxiv.org/abs/2512.22983) | arXiv | 2025-12-28 | - | Manipulation |
| [**Safe Learning for Contact-Rich Robot Tasks: A Survey from Classical Learning-Based Methods to Safe Foundation Models**](https://arxiv.org/abs/2512.11908) | arXiv | 2025-12-10 | - | Contact-Rich Manipulation |
| [**A Step Toward World Models: A Survey on Robotic Manipulation**](https://arxiv.org/abs/2511.02097) | arXiv | 2025-10-31 | - | World Model in Manipulation |
| [**Towards a Unified Understanding of Robot Manipulation: A Comprehensive Survey**](https://arxiv.org/abs/2510.10903) | arXiv | 2025-10-13 | ![Star](https://img.shields.io/github/stars/BaiShuanghao/Awesome-Robotics-Manipulation?style=social&label=Star) [Github](https://github.com/BaiShuanghao/Awesome-Robotics-Manipulation) | Manipulation |
| [**A Survey of Robotic Navigation and Manipulation with Physics Simulators in the Era of Embodied AI**](https://arxiv.org/abs/2505.01458) | arXiv | 2025-05-01 | - | Navigation and Manipulation |
| [**Diffusion Models for Robotic Manipulation: A Survey**](https://arxiv.org/abs/2504.08438) | arXiv | 2025-04-11 | - | Manipulation + DP |
| [**Multimodal Fusion and Vision-Language Models: A Survey for Robot Vision**](https://arxiv.org/abs/2504.02477) | arXiv | 2025-04-03 | ![Star](https://img.shields.io/github/stars/Xiaofeng-Han-Res/MF-RV?style=social&label=Star) [Github](https://github.com/Xiaofeng-Han-Res/MF-RV) | Robot Vision |
| [**Generative Artificial Intelligence in Robotic Manipulation: A Survey**](https://arxiv.org/abs/2503.03464) | arXiv | 2025-03-05 | ![Star](https://img.shields.io/github/stars/GAI4Manipulation/AwesomeGAIManipulation?style=social&label=Star) [Github](https://github.com/GAI4Manipulation/AwesomeGAIManipulation) | Manipulation + Generative Models |
| [**A Survey of Embodied Learning for Object-Centric Robotic Manipulation**](https://arxiv.org/abs/2408.11537) | MIR 2025 | 2024-08-21 | ![Star](https://img.shields.io/github/stars/RayYoh/OCRM_survey?style=social&label=Star) [Github](https://github.com/RayYoh/OCRM_survey) | Manipulation + Object-Centric |
| [**Aligning Cyber Space with Physical World: A Comprehensive Survey on Embodied AI**](https://arxiv.org/abs/2407.06886) | arXiv | 2024-07-09 | ![Star](https://img.shields.io/github/stars/HCPLab-SYSU/Embodied_AI_Paper_List?style=social&label=Star) [Github](https://github.com/HCPLab-SYSU/Embodied_AI_Paper_List) | Embodied Agent |
| [**Survey of Learning-based Approaches for Robotic In-Hand Manipulation**](https://arxiv.org/abs/2401.07915) | arXiv | 2024-01-15 | - | In-hand Manipulation |
| [**Language-conditioned Learning for Robotic Manipulation: A Survey**](https://arxiv.org/abs/2312.10807) | arXiv | 2023-12-17 | ![Star](https://img.shields.io/github/stars/hk-zh/language-conditioned-robot-manipulation-models?style=social&label=Star) [Github](https://github.com/hk-zh/language-conditioned-robot-manipulation-models) | Manipulation |
| [**Deep Learning Approaches to Grasp Synthesis: A Review**](https://arxiv.org/abs/2207.02556) | T-RO 2023 | 2023-07-06 | [Project](https://rhys-newbury.github.io/projects/6dof/) | Grasp |
| [**A Survey of Wheeled Mobile Manipulation: A Decision Making Perspective**](https://par.nsf.gov/servlets/purl/10393722) | J. Mech. Robot. 2023 | 2023-04 | - | Mobile Manipulation |
| [**A Review of Soft Manipulator Research, Applications, and Opportunities**](https://onlinelibrary.wiley.com/doi/abs/10.1002/rob.22051) | J Field Robot. 2023 | 2023-04 | - | Soft Manipulator |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

<!-- ------- 1.2 - Future Direction ------- -->
<!-- ### Future Direction
<!-- |  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Federated Learning for Large-Scale Cloud Robotic Manipulation: Opportunities and Challenges**](https://www.arxiv.org/abs/2507.17903) | ICMLC 2025 | 2025-07-23 | - | | --> 

> **Note:** Other papers are **summarized** in the [**Contents**](contents/).



<!-- ------- 2 - Benchmarks ------- -->
## 📊 Awesome Simulators, Benchmarks and Dataset

<!-- ------- 2.1 - Grasp Datasets ------- -->
### Grasp Datasets
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Rectangle-based Grasp_ |
| [Grasp-Anything-6D: **Language-Driven 6-DoF Grasp Detection Using Negative Prompt Guidance**](https://arxiv.org/abs/2407.13842) | ECCV 2024 | 2024-07-18 | ![Star](https://img.shields.io/github/stars/Fsoft-AIC/Language-Driven-6-DoF-Grasp-Detection-Using-Negative-Prompt-Guidance?style=social&label=Star) [Github](https://github.com/Fsoft-AIC/Language-Driven-6-DoF-Grasp-Detection-Using-Negative-Prompt-Guidance) |  |
| [Grasp-Anything++: **Language-driven Grasp Detection**](https://arxiv.org/abs/2406.09489) | CVPR 2024 | 2024-06-13 | ![Star](https://img.shields.io/github/stars/Fsoft-AIC/LGD?style=social&label=Star) [Github](https://github.com/Fsoft-AIC/LGD) |  |
| [**Grasp-Anything: Large-scale Grasp Dataset from Foundation Models**](https://arxiv.org/abs/2309.09818) | ICRA 2024 | 2023-09-18 | ![Star](https://img.shields.io/github/stars/Fsoft-AIC/Grasp-Anything?style=social&label=Star) [Github](https://github.com/Fsoft-AIC/Grasp-Anything) | |
| [**REGRAD: A Large-Scale Relational Grasp Dataset for Safe and Object-Specific Robotic Grasping in Clutter**](https://arxiv.org/abs/2104.14118) | ICRA 2021 | 2021-04-29 | ![Star](https://img.shields.io/github/stars/poisonwine/REGRAD?style=social&label=Star) [Github](https://github.com/poisonwine/REGRAD) | |
| [**Jacquard: A Large Scale Dataset for Robotic Grasp Detection**](https://arxiv.org/abs/1803.11469) | IROS 2018 | 2018-03-30 | [Project](https://jacquard.liris.cnrs.fr/) | |
| [Cornell: **Efficient Grasping from RGBD Images: Learning Using a New Rectangle Representation**](https://ieeexplore.ieee.org/document/5980145) | ICRA 2011 | 2011-08 | - | |
| _6-DoF Grasp_ |
| [**GraspFactory: A Large Object-Centric Grasping Dataset**](https://arxiv.org/abs/2509.20550) | CoRLW 2025 | 2025-09-24 | ![Star](https://img.shields.io/github/stars/AutodeskRoboticsLab/graspfactory?style=social&label=Star) [Github](https://github.com/AutodeskRoboticsLab/graspfactory) | |
| [**MapleGrasp: Mask-guided Feature Pooling for Language-driven Efficient Robotic Grasping**](https://arxiv.org/abs/2506.06535) | arXiv | 2025-06-06 | - | |
| [**GraspClutter6D: A Large-scale Real-world Dataset for Robust Perception and Grasping in Cluttered Scenes**](https://arxiv.org/abs/2504.06866) | arXiv | 2025-04-09 | [Project](https://sites.google.com/view/graspclutter6d) | |
| [**QDGset: A Large Scale Grasping Dataset Generated with Quality-Diversity**](https://arxiv.org/abs/2410.02319) | arXiv | 2024-10-03 | [Project](https://github.com/qdgrasp/qdgrasp.github.io/blob/main/qdg_set.md) | |
| [**Real-to-Sim Grasp: Rethinking the Gap between Simulation and Real World in Grasp Detection**](https://arxiv.org/abs/2410.06521) | CoRL 2024 | 2024-10-09 | [Project](https://isee-laboratory.github.io/R2SGrasp/) | |
| [**MetaGraspNetV2: All-in-One Dataset Enabling Fast and Reliable Robotic Bin Picking via Object Relationship Reasoning and Dexterous Grasping**](https://ieeexplore.ieee.org/document/10309974) | TASE 2023 | 2023-11-06 | ![Star](https://img.shields.io/github/stars/maximiliangilles/MetaGraspNet?style=social&label=Star) [Github](https://github.com/maximiliangilles/MetaGraspNet) | |
| [**MetaGraspNet: A Large-Scale Benchmark Dataset for Scene-Aware Ambidextrous Bin Picking via Physics-based Metaverse Synthesis**](https://arxiv.org/abs/2208.03963) | CASE 2022 | 2022-08-08 | ![Star](https://img.shields.io/github/stars/maximiliangilles/MetaGraspNet?style=social&label=Star) [Github](https://github.com/maximiliangilles/MetaGraspNet) | |
| [**ACRONYM: A Large-Scale Grasp Dataset Based on Simulation**](https://arxiv.org/abs/2011.09584) | ICRA 2021 | 2020-11-18 | ![Star](https://img.shields.io/github/stars/NVlabs/acronym?style=social&label=Star) [Github](https://github.com/NVlabs/acronym) | |
| [**GraspNet-1Billion: A Large-Scale Benchmark for General Object Grasping**](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fang_GraspNet-1Billion_A_Large-Scale_Benchmark_for_General_Object_Grasping_CVPR_2020_paper.pdf) | CVPR 2020 | 2020-08-05 | ![Star](https://img.shields.io/github/stars/graspnet/graspnet-baseline?style=social&label=Star) [Github](https://github.com/graspnet/graspnet-baseline) | |
| _Dexterous Grasp_ |
| [**Dex1B: Learning with 1B Demonstrations for Dexterous Manipulation**](https://arxiv.org/abs/2506.17198) | RSS 2025 | 2025-06-20 | [Project](https://jianglongye.com/dex1b/) | |
| [**DexGraspNet 2.0: Learning Generative Dexterous Grasping in Large-scale Synthetic Cluttered Scenes**](https://openreview.net/attachment?id=5W0iZR9J7h&name=pdf) | CoRL 2024 | 2024 | ![Star](https://img.shields.io/github/stars/PKU-EPIC/DexGraspNet2?style=social&label=Star) [Github](https://github.com/PKU-EPIC/DexGraspNet2)  |
| [**UniFucGrasp: Human-Hand-Inspired Unified Functional Grasp Annotation Strategy and Dataset for Diverse Dexterous Hands**](https://www.arxiv.org/abs/2508.03339) | arXiv | 2025-08-05 | ![Star](https://img.shields.io/github/stars/cxcAxxy/UniFucGrasp?style=social&label=Star) [Github](https://github.com/cxcAxxy/UniFucGrasp) | |
| [**DexGraspNet: A Large-Scale Robotic Dexterous Grasp Dataset for General Objects Based on Simulation**](https://arxiv.org/abs/2210.02697) | ICRA 2023 | 2022-10-06 | ![Star](https://img.shields.io/github/stars/PKU-EPIC/DexGraspNet?style=social&label=Star) [Github](https://github.com/PKU-EPIC/DexGraspNet) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

<!-- ------- 2.2 - Single-Embodiment Manipulation Simulators and Benchmarks ------- -->

<div align="center">

### Single-Embodiment Manipulation Simulators and Benchmarks </i>

</div>

### Basic Manipulation with a Single Arm
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**REALM: A Real-to-Sim Validated Benchmark for Generalization in Robotic Manipulation**](https://arxiv.org/abs/2512.19562) | arXiv | 2025-12-22 | ![Star](https://img.shields.io/github/stars/martin-sedlacek/REALM?style=social&label=Star) [Github](https://github.com/martin-sedlacek/REALM) | |
| [**RobotArena: Scalable Robot Benchmarking via Real-to-Sim Translation**](https://arxiv.org/abs/2510.23571) | arXiv | 2025-10-27 | [Project](https://robotarenainf.github.io/) | |
| [**GSWorld: Closed-Loop Photo-Realistic Simulation Suite for Robotic Manipulation**](https://arxiv.org/abs/2510.20813) | arXiv | 2025-10-23 | ![Star](https://img.shields.io/github/stars/luccachiang/GSWorld?style=social&label=Star) [Github](https://github.com/luccachiang/GSWorld) | |
| [**NEBULA: Do We Evaluate Vision-Language-Action Agents Correctly?**](https://arxiv.org/abs/2510.16263) | arXiv | 2025-10-17 | ![Star](https://img.shields.io/github/stars/JerryPeng0201/NEBULA?style=social&label=Star) [Github](https://github.com/JerryPeng0201/NEBULA) | |
| [**SRMP: Search-Based Robot Motion Planning Library**](https://arxiv.org/abs/2509.25352) | arXiv | 2025-09-29 | [Project](https://srmp.readthedocs.io/en/latest/) | |
| [**Robot Control Stack: A Lean Ecosystem for Robot Learning at Scale**](https://arxiv.org/abs/2509.14932) | arXiv | 2025-09-18 | ![Star](https://img.shields.io/github/stars/RobotControlStack/robot-control-stack?style=social&label=Star) [Github](https://github.com/RobotControlStack/robot-control-stack) | For VLA |
| [**LADEV: A Language-Driven Testing and Evaluation Platform for Vision-Language-Action Models in Robotic Manipulation**](https://arxiv.org/abs/2410.05191) | arXiv | 2024-10-07 | - | For VLA |
| [**RoboCAS: A Benchmark for Robotic Manipulation in Complex Object Arrangement Scenarios**](https://arxiv.org/abs/2407.06951) | arXiv | 2024-07-09 | ![Star](https://img.shields.io/github/stars/notFoundThisPerson/RoboCAS-v0?style=social&label=Star) [Github](https://github.com/notFoundThisPerson/RoboCAS-v0) |
| [**GenSim2: Scaling Robot Data Generation with Multi-modal and Reasoning LLMs**](https://arxiv.org/abs/2410.03645) | CoRL 2024 | 2024-10-04 | ![Star](https://img.shields.io/github/stars/GenSim2/gensim2?style=social&label=Star) [Github](https://github.com/GenSim2/gensim2) |
| [**FetchBench: A Simulation Benchmark for Robot Fetching**](https://arxiv.org/abs/2406.11793) | CoRL 2024 | 2024-06-17 | ![Star](https://img.shields.io/github/stars/princeton-vl/FetchBench-CORL2024?style=social&label=Star) [Github](https://github.com/princeton-vl/FetchBench-CORL2024) |  |
| [SIMPLER: **Evaluating Real-World Robot Manipulation Policies in Simulation**](https://arxiv.org/abs/2405.05941) | CoRL 2024 | 2024-05-09 | ![Star](https://img.shields.io/github/stars/simpler-env/SimplerEnv?style=social&label=Star) [Github](https://github.com/simpler-env/SimplerEnv) | For VLA |
| [**Towards Diverse Behaviors: A Benchmark for Imitation Learning with Human Demonstrations**](https://arxiv.org/abs/2402.14606) | ICLR 2024 | 2024-02-22 | ![Star](https://img.shields.io/github/stars/ALRhub/d3il?style=social&label=Star) [Github](https://github.com/ALRhub/d3il) | |
| [**LIBERO: Benchmarking Knowledge Transfer for Lifelong Robot Learning**](https://arxiv.org/abs/2306.03310) | NeurIPS 2023 | 2023-06-05 | ![Star](https://img.shields.io/github/stars/Lifelong-Robot-Learning/LIBERO?style=social&label=Star) [Github](https://github.com/Lifelong-Robot-Learning/LIBERO) | |
| [**ARNOLD: A Benchmark for Language-Grounded Task Learning With Continuous States in Realistic 3D Scenes**](https://arxiv.org/abs/2304.04321) | ICCV 2023 | 2023-04-09 | ![Star](https://img.shields.io/github/stars/arnold-benchmark/arnold?style=social&label=Star) [Github](https://github.com/arnold-benchmark/arnold) | |
| [**VIMA: General Robot Manipulation with Multimodal Prompts**](https://arxiv.org/abs/2210.03094) | ICML 2023 | 2022-10-06 | ![Star](https://img.shields.io/github/stars/vimalabs/VIMA?style=social&label=Star) [Github](https://github.com/vimalabs/VIMA) | |
| [**ManiSkill2: A Unified Benchmark for Generalizable Manipulation Skills**](https://arxiv.org/abs/2302.04659) | ICLR 2023 | 2023-02-09 | ![Star](https://img.shields.io/github/stars/haosulab/ManiSkill2?style=social&label=Star) [Github](https://github.com/haosulab/ManiSkill2) | |
| [**Perceiver-Actor: A Multi-Task Transformer for Robotic Manipulation**](https://arxiv.org/abs/2209.05451) | CoRL 2022 | 2022-11-11 | ![Star](https://img.shields.io/github/stars/peract/peract?style=social&label=Star) [Github](https://github.com/peract/peract) | |
| [**VLMbench: A Compositional Benchmark for Vision-and-Language Manipulation**](https://arxiv.org/abs/2206.08522) | NeurIPS 2022 | 2022-06-17 | ![Star](https://img.shields.io/github/stars/eric-ai-lab/VLMbench?style=social&label=Star) [Github](https://github.com/eric-ai-lab/VLMbench) | |
| [**ManiSkill: Generalizable Manipulation Skill Benchmark with Large-Scale Demonstrations**](https://arxiv.org/abs/2107.14483) | NeurIPS D&B 2021 | 2021-07-30 | ![Star](https://img.shields.io/github/stars/haosulab/ManiSkill?style=social&label=Star) [Github](https://github.com/haosulab/ManiSkill) | |
| [Robomimic: **What Matters in Learning from Offline Human Demonstrations for Robot Manipulation**](https://arxiv.org/abs/2108.03298) | CoRL 2021 | 2021-08-06 | ![Star](https://img.shields.io/github/stars/ARISE-Initiative/robomimic?style=social&label=Star) [Github](https://github.com/ARISE-Initiative/robomimic) | |
| [**RLBench: The Robot Learning Benchmark & Learning Environment**](https://arxiv.org/abs/1909.12271) | RA-L 2020 | 2019-09-26 | ![Star](https://img.shields.io/github/stars/stepjam/RLBench?style=social&label=Star) [Github](https://github.com/stepjam/RLBench) | |
| [Franka-Kitchen: **Relay Policy Learning: Solving Long-Horizon Tasks via Imitation and Reinforcement Learning**](https://arxiv.org/abs/1910.11956) | CoRL 2019 | 2019-10-25 | [Project](https://relay-policy-learning.github.io/) |
| [**Meta-World: A Benchmark and Evaluation for Multi-Task and Meta Reinforcement Learning**](https://arxiv.org/abs/1910.10897) | CoRL 2019 | 2019-10-24 | ![Star](https://img.shields.io/github/stars/Farama-Foundation/Metaworld?style=social&label=Star) [Github](https://github.com/Farama-Foundation/Metaworld) |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Basic Manipulation with Bimanual Arms
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**The Great March 100: 100 Detail-oriented Tasks for Evaluating Embodied AI Agents**](https://arxiv.org/abs/2601.11421) | arXiv | 2026-01-16 | ![Star](https://img.shields.io/github/stars/yuz1wan/GM-X?style=social&label=Star) [Github](https://github.com/yuz1wan/GM-X) | |
| [**RoboEval: Where Robotic Manipulation Meets Structured and Scalable Evaluation**](https://arxiv.org/abs/2507.00435) | arXiv | 2025-07-01 | ![Star](https://img.shields.io/github/stars/Robo-Eval/RoboEval?style=social&label=Star) [Github](https://github.com/Robo-Eval/RoboEval) | |
| [**RoboTwin 2.0: A Scalable Data Generator and Benchmark with Strong Domain Randomization for Robust Bimanual Robotic Manipulation**](https://arxiv.org/abs/2506.18088) | arXiv | 2025-06-22 | ![Star](https://img.shields.io/github/stars/robotwin-Platform/RoboTwin?style=social&label=Star) [Github](https://github.com/robotwin-Platform/RoboTwin) | |
| [**RoboTwin: Dual-Arm Robot Benchmark with Generative Digital Twins**](https://arxiv.org/abs/2504.13059) | CVPR 2025 | 2025-04-17 | ![Star](https://img.shields.io/github/stars/TianxingChen/RoboTwin?style=social&label=Star) [Github](https://github.com/TianxingChen/RoboTwin) | |
| [**PerAct2: Benchmarking and Learning for Robotic Bimanual Manipulation Tasks**](https://arxiv.org/abs/2407.00278) | CoRLW 2024 | 2024-07-29 | ![Star](https://img.shields.io/github/stars/markusgrotz/peract_bimanual?style=social&label=Star) [Github](https://github.com/markusgrotz/peract_bimanual) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Basic Manipulation with Long-horizon Tasks
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**RoboCerebra: A Large-scale Benchmark for Long-horizon Robotic Manipulation Evaluation**](https://arxiv.org/abs/2506.06677) | arXiv | 2025-06-07 | [Project](https://robocerebra.github.io/) | |
| [**MuBlE: MuJoCo and Blender simulation Environment and Benchmark for Task Planning in Robot Manipulation**](https://arxiv.org/abs/2503.02834) | arXiv | 2025-03-03 | ![Star](https://img.shields.io/github/stars/michaal94/MuBlE?style=social&label=Star) [Github](https://github.com/michaal94/MuBlE) | |
| [**VLABench: A Large-Scale Benchmark for Language-Conditioned Robotics Manipulation with Long-Horizon Reasoning Tasks**](https://arxiv.org/abs/2412.18194) | arXiv | 2024-12-24 | ![Star](https://img.shields.io/github/stars/OpenMOSS/VLABench?style=social&label=Star) [Github](https://github.com/OpenMOSS/VLABench) | |
| [**FurnitureBench: Reproducible Real-World Benchmark for Long-Horizon Complex Manipulation**](https://arxiv.org/abs/2305.12821) | RSS 2023 | 2023-05-22 | ![Star](https://img.shields.io/github/stars/clvrai/furniture-bench?style=social&label=Star) [Github](https://github.com/clvrai/furniture-bench) | |
| [**CALVIN: A Benchmark for Language-Conditioned Policy Learning for Long-Horizon Robot Manipulation Tasks**](https://arxiv.org/abs/2112.03227) | RA-L 2022 | 2021-12-06 | ![Star](https://img.shields.io/github/stars/mees/calvin?style=social&label=Star) [Github](https://github.com/mees/calvin) | |
| [**Panda-gym: Open-source Goal-conditioned Environments for Robotic Learning**](https://arxiv.org/abs/2106.13687) | NeurIPSW 2021 | 2021-06-25 | ![Star](https://img.shields.io/github/stars/qgallouedec/panda-gym?style=social&label=Star) [Github](https://github.com/qgallouedec/panda-gym) | |
| [**IKEA Furniture Assembly Environment for Long-Horizon Complex Manipulation Tasks**](https://arxiv.org/abs/1911.07246) | ICRA 2021 | 2019-11-17 | ![Star](https://img.shields.io/github/stars/clvrai/furniture?style=social&label=Star) [Github](https://github.com/clvrai/furniture) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Basic Manipulation with Generalization Tasks
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**LIBERO-X: Robustness Litmus for Vision-Language-Action Models**](https://arxiv.org/abs/2602.06556) | arXiv | 2026-02-06 | ![Star](https://img.shields.io/github/stars/zackhxn/LIBERO-X?style=social&label=Star) [Github](https://github.com/zackhxn/LIBERO-X) | |
| [**VLA-Arena: An Open-Source Framework for Benchmarking Vision-Language-Action Models**](https://arxiv.org/abs/2512.22539) | arXiv | 2025-12-27 | [Project](https://vla-arena.github.io/) | |
| [INT-ACT: **From Intention to Execution: Probing the Generalization Boundaries of Vision-Language-Action Models**](https://arxiv.org/abs/2506.09930) | arXiv | 2025-06-11 | ![Star](https://img.shields.io/github/stars/ai4ce/INT-ACT?style=social&label=Star) [Github](https://github.com/ai4ce/INT-ACT) | |
| [AGNOSTOS: **Exploring the Limits of Vision-Language-Action Manipulations in Cross-task Generalization**](https://arxiv.org/abs/2505.15660) | arXiv | 2025-05-21 | ![Star](https://img.shields.io/github/stars/jiaming-zhou/X-ICM?style=social&label=Star) [Github](https://github.com/jiaming-zhou/X-ICM) | |
| [Gembench: **Towards Generalizable Vision-Language Robotic Manipulation: A Benchmark and LLM-guided 3D Policy**](https://arxiv.org/abs/2410.01345) | ICRA 2025 | 2024-10-02 | ![Star](https://img.shields.io/github/stars/vlc-robot/robot-3dlotus?style=social&label=Star) [Github](https://github.com/vlc-robot/robot-3dlotus) | |
| [**THE COLOSSEUM: A Benchmark for Evaluating Generalization for Robotic Manipulation**](https://arxiv.org/abs/2402.08191) | RSSW 2024 | 2024-02-13 | ![Star](https://img.shields.io/github/stars/robot-colosseum/robot-colosseum?style=social&label=Star) [Github](https://github.com/robot-colosseum/robot-colosseum) | |
| [**KitchenShift: Evaluating Zero-Shot Generalization of Imitation-Based Policy Learning Under Domain Shifts**](https://openreview.net/pdf?id=DdglKo8hBq0) | NeurIPSW 2021 | 2021 | ![Star](https://img.shields.io/github/stars/etaoxing/kitchen-shift?style=social&label=Star) [Github](https://github.com/etaoxing/kitchen-shift) |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Basic Manipulation in Real World
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**AutoEval: Autonomous Evaluation of Generalist Robot Manipulation Policies in the Real World**](https://arxiv.org/pdf/2503.24278) | arXiv | 2025-03-31 | ![Star](https://img.shields.io/github/stars/zhouzypaul/auto_eval?style=social&label=Star) [Github](https://github.com/zhouzypaul/auto_eval) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Basic Manipulation with High-level Planner
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**AgenticLab: A Real-World Robot Agent Platform that Can See, Think, and Act**](https://arxiv.org/abs/2602.01662) | arXiv | 2026-02-02 | - | |
| [**ResponsibleRobotBench: Benchmarking Responsible Robot Manipulation using Multi-modal Large Language Models**](https://arxiv.org/abs/2512.04308) | CVPR 2025 | 2025-12-03 | [Project](https://sites.google.com/view/responsible-robotbench) | |
| [**GENMANIP: LLM-driven Simulation for Generalizable Instruction-Following Manipulation**](https://arxiv.org/abs/2506.10966) | CVPR 2025 | 2025-06-12 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/GenManip?style=social&label=Star) [Github](https://github.com/OpenRobotLab/GenManip) | |
| [**ALFRED: A Benchmark for Interpreting Grounded Instructions for Everyday Tasks**](https://arxiv.org/abs/1912.01734) | CVPR 2020 | 2019-12-03 | ![Star](https://img.shields.io/github/stars/askforalfred/alfred?style=social&label=Star) [Github](https://github.com/askforalfred/alfred) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Basic Manipulation with Tactile Representations
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**UniVTAC: A Unified Simulation Platform for Visuo-Tactile Manipulation Data Generation, Learning, and Benchmarking**](https://arxiv.org/abs/2602.10093) | arXiv | 2026-02-10 | ![Star](https://img.shields.io/github/stars/univtac/UniVTAC?style=social&label=Star) [Github](https://github.com/univtac/UniVTAC) | |
| [**ManiFeel: Benchmarking and Understanding Visuotactile Manipulation Policy Learning**](https://arxiv.org/abs/2505.18472) | arXiv | 2025-05-24 | [Project](https://zhengtongxu.github.io/manifeel-website/) | |
| [**TacCompress: A Benchmark for Multi-Point Tactile Data Compression in Dexterous Manipulation**](https://arxiv.org/abs/2505.16289) | arXiv | 2025-05-22 | - | |
| [**TacSL: A Library for Visuotactile Sensor Simulation and Learning**](https://arxiv.org/abs/2408.06506) | T-RO 2025 | 2024-08-12 | ![Star](https://img.shields.io/github/stars/isaac-sim/IsaacGymEnvs?style=social&label=Star) [Github](https://github.com/isaac-sim/IsaacGymEnvs/blob/tacsl/isaacgymenvs/tacsl_sensors/install/tacsl_setup.md) | |
| [**Efficient Tactile Simulation with Differentiability for Robotic Manipulation**](https://openreview.net/pdf?id=6BIffCl6gsM) | CoRL 2022 | 2022-09-10 | ![Star](https://img.shields.io/github/stars/eanswer/TactileSimulation?style=social&label=Star) [Github](https://github.com/eanswer/TactileSimulation) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Dexterous Manipulation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**TriFinger: An Open-Source Robot for Learning Dexterity**](https://arxiv.org/abs/2008.03596) | CoRL 2021 | 2020-08-08 | ![Star](https://img.shields.io/github/stars/open-dynamic-robot-initiative/trifinger_simulation?style=social&label=Star) [Github](https://github.com/open-dynamic-robot-initiative/trifinger_simulation) | |
| [**Learning Complex Dexterous Manipulation with Deep Reinforcement Learning and Demonstrations**](https://arxiv.org/abs/1709.10087) | RSS 2018 | 2017-09-28 | ![Star](https://img.shields.io/github/stars/aravindr93/hand_dapg?style=social&label=Star) [Github](https://github.com/aravindr93/hand_dapg) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Deformable Object Manipulation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Real Garment Benchmark (RGBench): A Comprehensive Benchmark for Robotic Garment Manipulation featuring a High-Fidelity Scalable Simulator**](https://arxiv.org/abs/2511.06434) | AAAI 2026 | 2025-11-09 | ![Star](https://img.shields.io/github/stars/hwk0809/RGBench?style=social&label=Star) [Github](https://github.com/hwk0809/RGBench) |
| [**MoDeSuite: Robot Learning Task Suite for Benchmarking Mobile Manipulation with Deformable Objects**](https://arxiv.org/abs/2507.21796) | arXiv | 2025-07-29 | [Project](https://sites.google.com/view/modesuite/home) |
| [**DaXBench: Benchmarking Deformable Object Manipulation with Differentiable Physics**](https://arxiv.org/abs/2210.13066) | ICLR 2023 | 2022-10-24 | ![Star](https://img.shields.io/github/stars/AdaCompNUS/DaXBench?style=social&label=Star) [Github](https://github.com/AdaCompNUS/DaXBench) | |
| [**PlasticineLab: A Soft-Body Manipulation Benchmark with Differentiable Physics**](https://arxiv.org/abs/2104.03311) | ICLR 2021 | 2021-04-07 | ![Star](https://img.shields.io/github/stars/hzaskywalker/PlasticineLab?style=social&label=Star) [Github](https://github.com/hzaskywalker/PlasticineLab) | |
| [**SoftGym: Benchmarking Deep Reinforcement Learning for Deformable Object Manipulation**](https://arxiv.org/abs/2011.07215) | CoRL 2020 | 2020-11-14 | ![Star](https://img.shields.io/github/stars/Xingyu-Lin/softgym?style=social&label=Star) [Github](https://github.com/Xingyu-Lin/softgym) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Mobile ManipulationSurgWorld: Learni
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**MobileManiBench: Simplifying Model Verification for Mobile Manipulation**](https://arxiv.org/abs/2602.05233) | arXiv | 2026-02-05 | [Project](https://dexhand.github.io/MobileManiBench_Website/) | |
| [**RoboBenchMart: Benchmarking Robots in Retail Environment**](https://arxiv.org/abs/2511.10276) | arXiv | 2025-11-13 | ![Star](https://img.shields.io/github/stars/emb-ai/RoboBenchMart?style=social&label=Star) [Github](https://github.com/emb-ai/RoboBenchMart) | |
| [**ReGen: Generative Robot Simulation via Inverse Design**](https://arxiv.org/abs/2511.04769) | ICLR 2025 | 2025-11-06 | [Project](https://regen-sim.github.io/) | |
| [**Mind and Motion Aligned: A Joint Evaluation IsaacSim Benchmark for Task Planning and Low-Level Policies in Mobile Manipulation**](https://arxiv.org/abs/2508.15663) | arXiv | 2023-08-21 | - | |
| [**CleanUpBench: Embodied Sweeping and Grasping Benchmark**](https://www.arxiv.org/abs/2508.05543) | arXiv | 2023-08-07 | - | |
| [**HomeRobot: Open-Vocabulary Mobile Manipulation**](https://arxiv.org/abs/2306.11565) | CoRL 2023 | 2023-06-20 | ![Star](https://img.shields.io/github/stars/facebookresearch/home-robot?style=social&label=Star) [Github](https://github.com/facebookresearch/home-robot) | |
| [**BEHAVIOR-1K: A Human-Centered, Embodied AI Benchmark with 1,000 Everyday Activities and Realistic Simulation**](https://arxiv.org/abs/2403.09227) | CoRL 2022 | 2024-03-14 | [Project](https://behavior.stanford.edu/) | |
| [**ManipulaTHOR: A Framework for Visual Object Manipulation**](https://arxiv.org/abs/2104.11213) | CVPR 2021 | 2021-04-22 | ![Star](https://img.shields.io/github/stars/allenai/manipulathor?style=social&label=Star) [Github](https://github.com/allenai/manipulathor) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Quadrupedal Manipulation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**ODYSSEY: Open-World Quadrupeds Exploration and Manipulation for Long-Horizon Tasks**](https://arxiv.org/abs/2508.08240) | arXiv | 2025-08-11 | [Project](https://kaijwang.github.io/odyssey.github.io/) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Humanoid Manipulation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Genie Sim 3.0 : A High-Fidelity Comprehensive Simulation Platform for Humanoid Robot**](https://arxiv.org/abs/2601.02078) | arXiv | 2026-01-05 | ![Star](https://img.shields.io/github/stars/AgibotTech/genie_sim?style=social&label=Star) [Github](https://github.com/AgibotTech/genie_sim) | |
| [**HumanoidGen: Data Generation for Bimanual Dexterous Manipulation via LLM Reasoning**](https://arxiv.org/abs/2507.00833) | arXiv | 2025-07-01 | ![Star](https://img.shields.io/github/stars/TeleHuman/HumanoidGen?style=social&label=Star) [Github](https://github.com/TeleHuman/HumanoidGen) | |
| [**BiGym: A Demo-Driven Mobile Bi-Manual Manipulation Benchmark**](https://arxiv.org/abs/2407.07788) | arXiv | 2024-07-10 | ![Star](https://img.shields.io/github/stars/chernyadev/bigym?style=social&label=Star) [Github](https://github.com/chernyadev/bigym) | |
| [**HumanoidBench: Simulated Humanoid Benchmark for Whole-Body Locomotion and Manipulation**](https://arxiv.org/abs/2403.10506) | arXiv | 2024-03-15 | ![Star](https://img.shields.io/github/stars/carlosferrazza/humanoid-bench?style=social&label=Star) [Github](https://github.com/carlosferrazza/humanoid-bench) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

<!-- ------- 2.3 - Cross-Embodiment Simulators and Benchmarks ------- -->
### Cross-Embodiment Simulators and Benchmarks
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**MolmoSpaces: A Large-Scale Open Ecosystem for Robot Navigation and Manipulation**](https://arxiv.org/abs/2602.11337) | arXiv | 2026-02-11 | ![Star](https://img.shields.io/github/stars/allenai/molmospaces?style=social&label=Star) [Github](https://github.com/allenai/molmospaces) |
| [**Isaac Lab: A GPU-Accelerated Simulation Framework for Multi-Modal Robot Learning**](https://arxiv.org/abs/2511.04831) | arXiv | 2025-11-06 | ![Star](https://img.shields.io/github/stars/isaac-sim/IsaacLab?style=social&label=Star) [Github](https://github.com/isaac-sim/IsaacLab) |
| [**AgentWorld: An Interactive Simulation Platform for Scene Construction and Mobile Robotic Manipulation**](https://arxiv.org/abs/2508.07770) | CoRL 2025 | 2025-08-11 | ![Star](https://img.shields.io/github/stars/yizhengzhang1/agent_world?style=social&label=Star) [Github](https://github.com/yizhengzhang1/agent_world) |
| [**VIKI-R: Coordinating Embodied Multi-Agent Cooperation via Reinforcement Learning**](https://arxiv.org/abs/2506.09049) | arXiv | 2025-06-10 | ![Star](https://img.shields.io/github/stars/MARS-EAI/VIKI-R?style=social&label=Star) [Github](https://github.com/MARS-EAI/VIKI-R) |
| [**ImagineBench: Evaluating Reinforcement Learning with Large Language Model Rollouts**](https://arxiv.org/abs/2505.10010) | arXiv | 2025-05-15 | ![Star](https://img.shields.io/github/stars/LAMDA-RL/ImagineBench?style=social&label=Star) [Github](https://github.com/LAMDA-RL/ImagineBench) |
| [**RoboVerse: Towards a Unified Platform, Dataset and Benchmark for Scalable and Generalizable Robot Learning**](https://arxiv.org/abs/2504.18904) | RSS 2025 | 2025-04-26 | ![Star](https://img.shields.io/github/stars/RoboVerseOrg/RoboVerse?style=social&label=Star) [Github](https://github.com/RoboVerseOrg/RoboVerse) |
| [**ManiSkill3: GPU Parallelized Robotics Simulation and Rendering for Generalizable Embodied AI**](https://arxiv.org/abs/2410.00425) | RSS 2025 | 2024-10-01 | ![Star](https://img.shields.io/github/stars/haosulab/ManiSkill?style=social&label=Star) [Github](https://github.com/haosulab/ManiSkill) |
| **GENESIS: A generative world for general-purpose robotics & embodied AI learning** | - | 2024-12 | ![Star](https://img.shields.io/github/stars/Genesis-Embodied-AI/Genesis?style=social&label=Star) [Github](https://github.com/Genesis-Embodied-AI/Genesis) |
| [**RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots**](https://arxiv.org/abs/2406.02523) | RSS 2024 | 2024-06-04 | ![Star](https://img.shields.io/github/stars/robocasa/robocasa?style=social&label=Star) [Github](https://github.com/robocasa/robocasa) |  |
| [**LocoMuJoCo: A Comprehensive Imitation Learning Benchmark for Locomotion**](https://arxiv.org/abs/2311.02496) | NeurIPSW 2023 | 2023-11-04 | ![Star](https://img.shields.io/github/stars/robfiras/loco-mujoco?style=social&label=Star) [Github](https://github.com/robfiras/loco-mujoco) | |
| [**RoboHive: A Unified Framework for Robot Learning**](https://arxiv.org/abs/2310.06828) | NeurIPS D&B 2023 | 2023-10-10 | ![Star](https://img.shields.io/github/stars/vikashplus/robohive?style=social&label=Star) [Github](https://github.com/vikashplus/robohive) | |
| [CortexBench: **Where are we in the search for an Artificial Visual Cortex for Embodied Intelligence?**](https://arxiv.org/abs/2303.18240) | NeurIPS 2023 | 2023-03-31 | ![Star](https://img.shields.io/github/stars/facebookresearch/eai-vc?style=social&label=Star) [Github](https://github.com/facebookresearch/eai-vc) | |
| [Isaac Lab: **Orbit: A Unified Simulation Framework for Interactive Robot Learning Environments**](https://arxiv.org/abs/2301.04195) | RA-L 2023 | 2023-01-10 | ![Star](https://img.shields.io/github/stars/isaac-sim/IsaacLab?style=social&label=Star) [Github](https://github.com/isaac-sim/IsaacLab) |
| [**robosuite: A Modular Simulation Framework and Benchmark for Robot Learning**](https://arxiv.org/abs/2009.12293) | arXiv | 2020-09-25 | ![Star](https://img.shields.io/github/stars/ARISE-Initiative/robosuite?style=social&label=Star) [Github](https://github.com/ARISE-Initiative/robosuite) |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

<!-- ------- 2.4 - Other Simulators and Benchmarks ------- -->
### Other Simulators and Benchmarks
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**TabletopGen: Instance-Level Interactive 3D Tabletop Scene Generation from Text or Single Image**](https://arxiv.org/abs/2512.01204) | arXiv | 2025-12-01 | ![Star](https://img.shields.io/github/stars/D-Robotics-AI-Lab/TabletopGen?style=social&label=Star) [Github](https://github.com/D-Robotics-AI-Lab/TabletopGen) | |
| [**SimWorld: An Open-ended Realistic Simulator for Autonomous Agents in Physical and Social Worlds**](https://arxiv.org/abs/2512.01078) | arXiv | 2025-11-30 | ![Star](https://img.shields.io/github/stars/SimWorld-AI/SimWorld?style=social&label=Star) [Github](https://github.com/SimWorld-AI/SimWorld) | |
| [**MarketGen: A Scalable Simulation Platform with Auto-Generated Embodied Supermarket Environments**](https://arxiv.org/abs/2511.21161) | arXiv | 2025-11-26 | [Project](https://xuhu0529.github.io/MarketGen/) | |
| [**MagBotSim: Physics-Based Simulation and Reinforcement Learning Environments for Magnetic Robotics**](https://arxiv.org/abs/2511.16158) | arXiv | 2025-11-20 | [Project](https://ubi-coro.github.io/MagBotSim/) | |
| [**SutureBot: A Precision Framework & Benchmark For Autonomous End-to-End Suturing**](https://arxiv.org/abs/2510.20965) | arXiv | 2025-10-23 | [Dataset](https://huggingface.co/datasets/jchen396/SutureBot) | |
| [**Space Robotics Bench: Robot Learning Beyond Earth**](https://arxiv.org/abs/2509.23328) | arXiv | 2025-09-27 | ![Star](https://img.shields.io/github/stars/AndrejOrsula/space_robotics_bench?style=social&label=Star) [Github](https://github.com/AndrejOrsula/space_robotics_bench) | |
| [**FLAME: A Federated Learning Benchmark for Robotic Manipulation**](https://arxiv.org/abs/2503.01729) | arXiv | 2025-03-03 | - | |
| [**Two by Two: Learning Multi-Task Pairwise Objects Assembly for Generalizable Robot Manipulation**](https://arxiv.org/abs/2504.06961) | CVPR 2025 | 2025-04-09 | ![Star](https://img.shields.io/github/stars/TEA-Lab/TwoByTWo?style=social&label=Star) [Github](https://github.com/TEA-Lab/TwoByTWo) | |
| [**FMB: a Functional Manipulation Benchmark for Generalizable Robotic Learning**](https://arxiv.org/abs/2401.08553) | IJRR 2024 | 2024-01-16 | ![Star](https://img.shields.io/github/stars/rail-berkeley/fmb?style=social&label=Star) [Github](https://github.com/rail-berkeley/fmb) | Functional Manipulation |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

<!-- ------- 2.5 - Trajectory Datasets ------- -->
### Trajectory Datasets
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Trustworthy Evaluation of Robotic Manipulation: A New Benchmark and AutoEval Methods**](https://arxiv.org/abs/2601.18723) | arXiv | 2026-01-26 | [Project](https://term-bench.github.io/) | |
| [**RoboMIND 2.0: A Multimodal, Bimanual Mobile Manipulation Dataset for Generalizable Embodied Intelligence**](https://arxiv.org/abs/2512.24653) | arXiv | 2025-12-31 | - | |
| [**OXE-AugE: A Large-Scale Robot Augmentation of OXE for Scaling Cross-Embodiment Policy Learning**](https://arxiv.org/abs/2512.13100) | arXiv | 2025-12-15 | ![Star](https://img.shields.io/github/stars/GuanhuaJi/oxe-auge?style=social&label=Star) [Github](https://github.com/GuanhuaJi/oxe-auge) | |
| [**RoboCOIN: An Open-Sourced Bimanual Robotic Data COllection for INtegrated Manipulation**](https://flagopen.github.io/RoboCOIN/robocoin.pdf) | - | 2025-11 | ![Star](https://img.shields.io/github/stars/FlagOpen/RoboCOIN?style=social&label=Star) [Github](https://github.com/FlagOpen/RoboCOIN) | |
| [**A Humanoid Visual-Tactile-Action Dataset for Contact-Rich Manipulation**](https://arxiv.org/abs/2510.25725) | arXiv | 2025-10-28 | - | |
| [**Humanoid Everyday: A Comprehensive Robotic Dataset for Open-World Humanoid Manipulation**](https://arxiv.org/abs/2510.08807) | arXiv | 2025-10-09 | ![Star](https://img.shields.io/github/stars/ausbxuse/Humanoid-Everyday?style=social&label=Star) [Github](https://github.com/ausbxuse/Humanoid-Everyday) | |
| [**FastUMI-100K: Advancing Data-driven Robotic Manipulation with a Large-scale UMI-style Datasetn**](https://arxiv.org/abs/2510.08022) | arXiv | 2025-10-09 | ![Star](https://img.shields.io/github/stars/MrKeee/FastUMI-100K?style=social&label=Star) [Github](https://github.com/MrKeee/FastUMI-100K) | |
| [**AIRoA MoMa Dataset: A Large-Scale Hierarchical Dataset for Mobile Manipulation**](https://arxiv.org/abs/2509.25032) | arXiv | 2025-09-29 | [Dataset](https://huggingface.co/datasets/airoa-org/airoa-moma) | |
| [**RoboFAC: A Comprehensive Framework for Robotic Failure Analysis and Correction**](https://arxiv.org/abs/2505.12224) | arXiv | 2025-05-18 | - | |
| [**AgiBot World Colosseo: A Large-scale Manipulation Platform for Scalable and Intelligent Embodied Systems**](https://arxiv.org/abs/2503.06669) | IROS 2025 | 2025-03-09 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/AgiBot-World?style=social&label=Star) [Github](https://github.com/OpenDriveLab/AgiBot-World) |
| [**RoboMIND: Benchmark on Multi-embodiment Intelligence Normative Data for Robot Manipulation**](https://arxiv.org/abs/2412.13877) | arXiv | 2024-12-18 | ![Star](https://img.shields.io/github/stars/x-humanoid-robomind/x-humanoid-robomind.github.io?style=social&label=Star) [Github](https://github.com/x-humanoid-robomind/x-humanoid-robomind.github.io) |
| [ARIO: **All Robots in One: A New Standard and Unified Dataset for Versatile, General-Purpose Embodied Agents**](https://arxiv.org/abs/2408.10899) | arXiv | 2024-08-20 | [Dataset](https://openi.pcl.ac.cn/ARIO/ARIO_Dataset) | |
| [**DROID: A Large-Scale In-The-Wild Robot Manipulation Dataset**](https://arxiv.org/abs/2403.12945) | RSS 2024 | 2024-03-19 | ![Star](https://img.shields.io/github/stars/droid-dataset/droid_policy_learning?style=social&label=Star) [Github](https://github.com/droid-dataset/droid_policy_learning) | |
| [**Open X-Embodiment: Robotic Learning Datasets and RT-X Models**](https://arxiv.org/abs/2310.08864) | ICRA 2024 | 2023-10-13 | ![Star](https://img.shields.io/github/stars/google-deepmind/open_x_embodiment?style=social&label=Star) [Github](https://github.com/google-deepmind/open_x_embodiment) | |
| [**RoboAgent: Generalization and Efficiency in Robot Manipulation via Semantic Augmentations and Action Chunking**](https://arxiv.org/abs/2309.01918) | ICRA 2024 | 2024-09-05 | ![Star](https://img.shields.io/github/stars/robopen/roboagent?style=social&label=Star) [Github](https://github.com/robopen/roboagent) | |
| [**BridgeData V2: A Dataset for Robot Learning at Scale**](https://arxiv.org/abs/2308.12952) | CoRL 2023 | 2023-08-24 | ![Star](https://img.shields.io/github/stars/rail-berkeley/bridge_data_v2?style=social&label=Star) [Github](https://github.com/rail-berkeley/bridge_data_v2) | |
| [**RH20T: A Comprehensive Robotic Dataset for Learning Diverse Skills in One-Shot**](https://arxiv.org/abs/2307.00595) | RSSW 2023 | 2023-07-02 | [Project](https://rh20t.github.io/) | |
| [**RT-1: Robotics Transformer for Real-World Control at Scale**](https://arxiv.org/abs/2212.06817) | RSS 2023 | 2022-12-13 | [Dataset](https://console.cloud.google.com/storage/browser/gresearch/rt-1-data-release?inv=1&invt=Ab39vQ) | |
| [**BC-Z: Zero-Shot Task Generalization with Robotic Imitation Learning**](https://arxiv.org/abs/2202.02005) | CoRL 2021 | 2022-02-04 | [Dataset](https://www.kaggle.com/datasets/google/bc-z-robot) | |
| [**Bridge Data: Boosting Generalization of Robotic Skills with Cross-Domain Datasets**](https://arxiv.org/abs/2109.13396) | CoRL 2018 | 2021-09-27 | ![Star](https://img.shields.io/github/stars/yanlai00/bridge_data_imitation_learning?style=social&label=Star) [Github](https://github.com/yanlai00/bridge_data_imitation_learning) | |
| [**Multiple Interactions Made Easy (MIME): Large Scale Demonstrations Data for Imitation**](https://arxiv.org/abs/1810.07121) | CoRL 2018 | 2018-10-16 | - | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

<!-- ------- 2.6 - Embodied QA and Affordance Datasets ------- -->
### Embodied QA and Affordance Datasets
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**VideoAfford: Grounding 3D Affordance from Human-Object-Interaction Videos via Multimodal Large Language Model**](https://arxiv.org/abs/2602.09638) | arXiv | 2026-02-10 | - | |
| [**Seeing Across Views: Benchmarking Spatial Reasoning of Vision-Language Models in Robotic Scenes**](https://arxiv.org/abs/2510.19400) | arXiv | 2025-10-22 | ![Star](https://img.shields.io/github/stars/microsoft/MV-RoboBench?style=social&label=Star) [Github](https://github.com/microsoft/MV-RoboBench) | |
| [**PhysToolBench: Benchmarking Physical Tool Understanding for MLLMs**](https://arxiv.org/abs/2510.09507) | arXiv | 2025-10-10 | ![Star](https://img.shields.io/github/stars/EnVision-Research/PhysToolBench?style=social&label=Star) [Github](https://github.com/EnVision-Research/PhysToolBench) | |
| [**Point-It-Out: Benchmarking Embodied Reasoning for Vision Language Models in Multi-Stage Visual Grounding**](https://arxiv.org/abs/2509.25794) | arXiv | 2025-09-30 | ![Star](https://img.shields.io/github/stars/xavihart/PIO?style=social&label=Star) [Github](https://github.com/xavihart/PIO) | |
| [**How Good are Foundation Models in Step-by-Step Embodied Reasoning?**](https://arxiv.org/abs/2509.15293) | arXiv | 2025-09-18 | ![Star](https://img.shields.io/github/stars/mbzuai-oryx/FoMER-Bench?style=social&label=Star) [Github](https://github.com/mbzuai-oryx/FoMER-Bench) | |
| [**RoboRefer: Towards Spatial Referring with Reasoning in Vision-Language Models for Robotics**](https://arxiv.org/abs/2506.04308) | NeurIPS 2025 | 2025-06-28 | ![Star](https://img.shields.io/github/stars/Zhoues/RoboRefer?style=social&label=Star) [Github](https://github.com/Zhoues/RoboRefer) |  |
| [**OmniEAR: Benchmarking Agent Reasoning in Embodied Tasks**](https://arxiv.org/abs/2508.05614) | arXiv | 2024-08-07 | ![Star](https://img.shields.io/github/stars/ZJU-REAL/OmniEmbodied?style=social&label=Star) [Github](https://github.com/ZJU-REAL/OmniEmbodied) | |
| [**PAC Bench: Do Foundation Models Understand Prerequisites for Executing Manipulation Policies?**](https://arxiv.org/abs/2506.23725) | arXiv | 2024-06-30 | [Project](https://pacbench.github.io/) | |
| [**Robo2VLM: Visual Question Answering from Large-Scale In-the-Wild Robot Manipulation Datasets**](https://arxiv.org/abs/2505.15517) | arXiv | 2024-05-21 | [Huggingface](https://huggingface.co/datasets/keplerccc/Robo2VLM-1) | |
| [**PointArena: Probing Multimodal Grounding Through Language-Guided Pointing**](https://arxiv.org/abs/2505.09990) | arXiv | 2024-05-15 | ![Star](https://img.shields.io/github/stars/pointarena/pointarena?style=social&label=Star) [Github](https://github.com/pointarena/pointarena) | |
| [**ManipBench: Benchmarking Vision-Language Models for Low-Level Robot Manipulation**](https://arxiv.org/abs/2505.09698) | arXiv | 2024-05-14 | [Project](https://manipbench.github.io/) | |
| [**RoboAfford++: A Generative AI-Enhanced Dataset for Multimodal Affordance Learning in Robotic Manipulation and Navigation**](https://arxiv.org/abs/2511.12436) | IROSW 2025 | 2025-11-16 | ![Star](https://img.shields.io/github/stars/tyb197/RoboAfford?style=social&label=Star) [Github](https://github.com/tyb197/RoboAfford) | |
| [**ManipVQA: Injecting Robotic Affordance and Physically Grounded Information into Multi-Modal Large Language Models**](https://arxiv.org/abs/2403.11289) | IROS 2024 | 2024-03-17 | ![Star](https://img.shields.io/github/stars/SiyuanHuang95/ManipVQA?style=social&label=Star) [Github](https://github.com/SiyuanHuang95/ManipVQA) | |
| [**OpenEQA: Embodied Question Answering in the Era of Foundation Models**](https://open-eqa.github.io/assets/pdfs/paper.pdf) | CVPR 2024 | 2024 | ![Star](https://img.shields.io/github/stars/facebookresearch/open-eqa?style=social&label=Star) [Github](https://github.com/facebookresearch/open-eqa) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

<!-- ------- 2.7 - Human and Robotic Video Datasets ------- -->
### Human and Robotic Video Datasets
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Wow, wo, val! A Comprehensive Embodied World Model Evaluation Turing Test**](https://arxiv.org/abs/2601.04137) | arXiv | 2026-01-07 | - | |
| [**Hoi! -- A Multimodal Dataset for Force-Grounded, Cross-View Articulated Manipulation**](https://arxiv.org/abs/2512.04884) | arXiv | 2025-12-04 | ![Star](https://img.shields.io/github/stars/showlab/RobotSeg?style=social&label=Star) [Github](https://github.com/showlab/RobotSeg) | |
| [**RobotSeg: A Model and Dataset for Segmenting Robots in Image and Video**](https://arxiv.org/abs/2511.22950) | arXiv | 2025-11-28 | ![Star](https://img.shields.io/github/stars/showlab/RobotSeg?style=social&label=Star) [Github](https://github.com/showlab/RobotSeg) | |
| [**OmniWorld: A Multi-Domain and Multi-Modal Dataset for 4D World Modeling**](https://arxiv.org/abs/2509.12201) | arXiv | 2025-09-15 | ![Star](https://img.shields.io/github/stars/yangzhou24/OmniWorld?style=social&label=Star) [Github](https://github.com/yangzhou24/OmniWorld) | |
| [**OpenEgo: A Large-Scale Multimodal Egocentric Dataset for Dexterous Manipulation**](https://arxiv.org/abs/2509.05513) | arXiv | 2025-09-05 | ![Star](https://img.shields.io/github/stars/physicalinc/openego?style=social&label=Star) [Github](https://github.com/physicalinc/openego) | |



<!-- ------- 3 - Techniques ------- -->
## 🛠️ Awesome Techniques

### Tutorial
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Robot Learning: A Tutorial**](https://arxiv.org/abs/2510.12403) | arXiv | 2025-10-14 | ![Star](https://img.shields.io/github/stars/huggingface/lerobot?style=social&label=Star) [Github](https://github.com/huggingface/lerobot) | |

### Github Repo
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| **Awesome-Dual-System-VLA: [OpenHelix: A Short Survey, Empirical Analysis, and Open-Source Dual-System VLA Model for Robotic Manipulation](https://arxiv.org/abs/2505.03912)** | - | 2025-05-06 | ![Star](https://img.shields.io/github/stars/OpenHelix-robot/awesome-dual-system-vla?style=social&label=Star) [Github](https://github.com/OpenHelix-robot/awesome-dual-system-vla) | |
| **Awesome-Implicit-NeRF-Robotics: [Neural Fields in Robotics: A Survey](https://arxiv.org/abs/2410.20220)** | - | 2024-10-26 | ![Star](https://img.shields.io/github/stars/zubair-irshad/Awesome-Implicit-NeRF-Robotics?style=social&label=Star) [Github](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics) | |
| **Awesome-Robotics-3D** | - | 2024-08-13 | ![Star](https://img.shields.io/github/stars/zubair-irshad/Awesome-Robotics-3D?style=social&label=Star) [Github](https://github.com/zubair-irshad/Awesome-Robotics-3D) | |
| **Awesome-Video-Robotic-Papers** | - | 2024-06-18 | ![Star](https://img.shields.io/github/stars/H-Freax/Awesome-Video-Robotic-Papers?style=social&label=Star) [Github](https://github.com/H-Freax/Awesome-Video-Robotic-Papers) | |
| **awesome-humanoid-learning** | - | 2024-01-16 | ![Star](https://img.shields.io/github/stars/jonyzhang2023/awesome-humanoid-learning?style=social&label=Star) [Github](https://github.com/jonyzhang2023/awesome-humanoid-learning) | |
| **Awesome-Robotics-Foundation-Models: [Foundation Models in Robotics: Applications, Challenges, and the Future](https://arxiv.org/abs/2312.07843)** | - | 2023-12-13 | ![Star](https://img.shields.io/github/stars/robotics-survey/Awesome-Robotics-Foundation-Models?style=social&label=Star) [Github](https://github.com/robotics-survey/Awesome-Robotics-Foundation-Models/tree/main) | |
| **Awesome-Generalist-Robots-via-Foundation-Models: [Neural Fields in Robotics: A Survey](https://arxiv.org/abs/2312.08782)** | - | 2023-06-20 | ![Star](https://img.shields.io/github/stars/JeffreyYH/Awesome-Generalist-Robots-via-Foundation-Models?style=social&label=Star) [Github](https://github.com/JeffreyYH/Awesome-Generalist-Robots-via-Foundation-Models) | |
| **Awesome-LLM-Robotics** | - | 2022-08-12 | ![Star](https://img.shields.io/github/stars/GT-RIPL/Awesome-LLM-Robotics?style=social&label=Star) [Github](https://github.com/GT-RIPL/Awesome-LLM-Robotics) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>



## ✨ Citation

If you find this repository useful, please consider citing:
```
@article{bai2025towards,
  title={Towards a Unified Understanding of Robot Manipulation: A Comprehensive Survey},
  author={Bai, Shuanghao and Song, Wenxuan and Chen, Jiayi and Ji, Yuheng and Zhong, Zhide and Yang, Jin and Zhao, Han and Zhou, Wanqi and Zhao, Wei and Li, Zhe and Ding, Pengxiang and Chi, Cheng and Li, Haoang and Xu, Chang and Zheng, Xiaolong and Wang, Donglin and Zhang, Shanghang and Chen, Badong},
  journal={arXiv preprint arXiv:2510.10903},
  year={2025}
}

@article{bai2025embodied,
  title={Embodied Robot Manipulation in the Era of Foundation Models: Planning and Learning Perspectives},
  author={Bai, Shuanghao and Song, Wenxuan and Chen, Jiayi and Ji, Yuheng and Zhong, Zhide and Yang, Jin and Zhao, Han and Zhou, Wanqi and Li, Zhe and Ding, Pengxiang and others},
  journal={arXiv preprint arXiv:2512.22983},
  year={2025}
}
```
