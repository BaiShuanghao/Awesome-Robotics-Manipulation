<h2 id="table-of-contents">🏠 Table of Contents</h2>

- Bottlenecks
    - [Data Collection and Utilization](#data-collection-and-utilization)
        - [Data Collection](#data-collection)
            - [Data Collection strategy](#data-collection-strategy)
            - [Human Teleoperation](#human-teleoperation)
            - [Human-in-the-Loop Enhancement](#human-in-the-loop-enhancement)
            - [Automatic Generation](#automatic-generation)
            - [Crowdsourcing](#crowdsourcing)
        - [Data Utilization](#data-utilization)
            - [Data Expansion](#data-expansion)
            - [Data Reweighting](#data-reweighting)
            - [Data Selection](#data-selection)
            - [Data Retrieval](#data-retrieval)
            - [Data Augmentation](#data-augmentation)
    - [Generalization](#generalization)
        - [Task Generalization](#task-generalization)
            - [Compositional Generalization](#compositional-generalization)
            - [Cross-Embodiment Generalization](#cross-embodiment-generalization)
            - [Long-horizon Generalization](#long-horizon-generalization)
            - [Few-shot Learning](#few-shot-learning)
            - [Meta Learning](#meta-learning)
            - [Lifelong/Continual/Incremental Learning](#lifelongcontinualincremental-learning)
            - [Test-Time Adaptation](#test-time-adaptation)
        - [Environment Generalization](#environment-generalization)
            - [Sim2Real or Real2Sim2Real Generalization](#sim2real-or-real2sim2real-generalization)
            - [SE(3)/SIM(3)-Equivariance/View Changes](#se3sim3-equivarianceview-changes)
            - [Lighting/background/distractor Changes](#lightingbackgrounddistractor-changes)
        - [Cross-Embodiment Generalization](#cross-embodiment-generalization)
    - [Agent](#agent)
    - [Human-Robot Interaction and Collaboration](#human-robot-interaction-and-collaboration)
    - [Safety](#safety)



## Data Collection and Utilization

<!-- Data Collection -->
<div align="center">

### <i>Data Collection</i>

</div>

### Data Collection strategy
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**EgoGuide: Egocentric Guidance for Efficient Robot-Free Demonstration Collection and Learning**](https://arxiv.org/abs/2606.14665) | arXiv | 2026-06-12 | [Project](https://silicx.github.io/EgoGuide/) |  |
| [**Towards Generalizable Robotic Data Flywheel: High-Dimensional Factorization and Composition**](https://arxiv.org/abs/2603.25583) | arXiv | 2026-03-26 | [Project](https://f-acil.github.io/) |  |
| [**Efficient and Reliable Teleoperation through Real-to-Sim-to-Real Shared Autonomy**](https://arxiv.org/abs/2603.17016) | arXiv | 2026-03-17 | ![Star](https://img.shields.io/github/stars/shuosha/Residual_Copilot?style=social&label=Star) [GitHub](https://github.com/shuosha/Residual_Copilot) |  |
| [**Bootstrapping Imitation Learning for Long-horizon Manipulation via Hierarchical Data Collection Space**](https://arxiv.org/abs/2505.17389) | arXiv | 2025-05-23 | [Project](https://hd-space-robotics.github.io/) |  |
| [**Adversarial Data Collection: Human-Collaborative Perturbations for Efficient and Robust Robotic Imitation Learning**](https://arxiv.org/abs/2503.11646) | arXiv | 2025-03-14 | [Project](https://sites.google.com/view/adc-robot) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Human Teleoperation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Simulation_ |
| [**RynnWorld-Teleop: An Action-Conditioned World Model for Digital Teleoperation**](https://arxiv.org/abs/2607.06558) | arXiv | 2026-07-07 | ![Star](https://img.shields.io/github/stars/alibaba-damo-academy/RynnWorld-Teleop?style=social&label=Star) [GitHub](https://github.com/alibaba-damo-academy/RynnWorld-Teleop) |  |
| [**Lucid-XR: An Extended-Reality Data Engine for Robotic Manipulation**](https://arxiv.org/abs/2605.00244) | CoRL 2025 | 2026-05-30 | [Project](https://lucidxr.github.io/) |  |
| _UMI_ |
| [**WT-UMI: Tactile-based Whole-Body Manipulation via Force-Supervised Contact-Aware Planning**](https://arxiv.org/abs/2606.13232) | arXiv | 2026-06-11 | [Project](https://wt-umi.github.io/WTUMI/) |  |
| [**UMI-Bench 1.0: An Open and Reproducible Real-World Benchmark for Tabletop Robotic Manipulation with UMI Data**](https://arxiv.org/abs/2606.10382) | arXiv | 2026-06-09 | [Project](https://umibenchmark.github.io/) |  |
| [**RealDexUMI: A Wearable Universal Manipulation Interface for Dexterous Robot Learning**](https://arxiv.org/abs/2606.06033) | arXiv | 2026-06-04 | [Project](https://research.beingbeyond.com/realdexumi) |  |
| [**XRZero-G0: Pushing the Frontier of Dexterous Robotic Manipulation with Interfaces, Quality and Ratios**](https://arxiv.org/abs/2604.13001) | arXiv | 2026-04-14 | [Project](https://github.com/X-Square-Robot/XRZero-G0) |  |
| [**OmniUMI: Towards Physically Grounded Robot Learning via Human-Aligned Multimodal Interaction**](https://arxiv.org/abs/2604.10647) | arXiv | 2026-04-12 | - |  |
| [**TAMEn: Tactile-Aware Manipulation Engine for Closed-Loop Data Collection in Contact-Rich Tasks**](https://arxiv.org/abs/2604.07335) | arXiv | 2026-04-08 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/TAMEn?style=social&label=Star) [GitHub](https://github.com/OpenDriveLab/TAMEn) |  |
| [**FeasibleCap: Real-Time Embodiment Constraint Guidance for In-the-Wild Robot Demonstration Collection**](https://arxiv.org/abs/2603.07580) | arXiv | 2026-03-08 | - |  |
| [**In-the-Wild Compliant Manipulation with UMI-FT**](https://arxiv.org/abs/2601.09988) | arXiv | 2026-01-15 | ![Star](https://img.shields.io/github/stars/real-stanford/UMI-FT?style=social&label=Star) [GitHub](https://github.com/real-stanford/UMI-FT) |  |
| [**ActiveUMI: Robotic Manipulation with Active Perception from Robot-Free Human Demonstrations**](https://arxiv.org/abs/2510.01607) | arXiv | 2025-10-02 | [Project](https://activeumi.github.io/) |  |
| [**Universal Manipulation Interface: In-The-Wild Robot Teaching Without In-The-Wild Robots**](https://arxiv.org/abs/2402.10329) | RSS 2024 | 2024-02-15 | ![Star](https://img.shields.io/github/stars/real-stanford/universal_manipulation_interface?style=social&label=Star) [GitHub](https://github.com/real-stanford/universal_manipulation_interface) | |
| _Kinematically Matched Master Arm / Exoskeletons_ |
| [**MEVION: Low-Cost Open-Source Data Collection System for Powerful and High-Speed Dual-Arm Manipulation**](https://arxiv.org/abs/2607.17970) | RA-P 2026 | 2026-07-20 | ![Star](https://img.shields.io/github/stars/haraduka/mevion?style=social&label=Star) [GitHub](https://github.com/haraduka/mevion) |  |
| [**AssistDLO: Assistive Teleoperation for Deformable Linear Object Manipulation**](https://arxiv.org/abs/2605.06323) | arXiv | 2026-05-07 | - |  |
| [**TriPilot-FF: Coordinated Whole-Body Teleoperation with Force Feedback**](https://arxiv.org/abs/2602.09888) | arXiv | 2026-02-10 | ![Star](https://img.shields.io/github/stars/Jeong-zju/zeno-wholebody-teleop?style=social&label=Star) [GitHub](https://github.com/Jeong-zju/zeno-wholebody-teleop) |  |
| [**ACE-F: A Cross Embodiment Foldable System with Force Feedback for Dexterous Teleoperation**](https://arxiv.org/abs/2511.20887) | arXiv | 2025-11-25 | ![Star](https://img.shields.io/github/stars/ACEFoldable/acef_software?style=social&label=Star) [GitHub](https://github.com/ACEFoldable/acef_software) |  |
| [**U-ARM: Ultra Low-Cost General Teleoperation Interface for Robot Manipulation**](https://arxiv.org/abs/2509.02437) | arXiv | 2025-09-02 | ![Star](https://img.shields.io/github/stars/MINT-SJTU/LeRobot-Anything-U-Arm?style=social&label=Star) [GitHub](https://github.com/MINT-SJTU/LeRobot-Anything-U-Arm) |  |
| [**Fast Bilateral Teleoperation and Imitation Learning Using Sensorless Force Control via Accurate Dynamics Model**](https://arxiv.org/abs/2507.06174) | arXiv | 2025-07-08 | - |  |
| [**AirExo-2: Scaling up Generalizable Robotic Imitation Learning with Low-Cost Exoskeletons**](https://arxiv.org/abs/2503.03081) | ICLRW 2025 | 2025-03-05 | [Project](https://airexo.tech/airexo2/) |  |
| [**ALPHA-α and Bi-ACT Are All You Need: Importance of Position and Force Information/Control for Imitation Learning of Unimanual and Bimanual Robotic Manipulation with Low-Cost System**](https://arxiv.org/abs/2411.09942) | IEEE Access 2025 | 2024-11-15 | [Project](https://mertcookimg.github.io/alpha-biact/) |  |
| [**GELLO: A General, Low-Cost, and Intuitive Teleoperation Framework for Robot Manipulators**](https://arxiv.org/abs/2309.13037) | IROS 2024 | 2023-09-22 | ![Star](https://img.shields.io/github/stars/wuphilipp/gello_software?style=social&label=Star) [GitHub](https://github.com/wuphilipp/gello_software) |  |
| [**AirExo: Low-Cost Exoskeletons for Learning Whole-Arm Manipulation in the Wild**](https://arxiv.org/abs/2309.14975) | ICRA 2024 | 2023-09-26 | ![Star](https://img.shields.io/github/stars/AirExo/collector?style=social&label=Star) [GitHub](https://github.com/AirExo/collector) | |
| [**Training Robots without Robots: Deep Imitation Learning for Master-to-Robot Policy Transfer**](https://arxiv.org/abs/2202.09574) | RA-L 2023 | 2022-02-19 | - |  |
| _VR-Arms_ |
| [**RoboPocket: Improve Robot Policies Instantly with Your Phone**](https://arxiv.org/abs/2603.05504) | arXiv | 2026-03-05 | [Project](https://robo-pocket.github.io/) |  |
| [**A Multimodal Data Collection Framework for Dialogue-Driven Assistive Robotics to Clarify Ambiguities: A Wizard-of-Oz Pilot Study**](https://arxiv.org/abs/2601.16870) | arXiv | 2026-01-23 | - |  |
| [**LeVR: A Modular VR Teleoperation Framework for Imitation Learning in Dexterous Manipulation**](https://arxiv.org/abs/2509.14349) | arXiv | 2025-09-17 | ![Star](https://img.shields.io/github/stars/wengmister/LeFranX?style=social&label=Star) [GitHub](https://github.com/wengmister/LeFranX) |  |
| [**BEAVR: Bimanual, multi-Embodiment, Accessible, Virtual Reality Teleoperation System for Robots**](https://arxiv.org/abs/2508.09606) | ICCR 2025 | 2025-08-13 | ![Star](https://img.shields.io/github/stars/ARCLab-MIT/BEAVR-Bot?style=social&label=Star) [GitHub](https://github.com/ARCLab-MIT/BEAVR-Bot) |  |
| [**XRoboToolkit: A Cross-Platform Framework for Robot Teleoperation**](https://arxiv.org/abs/2508.00097) | arXiv | 2025-07-31 | [GitHub](https://github.com/XR-Robotics) |  |
| [**Dexterous Teleoperation of 20-DoF ByteDexter Hand via Human Motion Retargeting**](https://arxiv.org/abs/2507.03227) | arXiv | 2025-07-04 | [Project](https://byte-dexter.github.io/) |  |
| [**TypeTele: Releasing Dexterity in Teleoperation by Dexterous Manipulation Types**](https://arxiv.org/abs/2507.01857) | CoRL 2025 | 2025-07-02 | [Project](https://isee-laboratory.github.io/TypeTele/) |
| [**mimic-one: a Scalable Model Recipe for General Purpose Robot Dexterity**](https://arxiv.org/abs/2506.11916) | CoRLW 2025 | 2025-06-13 | [Project](https://mimicrobotics.github.io/mimic-one/) |  |
| [**AVR: Active Vision-Driven Robotic Precision Manipulation with Viewpoint and Focal Length Optimization**](https://arxiv.org/abs/2503.01439) | ICRA 2026 | 2025-03-03 | [Project](https://avr-robot.github.io/) |  |
| [**ARCap: Collecting High-quality Human Demonstrations for Robot Learning with Augmented Reality Feedback**](https://arxiv.org/abs/2410.08464) | ICRA 2025 | 2024-10-11 | ![Star](https://img.shields.io/github/stars/Ericcsr/ARCap?style=social&label=Star) [GitHub](https://github.com/Ericcsr/ARCap) |  |
| [**Bunny-VisionPro: Real-Time Bimanual Dexterous Teleoperation for Imitation Learning**](https://arxiv.org/abs/2407.03162) | IROS 2025 | 2024-07-03 | ![Star](https://img.shields.io/github/stars/Dingry/BunnyVisionPro?style=social&label=Star) [GitHub](https://github.com/Dingry/BunnyVisionPro) |  |
| [RDP: **Reactive Diffusion Policy: Slow-Fast Visual-Tactile Policy Learning for Contact-Rich Manipulation**](https://arxiv.org/abs/2503.02881) | RSS 2025 | 2025-03-04 | ![Star](https://img.shields.io/github/stars/xiaoxiaoxh/reactive_diffusion_policy?style=social&label=Star) [GitHub](https://github.com/xiaoxiaoxh/reactive_diffusion_policy) | |
| [**Active Vision Might Be All You Need: Exploring Active Vision in Bimanual Robotic Manipulation**](https://arxiv.org/abs/2409.17435) | CoRLW 2024 | 2024-09-26 | ![Star](https://img.shields.io/github/stars/soltanilara/av-aloha?style=social&label=Star) [GitHub](https://github.com/soltanilara/av-aloha) | Bi, VR |
| [**OPEN TEACH: A Versatile Teleoperation System for Robotic Manipulation**](https://arxiv.org/abs/2403.07870) | CoRL 2024 | 2024-03-12 | ![Star](https://img.shields.io/github/stars/aadhithya14/Open-Teach?style=social&label=Star) [GitHub](https://github.com/aadhithya14/Open-Teach) | |
| [**TeleMoMa: A Modular and Versatile Teleoperation System for Mobile Manipulation**](https://arxiv.org/abs/2403.07869) | ICRAW 2024 | 2024-03-12 | ![Star](https://img.shields.io/github/stars/UT-Austin-RobIn/telemoma?style=social&label=Star) [GitHub](https://github.com/UT-Austin-RobIn/telemoma) | |
| [**Deep Imitation Learning for Complex Manipulation Tasks from Virtual Reality Teleoperation**](https://arxiv.org/abs/1710.04615) | ICRA 2018 | 2017-10-12 | - |  |
| _VR-Humanoids_ |
| [**EgoKit: Towards Unified Low-Cost Egocentric Data Collection with Heterogeneous Devices**](https://arxiv.org/abs/2605.16797) | arXiv | 2026-05-16 | [Project](https://www.chuange.org/papers/EgoKit.html) |  |
| [**OmniClone: Engineering a Robust, All-Rounder Whole-Body Humanoid Teleoperation System**](https://arxiv.org/abs/2603.14327) | arXiv | 2026-03-15 | - |  |
| [**A Closed-Form Geometric Retargeting Solver for Upper Body Humanoid Robot Teleoperation**](https://arxiv.org/abs/2602.01632) | arXiv | 2026-02-02 | [Project](https://sew-mimic.com/) |  |
| [**Coordinated Humanoid Manipulation with Choice Policies**](https://arxiv.org/abs/2512.25072) | arXiv | 2025-12-31 | ![Star](https://img.shields.io/github/stars/x-robotics-lab/modular-teleop?style=social&label=Star) [GitHub](https://github.com/x-robotics-lab/modular-teleop) |  |
| [**TWIST2: Scalable, Portable, and Holistic Humanoid Data Collection System**](https://arxiv.org/abs/2511.02832) | arXiv | 2025-11-04 | ![Star](https://img.shields.io/github/stars/amazon-far/TWIST2?style=social&label=Star) [GitHub](https://github.com/amazon-far/TWIST2) |  |
| _Exoskeleton-Dexterous_ |
| [**DexUMI: Using Human Hand as the Universal Manipulation Interface for Dexterous Manipulation**](https://arxiv.org/abs/2505.21864) | RSSW 2025 | 2025-05-28 | ![Star](https://img.shields.io/github/stars/real-stanford/DexUMI?style=social&label=Star) [GitHub](https://github.com/real-stanford/DexUMI) |  |
| [**DexEXO: A Wearability-First Dexterous Exoskeleton for Operator-Agnostic Demonstration and Learning**](https://arxiv.org/abs/2603.17323) | arXiv | 2026-03-18 | [Project](https://dexexo-research.github.io/) |  |
| _Tactile-Dexterous_ |
| [**DexTeleop-0: Force-Aware Bimanual Dexterous Teleoperation with Ego-Centric Perception towards Shared Autonomy**](https://arxiv.org/abs/2606.23431) | arXiv | 2026-06-22 | [Project](https://henryhcliu.github.io/dexteleop-0/) | V, T |
| [**FlexiTac: A Low-Cost, Open-Source, Scalable Tactile Sensing Solution for Robotic Systems**](https://arxiv.org/abs/2604.28156) | arXiv | 2026-04-30 | ![Star](https://img.shields.io/github/stars/FlexiTac/FlexiTac_Hardware_Repo?style=social&label=Star) [GitHub](https://github.com/FlexiTac/FlexiTac_Hardware_Repo) | V, T |
| [**DexViTac: Collecting Human Visuo-Tactile-Kinematic Demonstrations for Contact-Rich Dexterous Manipulation**](https://arxiv.org/abs/2603.17851) | arXiv | 2026-03-18 | ![Star](https://img.shields.io/github/stars/xitong-c/DexViTac_Code?style=social&label=Star) [GitHub](https://github.com/xitong-c/DexViTac_Code) | V, T |
| [**FreeTacMan: Robot-free Visuo-Tactile Data Collection System for Contact-rich Manipulation**](https://arxiv.org/abs/2506.01941) | ICRA 2026 | 2025-06-02 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/FreeTacMan?style=social&label=Star) [GitHub](https://github.com/OpenDriveLab/FreeTacMan) |
| _EMG-Dexterous_ |
| [**DexEMG: Towards Dexterous Teleoperation System via EMG2Pose Generalization**](https://arxiv.org/abs/2603.05861) | arXiv | 2026-03-06 | - |  |
| _Mocap_ |
| [**HumDex: Humanoid Dexterous Manipulation Made Easy**](https://arxiv.org/abs/2603.12260) | arXiv | 2026-03-12 | ![Star](https://img.shields.io/github/stars/physical-superintelligence-lab/humdex?style=social&label=Star) [GitHub](https://github.com/physical-superintelligence-lab/humdex) |  |
| [**Prometheus: Universal, Open-Source Mocap-Based Teleoperation System with Force Feedback for Dataset Collection in Robot Learning**](https://arxiv.org/abs/2510.01023) | arXiv | 2025-10-01 | ![Star](https://img.shields.io/github/stars/Eterwait/Prometheus?style=social&label=Star) [GitHub](https://github.com/Eterwait/Prometheus) |  |
| _Glove_ |
| [**Towards Human-level Dexterous Teleoperation**](https://arxiv.org/abs/2607.11481) | arXiv | 2026-07-13 | [Project](https://bigai-dex.github.io/blog/teledexter/) |  |
| [**Feel Robot Feels: Tactile Feedback Array Glove for Dexterous Manipulation**](https://arxiv.org/abs/2603.28542) | arXiv | 2026-03-30 | [Project](https://trap-1.github.io/TAG.github.io/) |  |
| [**ExoStart: Efficient Learning for Dexterous Manipulation with Sensorized Exoskeleton Demonstrations**](https://arxiv.org/abs/2506.11775) | arXiv | 2025-06-13 | [Project](https://sites.google.com/view/exostart) | Exoskeleton Gloves |
| [**DexCap: Scalable and Portable Mocap Data Collection System for Dexterous Manipulation**](https://arxiv.org/abs/2403.07788) | CoRL 2024 | 2024-03-12 | ![Star](https://img.shields.io/github/stars/j96w/DexCap?style=social&label=Star) [GitHub](https://github.com/j96w/DexCap) | |
| _Glasses_ |
| [**Dexterity from Smart Lenses: Multi-Fingered Robot Manipulation with In-the-Wild Human Demonstrations**](https://arxiv.org/abs/2511.16661) | arXiv | 2025-11-20 | ![Star](https://img.shields.io/github/stars/irmakguzey/AINA?style=social&label=Star) [GitHub](https://github.com/irmakguzey/AINA) |  |
| [**EgoMimic: Scaling Imitation Learning via Egocentric Video**](https://arxiv.org/abs/2410.24221) | CoRLW 2024 | 2024-10-31 | ![Star](https://img.shields.io/github/stars/SimarKareer/EgoMimic?style=social&label=Star) [GitHub](https://github.com/SimarKareer/EgoMimic) | Bi, Aria Glasses |
| _Phone Stand or Phone_ |
| [**Phone2Act: A Low-Cost, Hardware-Agnostic Teleoperation System for Scalable VLA Data Collection**](https://arxiv.org/abs/2605.01948) | arXiv | 2026-05-03 | - |  |
| [**TeleDex: Accessible Dexterous Teleoperation**](https://arxiv.org/abs/2603.17065) | arXiv | 2026-03-17 | [Project](https://orayyan.com/teledex) |  |
| [**AoE: Always-on Egocentric Human Video Collection for Embodied AI**](https://arxiv.org/abs/2602.23893) | arXiv | 2026-02-27 | - |  |
| _Reacher-grabber Tools_ |
| [**Visual Imitation Made Easy**](https://arxiv.org/abs/2008.04899) | CoRL 2021 | 2020-8-11 | ![Star](https://img.shields.io/github/stars/sarahisyoung/Visual-Imitation-Made-Easy?style=social&label=Star) [GitHub](https://github.com/sarahisyoung/Visual-Imitation-Made-Easy) |  |
| _System_ |
| [**UniBiDex: A Unified Teleoperation Framework for Robotic Bimanual Dexterous Manipulation**](https://arxiv.org/abs/2601.04629) | ROBIO 2025 | 2026-01-08 | - |  |
| [**Open TeleDex: A Hardware-Agnostic Teleoperation System for Imitation Learning based Dexterous Manipulation**](https://arxiv.org/abs/2510.14771) | arXiv | 2025-10-16 | - |  |
| [**Kaiwu: A Multimodal Manipulation Dataset and Framework for Robot Learning and Human-Robot Interaction**](https://arxiv.org/abs/2503.05231) | RA-L 2025 | 2025-03-07 | - |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Human-in-the-Loop Enhancement
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**AutoIntervene: Calibrated Intervention for Action-Chunking Imitation Learning Policies**](https://arxiv.org/abs/2608.07065) | arXiv | 2026-08-07 | [Project](https://aus.bot/research/autointervene/) |  |
| [**HapCompass: A Rotational Haptic Device for Contact-Rich Robotic Teleoperation**](https://arxiv.org/abs/2603.30042) | ICRA 2026 | 2026-03-31 | ![Star](https://img.shields.io/github/stars/ripl/HapCompass?style=social&label=Star) [GitHub](https://github.com/ripl/HapCompass) |  |
| [**CUPID: Curating Data your Robot Loves with Influence Functions**](https://arxiv.org/abs/2506.19121) | CoRL 2025 | 2025-06-23 | ![Star](https://img.shields.io/github/stars/agiachris/cupid?style=social&label=Star) [GitHub](https://github.com/agiachris/cupid) |  |
| [**Compliant Residual DAgger: Improving Real-World Contact-Rich Manipulation with Human Corrections**](https://arxiv.org/abs/2506.16685) | NeurIPS 2025 | 2025-06-20 | ![Star](https://img.shields.io/github/stars/yifan-hou/cr-dagger?style=social&label=Star) [GitHub](https://github.com/yifan-hou/cr-dagger) |  |
| [**IntervenGen: Interventional Data Generation for Robust and Data-Efficient Robot Imitation Learning**](https://arxiv.org/abs/2405.01472) | IROS 2024 | 2024-05-02 | [Project](https://sites.google.com/view/intervengen2024) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Automatic Generation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Worlds in One Demo: A Synthetic Data Engine for Learning Open-World Mobile Manipulation**](https://arxiv.org/abs/2607.13154) | arXiv | 2026-07-14 | [Project](https://wanda.lecar-lab.org/) |  |  
| [**RoboSnap: One-Shot Real-to-Sim Scene Generation for Generalizable Robot Learning and Evaluation**](https://arxiv.org/abs/2607.06699) | arXiv | 2026-07-07 | ![Star](https://img.shields.io/github/stars/robosnap/robosnap?style=social&label=Star) [GitHub](https://github.com/robosnap/robosnap) |  |  
| [**PRISM: Personalized Robotic Dataset Generation via Image-based Scene and Motion Synthesis**](https://arxiv.org/abs/2607.04880) | arXiv | 2026-07-06 | - |  |  
| [**AutoDex: An Automated Real-World System for Dexterous Grasping Data Collection**](https://arxiv.org/abs/2606.23689) | arXiv | 2026-06-22 | ![Star](https://img.shields.io/github/stars/willi19/autodex-code?style=social&label=Star) [GitHub](https://github.com/willi19/autodex-code) |  |  
| [**Scalable Trajectory Generation for Whole-Body Mobile Manipulation**](https://arxiv.org/abs/2604.12565) | arXiv | 2026-04-14 | [Project](https://automoma.pages.dev/) |  |  
| [**AffordSim: A Scalable Data Generator and Benchmark for Affordance-Aware Robotic Manipulation**](https://arxiv.org/abs/2604.11674) | arXiv | 2026-04-13 | - |  |  
| [**SIM1: Physics-Aligned Simulator as Zero-Shot Data Scaler in Deformable Worlds**](https://arxiv.org/abs/2604.08544) | arXiv | 2026-04-09 | ![Star](https://img.shields.io/github/stars/InternRobotics/SIM1?style=social&label=Star) [GitHub](https://github.com/InternRobotics/SIM1) |  |  
| [**CRAFT: Video Diffusion for Bimanual Robot Data Generation**](https://arxiv.org/abs/2604.03552) | arXiv | 2026-04-04 | [Project](https://craftaug.github.io/) |  |  
| [**V-Dreamer: Automating Robotic Simulation and Trajectory Synthesis via Video Generation Priors**](https://arxiv.org/abs/2603.18811) | arXiv | 2026-03-19 | [Project](https://jia-handsome.github.io/v-Dreamer/) |  |  
| [**RADAR: Closed-Loop Robotic Data Generation via Semantic Planning and Autonomous Causal Environment Reset**](https://arxiv.org/abs/2603.11811) | arXiv | 2026-03-12 | - |  |  
| [**RoboCurate: Harnessing Diversity with Action-Verified Neural Trajectory for Robot Learning**](https://arxiv.org/abs/2602.18742) | arXiv | 2026-02-21 | [Project](https://seungkukim.github.io/robocurate/) |  |  
| [**RoboGene: Boosting VLA Pre-training via Diversity-Driven Agentic Framework for Real-World Task Generation**](https://arxiv.org/abs/2602.16444) | arXiv | 2026-02-18 | [Project](https://robogene-boost-vla.github.io/) |  |  
| [**ExoGS: A 4D Real-to-Sim-to-Real Framework for Scalable Manipulation Data Collection**](https://arxiv.org/abs/2601.18629) | arXiv | 2026-01-26 | ![Star](https://img.shields.io/github/stars/zaixiabalala/ExoGS?style=social&label=Star) [GitHub](https://github.com/zaixiabalala/ExoGS) |  |  
| [**One-Shot Real-World Demonstration Synthesis for Scalable Bimanual Manipulation**](https://arxiv.org/abs/2512.09297) | arXiv | 2025-12-10 | [Project](https://hnuzhy.github.io/projects/BiDemoSyn/) |  |  
| [**AOMGen: Photoreal, Physics-Consistent Demonstration Generation for Articulated Object Manipulation**](https://arxiv.org/abs/2512.18396) | arXiv | 2025-12-20 | - |  |  
| [**AnyTask: an Automated Task and Data Generation Framework for Advancing Sim-to-Real Policy Learning**](https://arxiv.org/abs/2512.17853) | arXiv | 2025-12-19 | [Project](https://anytask.rai-inst.com/) |  |  
| [**Iterative Compositional Data Generation for Robot Control**](https://arxiv.org/abs/2512.10891) | arXiv | 2025-12-11 | - |  |  
| [**IGen: Scalable Data Generation for Robot Learning from Open-World Images**](https://arxiv.org/abs/2512.01773) | arXiv | 2025-12-01 | ![Star](https://img.shields.io/github/stars/ChenghaoGu/IGen_Robot?style=social&label=Star) [GitHub](https://github.com/ChenghaoGu/IGen_Robot) |  |  
| [**Robot-Powered Data Flywheels: Deploying Robots in the Wild for Continual Data Collection and Foundation Model Adaptation**](https://arxiv.org/abs/2511.19647) | arXiv | 2025-11-24 | [Project](https://scanford-robot.github.io/) |  |  
| [**InternData-A1: Pioneering High-Fidelity Synthetic Data for Pre-training Generalist Policy**](https://arxiv.org/abs/2511.16651) | arXiv | 2025-11-20 | [Project](https://internrobotics.github.io/interndata-a1.github.io/) |  |  
| [**DynaMimicGen: A Data Generation Framework for Robot Learning of Dynamic Tasks**](https://arxiv.org/abs/2511.16223) | arXiv | 2025-11-20 | ![Star](https://img.shields.io/github/stars/automation-robotics-machines/DynaMimicGen?style=social&label=Star) [GitHub](https://github.com/automation-robotics-machines/DynaMimicGen) |  |  
| [**FieldGen: From Teleoperated Pre-Manipulation Trajectories to Field-Guided Data Generation**](https://arxiv.org/abs/2510.20774) | arXiv | 2025-10-23 | ![Star](https://img.shields.io/github/stars/FieldGen/FieldGen?style=social&label=Star) [GitHub](https://github.com/FieldGen/FieldGen) |  |  
| [**SoftMimicGen: A Data Generation System for Scalable Robot Learning in Deformable Object Manipulation**](https://arxiv.org/abs/2603.25725) | ICRA 2026 | 2026-03-26 | [Project](https://softmimicgen.github.io/) |  |  
| [**MoMaGen: Generating Demonstrations under Soft and Hard Constraints for Multi-Step Bimanual Mobile Manipulation**](https://arxiv.org/abs/2510.18316) | ICLR 2026 | 2025-10-21 | ![Star](https://img.shields.io/github/stars/ChengshuLi/MoMaGen?style=social&label=Star) [GitHub](https://github.com/ChengshuLi/MoMaGen) |  |  
| [**DexFlyWheel: A Scalable and Self-improving Data Generation Framework for Dexterous Manipulation**](https://arxiv.org/abs/2509.23829) | NeurIPS 2025 | 2025-09-28 | [Project](https://dexflywheel.github.io/) |  |  
| [**LLM Trainer: Automated Robotic Data Generating via Demonstration Augmentation using LLMs**](https://arxiv.org/abs/2509.20070) | arXiv | 2025-09-24 | [Project](https://sites.google.com/andrew.cmu.edu/llm-trainer) |  |  
| [**RaC: Robot Learning for Long-Horizon Tasks by Scaling Recovery and Correction**](https://arxiv.org/abs/2509.07953) | CoRL 2025 | 2025-09-09 | [Project](https://rac-scaling-robot.github.io/) |  |  
| [**Fail2Progress: Learning from Real-World Robot Failures with Stein Variational Inference**](https://arxiv.org/abs/2509.01746) | CoRL 2025 | 2025-08-11 | [Project](https://sites.google.com/view/fail2progress) |  |  
| [**Constraint-Preserving Data Generation for Visuomotor Policy Learning**](https://arxiv.org/abs/2508.03944) | CoRL 2025 | 2025-08-11 | [Project](https://cp-gen.github.io/) |  |  
| [**HybridGen: VLM-Guided Hybrid Planning for Scalable Data Generation of Imitation Learning**](https://arxiv.org/abs/2503.13171) | arXiv | 2025-03-17 | - |  |  
| [**Physics-Driven Data Generation for Contact-Rich Manipulation via Trajectory Optimization**](https://arxiv.org/abs/2502.20382) | RSS 2025 | 2025-02-27 | [Project](https://lujieyang.github.io/physicsgen/) |  |  
| [**DemoGen: Synthetic Demonstration Generation for Data-Efficient Visuomotor Policy Learning**](https://arxiv.org/abs/2502.16932) | RSS 2025 | 2025-02-24 | ![Star](https://img.shields.io/github/stars/TEA-Lab/DemoGen?style=social&label=Star) [GitHub](https://github.com/TEA-Lab/DemoGen) |  |  
| [**Re<sup>3</sup>Sim: Generating High-Fidelity Simulation Data via 3D-Photorealistic Real-to-Sim for Robotic Manipulation**](https://arxiv.org/abs/2502.08645) | ICRA 2026 | 2025-02-12 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/Re3Sim?style=social&label=Star) [GitHub](https://github.com/OpenRobotLab/Re3Sim) |  |
| [**ARMADA: Augmented Reality for Robot Manipulation and Robot-Free Data Acquisition**](https://arxiv.org/abs/2412.10631) | RSSW 2025 | 2024-12-14 | [Project](https://nataliya.dev/armada) |  |
| [**DexMimicGen: Automated Data Generation for Bimanual Dexterous Manipulation via Imitation Learning**](https://arxiv.org/abs/2410.24185) | ICRA 2025 | 2024-10-31 | ![Star](https://img.shields.io/github/stars/NVlabs/dexmimicgen?style=social&label=Star) [GitHub](https://github.com/NVlabs/dexmimicgen) |  |  
| [**ARCADE: Scalable Demonstration Collection and Generation via Augmented Reality for Imitation Learning**](https://arxiv.org/abs/2410.15994) | IROS 2024 | 2024-10-21 | ![Star](https://img.shields.io/github/stars/YY-GX/ARCADE?style=social&label=Star) [GitHub](https://github.com/YY-GX/ARCADE/tree/Unity_ROS) |  |  
| [**MILES: Making Imitation Learning Easy with Self-Supervision**](https://arxiv.org/abs/2410.19693) | CoRL 2024 | 2024-10-25 | ![Star](https://img.shields.io/github/stars/gpapagiannis/miles-imitation?style=social&label=Star) [GitHub](https://github.com/gpapagiannis/miles-imitation) |  |
| [**SkillMimicGen: Automated Demonstration Generation for Efficient Skill Learning and Deployment**](https://arxiv.org/abs/2410.18907) | CoRL 2024 | 2024-10-24 | [Project](https://skillgen.github.io/) |  |
| [NILS: **Scaling Robot Policy Learning via Zero-Shot Labeling with Foundation Models**](https://arxiv.org/abs/2410.17772) | CoRL 2024 | 2024-10-23 | [Project](https://robottasklabeling.github.io/) |  |
| [SOAR: **Autonomous Improvement of Instruction Following Skills via Foundation Models**](https://arxiv.org/abs/2407.20635) | CoRL 2024 | 2024-07-30 | ![Star](https://img.shields.io/github/stars/rail-berkeley/soar?style=social&label=Star) [GitHub](https://github.com/rail-berkeley/soar) |  |
| [**Manipulate-Anything: Automating Real-World Robots using Vision-Language Models**](https://arxiv.org/abs/2406.18915) | CoRL 2024 | 2024-06-27 | [Project](https://robot-ma.github.io/) | |
| [**SPRINT: Scalable Policy Pre-Training via Language Instruction Relabeling**](https://arxiv.org/abs/2306.11886) | ICRA 2024 | 2023-06-20 | ![Star](https://img.shields.io/github/stars/clvrai/sprint?style=social&label=Star) [GitHub](https://github.com/clvrai/sprint) | |
| [**Offline Imitation Learning with Variational Counterfactual Reasoning**](https://arxiv.org/abs/2310.04706) | NeurIPS 2023 | 2023-10-07 | ![Star](https://img.shields.io/github/stars/ZexuSun/OILCA-NeurIPS23?style=social&label=Star) [GitHub](https://github.com/ZexuSun/OILCA-NeurIPS23) |  |
| [**MimicGen: A Data Generation System for Scalable Robot Learning using Human Demonstrations**](https://arxiv.org/abs/2310.17596) | CoRL 2023 | 2023-10-26 | ![Star](https://img.shields.io/github/stars/NVlabs/mimicgen?style=social&label=Star) [GitHub](https://github.com/NVlabs/mimicgen) |  |
| [**Scaling Up and Distilling Down: Language-Guided Robot Skill Acquisition**](https://arxiv.org/abs/2307.14535) | CoRL 2023 | 2023-07-26 | ![Star](https://img.shields.io/github/stars/real-stanford/scalingup?style=social&label=Star) [GitHub](https://github.com/real-stanford/scalingup) |  |
| [**RoboCat: A Self-Improving Generalist Agent for Robotic Manipulation**](https://arxiv.org/abs/2306.11706) | TMLR 2023 | 2023-06-20 | ![Star](https://img.shields.io/github/stars/kyegomez/RoboCAT?style=social&label=Star) [GitHub](https://github.com/kyegomez/RoboCAT) | |
| [DIAL: **Robotic Skill Acquisition via Instruction Augmentation with Vision-Language Models**](https://arxiv.org/abs/2211.11736) | RSS 2023 | 2022-11-21 | [Project](https://instructionaugmentation.github.io/) |  |
| [**SEIL: Simulation-augmented Equivariant Imitation Learning**](https://arxiv.org/abs/2211.00194) | ICRA 2023 | 2022-11-26 | ![Star](https://img.shields.io/github/stars/SaulBatman/SEIL?style=social&label=Star) [GitHub](https://github.com/SaulBatman/SEIL) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Crowdsourcing
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**AXIS: A Growable Community-Driven Data Engine for Scalable Robot Manipulation**](https://arxiv.org/abs/2607.21588) | arXiv | 2026-07-23 | [Project](https://axisaiorg.github.io/AXIS-V1/) |  |  
| [**COBALT: Crowdsourcing Robot Learning via Cloud-Based Teleoperation with Smartphones**](https://arxiv.org/abs/2605.19138) | ICRA 2026 | 2026-05-18 | ![Star](https://img.shields.io/github/stars/pairlab/COBALT?style=social&label=Star) [GitHub](https://github.com/pairlab/COBALT) |  |  
| [**EgoZero: Robot Learning from Smart Glasses**](https://arxiv.org/abs/2505.20290) | arXiv | 2025-05-26 | ![Star](https://img.shields.io/github/stars/vliu15/egozero?style=social&label=Star) [GitHub](https://github.com/vliu15/egozero) | Aria Glasses |  
| [**AR2-D2: Training a Robot Without a Robot**](https://arxiv.org/abs/2306.13818) | CoRL 2023 | 2023-06-23 | ![Star](https://img.shields.io/github/stars/jiafei1224/AR2-D2?style=social&label=Star) [GitHub](https://github.com/jiafei1224/AR2-D2) |  |
| [**Learning Multi-Arm Manipulation Through Collaborative Teleoperation**](https://arxiv.org/abs/2012.06738) | ICRA 2021 | 2020-12-12 | [Project](https://roboturk.stanford.edu/multiarm) |  |
| [**Scaling Robot Supervision to Hundreds of Hours with RoboTurk: Robotic Manipulation Dataset through Human Reasoning and Dexterity**](https://arxiv.org/abs/1911.04052) | IROS 2019 | 2019-11-11 | [Project](https://roboturk.stanford.edu/realrobotdataset) |  |
| [**RoboTurk: A Crowdsourcing Platform for Robotic Skill Learning through Imitation**](https://arxiv.org/abs/1811.02790) | CoRL 2018 | 2018-11-07 | [Project](https://roboturk.stanford.edu/) |  |
| [**Accelerating Imitation Learning through Crowdsourcing**](https://ieeexplore.ieee.org/document/6907558) | ICRA 2014 | 2014-09-29 | - |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>


<!-- Data Utilization -->
<div align="center">

### <i>Data Utilization</i>

</div>

### Data Expansion
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**EXIMO: VLM Guided Exploration of VLA Policies**](https://arxiv.org/abs/2608.19891) | arXiv | 2026-08-20 | - |  |
| [**RoboReact: Agentic Skill Distillation from Generated Egocentric Videos for Generalizable Whole-Body Manipulation**](https://arxiv.org/abs/2608.03387) | arXiv | 2026-08-04 | [Project](https://roboreact.github.io/) |  |
| [**Self-Evolving Learning for Embodied AI with Criticality Model**](https://arxiv.org/abs/2607.28251) | arXiv | 2026-07-30 | [Project](https://r2rdreamer.github.io/) |  |
| [**R2RDreamer: 3D-aware Data Augmentation for Spatially-generalized 2D Manipulation Policies**](https://arxiv.org/abs/2606.17040) | arXiv | 2026-06-15 | [Project](https://r2rdreamer.github.io/) |  |
| [**WM-DAgger: Enabling Efficient Data Aggregation for Imitation Learning with World Models**](https://arxiv.org/abs/2604.11351) | arXiv | 2026-04-13 | ![Star](https://img.shields.io/github/stars/czs12354-xxdbd/WM-Dagger?style=social&label=Star) [GitHub](https://github.com/czs12354-xxdbd/WM-Dagger) |  |
| [**RoboVIP: Multi-View Video Generation with Visual Identity Prompting Augments Robot Manipulation**](https://arxiv.org/abs/2601.05241) | arXiv | 2026-01-08 | ![Star](https://img.shields.io/github/stars/RoboVIP/RoboVIP_VDM?style=social&label=Star) [GitHub](https://github.com/RoboVIP/RoboVIP_VDM) |  |
| [**MOVE: A Simple Motion-Based Data Collection Paradigm for Spatial Generalization in Robotic Manipulation**](https://arxiv.org/abs/2512.04813) | arXiv | 2025-12-04 | ![Star](https://img.shields.io/github/stars/lucywang720/MOVE?style=social&label=Star) [GitHub](https://github.com/lucywang720/MOVE) |  |
| [**Restoring  Noisy Demonstration for Imitation Learning With Diffusion Models**](https://arxiv.org/abs/2510.14467) | TNNLS 2025 | 2025-10-16 | - |  |
| [**R2RGEN: Real-to-Real 3D Data Generation for Spatially Generalized Manipulation**](https://arxiv.org/abs/2510.08547) | arXiv | 2025-10-09 | [Project](https://r2rgen.github.io/) |  |
| [**EMMA: Generalizing Real-World Robot Manipulation via Generative Visual Transfer**](https://arxiv.org/abs/2509.22407) | arXiv | 2025-09-26 | [Project](https://egodemogen.github.io/) |  |
| [**EgoDemoGen: Novel Egocentric Demonstration Generation Enables Viewpoint-Robust Manipulation**](https://arxiv.org/abs/2509.22578) | arXiv | 2025-09-26 | [Project](https://egodemogen.github.io/) |  |
| [**One Demo is Worth a Thousand Trajectories: Action-View Augmentation for Visuomotor Policies**](https://arxiv.org/abs/2606.19586) | CoRL 2025 | 2026-06-17 | [Project](https://chuerpan.com/1001-demos.github.io/) |  |
| [**DataPlatter: Boosting Robotic Manipulation Generalization with Minimal Costly Data**](https://arxiv.org/abs/2503.19516) | arXiv | 2025-03-25 | ![Star](https://img.shields.io/github/stars/notFoundThisPerson/RoboTron-Craft?style=social&label=Star) [GitHub](https://github.com/notFoundThisPerson/RoboTron-Craft) |  |
| [**TASTE-Rob: Advancing Video Generation of Task-Oriented Hand-Object Interaction for Generalizable Robotic Manipulation**](https://arxiv.org/abs/2503.11423) | CVPR 2025 | 2025-03-14 | ![Star](https://img.shields.io/github/stars/GAP-LAB-CUHK-SZ/TASTE-Rob?style=social&label=Star) [GitHub](https://github.com/GAP-LAB-CUHK-SZ/TASTE-Rob) | Video Generation |
| [**Diff-DAgger: Uncertainty Estimation with Diffusion Policy for Robotic Manipulation**](https://arxiv.org/abs/2410.14868) | ICRA 2025 | 2024-10-18 | ![Star](https://img.shields.io/github/stars/sean1295/DiffDAgger?style=social&label=Star) [GitHub](https://github.com/sean1295/DiffDAgger) |  |
| [**JUICER: Data-Efficient Imitation Learning for Robotic Assembly**](https://arxiv.org/abs/2404.03729) | IROS 2024 | 2024-04-04 | ![Star](https://img.shields.io/github/stars/ankile/imitation-juicer?style=social&label=Star) [GitHub](https://github.com/ankile/imitation-juicer) |  |
| [**Learning Category-Level Generalizable Object Manipulation Policy via Generative Adversarial Self-Imitation Learning from Demonstrations**](https://arxiv.org/abs/2203.02107) | RA-L 2022 | 2022-03-04 | ![Star](https://img.shields.io/github/stars/wkwan7/Category_Level_Manipulation?style=social&label=Star) [GitHub](https://github.com/wkwan7/Category_Level_Manipulation) | GAIL |
| [**Self-Imitation Learning by Planning**](https://arxiv.org/abs/2103.13834) | ICRA 2021 | 2021-03-25 | - |  |
| [**SAFARI: Safe and Active Robot Imitation Learning with Imagination**](https://arxiv.org/abs/2011.09586) | NeurIPSW 2020 | 2020-11-18 | [Project](https://www.robot-learning.uk/safari) |  |
| [**Scalable Multi-Task Imitation Learning with Autonomous Improvement**](https://arxiv.org/abs/2003.02636) | ICRA 2020 | 2020-03-25 | [Project](https://sites.google.com/view/scalable-mili/) |  |
| [**Generative predecessor models for sample-efficient imitation learning**](https://arxiv.org/abs/1904.01139) | ICLR 2019 | 2019-04-01 | - |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Data Reweighting
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**When Does Legacy Data Start to Help? Emergent Transfer in Cross-Configuration Robot Learning**](https://arxiv.org/abs/2607.25593) | arXiv | 2026-07-28 | - |  |
| [**BEACON: Cross-Domain Co-Training of Generative Robot Policies via Best-Effort Adaptation**](https://arxiv.org/abs/2605.08571) | arXiv | 2026-05-09 | [Project](https://computationalrobotics.seas.harvard.edu/BEACON/) |  |
| [**Conservative Offline Robot Policy Learning via Posterior-Transition Reweighting**](https://arxiv.org/abs/2603.16542) | arXiv | 2026-03-17 | ![Star](https://img.shields.io/github/stars/BeingBeyond/PTR?style=social&label=Star) [GitHub](https://github.com/BeingBeyond/PTR) |  |
| [**Towards Balanced Behavior Cloning from Imbalanced Datasets**](https://arxiv.org/abs/2508.06319) | arXiv | 2025-08-08 | [Project](https://collab.me.vt.edu/data_curation/) |  |
| [**Policy Learning from Large Vision-Language Model Feedback without Reward Modeling**](https://arxiv.org/abs/2507.23391) | IROS 2025 | 2025-07-31 | ![Star](https://img.shields.io/github/stars/tunglm2203/plare?style=social&label=Star) [GitHub](https://github.com/tunglm2203/plare) |  |
| [**Feasibility-aware Imitation Learning from Observations through a Hand-mounted Demonstration Interface**](https://arxiv.org/abs/2503.09018) | ICRA 2025 | 2025-03-12 | - |  |
| [**Imitation Learning by Estimating Expertise of Demonstrators**](https://arxiv.org/abs/2202.01288) | ICML 2022 | 2022-02-02 | ![Star](https://img.shields.io/github/stars/Stanford-ILIAD/ILEED?style=social&label=Star) [GitHub](https://github.com/Stanford-ILIAD/ILEED) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Data Selection
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**SiMDex: Mining Similar Egocentric Videos for Cross-Embodiment Dexterous Manipulation**](https://arxiv.org/abs/2608.04196) | arXiv | 2026-08-04 | [Project](https://lin-nie.github.io/SiMDex/) |  |
| [**HiFi-UMI: Learning Deployable Manipulation Policies from High-Fidelity UMI Data Alone**](https://arxiv.org/abs/2607.25895) | arXiv | 2026-07-28 | [Project](https://cloud.simpleai.tech/simple-world-lab/hifi-umi/) |  |
| [**SIEVE: Structure-Aware Data Selection for Imitation Learning with VLA Models**](https://arxiv.org/abs/2607.06442) | arXiv | 2026-07-07 | ![Star](https://img.shields.io/github/stars/ChangtiWu/SIEVE?style=social&label=Star) [GitHub](https://github.com/ChangtiWu/SIEVE) |  |
| [**ATHENA: Accelerated Multi-Task Heterogeneous Influence Functions for Robot Data Curation**](https://arxiv.org/abs/2606.16208) | arXiv | 2026-06-15 | [Project](https://sii-quantum.github.io/ATHENA.github.io/) |  |
| [**Perfect Demo Makes Poor Teacher: Learning Robust Alignment from Critical Motion Segments**](https://arxiv.org/abs/2606.15587) | arXiv | 2026-06-14 | ![Star](https://img.shields.io/github/stars/aim-uofa/STAIR?style=social&label=Star) [GitHub](https://github.com/aim-uofa/STAIR) |  |
| [**EmbodiedMidtrain: Bridging the Gap between Vision-Language Models and Vision-Language-Action Models via Mid-training**](https://arxiv.org/abs/2604.20012) | arXiv | 2026-04-21 | [Project](https://adu2021.github.io/blog/EmbodiedMidtrain/) |  |
| [**It's Not Just More Demos: Counterfactual Action Sensitivity Coverage for Data-Efficient Robust Robot Imitation**](https://arxiv.org/abs/2607.27261) | RSSW 2026 | 2026-07-29 | - |  |
| [**Quality over Quantity: Demonstration Curation via Influence Functions for Data-Centric Robot Learning**](https://arxiv.org/abs/2603.09056) | ICRA 2026 | 2026-03-10 | - |  |
| [**FT-NCFM: An Influence-Aware Data Distillation Framework for Efficient VLA Models**](https://arxiv.org/abs/2511.16233) | AAAI 2026 | 2025-11-20 | - |  |
| [**Using Temperature Sampling to Effectively Train Robot Learning Policies on Imbalanced Datasets**](https://arxiv.org/abs/2510.19373) | arXiv | 2025-10-22 | [Project](https://basavasagarkp.github.io/temp_samp/) |  |
| [**Is Diversity All You Need for Scalable Robotic Manipulation?**](https://arxiv.org/abs/2507.06219) | T-RO 2026 | 2025-07-08 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/AgiBot-World?style=social&label=Star) [GitHub](https://github.com/OpenDriveLab/AgiBot-World) |  |
| [**DataMIL: Selecting Data for Robot Imitation Learning with Datamodels**](https://arxiv.org/abs/2505.09603) | ICLR 2026 | 2025-05-14 | [Project](https://robin-lab.cs.utexas.edu/datamodels4imitation/) |  |
| [**Dynamic Test-Time Compute Scaling in Control Policy: Difficulty-Aware Stochastic Interpolant Policy**](https://arxiv.org/abs/2511.20906) | NeurIPS 2025 | 2025-11-25 | - |  |
| [**SCIZOR: A Self-Supervised Approach to Data Curation for Large-Scale Imitation Learning**](https://arxiv.org/abs/2505.22626) | CoRLW 2025 | 2025-05-28 | [Project](https://ut-austin-rpl.github.io/SCIZOR/) |  |
| [**Shortcut Learning in Generalist Robot Policies: The Role of Dataset Diversity and Fragmentation**](https://arxiv.org/abs/2508.06426) | CoRL 2025 | 2025-08-08 | [Project](https://lucky-light-sun.github.io/proj/shortcut-learning-in-grps/) |  |
| [AMF: **Active Fine-Tuning of Generalist Policies**](https://arxiv.org/abs/2410.05026) | ICML 2025 | 2024-10-07 | - |  |
| [**Guiding Data Collection via Factored Scaling Curves**](https://arxiv.org/abs/2505.07728) | RSSW 2025 | 2025-05-12 | [Project](https://factored-data-scaling.github.io/) |  |  
| [**Robot Data Curation with Mutual Information Estimators**](https://arxiv.org/abs/2502.08623) | RSS 2025 | 2025-02-12 | [Project](https://joeyhejna.com/demonstration-info/) |  |
| [**What Matters in Learning from Large-Scale Datasets for Robot Manipulation**](https://openreview.net/forum?id=LqhorpRLIm) | ICLR 2025 | 2025-01-23 | [Project](https://mimiclabs-iclr.github.io/) |  |
| [**How to Train Your Robots? The Impact of Demonstration Modality on Imitation Learning**](https://arxiv.org/abs/2503.07017) | ICRA 2025 | 2025-03-10 | - |  |
| [**Re-Mix: Optimizing Data Mixtures for Large Scale Imitation Learning**](https://arxiv.org/abs/2408.14037) | CoRL 2024 | 2024-08-26 | ![Star](https://img.shields.io/github/stars/jhejna/remix?style=social&label=Star) [GitHub](https://github.com/jhejna/remix) |  |
| [**How to Leverage Diverse Demonstrations in Offline Imitation Learning**](https://arxiv.org/abs/2405.17476) | ICML 2024 | 2024-05-24 | ![Star](https://img.shields.io/github/stars/HansenHua/ILID-ICML24?style=social&label=Star) [GitHub](https://github.com/HansenHua/ILID-ICML24) |  |
| [**Learning from Imperfect Demonstrations with Self-Supervision for Robotic Manipulation**](https://arxiv.org/abs/2401.08957) | ICRA 2025 | 2024-01-17 | - | |
| [**Learning to Discern: Imitating Heterogeneous Human Demonstrations with Preference and Representation Learning**](https://arxiv.org/abs/2310.14196) | CoRL 2023 | 2023-10-22 | - |  |
| [**Data Quality in Imitation Learning**](https://arxiv.org/abs/2306.02437) | NeurIPS 2023 | 2023-06-04 | - |  |
| [**An Unbiased Look at Datasets for Visuo-Motor Pre-Training**](https://arxiv.org/abs/2310.09289) | CoRL 2023 | 2023-10-13 | ![Star](https://img.shields.io/github/stars/SudeepDasari/data4robotics?style=social&label=Star) [GitHub](https://github.com/SudeepDasari/data4robotics) |  |
| [**Extraneousness-Aware Imitation Learning**](https://arxiv.org/abs/2210.01379) | ICRA 2023 | 2022-10-04 | ![Star](https://img.shields.io/github/stars/zhengrc19/eil-code?style=social&label=Star) [GitHub](https://github.com/zhengrc19/eil-code) |  |
| [**Eliciting Compatible Demonstrations for Multi-Human Imitation Learning**](https://arxiv.org/abs/2210.08073) | CoRL 2022 | 2022-10-14 | ![Star](https://img.shields.io/github/stars/kanishkg/elicit?style=social&label=Star) [GitHub](https://github.com/kanishkg/elicit) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Data Retrieval
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**ReGIL: Retrieval-Guided Imitation Learning from a Single Demonstration**](https://arxiv.org/abs/2606.09381) | arXiv | 2026-06-08 | [Project](https://regil2026.github.io/) | |
| [**Grounding Robot Generalization in Training Data via Retrieval-Augmented VLMs**](https://arxiv.org/abs/2603.11426) | arXiv | 2026-03-12 | [Project](https://radar-analysis.github.io/) | |
| [**Memory Retrieval in Visuomotor Policies for Long-Horizon Robot Control**](https://arxiv.org/abs/2606.25136) | RSS 2026 | 2026-06-23 | ![Star](https://img.shields.io/github/stars/UT-Austin-RobIn/HALO?style=social&label=Star) [GitHub](https://github.com/UT-Austin-RobIn/HALO) | |
| [**Dejavu: Post-Deployment Learning for Embodied Agents via Experience Feedback**](https://arxiv.org/abs/2510.10181) | arXiv | 2025-10-11 | - | |
| [**Self-evolved Imitation Learning in Simulated World**](https://arxiv.org/abs/2509.19460) | arXiv | 2025-09-23 | ![Star](https://img.shields.io/github/stars/Jasper-aaa/SEIL?style=social&label=Star) [GitHub](https://github.com/Jasper-aaa/SEIL) | |
| [**ROSER: Few-Shot Robotic Sequence Retrieval for Scalable Robot Learning**](https://arxiv.org/abs/2603.01474) | ICLRW 2026 | 2026-03-02 | - | |
| [**Difference-Aware Retrieval Policies for Imitation Learning**](https://arxiv.org/abs/2606.09758) | ICLR 2026 | 2026-06-08 | ![Star](https://img.shields.io/github/stars/WEIRDLabUW/darp?style=social&label=Star) [GitHub](https://github.com/WEIRDLabUW/darp) | |
| [**E<sup>2</sup>DT: Efficient and Effective Decision Transformer with Experience-Aware Sampling for Robotic Manipulation**](https://arxiv.org/abs/2605.00159) | ICRA 2026 | 2026-04-30 | - | |
| [**Retrieve-Augmented Generation for Speeding up Diffusion Policy without Additional Training**](https://arxiv.org/abs/2507.21452) | arXiv | 2025-07-29 | - | |
| [**Data Retrieval with Importance Weights for Few-Shot Imitation Learning**](https://arxiv.org/abs/2509.01657) | CoRL 2025 | 2025-09-01 | ![Star](https://img.shields.io/github/stars/jhejna/importance-retrieval?style=social&label=Star) [GitHub](https://github.com/jhejna/importance-retrieval) | |
| [**COLLAGE: Adaptive Fusion-based Retrieval for Augmented Policy Learning**](https://arxiv.org/abs/2508.01131) | CoRL 2025 | 2025-08-11 | [Project](https://robin-lab.cs.utexas.edu/COLLAGE/) | |
| [**Let Me Show You: Learning by Retrieving from Egocentric Video for Robotic Manipulation**](https://arxiv.org/abs/2511.05199) | IROS 2025 | 2025-11-07 | - | |
| [**STRAP: Robot Sub-Trajectory Retrieval for Augmented Policy Learning**](https://arxiv.org/abs/2412.15182) | ICLR 2025 | 2024-12-19 | [Project](https://weirdlabuw.github.io/strap/) | |
| [**FlowRetrieval: Flow-Guided Data Retrieval for Few-Shot Imitation Learning**](https://arxiv.org/abs/2408.16944) | CoRL 2024 | 2024-08-29 | ![Star](https://img.shields.io/github/stars/lihenglin/bridge_training_code?style=social&label=Star) [GitHub](https://github.com/lihenglin/bridge_training_code) | |
| [**Offline Imitation Learning Through Graph Search and Retrieval**](https://arxiv.org/abs/2407.15403) | RSS 2024 | 2024-07-22 | [Project](https://zhaohengyin.github.io/gsr/) | |
| [**Retrieval-Augmented Embodied Agents**](https://arxiv.org/abs/2404.11699) | CVPR 2024 | 2024-04-17 | - | |
| [**DINOBot: Robot Manipulation via Retrieval and Alignment with Vision Foundation Models**](https://arxiv.org/abs/2402.13181) | ICRA 2024 | 2024-02-20 | [GitHub Gist](https://gist.github.com/normandipalo/fbc21f23606fbe3d407e22c363cb134e) | |
| [**On the Effectiveness of Retrieval, Alignment, and Replay in Manipulation**](https://arxiv.org/abs/2312.12345) | RA-L 2024 | 2023-12-19 | [Project](https://www.robot-learning.uk/retrieval-alignment-replay) | |
| [**Behavior Retrieval: Few-Shot Imitation Learning by Querying Unlabeled Datasets**](https://arxiv.org/abs/2304.08742) | RSS 2023 | 2023-04-08 | ![Star](https://img.shields.io/github/stars/MaxDu17/BehaviorRetrieval?style=social&label=Star) [GitHub](https://github.com/MaxDu17/BehaviorRetrieval) | |
| [**Learning and Retrieval from Prior Data for Skill-based Imitation Learning**](https://arxiv.org/abs/2210.11435) | CoRL 2022 | 2022-10-20 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/sailor?style=social&label=Star) [GitHub](https://github.com/UT-Austin-RPL/sailor) | |
| [**The Surprising Effectiveness of Representation Learning for Visual Imitation**](https://arxiv.org/abs/2112.01511) | RSS 2022 | 2021-12-02 | ![Star](https://img.shields.io/github/stars/jyopari/VINN?style=social&label=Star) [GitHub](https://github.com/jyopari/VINN) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Data Augmentation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**RoboEdit: Turning Human Manipulation Videos into Scalable Robot Experience**](https://arxiv.org/abs/2608.18948) | arXiv | 2026-08-19 | - |  |
| [**Ego2Robot: Scalable Robot Data Synthesis from Egocentric Human Data**](https://arxiv.org/abs/2608.02580) | arXiv | 2026-08-03 | [Project](https://www-ye.github.io/ego2robot_blog/) |  |
| [**WARP-RM: A Warp-Augmented Relative Progress Reward Model for Data Curation**](https://arxiv.org/abs/2606.28320) | arXiv | 2026-06-26 | ![Star](https://img.shields.io/github/stars/uynitsuj/WARP-RM?style=social&label=Star) [GitHub](https://github.com/uynitsuj/WARP-RM) |  |
| [**Improving Robotic Imitation Learning via Trajectory Standardization**](https://arxiv.org/abs/2606.22907) | arXiv | 2026-06-22 | ![Star](https://img.shields.io/github/stars/D-Robotics-AI-Lab/ISR?style=social&label=Star) [GitHub](https://github.com/D-Robotics-AI-Lab/ISR) |  |
| [**Bridging the Embodiment Gap: Disentangled Cross-Embodiment Video Editing**](https://arxiv.org/abs/2605.03637) | arXiv | 2026-05-05 | - |  |
| [**Seed2Scale: A Self-Evolving Data Engine for Embodied AI via Small to Large Model Synergy and Multimodal Evaluation**](https://arxiv.org/abs/2603.08260) | arXiv | 2026-03-09 | [Project](https://terminators2025.github.io/Seed2Scale.github.io/) |  |
| [**RoboAug: One Annotation to Hundreds of Scenes via Region-Contrastive Data Augmentation for Robotic Manipulation**](https://arxiv.org/abs/2602.14032) | arXiv | 2026-02-15 | [Project](https://x-roboaug.github.io/) |  |
| [**RoboPaint: From Human Demonstration to Any Robot and Any View**](https://arxiv.org/abs/2602.05325) | arXiv | 2026-02-05 | - |  |
| [**M<sup>3</sup>A Policy: Mutable Material Manipulation Augmentation Policy through Photometric Re-rendering**](https://arxiv.org/abs/2512.01446) | arXiv | 2025-12-01 | - |  |
| [**Improving Robotic Manipulation Robustness via NICE Scene Surgery**](https://arxiv.org/abs/2511.22777) | arXiv | 2025-11-27 | - |  |
| [**A Study on Enhancing the Generalization Ability of Visuomotor Policies via Data Augmentation**](https://arxiv.org/abs/2511.09932) | arXiv | 2025-11-13 | - |  |
| [**RESample: A Robust Data Augmentation Framework via Exploratory Sampling for Robotic Manipulation**](https://arxiv.org/abs/2510.17640) | arXiv | 2025-10-20 | - |  |
| [**Fidelity-Aware Data Composition for Robust Robot Generalization**](https://arxiv.org/abs/2509.24797) | arXiv | 2025-09-29 | - |  |
| [**Learning in ImaginationLand: Omnidirectional Policies through 3D Generative Models (OP-Gen)**](https://arxiv.org/abs/2509.06191) | arXiv | 2025-09-07 | [Project](https://www.robot-learning.uk/op-gen) |  |
| [**ROPA: Synthetic Robot Pose Generation for RGB-D Bimanual Data Augmentation**](https://arxiv.org/abs/2509.19454) | ICRA 2026 | 2025-09-23 | [Project](https://ropaaug.github.io/) |  |
| [**Masquerade: Learning from In-the-wild Human Videos using Data-Editing**](https://arxiv.org/abs/2508.09976) | ICRA 2026 | 2025-08-13 | [Project](https://masquerade-robot.github.io/) |  |
| [**ControlTac: Force- and Position-Controlled Tactile Data Augmentation with a Single Reference Image**](https://arxiv.org/abs/2505.20498) | arXiv | 2025-05-26 | [Project](https://dongyuluo.github.io/controltac/) |
| [**Robust Offline Imitation Learning Through State-level Trajectory Stitching**](https://arxiv.org/abs/2503.22524) | IROS 2025 | 2025-03-28 | - |  |
| [**RoboEngine: Plug-and-Play Robot Data Augmentation with Semantic Robot Segmentation and Background Generation**](https://arxiv.org/abs/2503.18738) | IROS 2025 | 2025-03-24 | ![Star](https://img.shields.io/github/stars/michaelyuancb/roboengine?style=social&label=Star) [GitHub](https://github.com/michaelyuancb/roboengine) |  |
| [**Predictive Red Teaming: Breaking Policies Without Breaking Robots**](https://arxiv.org/abs/2502.06575) | CoRL 2025 | 2025-02-10 | [Project](https://predictive-red-team.github.io/) |  |
| [**RoboPearls: Editable Video Simulation for Robot Manipulation**](https://arxiv.org/abs/2506.22756) | ICCV 2025 | 2025-06-28 | [Project](https://tangtaogo.github.io/RoboPearls/) |  |
| [**H2R: A Human-to-Robot Data Augmentation for Robot Pre-training from Videos**](https://arxiv.org/abs/2505.11920) | CVPRW 2025 | 2025-05-17 | - |  |
| [**Stem-OB: Generalizable Visual Imitation Learning with Stem-Like Convergent Observation through Diffusion Inversion**](https://arxiv.org/abs/2411.04919) | ICLR 2025 | 2024-11-07 | ![Star](https://img.shields.io/github/stars/hukz18/Stem-Ob-Code?style=social&label=Star) [GitHub](https://github.com/hukz18/Stem-Ob-Code) |  |
| [**RoCoDA: Counterfactual Data Augmentation for Data-Efficient Robot Learning from Demonstrations**](https://arxiv.org/abs/2411.16959) | ICRA 2025 | 2024-11-25 | [Project](https://rocoda.github.io/) |  |
| [**DABI: Evaluation of Data Augmentation Methods Using Downsampling in Bilateral Control-Based Imitation Learning with Images**](https://arxiv.org/abs/2410.04370) | ICRA 2025 | 2024-10-06 | [Project](https://mertcookimg.github.io/dabi/) |  |
| [**Towards Effective Utilization of Mixed-Quality Demonstrations in Robotic Manipulation via Segment-Level Selection and Optimization**](https://arxiv.org/abs/2409.19917) | ICRA 2025 | 2024-09-30 | ![Star](https://img.shields.io/github/stars/junxix/s2i?style=social&label=Star) [GitHub](https://github.com/junxix/s2i) |  |
| [**Green Screen Augmentation Enables Scene Generalisation in Robotic Manipulation**](https://arxiv.org/abs/2407.07868) | arXiv | 2024-07-10 | ![Star](https://img.shields.io/github/stars/eugeneteoh/greenaug?style=social&label=Star) [GitHub](https://github.com/eugeneteoh/greenaug) |  |
| [**Enhancing Visual Domain Robustness in Behaviour Cloning via Saliency-Guided Augmentation**](https://arxiv.org/abs/2608.11870) | CoRL 2024 | 2026-08-12 | ![Star](https://img.shields.io/github/stars/Zheyu-Zhuang/RoboSaGA?style=social&label=Star) [GitHub](https://github.com/Zheyu-Zhuang/RoboSaGA) |  |
| [**View-Invariant Policy Learning via Zero-Shot Novel View Synthesis**](https://arxiv.org/abs/2409.03685) | CoRL 2024 | 2024-09-05 | ![Star](https://img.shields.io/github/stars/s-tian/VISTA?style=social&label=Star) [GitHub](https://github.com/s-tian/VISTA) |  |
| [**RoVi-Aug: Robot and Viewpoint Augmentation for Cross-Embodiment Robot Learning**](https://arxiv.org/abs/2409.03403) | CoRL 2024 | 2024-09-05 | [Project](https://rovi-aug.github.io/) |  |
| [GENIMA: **Generative Image as Action Models**](https://arxiv.org/abs/2407.07875) | CoRL 2024 | 2024-07-10 | ![Star](https://img.shields.io/github/stars/MohitShridhar/genima?style=social&label=Star)  [GitHub](https://github.com/MohitShridhar/genima) |  |
| [**RT-Sketch: Goal-Conditioned Imitation Learning from Hand-Drawn Sketches**](https://arxiv.org/abs/2403.02709) | CoRL 2024 | 2024-03-05 | [Project](https://rt-sketch.github.io/) | Sketch |
| [**Diffusion Augmented Agents: A Framework for Efficient Exploration and Transfer Learning**](https://arxiv.org/abs/2407.20798) | CoLLAs 2024 | 2024-07-30 | [Project](https://sites.google.com/view/diffusion-augmented-agents/) |  |
| [**Diffusion Meets DAgger: Supercharging Eye-in-hand Imitation Learning**](https://arxiv.org/abs/2402.17768) | RSS 2024 | 2024-02-27 | ![Star](https://img.shields.io/github/stars/ErinZhang1998/dmd_diffusion?style=social&label=Star) [GitHub](https://github.com/ErinZhang1998/dmd_diffusion) | |
| [**Offline Imitation Learning with Variational Counterfactual Reasoning**](https://arxiv.org/abs/2310.04706) | NeurIPS 2023 | 2023-10-07 | ![Star](https://img.shields.io/github/stars/ZexuSun/OILCA-NeurIPS23?style=social&label=Star) [GitHub](https://github.com/ZexuSun/OILCA-NeurIPS23) |  |
| [ROSIE: **Scaling Robot Learning with Semantically Imagined Experience**](https://arxiv.org/abs/2302.11550) | RSS 2023 | 2023-02-22 | [Project](https://diffusion-rosie.github.io/) |  |
| [**GenAug: Retargeting behaviors to unseen situations via Generative Augmentation**](https://arxiv.org/abs/2302.06671) | RSS 2023 | 2023-02-13 | ![Star](https://img.shields.io/github/stars/genaug/genaug?style=social&label=Star) [GitHub](https://github.com/genaug/genaug) |  |
| [**Identifying Expert Behavior in Offline Training Datasets Improves Behavioral Cloning of Robotic Manipulation Policies**](https://arxiv.org/abs/2301.13019) | RA-L 2023 | 2023-01-30 | ![Star](https://img.shields.io/github/stars/genaug/genaug?style=social&label=Star) [GitHub](https://github.com/genaug/genaug) |  |
| [**Data Augmentation for Manipulation**](https://arxiv.org/abs/2205.02886) | RSS 2022 | 2022-05-05 | ![Star](https://img.shields.io/github/stars/UM-ARM-Lab/data-augmentation-for-manipulation?style=social&label=Star) [GitHub](https://github.com/UM-ARM-Lab/data-augmentation-for-manipulation) |  |
| [**Goal-conditioned Imitation Learning**](https://arxiv.org/abs/1906.05838) | NeurIPS 2019 | 2019-06-13 | ![Star](https://img.shields.io/github/stars/dingyiming0427/goalgail?style=social&label=Star) [GitHub](https://github.com/dingyiming0427/goalgail) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>



## Generalization

<!-- Task Generalization -->
<div align="center">

### <i>Task Generalization</i>

</div>

### Compositional Generalization
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Diagnosing Compositional Generalization in Sequential Robot Tasks**](https://arxiv.org/abs/2607.29687) | arXiv | 2026-07-31 | ![Star](https://img.shields.io/github/stars/YixiaoWang7/Diagnosing_Compositional_Generalization_Robot?style=social&label=Star) [GitHub](https://github.com/YixiaoWang7/Diagnosing_Compositional_Generalization_Robot) |  |
| [**Scale Up Strategically: Learning Compositional Generalization via Bias-Aware Evaluation and Data Collection for Robotic Manipulation**](https://arxiv.org/abs/2607.21582) | arXiv | 2026-07-23 | - |  |
| [**AC-VLA: Robust Out-of-Distribution Action Execution via Compositional Learning**](https://arxiv.org/abs/2607.15714) | arXiv | 2026-07-17 | [Project](https://ac-vla.github.io/) |  |
| [**Efficient Data Collection for Robotic Manipulation via Compositional Generalization**](https://arxiv.org/abs/2403.05110) | RSS 2024 | 2024-03-08 | [Project](https://iliad.stanford.edu/robot-data-comp/) | Compositional Generalization |
| [PROGRAMPORT: **Programmatically Grounded, Compositionally Generalizable Robotic Manipulation**](https://arxiv.org/abs/2304.13826) | ICLR 2023 | 2023-04-26 | [Project](https://progport.github.io/) | Compositional Generalization |
| [**Policy Architectures for Compositional Generalization in Control**](https://arxiv.org/abs/2203.05960) | NeurIPSW 2022 | 2022-03-10 | ![Star](https://img.shields.io/github/stars/facebookresearch/entity-factored-rl?style=social&label=Star) [GitHub](https://github.com/facebookresearch/entity-factored-rl) | Compositional Generalization |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Long-horizon Generalization
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**SkillMemo: Expert-guided Skill Memory Framework for Compositional Embodied Manipulation**](https://arxiv.org/abs/2608.05970) | arXiv | 2026-08-06 | [Project](https://changyuanwang17.github.io/SkillMemo/) | |
| [**Scaling Short-Term Memory of Visuomotor Policies for Long-Horizon Tasks**](https://arxiv.org/abs/2606.16178) | arXiv | 2026-06-15 | [Project](https://shahrutav.github.io/short-term-memory/) | |
| [**Goal2Skill: Long-Horizon Manipulation with Adaptive Planning and Reflection**](https://arxiv.org/abs/2604.13942) | arXiv | 2026-04-15 | - | |
| [**Chameleon: Episodic Memory for Long-Horizon Robotic Manipulation**](https://arxiv.org/abs/2603.24576) | arXiv | 2026-03-25 | ![Star](https://img.shields.io/github/stars/gxyes/MARS_Chameleon?style=social&label=Star) [GitHub](https://github.com/gxyes/MARS_Chameleon) | |
| [**Offline Discovery of Interpretable Skills from Multi-Task Trajectories**](https://arxiv.org/abs/2602.01018) | arXiv | 2026-02-01 | ![Star](https://img.shields.io/github/stars/ChongyuZhu/LOKI?style=social&label=Star) [GitHub](https://github.com/ChongyuZhu/LOKI) | |
| [**Learning a Thousand Tasks in a Day**](https://arxiv.org/abs/2511.10110) | SR 2025 | 2025-11-13 | ![Star](https://img.shields.io/github/stars/kamil-dreczkowski/learning_thousand_tasks?style=social&label=Star) [GitHub](https://github.com/kamil-dreczkowski/learning_thousand_tasks) | |
| [**SARM: Stage-Aware Reward Modeling for Long Horizon Robot Manipulation**](https://arxiv.org/abs/2509.25358) | ICLR 2026 | 2025-09-29 | [Project](https://qianzhong-chen.github.io/sarm.github.io/) | |
| [**Compose by Focus: Scene Graph-based Atomic Skills**](https://arxiv.org/abs/2509.16053) | arXiv | 2025-09-19 | [Project](https://computationalrobotics.seas.harvard.edu/SkillComposition/) | |
| [**ManiLong-Shot: Interaction-Aware One-Shot Imitation Learning for Long-Horizon Manipulation**](https://arxiv.org/abs/2512.16302) | AAAI 2026 | 2025-12-18 | [Project](https://sites.google.com/view/manilong-shot) | |
| [**Actor-Critic for Continuous Action Chunks: A Reinforcement Learning Framework for Long-Horizon Robotic Manipulation with Sparse Reward**](https://arxiv.org/abs/2508.11143) | AAAI 2026 | 2025-08-15 | - |  |
| [**BT-TL-DMPs: A Novel Robot TAMP Framework Combining Behavior Tree, Temporal Logic and Dynamical Movement Primitives**](https://arxiv.org/abs/2507.14582) | arXiv | 2025-07-19 | - | |
| [**Bootstrapping Imitation Learning for Long-horizon Manipulation via Hierarchical Data Collection Space**](https://arxiv.org/abs/2505.17389) | arXiv | 2025-05-23 | [Project](https://hd-space-robotics.github.io/) | |
| [**Look Before You Leap: Using Serialized State Machine for Language Conditioned Robotic Manipulation**](https://arxiv.org/abs/2503.05114) | IROS 2025 | 2025-03-07 | [Project](https://hd-space-robotics.github.io/) | |
| [**Symskill: Symbol and Skill Co-Invention for Data-Efficient and Real-Time Long-Horizon Manipulation**](https://arxiv.org/abs/2510.01661) | CoRLW 2025 | 2025-10-02 | ![Star](https://img.shields.io/github/stars/shaoyifei96/Symskill?style=social&label=Star) [GitHub](https://github.com/shaoyifei96/Symskill) | |
| [**Long-VLA: Unleashing Long-Horizon Capability of Vision Language Action Model for Robot Manipulation**](https://arxiv.org/abs/2508.19958) | CoRL 2025 | 2025-08-27 | [Project](https://long-vla.github.io/) | |
| [**RoboHorizon: An LLM-Assisted Multi-View World Model for Long-Horizon Robotic Manipulation**](https://arxiv.org/abs/2501.06605) | arXiv | 2025-01-11 | - | |
| [**ARCH: Hierarchical Hybrid Learning for Long-Horizon Contact-Rich Robotic Assembly**](https://arxiv.org/abs/2409.16451) | CoRL 2025 | 2024-09-24 | [Project](https://long-horizon-assembly.github.io/) | |
| [**What's the Move? Hybrid Imitation Learning via Salient Points**](https://arxiv.org/abs/2412.05426) | ICLR 2025 | 2024-12-06 | ![Star](https://img.shields.io/github/stars/priyasundaresan/sphinx?style=social&label=Star) [GitHub](https://github.com/priyasundaresan/sphinx) | |
| [TBBF: **A Backbone for Long-Horizon Robot Task Understanding**](https://arxiv.org/abs/2408.01334) | RA-L 2025 | 2024-08-02 | [Project](https://sites.google.com/view/therbligsbasedbackbone/home) | |
| [**The Art of Imitation: Learning Long-Horizon Manipulation Tasks from Few Demonstrations**](https://arxiv.org/abs/2407.13432) | RA-L 2024 | 2024-07-18 | ![Star](https://img.shields.io/github/stars/robot-learning-freiburg/TAPAS?style=social&label=Star) [GitHub](https://github.com/robot-learning-freiburg/TAPAS) |  |
| [**SCaR: Refining Skill Chaining for Long-Horizon Robotic Manipulation via Dual Regularization**](https://openreview.net/forum?id=RnxJc4vTVi) | NeurIPS 2024 | 2024-09-26 | [Project](https://sites.google.com/view/scar8297) | |
| [ManipGen: **Local Policies Enable Zero-shot Long-horizon Manipulation**](https://arxiv.org/abs/2410.22332) | CoRLW 2024 | 2024-10-29 | [Project](https://mihdalal.github.io/manipgen/) | |
| [**SPIRE: Synergistic Planning, Imitation, and Reinforcement for Long-Horizon Manipulation**](https://arxiv.org/abs/2410.18065) | CoRL 2024 | 2024-10-23 | [Project](https://sites.google.com/view/spire-corl-2024) |  |
| [BLADE: **Learning Compositional Behaviors from Demonstration and Language**](https://arxiv.org/abs/2505.21981) | CoRL 2024 | 2025-05-28 | [Project](https://blade-bot.github.io/) | IL, RepL, Policy Head, Few-Shot Policy Adaptation |
| [PALO: **Policy Adaptation via Language Optimization: Decomposing Tasks for Few-Shot Imitation**](https://arxiv.org/abs/2408.16228) | CoRL 2024 | 2024-08-29 | ![Star](https://img.shields.io/github/stars/vivekmyers/palo?style=social&label=Star) [GitHub](https://github.com/vivekmyers/palo) | Fine-grained Atom Action |
| [**DexSkills: Skill Segmentation Using Haptic Data for Learning Autonomous Long-Horizon Robotic Manipulation Tasks**](https://arxiv.org/abs/2405.03476) | IROS 2024 | 2024-05-06 | ![Star](https://img.shields.io/github/stars/ARQ-CRISP/DexSkills?style=social&label=Star) [GitHub](https://github.com/ARQ-CRISP/DexSkills) |  |
| [PSL: **Plan-Seq-Learn: Language Model Guided RL for Solving Long Horizon Robotics Tasks**](https://arxiv.org/abs/2405.01534) | ICLR 2024 | 2024-05-02 | ![Star](https://img.shields.io/github/stars/mihdalal/planseqlearn?style=social&label=Star) [GitHub](https://github.com/mihdalal/planseqlearn) | |
| [**Hierarchical Human-to-Robot Imitation Learning for Long-Horizon Tasks via Cross-Domain Skill Alignment**](https://ieeexplore.ieee.org/document/10610084) | ICRA 2024 | 2024-08-08 | - | |
| [**PRIME: Scaffolding Manipulation Tasks with Behavior Primitives for Data-Efficient Imitation Learning**](https://arxiv.org/abs/2403.00929) | RA-L 2024 | 2024-03-01 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/PRIME?style=social&label=Star) [GitHub](https://github.com/UT-Austin-RPL/PRIME) |  |
| [**GO-DICE: Goal-Conditioned Option-Aware Offline Imitation Learning via Stationary Distribution Correction Estimation**](https://arxiv.org/abs/2312.10802) | AAAI 2024 | 2023-12-17 | - |  |
| [**Hybrid Hierarchical Learning for Solving Complex Sequential Tasks Using the Robotic Manipulation Network ROMAN**](https://arxiv.org/abs/2307.00125) | NMI 2023 | 2023-07-30 | - |  |
| [BOSS: **Bootstrap Your Own Skills: Learning to Solve New Tasks with Large Language Model Guidance**](https://arxiv.org/abs/2310.10021) | CoRL 2023 | 2023-12-16 | ![Star](https://img.shields.io/github/stars/clvrai/boss?style=social&label=Star) [GitHub](https://github.com/clvrai/boss) | Skill Bootstrapping |
| [**HYDRA: Hybrid Robot Actions for Imitation Learning**](https://arxiv.org/abs/2306.17237) | CoRL 2023 | 2023-06-29 | [Project](https://sites.google.com/view/hydra-il-2023) |  |
| [**STAP: Sequencing Task-Agnostic Policies**](https://arxiv.org/abs/2210.12250) | ICRA 2023 | 2022-10-21 | ![Star](https://img.shields.io/github/stars/agiachris/STAP?style=social&label=Star) [GitHub](https://github.com/agiachris/STAP) |  |
| [**Divide & Conquer Imitation Learning**](https://arxiv.org/abs/2204.07404) | IROS 2022 | 2022-02-15 | - |  |
| [**Bottom-Up Skill Discovery from Unsegmented Demonstrations for Long-Horizon Robot Manipulation**](https://arxiv.org/abs/2109.13841) | RA-L 2022 | 2021-09-28 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/BUDS?style=social&label=Star) [GitHub](https://github.com/UT-Austin-RPL/BUDS) |  |
| [**Adversarial Skill Chaining for Long-Horizon Robot Manipulation via Terminal State Regularization**](https://arxiv.org/abs/2111.07999) | CoRL 2021 | 2021-11-15 | ![Star](https://img.shields.io/github/stars/clvrai/skill-chaining?style=social&label=Star) [GitHub](https://github.com/clvrai/skill-chaining) |  |
| [**Sequential Robot Imitation Learning from Observations**](https://journals.sagepub.com/doi/abs/10.1177/02783649211032721) | IJRR 2021 | 2021-08-06 | - |  |
| [**SQUIRL: Robust and Efficient Learning from Video Demonstration of Long-Horizon Robotic Manipulation Tasks**](https://arxiv.org/abs/2003.04956) | IROS 2020 | 2020-03-10 | [Project](https://crlab.cs.columbia.edu/squirl/) |  |
| [**Learning to Generalize Across Long-Horizon Tasks from Human Demonstrations**](https://arxiv.org/abs/2003.06085) | RSS 2020 | 2020-03-13 | [Project](https://sites.google.com/view/gti2020/) |  |
| [**Learning to Combine Primitive Skills: A Step towards Versatile Robotic Manipulation**](https://arxiv.org/abs/1908.00722) | ICRA 2020 | 2019-08-02 | ![Star](https://img.shields.io/github/stars/rstrudel/rlbc?style=social&label=Star) [GitHub](https://github.com/rstrudel/rlbc) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Few-shot Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Adaptation of Generalist Robot Policies with Minimal Data**](https://arxiv.org/abs/2608.11363) | arXiv | 2026-08-11 | - |  |
| [**SemAnCorr: Semantic Anchored Correspondence for Zero-Shot Manipulation Skill Transfer**](https://arxiv.org/abs/2607.28382) | arXiv | 2026-07-30 | ![Star](https://img.shields.io/github/stars/semancorr/SemAnCorr?style=social&label=Star) [GitHub](https://github.com/semancorr/SemAnCorr) |  |
| [**PGDG: Physically Grounded Data Generation for Robust Bimanual Policy Learning from a Single Demonstration**](https://arxiv.org/abs/2605.21710) | arXiv | 2026-05-20 | [Project](https://cunxid.github.io/PGDG/) |  |
| [**SID: Sliding into Distribution for Robust Few-Demonstration Manipulation**](https://arxiv.org/abs/2605.13428) | arXiv | 2026-05-13 | [Project](https://sliding-into-distribution.github.io/) |  |
| [**UMIGen: A Unified Framework for Egocentric Point Cloud Generation and Cross-Embodiment Robotic Imitation Learning**](https://arxiv.org/abs/2511.09302) | arXiv | 2025-11-12 | - |  |
| [**EmbodiSwap for Zero-Shot Robot Imitation Learning**](https://arxiv.org/abs/2510.03706) | arXiv | 2025-10-04 | - |  |
| [**Annotation-Free One-Shot Imitation Learning for Multi-Step Manipulation Tasks**](https://arxiv.org/abs/2509.24972) | arXiv | 2025-09-29 | ![Star](https://img.shields.io/github/stars/vijja-w/AF-OSIL-MS?style=social&label=Star) [GitHub](https://github.com/vijja-w/AF-OSIL-MS) |  |
| [**Flow-Enabled Generalization to Human Demonstrations in Few-Shot Imitation Learning**](https://arxiv.org/abs/2602.10594) | ICRA 2026 | 2026-02-11 | - |  |
| [**TReF-6: Inferring Task-Relevant Frames from a Single Demonstration for One-Shot Skill Generalization**](https://arxiv.org/abs/2509.00310) | CoRL 2025 | 2025-08-30 | - |  |
| [**Zero-Shot Visual Generalization in Robot Manipulation**](https://arxiv.org/abs/2505.11719) | NeurIPS 2025 | 2025-05-16 | [Project](https://sites.google.com/view/vis-gen-robotics/home) |  |
| [**Elastic Motion Policy: An Adaptive Dynamical System for Robust and Efficient One-Shot Imitation Learning**](https://arxiv.org/abs/2503.08029) | IROS 2025 | 2025-03-11 | [Project](https://elastic-motion-policy.github.io/EMP/) |  |
| [**VidBot: Learning Generalizable 3D Actions from In-the-Wild 2D Human Videos for Zero-Shot Robotic Manipulation**](https://arxiv.org/abs/2503.07135) | CVPR 2025 | 2025-03-10 | [Project](https://hanzhic.github.io/vidbot-project/) |  |
| [**One-Shot Dual-Arm Imitation Learning**](https://arxiv.org/abs/2503.06831) | ICRA 2025 | 2025-03-10 | [Project](https://www.robot-learning.uk/one-shot-dual-arm) |  |
| [**You Only Teach Once: Learn One-Shot Bimanual Robotic Manipulation from Video Demonstrations**](https://arxiv.org/abs/2501.14208) | RSS 2025 | 2025-01-24 | ![Star](https://img.shields.io/github/stars/hnuzhy/YOTO?style=social&label=Star) [GitHub](https://github.com/hnuzhy/YOTO) |  |
| [**Zero-Shot Offline Imitation Learning via Optimal Transport**](https://arxiv.org/abs/2410.08751) | ICML 2025 | 2024-10-11 | ![Star](https://img.shields.io/github/stars/martius-lab/zilot?style=social&label=Star) [GitHub](https://github.com/martius-lab/zilot) |  |
| [**Vision-based Manipulation from Single Human Video with Open-World Object Graphs**](https://arxiv.org/abs/2405.20321) | CoRLW 2024 | 2024-05-30 | [Project](https://ut-austin-rpl.github.io/ORION-release/) |  |
| [**DITTO: Demonstration Imitation by Trajectory Transformation**](https://arxiv.org/abs/2403.15203) | IROS 2024 | 2024-03-22 | ![Star](https://img.shields.io/github/stars/robot-learning-freiburg/DITTO?style=social&label=Star) [GitHub](https://github.com/robot-learning-freiburg/DITTO) |  
| [**CoBT: Collaborative Programming of Behaviour Trees from One Demonstration for Robot Manipulation**](https://arxiv.org/abs/2404.05870) | ICRA 2024 | 2024-04-08 | ![Star](https://img.shields.io/github/stars/jainaayush2006/CoBT?style=social&label=Star) [GitHub](https://github.com/jainaayush2006/CoBT) |  
| [**One-Shot Domain-Adaptive Imitation Learning via Progressive Learning**](https://arxiv.org/abs/2204.11251) | TASE 2022 | 2022-04-24 | - |  |
| [**Demonstrate Once, Imitate Immediately (DOME): Learning Visual Servoing for One-Shot Imitation Learning**](https://arxiv.org/abs/2204.02863) | IROS 2022 | 2022-04-06 | [Project](https://www.robot-learning.uk/dome) |  |
| [**Coarse-to-Fine Imitation Learning: Robot Manipulation from a Single Demonstration**](https://arxiv.org/abs/2105.06411) | ICRA 2021 | 2021-05-13 | [Project](https://www.robot-learning.uk/coarse-to-fine-imitation-learning) |  |
| [**SOZIL: Self-Optimal Zero-Shot Imitation Learning**](https://ieeexplore.ieee.org/document/9552943) | TCDS 2021 | 2021-09-30 | - |  |
| [**Zero-Shot Visual Imitation**](https://arxiv.org/abs/1804.08606) | ICLR 2018  | 2018-04-23 | ![Star](https://img.shields.io/github/stars/pathak22/zeroshot-imitation?style=social&label=Star) [GitHub](https://github.com/pathak22/zeroshot-imitation) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Meta Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Few-Shot Vision-Language Action-Incremental Policy Learning**](https://arxiv.org/abs/2504.15517) | arXiv | 2025-04-22 | ![Star](https://img.shields.io/github/stars/codeshop715/FSAIL?style=social&label=Star) [GitHub](https://github.com/codeshop715/FSAIL) |  |
| [**Learning Generalizable 3D Manipulation With 10 Demonstrations**](https://arxiv.org/abs/2411.10203) | IROS 2025 | 2024-11-15 | ![Star](https://img.shields.io/github/stars/renyu2016/Generalized-3D-Manipulation?style=social&label=Star) [GitHub](https://github.com/renyu2016/Generalized-3D-Manipulation) |  |
| [**One-Shot Imitation Learning with Invariance Matching for Robotic Manipulation**](https://arxiv.org/abs/2405.13178) | RSS 2024 | 2024-05-21 | ![Star](https://img.shields.io/github/stars/mlzxy/imop?style=social&label=Star) [GitHub](https://github.com/mlzxy/imop) | |
| [**One-Shot Imitation Learning With Graph Neural Networks for Pick-and-Place Manipulation Tasks**](https://ieeexplore.ieee.org/document/10202200/) | RA-L 2023 | 2023-08-02 | - |
| [**One-Shot Imitation Learning: A Pose Estimation Perspective**](https://arxiv.org/pdf/2310.12077) | CoRL 2023 | 2023-10-18 | [Project](https://www.robot-learning.uk/pose-estimation-perspective) |  |
| [**One-shot Imitation Learning via Interaction Warping**](https://arxiv.org/abs/2306.12392) | CoRL 2023 | 2023-06-21 | ![Star](https://img.shields.io/github/stars/ondrejbiza/shapewarping?style=social&label=Star) [GitHub](https://github.com/ondrejbiza/shapewarping) |
| [**Teach a Robot to FISH: Versatile Imitation from One Minute of Demonstrations**](https://arxiv.org/abs/2303.01497) | RSS 2023 | 2023-03-02 | ![Star](https://img.shields.io/github/stars/siddhanthaldar/FISH?style=social&label=Star) [GitHub](https://github.com/siddhanthaldar/FISH) |
| [**Meta-Reinforcement Learning via Language Instructions**](https://arxiv.org/abs/2209.04924) | ICRA 2023 | 2022-09-11 | ![Star](https://img.shields.io/github/stars/yaoxt3/MILLION?style=social&label=Star) [GitHub](https://github.com/yaoxt3/MILLION) |
| [**Transfering Hierarchical Structure with Dual Meta Imitation Learning**](https://arxiv.org/abs/2201.11981) | CoRL 2022 | 2022-01-28 | - |
| [**Towards More Generalizable One-shot Visual Imitation Learning**](https://arxiv.org/abs/2110.13423) | ICRA 2022 | 2021-10-26 | ![Star](https://img.shields.io/github/stars/rll-research/mosaic?style=social&label=Star) [GitHub](https://github.com/rll-research/mosaic) | | 
| [**Attentive One-Shot Meta-Imitation Learning From Visual Demonstration**](https://ieeexplore.ieee.org/document/9812281) | ICRA 2022 | 2021-07-12 | - | | 
| [**Meta-Imitation Learning by Watching Video Demonstrations**](https://openreview.net/forum?id=KTPuIsx4pmo) | ICLR 2022 | 2022-01-29 | - | | 
| [**Visual Goal-Directed Meta-Learning with Contextual Planning Networks**](https://arxiv.org/abs/2111.09908) | CVPRW 2021 | 2021-11-18 | - | | 
| [**Watch, Try, Learn: Meta-Learning from Demonstrations and Reward**](https://arxiv.org/abs/1906.03352) | ICLR 2020 | 2019-06-07 | - | | 
| [**One-Shot Hierarchical Imitation Learning of Compound Visuomotor Tasks**](https://arxiv.org/abs/1810.11043) | arXiv | 2018-10-08 | [Project](https://sites.google.com/view/one-shot-hil) | | 
| [**Task-Embedded Control Networks for Few-Shot Imitation Learning**](https://arxiv.org/abs/1810.03237) | CoRL 2018 | 2018-10-08 | ![Star](https://img.shields.io/github/stars/stepjam/TecNets?style=social&label=Star) [GitHub](https://github.com/stepjam/TecNets) | | 
| [**One-Shot Imitation from Observing Humans via Domain-Adaptive Meta-Learning**](https://arxiv.org/abs/1802.01557) | RSS 2018 | 2018-02-05 | ![Star](https://img.shields.io/github/stars/tianheyu927/mil?style=social&label=Star) [GitHub](https://github.com/tianheyu927/mil) | | 
| [**One-Shot Visual Imitation Learning via Meta-Learning**](https://arxiv.org/abs/1709.04905) | CoRL 2017 | 2017-09-14 | ![Star](https://img.shields.io/github/stars/tianheyu927/mil?style=social&label=Star) [GitHub](https://github.com/tianheyu927/mil) | | 
| [**One-Shot Imitation Learning**](https://arxiv.org/abs/1703.07326) | NeurIPS 2017 | 2017-03-21 | [Project](https://sites.google.com/view/nips2017-one-shot-imitation/home) | | 

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Lifelong/Continual/Incremental Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**T2S: Tokenized Skill Scaling for Lifelong Imitation Learning**](https://arxiv.org/abs/2508.01167) | arXiv | 2025-08-12 | - |  |
| [**Dynamic Mixture of Progressive Parameter-Efficient Expert Library for Lifelong Robot Learning**](https://arxiv.org/abs/2506.05985) | TMLR 2026 | 2025-06-06 | - |  |
| [**Policy Compatible Skill Incremental Learning via Lazy Learning Interface**](https://arxiv.org/abs/2509.20612) | NeurIPS 2025 | 2025-09-24 | ![Star](https://img.shields.io/github/stars/L2dulgi/SIL-C?style=social&label=Star) [GitHub](https://github.com/L2dulgi/SIL-C) |  |
| [**SPECI: Skill Prompts based Hierarchical Continual Imitation Learning for Robot Manipulation**](https://arxiv.org/abs/2504.15561) | TCDS 2025 | 2025-04-22 | - |  |
| [**Think Small, Act Big: Primitive Prompt Learning for Lifelong Robot Manipulation**](https://arxiv.org/abs/2504.00420) | CVPR 2025 | 2025-04-01 | - |  |
| [**iManip: Skill-Incremental Learning for Robotic Manipulation**](https://arxiv.org/abs/2503.07087) | ICCV 2025 | 2025-03-10 | - |  |
| [**M2Distill: Multi-Modal Distillation for Lifelong Imitation Learning**](https://arxiv.org/abs/2410.00064) | ICRA 2025 | 2024-10-30 | - |  |
| [**LOTUS: Continual Imitation Learning for Robot Manipulation Through Unsupervised Skill Discovery**](https://arxiv.org/abs/2311.02058) | ICRA 2024 | 2023-11-03 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/Lotus?style=social&label=Star) [GitHub](https://github.com/UT-Austin-RPL/Lotus) |  |
| [**CRIL: Continual Robot Imitation Learning via Generative and Prediction Model**](https://arxiv.org/abs/2106.09422) | IROS 2021 | 2021-06-17 | ![Star](https://img.shields.io/github/stars/HeegerGao/CRIL?style=social&label=Star) [GitHub](https://github.com/HeegerGao/CRIL) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Test-Time Adaptation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Adapting by Analogy: OOD Generalization of Visuomotor Policies via Functional Correspondence**](https://arxiv.org/abs/2506.12678) | arXiv | 2025-06-15 | - |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>


<!-- Environment Generalization -->
<div align="center">

### <i>Environment Generalization</i>

</div>

### Sim2Real or Real2Sim2Real Generalization
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Pre-training Visual Dexterity in Simulation**](https://arxiv.org/abs/2608.15917) | arXiv | 2026-08-16 | [Project](https://spd.bot/) |  |
| [**Agentic Real2Sim: Physics-based World Modeling with Vision-Language Agents**](https://arxiv.org/abs/2607.19190) | arXiv | 2026-07-21 | [Project](https://agentic-real2sim.github.io/) |  |  
| [**ConCent: Contact-Centric Real-to-Sim-to-Real Learning from One Demonstration**](https://arxiv.org/abs/2606.30268) | arXiv | 2026-06-29 | - |  |
| [**DataLadder: A Simulation-Enabled Interconversion Toolchain for the Embodied Data Pyramid**](https://arxiv.org/abs/2606.16776) | arXiv | 2026-06-15 | [Project](https://joyai-sim.github.io/) |  |
| [**SimWeaver: Zero-Shot RGB Sim-to-Real for Deformable Manipulation**](https://arxiv.org/abs/2606.15338) | arXiv | 2026-06-13 | ![Star](https://img.shields.io/github/stars/simWeaver/SimWeaver?style=social&label=Star) [GitHub](https://github.com/simWeaver/SimWeaver) |  |
| [**Video2Sim2Real: Full-Stack Autonomous Dexterous Skill Acquisition from a Single Human Video**](https://arxiv.org/abs/2606.08828) | arXiv | 2026-06-07 | [Project](https://video2sim2real.github.io/) |  |
| [**HyperSim: A Holistic Sim-To-Real Framework For Robust Robotic Manipulation**](https://arxiv.org/abs/2605.26638) | arXiv | 2026-05-26 | - |  |
| [**Zero-Shot Sim-to-Real Robot Learning: A Dexterous Manipulation Study on Reactive Catching**](https://arxiv.org/abs/2605.09789) | arXiv | 2026-05-10 | - |  |
| [**A Mechanistic Analysis of Sim-and-Real Co-Training in Generative Robot Policies**](https://arxiv.org/abs/2604.13645) | arXiv | 2026-04-15 | [Project](https://science-of-co-training.github.io/    ) |  |
| [**ExpertGen: Scalable Sim-to-Real Expert Policy Learning from Imperfect Behavior Priors**](https://arxiv.org/abs/2603.15956) | arXiv | 2026-03-16 | [Project](https://pages.rai-inst.com/expertgen/) |  |
| [**Building Explicit World Model for Zero-Shot Open-World Object Manipulation**](https://arxiv.org/abs/2603.13825) | arXiv | 2026-03-14 | [Project](https://bojack-bj.github.io/projects/thesis/) |  |
| [**TwinAligner: Visual-Dynamic Alignment Empowers Physics-aware Real2Sim2Real for Robotic Manipulation**](https://arxiv.org/abs/2512.19390) | arXiv | 2025-12-22 | ![Star](https://img.shields.io/github/stars/TwinAligner/TwinAligner?style=social&label=Star) [GitHub](https://github.com/TwinAligner/TwinAligner) |  |
| [**PolaRiS: Scalable Real-to-Sim Evaluations for Generalist Robot Policies**](https://arxiv.org/abs/2512.16881) | arXiv | 2025-12-18 | ![Star](https://img.shields.io/github/stars/arhanjain/PolaRiS?style=social&label=Star) [GitHub](https://github.com/arhanjain/PolaRiS) |  |
| [**Phys2Real: Fusing VLM Priors with Interactive Online Adaptation for Uncertainty-Aware Sim-to-Real Manipulation**](https://arxiv.org/abs/2510.11689) | arXiv | 2025-10-13 | [Project](https://phys2real.github.io/) |  |
| [**Real2Edit2Real: Generating Robotic Demonstrations via a 3D Control Interface**](https://arxiv.org/abs/2512.19402) | CVPR 2026 | 2025-12-22 | ![Star](https://img.shields.io/github/stars/Real2Edit2Real/Real2Edit2Real?style=social&label=Star) [GitHub](https://github.com/Real2Edit2Real/Real2Edit2Real) |  |
| [**High-Fidelity Simulated Data Generation for Real-World Zero-Shot Robotic Manipulation Learning with Gaussian Splatting**](https://arxiv.org/abs/2510.10637) | RA-L 2025 | 2025-10-12 | ![Star](https://img.shields.io/github/stars/Maxwell-Zhao/RoboSimGS?style=social&label=Star) [GitHub](https://github.com/Maxwell-Zhao/RoboSimGS) |  |
| [**A Recipe for Efficient Sim-to-Real Transfer in Manipulation with Online Imitation-Pretrained World Models**](https://arxiv.org/abs/2510.02538) | arXiv | 2025-10-02 | - |  |
| [**FUNCanon: Learning Pose-Aware Action Primitives via Functional Object Canonicalization for Generalizable Robotic Manipulation**](https://arxiv.org/abs/2509.19102) | arXiv | 2025-09-23 | [Project](https://sites.google.com/view/funcanon) |  |
| [**RoboSeek: You Need to Interact with Your Objects**](https://arxiv.org/abs/2509.17783) | arXiv | 2025-09-22 | [Project](https://russderrick.github.io/Roboseek/) |  |
| [**Manipulation as in Simulation: Enabling Accurate Geometry Perception in Robots**](https://arxiv.org/abs/2509.02530) | arXiv | 2025-09-17 | ![Star](https://img.shields.io/github/stars/ByteDance-Seed/manip-as-in-sim-suite?style=social&label=Star) [GitHub](https://github.com/ByteDance-Seed/manip-as-in-sim-suite) |  |
| [**Generalizable Domain Adaptation for Sim-and-Real Policy Co-Training**](https://arxiv.org/abs/2509.18631) | NeurIPS 2025 | 2025-09-23 | - |  |
| [**Robot Learning from Any Images**](https://arxiv.org/abs/2509.22970) |CoRL 2025 | 2025-09-26 | ![Star](https://img.shields.io/github/stars/sihengz02/RoLA?style=social&label=Star) [GitHub](https://github.com/sihengz02/RoLA) |  |
| [**Real2Render2Real: Scaling Robot Data Without Dynamics Simulation or Robot Hardware**](https://arxiv.org/abs/2505.09601) | CoRL 2025 | 2025-05-14 | [Project](https://real2render2real.com/) |  |
| [**Sim-and-Real Co-Training: A Simple Recipe for Vision-Based Robotic Manipulation**](https://arxiv.org/abs/2405.10020) | RSS 2025 | 2025-03-31 | [Project](https://co-training.github.io/) |  |
| [**Robot Policy Evaluation for Sim-to-Real Transfer: A Benchmarking Perspective**](https://arxiv.org/abs/2508.11117) | RSSW 2025 | 2025-08-14 | - |  |
| [**ScissorBot: Learning Generalizable Scissor Skill for Paper Cutting via Simulation, Imitation, and Sim2Real**](https://arxiv.org/abs/2409.13966) | CoRL 2024 | 2024-09-21 | ![Star](https://img.shields.io/github/stars/jiangranlv/ScissorBot?style=social&label=Star) [GitHub](https://github.com/jiangranlv/ScissorBot) |  |
| [Maniwhere: **Learning to Manipulate Anywhere: A Visual Generalizable Framework For Reinforcement Learning**](https://arxiv.org/abs/2407.15815) | CoRL 2024 | 2024-07-22 | [Project](https://gemcollector.github.io/maniwhere/) |  |
| [**Natural Language Can Help Bridge the Sim2Real Gap**](https://arxiv.org/abs/2405.10020) | RSS 2024 | 2024-05-16 | ![Star](https://img.shields.io/github/stars/UT-Austin-RobIn/lang4sim2real?style=social&label=Star) [GitHub](https://github.com/UT-Austin-RobIn/lang4sim2real) |  |
| [RialTo: **Reconciling Reality through Simulation: A Real-to-Sim-to-Real Approach for Robust Manipulation**](https://arxiv.org/abs/2403.03949) | RSS 2024 | 2024-03-06 | ![Star](https://img.shields.io/github/stars/real-to-sim-to-real/RialToPolicyLearning?style=social&label=Star) [GitHub](https://github.com/real-to-sim-to-real/RialToPolicyLearning) |  |
| [**Practical Visual Deep Imitation Learning via Task-Level Domain Consistency**](https://ieeexplore.ieee.org/document/10161202) | ICRA 2023 | 2023-07-04 | - |  |
| [**RetinaGAN: An Object-aware Approach to Sim-to-Real Transfer**](https://arxiv.org/abs/2011.03148) | ICRA 2021 | 2020-11-06 | [Project](https://retinagan.github.io/) |  |
| [**Self-Supervised Sim-to-Real Adaptation for Visual Robotic Manipulation**](https://arxiv.org/abs/1910.09470) | ICRA 2020 | 2019-10-21 | - |  |
| [**Transferring Visuomotor Learning from Simulation to the Real World for Robotics Manipulation Tasks**](https://ieeexplore.ieee.org/document/8594519) | IROS 2018 | 2019-01-06 | - |  |
| [**Sim-to-Real Transfer of Robotic Control with Dynamics Randomization**](https://arxiv.org/abs/1710.06537) | ICRA 2018 | 2017-10-18 | - |  |
| [**Transferring End-to-End Visuomotor Control from Simulation to Real World for a Multi-Stage Task**](https://arxiv.org/abs/1707.02267) | CoRL 2017 | 2017-07-07 | - |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### SE(3)/SIM(3)-Equivariance/View Changes
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**ARGUS: Aligning Robot Scene Geometry Under Shifting Views with Large 3D Vision Models**](https://arxiv.org/abs/2608.05579) | arXiv | 2026-08-06 | [Project](https://rsathua.github.io/ARGUS/) | |
| [**OC-VLA++: Monocular Geometry-Guided Cross-View Consistency for Viewpoint-Robust Robotic Manipulation**](https://arxiv.org/abs/2608.01066) | arXiv | 2026-08-02 | - | |
| [**Pix2Act: Image-Space Manipulation Policies with Equivariant Augmentation**](https://arxiv.org/abs/2607.11167) | arXiv | 2026-07-13 | [Project](https://haojhuang.github.io/pix2act_page/) | |
| [**From Fixed to Free Cameras: Calibration-Free View-Robust Vision-Language-Action Model**](https://arxiv.org/abs/2607.05396) | arXiv | 2026-07-06 | [Project](https://alibaba-damo-academy.github.io/CamVLA/) | |
| [**Learning to See While Learning to Act: Diffusion Models for Active Perception in Robot Imitation**](https://arxiv.org/abs/2606.23625) | arXiv | 2026-06-22 | [Project](https://see2act.github.io/) | |
| [**UniviewVLA: A Unified Multiview Vision-Language-Action Model with World Modeling**](https://arxiv.org/abs/2606.21501) | arXiv | 2026-06-19 | [Project](https://sii-quantum.github.io/MultiviewVLA.github.io/) | |
| [**OASIS: Observation-Action Space Alignment via SE(3) Trajectory Prediction for Robotic Manipulation**](https://arxiv.org/abs/2605.25829) | arXiv | 2026-05-25 | [Project](https://npuhandsome.github.io/OASIS_web/) | |
| [**Efficient Camera Pose Augmentation for View Generalization in Robotic Policy Learning**](https://arxiv.org/abs/2603.29192) | arXiv | 2026-03-31 | ![Star](https://img.shields.io/github/stars/SanMumumu/GenSplat?style=social&label=Star) [GitHub](https://github.com/SanMumumu/GenSplat) | |
| [**AnyCamVLA: Zero-Shot Camera Adaptation for Viewpoint Robust Vision-Language-Action Models**](https://arxiv.org/abs/2603.05868) | arXiv | 2026-03-06 | - | |
| [**EquiForm: Noise-Robust SE(3)-Equivariant Policy Learning from 3D Point Clouds**](https://arxiv.org/abs/2601.17486) | arXiv | 2026-01-24 | [Project](https://zhangzhiyuanzhang.github.io/equiform-website/) | |
| [**Sim2real Image Translation Enables Viewpoint-Robust Policies from Fixed-Camera Datasets**](https://arxiv.org/abs/2601.09605) | arXiv | 2026-01-14 | [Project](https://sites.google.com/view/sim2real-viewpoints) | |
| [**Learning to Act Robustly with View-Invariant Latent Actions**](https://arxiv.org/abs/2601.02994) | arXiv | 2026-01-06 | [Project](https://joon-stack.github.io/VILA/) | |
| [**Bridging Simulation and Reality: Cross-Domain Transfer with Semantic 2D Gaussian Splatting**](https://arxiv.org/abs/2512.04731) | arXiv | 2025-12-04 | - | |
| [**Eq.Bot: Enhance Robotic Manipulation Learning via Group Equivariant Canonicalization**](https://arxiv.org/abs/2511.15194) | arXiv | 2025-11-19 | - | |
| [**EgoMI: Learning Active Vision and Whole-Body Manipulation from Egocentric Human Demonstrations**](https://arxiv.org/abs/2511.00153) | arXiv | 2025-10-31 | [Project](https://egocentric-manipulation-interface.github.io/) | |
| [**SaPaVe: Towards Active Perception and Manipulation in Vision-Language-Action Models for Robotics**](https://arxiv.org/abs/2603.12193) | CVPR 2026 | 2026-03-12 | [Project](https://lmzpai.github.io/SaPaVe/) | |
| [**Efficient Hybrid SE(3)-Equivariant Visuomotor Flow Policy via Spherical Harmonics for Robot Manipulation**](https://arxiv.org/abs/2603.23227) | CVPR 2026 | 2026-03-24 | ![Star](https://img.shields.io/github/stars/zql-kk/E3Flow?style=social&label=Star) [GitHub](https://github.com/zql-kk/E3Flow) | |
| [**Do You Know Where Your Camera Is? View-Invariant Policy Learning with Camera Conditioning**](https://arxiv.org/abs/2510.02268) | arXiv | 2025-10-02 | [Project](https://ripl.github.io/know_your_camera/) | |
| [**VistaBot: View-Robust Robot Manipulation via Spatiotemporal-Aware View Synthesis**](https://arxiv.org/abs/2604.21914) | ICRA 2026 | 2026-04-23 | - | |
| [**ManiVID-3D: Generalizable View-Invariant Reinforcement Learning for Robotic Manipulation via Disentangled 3D Representations**](https://arxiv.org/abs/2509.11125) | RA-L 2026 | 2025-09-14 | ![Star](https://img.shields.io/github/stars/Zheng-Joe-Lee/ManiVID-3D?style=social&label=Star) [GitHub](https://github.com/Zheng-Joe-Lee/ManiVID-3D) | |
| [**Imitation Learning for Active Neck Motion Enabling Robot Manipulation beyond the Field of View**](https://arxiv.org/abs/2506.17624) | arXiv | 2025-06-21 | - | View Changes |
| [**Vision in Action: Learning Active Perception from Human Demonstrations**](https://arxiv.org/abs/2506.15666) | CoRL 2025 | 2025-06-18 | ![Star](https://img.shields.io/github/stars/haoyu-x/vision-in-action?style=social&label=Star) [GitHub](https://github.com/haoyu-x/vision-in-action) | |
| [**Adapt3R: Adaptive 3D Scene Representation for Domain Transfer in Imitation Learning**](https://arxiv.org/abs/2503.04877) | CoRL 2025 | 2025-03-06 | ![Star](https://img.shields.io/github/stars/pairlab/Adapt3R?style=social&label=Star) [GitHub](https://github.com/pairlab/Adapt3R) | View Changes & Cross-Embodiment |
| [**ET-SEED: Efficient Trajectory-Level SE(3) Equivariant Diffusion Policy**](https://arxiv.org/abs/2411.03990) | ICLR 2025 | 2024-11-06 | ![Star](https://img.shields.io/github/stars/yuechen0614/ET-SEED?style=social&label=Star) [GitHub](https://github.com/yuechen0614/ET-SEED) |  |
| [**EquiBot: SIM(3)-Equivariant Diffusion Policy for Generalizable and Data Efficient Learning**](https://arxiv.org/abs/2407.01479) | CoRL 2024 | 2024-07-01 | ![Star](https://img.shields.io/github/stars/yjy0625/equibot?style=social&label=Star) [GitHub](https://github.com/yjy0625/equibot) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Lighting/background/distractor Changes
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Inductive Generalization for Robotic Manipulation**](https://arxiv.org/abs/2606.20999) | arXiv | 2026-06-19 | - |  |
| [**GraspALL: Adaptive Structural Compensation from Illumination Variation for Robotic Garment Grasping in Any Low-Light Conditions**](https://arxiv.org/abs/2603.14789) | arXiv | 2026-03-16 | ![Star](https://img.shields.io/github/stars/Zhonghaifeng6/GraspALL?style=social&label=Star) [GitHub](https://github.com/Zhonghaifeng6/GraspALL) |  |
| [**PALM: Enhanced Generalizability for Local Visuomotor Policies via Perception Alignment**](https://arxiv.org/abs/2601.19514) | RA-L 2026 | 2026-01-27 | - |  |
| [**RoboView-Bias: Benchmarking Visual Bias in Embodied Agents for Robotic Manipulation**](https://arxiv.org/abs/2509.22356) | arXiv | 2025-09-26 | - |  |
| [**Towards Exploratory and Focused Manipulation with Bimanual Active Perception: A New Problem, Benchmark and Strategy**](https://arxiv.org/abs/2602.01939) | ICRA 2026 | 2026-02-02 | [Project](https://efmanipulation.github.io/) |  |
| [**Physically-based Lighting Augmentation for Robotic Manipulation**](https://www.arxiv.org/abs/2508.01442) | arXiv | 2025-08-02 | - | Lighting Changes |
| [**Is an object-centric representation beneficial for robotic manipulation?**](https://arxiv.org/abs/2506.19408) | ROBOVIS 2025 | 2025-06-24 | - |  |
| [**SwitchVLA: Execution-Aware Task Switching for Vision-Language-Action Models**](https://arxiv.org/abs/2506.03574) | IROSW 2025 | 2025-06-04 | [Project](https://switchvla.github.io/) | |
| [**Diffusion-VLA: Scaling Robot Foundation Models via Unified Diffusion and Autoregression**](https://arxiv.org/abs/2412.03293) | ICML 2025 | 2024-12-14 | [Project](https://diffusion-vla.github.io/) |  |
| [**Decomposing the Generalization Gap in Imitation Learning for Visual Robotic Manipulation**](https://arxiv.org/abs/2307.03659) | ICRA 2024 | 2024-02-29 | ![Star](https://img.shields.io/github/stars/RLAgent/factor-world?style=social&label=Star) [GitHub](https://github.com/RLAgent/factor-world) | 
| [**Robot Learning from Human Demonstrations with Inconsistent Contexts**](https://www.sciencedirect.com/science/article/pii/S0921889023001057) | RAS 2023 | 2023-06-01 | - |  |
| [**Spatial Generalization of Visual Imitation Learning with Position-Invariant Regularization**](https://openreview.net/forum?id=N00uQFLlvHC) | RSSW 2023 | 2023-06-24 | - | Position Changes |
| [**Cross-context Visual Imitation Learning from Demonstrations**](https://ieeexplore.ieee.org/document/9196868) | ICRA 2020 | 2020-09-16 | [Project](https://vsislab.github.io/ccvil/) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>



<!-- Cross-Embodiment Generalization -->
<div align="center">

### <i>Cross-Embodiment Generalization</i>

</div>

<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**C2Dex: Contact-Consistent Reconstruction and Retargeting for Dexterous Manipulation from Monocular Video**](https://arxiv.org/abs/2608.07045) | arXiv | 2026-08-07 | ![Star](https://img.shields.io/github/stars/K-Jie/C2Dex_code?style=social&label=Star) [GitHub](https://github.com/K-Jie/C2Dex_code) |
| [**UniCross: Unified Cross-Skill Dexterous Manipulation Synthesis**](https://arxiv.org/abs/2607.28198) | arXiv | 2026-07-30 | [Project](https://zdchan.github.io/UniCross/) |
| [**AnyDexRT: Calibration-Free Dexterous Hand Retargeting with Few-Shot Human Guidance**](https://arxiv.org/abs/2607.08341) | arXiv | 2026-07-09 | [Project](https://chenxi-wang.github.io/projects/anydexrt/) |
| [**Translation as a Bridging Action: Transferring Manipulation Skills from Humans to Robots**](https://arxiv.org/abs/2606.28133) | arXiv | 2026-06-26 | [Project](https://translation-as-a-bridging-action.github.io/) |
| [**SPACE: Enabling Learning from Cross-Robot Data Toward Generalist Policies**](https://arxiv.org/abs/2606.24049) | arXiv | 2026-06-23 | [Project](https://haeone.site/space-website/) |  |
| [**EmbodiSteer: Steering Embodiment-Agnostic Visuomotor Policies with Joint-Space Guidance for Zero-Shot Cross-Embodiment Deployment**](https://arxiv.org/abs/2606.12965) | arXiv | 2026-06-11 | [Project](https://frankwang67.github.io/EmbodiSteer-Page/) |  |
| [**Imitation from Heterogeneous Demonstrations using Grounded Latent-Action World Models**](https://arxiv.org/abs/2606.21672) | arXiv | 2026-06-19 | [Project](https://viccccciv.github.io/glam/) |  |
| [**LUCID: Learning Embodiment-Agnostic Intent Models from Unstructured Human Videos for Scalable Dexterous Robot Skill Acquisition**](https://arxiv.org/abs/2606.11628) | arXiv | 2026-06-10 | [Project](https://lucid-robot.github.io/) |  |
| [**Hand-centric Human-to-Robot Trajectory Transfer from Video Demonstrations via Open-World Contact Localization**](https://arxiv.org/abs/2606.10743) | arXiv | 2026-06-09 | - |  |
| [**GraspGen-X: Cross-Embodiment 6-DOF Diffusion-based Grasping**](https://arxiv.org/abs/2606.00998) | arXiv | 2026-05-31 | ![Star](https://img.shields.io/github/stars/NVlabs/GraspGenX?style=social&label=Star) [GitHub](https://github.com/NVlabs/GraspGenX) |  |
| [**X-DiffVLA: X-Embodied Diffusion Action Heads for Vision-Language-Action Models**](https://arxiv.org/abs/2605.25044) | arXiv | 2026-05-24 | - |  |
| [**HumanEgo: Zero-Shot Robot Learning from Minutes of Human Egocentric Videos**](https://arxiv.org/abs/2605.24934) | arXiv | 2026-05-24 | ![Star](https://img.shields.io/github/stars/TX-Leo/HumanEgo?style=social&label=Star) [GitHub](https://github.com/TX-Leo/HumanEgo) |  |
| [**Demo-JEPA: Joint-Embedding Predictive Architecture for One-shot Cross-Embodiment Imitation**](https://arxiv.org/abs/2605.20811) | arXiv | 2026-05-20 | ![Star](https://img.shields.io/github/stars/banban3forever/Demo-JEPA?style=social&label=Star) [GitHub](https://github.com/banban3forever/Demo-JEPA) |  |
| [**RIO: Flexible Real-Time Robot I/O for Cross-Embodiment Robot Learning**](https://arxiv.org/abs/2605.11564) | RSS 2026 | 2026-05-12 | ![Star](https://img.shields.io/github/stars/robot-i-o/rio?style=social&label=Star) [GitHub](https://github.com/robot-i-o/rio) |  |
| [**LIDEA: Human-to-Robot Imitation Learning via Implicit Feature Distillation and Explicit Geometry Alignment**](https://arxiv.org/abs/2604.10677) | arXiv | 2026-04-12 | [Project](https://yifuxu1127.github.io/LIDEA/) |  |
| [**Cross-Embodiment Transfer via Behavior-Aligned Representations**](https://arxiv.org/abs/2607.27549) | ICRA 2026 | 2026-07-30 | ![Star](https://img.shields.io/github/stars/ajaysridhar0/barx?style=social&label=Star) [GitHub](https://github.com/ajaysridhar0/barx) |
| [**MonoDuo: Using One Robot Arm to Learn Bimanual Policies**](https://arxiv.org/abs/2605.29298) | ICRA 2026 | 2026-05-28 | [Project](https://bimanual-monoduo.github.io/) |  |
| [**One-Policy-Fits-All: Geometry-Aware Action Latents for Cross-Embodiment Manipulation**](https://arxiv.org/abs/2603.14522) | ICRA 2026 | 2026-03-15 | [Project](https://mujc2021.github.io/opfa/) |  |
| [**Data Analogies Enable Efficient Cross-Embodiment Transfer**](https://arxiv.org/abs/2603.06450) | arXiv | 2026-03-06 | - |  |
| [**Embedding Morphology into Transformers for Cross-Robot Policy Learning**](https://arxiv.org/abs/2603.00182) | arXiv | 2026-02-26 | - |  |
| [**MOTIF: Learning Action Motifs for Few-shot Cross-Embodiment Transfer**](https://arxiv.org/abs/2602.13764) | arXiv | 2026-02-14 | ![Star](https://img.shields.io/github/stars/buduz/MOTIF?style=social&label=Star) [GitHub](https://github.com/buduz/MOTIF) |  |
| [**LAP: Language-Action Pre-Training Enables Zero-shot Cross-Embodiment Transfer**](https://arxiv.org/abs/2602.10556) | arXiv | 2026-02-11 | ![Star](https://img.shields.io/github/stars/lihzha/lap?style=social&label=Star) [GitHub](https://github.com/lihzha/lap) |  |
| [**Sim-and-Human Co-training for Data-Efficient and Generalizable Robotic Manipulation**](https://arxiv.org/abs/2601.19406) | arXiv | 2026-01-27 | ![Star](https://img.shields.io/github/stars/kaipengfang/SimHum?style=social&label=Star) [GitHub](https://github.com/kaipengfang/SimHum) |  |
| [**CEI: A Unified Interface for Cross-Embodiment Visuomotor Policy Learning in 3D Space**](https://arxiv.org/abs/2601.09163) | RA-L 2026 | 2026-01-14 | [Project](https://cross-embodiment-interface.github.io/) |  |
| [**X-Diffusion: Training Diffusion Policies on Cross-Embodiment Human Demonstrations**](https://arxiv.org/abs/2511.04671) | arXiv | 2025-11-06 | [Project](https://portal-cornell.github.io/X-Diffusion/) |  |
| [**Trajectory Conditioned Cross-embodiment Skill Transfer**](https://arxiv.org/abs/2510.07773) | arXiv | 2025-10-09 | - |  |
| [**MV-UMI: A Scalable Multi-View Interface for Cross-Embodiment Learning**](https://arxiv.org/abs/2509.18757) | arXiv | 2025-09-23 | [Project](https://mv-umi.github.io/) |  |
| [**From Human Hands to Robot Arms: Manipulation Skills Transfer via Trajectory Alignment**](https://arxiv.org/abs/2510.00491) | arXiv | 2025-10-01 | [Project](https://anonymous.4open.science/w/Traj2Action-4A45/) |  |
| [**UniPrototype: Human-Robot Skill Learning with Uniform Prototypes**](https://arxiv.org/abs/2509.23021) | arXiv | 2025-09-27 | - |  |
| [**Prepare Before You Act: Learning From Humans to Rearrange Initial States**](https://arxiv.org/abs/2509.18043) | arXiv | 2025-09-22 | [Project](https://reset2025paper.github.io/) |  |
| [**MotionTrans: Human VR Data Enable Motion-Level Learning for Robotic Manipulation Policies**](https://arxiv.org/abs/2509.17759) | arXiv | 2025-09-22 | ![Star](https://img.shields.io/github/stars/michaelyuancb/motiontrans?style=social&label=Star) [GitHub](https://github.com/michaelyuancb/motiontrans) |  |
| [**Tenma: Robust Cross-Embodiment Robot Manipulation with Diffusion Transformer**](https://arxiv.org/abs/2509.11865) | arXiv | 2025-09-15 | - |  |
| [**3DFlowAction: Learning Cross-Embodiment Manipulation from 3D Flow World Model**](https://arxiv.org/abs/2506.06199) | arXiv | 2025-06-06 | ![Star](https://img.shields.io/github/stars/Hoyyyaard/3DFlowAction?style=social&label=Star) [GitHub](https://github.com/Hoyyyaard/3DFlowAction/) |  |
| [**RoboOS: A Hierarchical Embodied Framework for Cross-Embodiment and Multi-Agent Collaboration**](https://arxiv.org/abs/2505.03673) | arXiv | 2025-05-06 | ![Star](https://img.shields.io/github/stars/FlagOpen/RoboOS?style=social&label=Star) [GitHub](https://github.com/FlagOpen/RoboOS) |  |
| [**ImMimic: Cross-Domain Imitation from Human Videos via Mapping and Interpolation**](https://arxiv.org/abs/2509.10952) | CoRL 2025 | 2025-09-13 | ![Star](https://img.shields.io/github/stars/GaTech-RL2/ImMimic-CoRL2025?style=social&label=Star) [GitHub](https://github.com/GaTech-RL2/ImMimic-CoRL2025) |  |
| [**X-Sim: Cross-Embodiment Learning via Real-to-Sim-to-Real**](http://arxiv.org/abs/2505.07096) | CoRL 2025 | 2025-05-11 | ![Star](https://img.shields.io/github/stars/portal-cornell/X-Sim?style=social&label=Star) [GitHub](https://github.com/portal-cornell/X-Sim) |  |
| [**Crossing the Human-Robot Embodiment Gap with Sim-to-Real RL using One Human Demonstration**](https://arxiv.org/abs/2504.12609) | CoRL 2025 | 2025-04-17 | ![Star](https://img.shields.io/github/stars/tylerlum/human2sim2robot?style=social&label=Star) [GitHub](https://github.com/tylerlum/human2sim2robot) |  |
| [**EgoBridge: Domain Adaptation for Generalizable Imitation from Egocentric Human Data**](https://arxiv.org/abs/2509.19626) | NeurIPS 2025 | 2025-09-23 | [Project](https://ego-bridge.github.io/) |  |
| [**UniSkill: Imitating Human Videos via Cross-Embodiment Skill Representations**](https://arxiv.org/abs/2505.08787) | CoRL 2025 | 2025-05-13 | ![Star](https://img.shields.io/github/stars/KimHanjung/UniSkill?style=social&label=Star) [GitHub](https://github.com/KimHanjung/UniSkill) |  |
| [**AnyBimanual: Transferring Unimanual Policy for General Bimanual Manipulation**](https://arxiv.org/abs/2412.06779) | ICCV 2025 | 2024-12-09 | ![Star](https://img.shields.io/github/stars/Tengbo-Yu/AnyBimanual?style=social&label=Star) [GitHub](https://github.com/Tengbo-Yu/AnyBimanual) |  |
| [**LEGATO: Cross-Embodiment Imitation Using a Grasping Tool**](https://arxiv.org/abs/2411.03682) | RA-L 2025 | 2024-11-06 | ![Star](https://img.shields.io/github/stars/UT-HCRL/LEGATO?style=social&label=Star) [GitHub](https://github.com/UT-HCRL/LEGATO) | |
| [**Cross-Embodiment Robot Manipulation Skill Transfer using Latent Space Alignment**](https://arxiv.org/abs/2406.01968) | arXiv | 2024-06-04 | ![Star](https://img.shields.io/github/stars/ExistentialRobotics/cross_embodiment_transfer?style=social&label=Star) [GitHub](https://github.com/ExistentialRobotics/cross_embodiment_transfer) | |
| [HPT: **Scaling Proprioceptive-Visual Learning with Heterogeneous Pre-trained Transformers**](https://arxiv.org/abs/2409.20537) | NeurIPS 2024 | 2024-09-30 | ![Star](https://img.shields.io/github/stars/liruiw/HPT?style=social&label=Star) [GitHub](https://github.com/liruiw/HPT) |  |
| [CrossFormer: **Scaling Cross-Embodied Learning: One Policy for Manipulation, Navigation, Locomotion and Aviation**](https://arxiv.org/abs/2408.11812) | CoRL 2024 | 2024-08-21 | ![Star](https://img.shields.io/github/stars/rail-berkeley/crossformer?style=social&label=Star) [GitHub](https://github.com/rail-berkeley/crossformer) | Cross-Embodied |
| [**Pushing the Limits of Cross-Embodiment Learning for Manipulation and Navigation**](https://arxiv.org/abs/2402.19432) | RSS 2024 | 2024-02-29 | ![Star](https://img.shields.io/github/stars/JonathanYang0127/omnimimic?style=social&label=Star) [GitHub](https://github.com/JonathanYang0127/omnimimic) | |
| [**Mirage: Cross-Embodiment Zero-Shot Policy Transfer with Cross-Painting**](https://arxiv.org/abs/2402.19249) | RSS 2024 | 2024-02-29 | ![Star](https://img.shields.io/github/stars/BerkeleyAutomation/mirage?style=social&label=Star) [GitHub](https://github.com/BerkeleyAutomation/mirage) | |
| [**XSkill: Cross Embodiment Skill Discovery**](https://arxiv.org/abs/2307.09955) | CoRL 2023 | 2023-07-19 | ![Star](https://img.shields.io/github/stars/real-stanford/xskill?style=social&label=Star) [GitHub](https://github.com/real-stanford/xskill) | |
| [**Modularity through Attention: Efficient Training and Transfer of Language-Conditioned Policies for Robot Manipulation**](https://arxiv.org/abs/2212.04573) | CoRL 2022 | 2022-12-08 | ![Star](https://img.shields.io/github/stars/ir-lab/ModAttn?style=social&label=Star) [GitHub](https://github.com/ir-lab/ModAttn) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>


## Agent
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Zetta ζ: An Efficient Closed-Loop Embodied Harness for Self-Evolving Physical Intelligence**](https://arxiv.org/abs/2608.16590) | arXiv | 2026-08-17 | ![Star](https://img.shields.io/github/stars/air-embodied-brain/Zetta-Embodiment?style=social&label=Star) [GitHub](https://github.com/air-embodied-brain/Zetta-Embodiment) | |
| [**Practice Makes Policies: Bootstrapping and Consolidating Robotic Capabilities from Zero Human Demonstrations**](https://arxiv.org/abs/2607.26809) | arXiv | 2026-07-29 | - | |
| [**Addressing the Orchestration Gap in Generalist Robots via Physical Agency**](https://arxiv.org/abs/2607.21725) | arXiv | 2026-07-23 | ![Star](https://img.shields.io/github/stars/lianegalanti/Pigey?style=social&label=Star) [GitHub](https://github.com/lianegalanti/Pigey) | |
| [**RoboHarness: Memory-Driven Orchestration of Heterogeneous Robot Policies for Long-Horizon Planning**](https://arxiv.org/abs/2607.18060) | arXiv | 2026-07-20 | - | |
| [**In-Context VLA: Endowing Vision-Language-Action Models with Language via In-Context Post-Training and Agentic Tool Use**](https://arxiv.org/abs/2608.05738) | arXiv | 2026-08-06 | ![Star](https://img.shields.io/github/stars/robo-architect/architect-franka?style=social&label=Star) [GitHub](https://github.com/robo-architect/architect-franka) | |
| [**A Few Words Go a Long Way: Language Guided Robot Policy Synthesis**](https://arxiv.org/abs/2607.23784) | arXiv | 2026-07-26 | ![Star](https://img.shields.io/github/stars/robo-architect/architect-franka?style=social&label=Star) [GitHub](https://github.com/robo-architect/architect-franka) | |
| [**PhyAgentOS: A Self-Evolving Operating System for Embodied Agents with Decoupled Cognitive Planning and Physical Execution**](https://arxiv.org/abs/2607.16636) | arXiv | 2026-07-18 | ![Star](https://img.shields.io/github/stars/PhyAgentOS-Dev/PhyAgentOS?style=social&label=Star) [GitHub](https://github.com/PhyAgentOS-Dev/PhyAgentOS) | |
| [**PhysClaw-0: A Symbiotic Agentic System for Robot Autonomy via Language Corrections**](https://arxiv.org/abs/2607.14047) | arXiv | 2026-07-15 | [Project](https://open-gigaai.github.io/PhysClaw) | |
| [**A Glimpse into Long-term Physical Coexistence with Intelligent Robots**](https://arxiv.org/abs/2607.11377) | arXiv | 2026-07-13 | [Project](https://www.astribot.com/en/research/Philia) | |
| [**VIA: Visual Interface Agent for Robot Control**](https://arxiv.org/abs/2607.11119) | arXiv | 2026-07-13 | - | |
| [**Harness VLA: Steering Frozen VLAs into Reliable Manipulation Primitives via Memory-Guided Agents**](https://arxiv.org/abs/2607.08448) | arXiv | 2026-07-09 | [Project](https://harnessvla.github.io/) | |
| [**A Closed-Loop Multi-Agent Framework for Robust Multi-Robot Manipulation**](https://arxiv.org/abs/2607.06990) | arXiv | 2026-07-08 | - | |
| [**ENPIRE: Agentic Robot Policy Self-Improvement in the Real World**](https://arxiv.org/abs/2606.19980) | arXiv | 2026-06-18 | [Project](https://research.nvidia.com/labs/gear/enpire/) | |
| [**Guava: An Effective and Universal Harness for Embodied Manipulation**](https://arxiv.org/abs/2606.18363) | arXiv | 2026-06-16 | [Project](https://guava-harness.github.io/) | |
| [**Agentic-VLA: Efficient Online Adaptation for Vision-Language-Action Models**](https://arxiv.org/abs/2605.22896) | arXiv | 2026-05-21 | - | |
| [**Towards Long-horizon Embodied Agents with Tool-Aligned Vision-Language-Action Models**](https://arxiv.org/abs/2605.13119) | arXiv | 2026-05-13 | - | |
| [**Nautilus: From One Prompt to Plug-and-Play Robot Learning**](https://arxiv.org/abs/2605.11665) | arXiv | 2026-05-12 | - | |
| [**Long-Term Memory for VLA-based Agents in Open-World Task Execution**](https://arxiv.org/abs/2604.15671) | arXiv | 2026-04-17 | - | |
| [**ABot-Claw: A Foundation for Persistent, Cooperative, and Self-Evolving Robotic Agents**](https://arxiv.org/abs/2604.10096) | arXiv | 2026-04-11 | ![Star](https://img.shields.io/github/stars/amap-cvlab/ABot-Claw?style=social&label=Star) [GitHub](https://github.com/amap-cvlab/ABot-Claw) | |
| [**SOMA: Strategic Orchestration and Memory-Augmented System for Vision-Language-Action Model Robustness via In-Context Adaptation**](https://arxiv.org/abs/2603.24060) | arXiv | 2026-03-25 | ![Star](https://img.shields.io/github/stars/LZY-1021/SOMA?style=social&label=Star) [GitHub](https://github.com/LZY-1021/SOMA) | |
| [**RoboClaw: An Agentic Framework for Scalable Long-Horizon Robotic Tasks**](https://arxiv.org/abs/2603.11558) | ECCV 2026 | 2026-03-12 | ![Star](https://img.shields.io/github/stars/RoboClaw-Robotics/RoboClaw?style=social&label=Star) [GitHub](https://github.com/RoboClaw-Robotics/RoboClaw) | |
| [**Decompose and Recompose: Reasoning New Skills from Existing Abilities for Cross-Task Robotic Manipulation**](https://arxiv.org/abs/2605.01448) | ICML 2026 | 2026-05-02 | - | |
| [**Evolve Vision-Language-Action Model into an Agent with On-the-fly Tool-use**](https://arxiv.org/abs/2608.14047) | CVPRF 2026 | 2026-08-14 | - | |
| [**VLA<sup>2</sup>: Empowering Vision-Language-Action Models with an Agentic Framework for Unseen Concept Manipulation**](https://arxiv.org/abs/2510.14902) | arXiv | 2025-10-16 | ![Star](https://img.shields.io/github/stars/OpenHelix-Team/VLA-2?style=social&label=Star) [GitHub](https://github.com/OpenHelix-Team/VLA-2) | |
| [**Agentic Robot: A Brain-Inspired Framework for Vision-Language-Action Models in Embodied Agents**](https://arxiv.org/abs/2505.23450) | arXiv | 2025-05-29 | ![Star](https://img.shields.io/github/stars/Agentic-Robot/agentic-robot?style=social&label=Star) [GitHub](https://github.com/Agentic-Robot/agentic-robot) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>


## Human-Robot Interaction and Collaboration
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**From Perception to Assistance: Open-Vocabulary Shared Autonomy for Robotic Manipulation**](https://arxiv.org/abs/2607.17323) | arXiv | 2026-07-19 | ![Star](https://img.shields.io/github/stars/EESC-LabRoM/open-vocab-shared-autonomy?style=social&label=Star) [GitHub](https://github.com/EESC-LabRoM/open-vocab-shared-autonomy) |  |
| [**Robots that Collaborate: Sequential Asymmetric Imitation for Learning Coupled Robot Policies**](https://arxiv.org/abs/2606.16490) | arXiv | 2026-06-15 | [Project](https://cyc0429.github.io/sai-project-page/) |  |
| [**Hierarchical Policies from Verbal and Egocentric Human Signals for Natural Human-Robot Interaction**](https://arxiv.org/abs/2606.10276) | arXiv | 2026-06-09 | [Project](https://project-edith.github.io/) |  |
| [**NeuroCommitSSM: Decision-Centric Shared Autonomy for Safe Assistive Manipulation via EEG-EMG-ET Commit Readiness**](https://arxiv.org/abs/2607.15395) | IROS 2026 | 2026-07-16 | ![Star](https://img.shields.io/github/stars/madibabaiasl/NeuroCommitSSM?style=social&label=Star) [GitHub](https://github.com/madibabaiasl/NeuroCommitSSM) |  |
| [**Assistance Without Interruption: A Benchmark and LLM-based Framework for Non-Intrusive Human-Robot Assistance**](https://arxiv.org/abs/2605.01368) | IROS 2026 | 2026-05-02 | ![Star](https://img.shields.io/github/stars/Cognition2Action-Lab/NIABench?style=social&label=Star) [GitHub](https://github.com/Cognition2Action-Lab/NIABench) |  |
| [**Shared Autonomy Assisted by Impedance-Driven Anisotropic Guidance Field**](https://arxiv.org/abs/2605.02410) | RA-L 2026 | 2026-05-04 | - |  |
| [**OmniRobotHome: A Multi-Camera Platform for Real-Time Multiadic Human-Robot Interaction**](https://arxiv.org/abs/2604.28197) | arXiv | 2026-04-30 | [Project](https://junc0ng.github.io/omnirobothome/) |  |
| [**M2HRI: An LLM-Driven Multimodal Multi-Agent Framework for Personalized Human-Robot Interaction**](https://arxiv.org/abs/2604.11975) | arXiv | 2026-04-13 | ![Star](https://img.shields.io/github/stars/project-m2hri/m2hri?style=social&label=Star) [GitHub](https://github.com/project-m2hri/m2hri) |  |
| [**Generative Simulation for Policy Learning in Physical Human-Robot Interaction**](https://arxiv.org/abs/2604.08664) | arXiv | 2026-04-09 | [Project](https://rchi-lab.github.io/gen_phri/) |  |
| [**TATIC: Task-Aware Temporal Learning for Human Intent Inference from Physical Corrections in Human-Robot Collaboration**](https://arxiv.org/abs/2603.11077) | arXiv | 2026-03-10 | - |  |
| [**Sticky-Glance: Robust Intent Recognition for Human Robot Collaboration via Single-Glance**](https://arxiv.org/abs/2603.06121) | arXiv | 2026-03-06 | - |  |
| [**SPIRIT: Perceptive Shared Autonomy for Robust Robotic Manipulation under Deep Learning Uncertainty**](https://arxiv.org/abs/2603.05111) | arXiv | 2026-03-05 | - |  |
| [**Transforming Monolithic Foundation Models into Embodied Multi-Agent Architectures for Human-Robot Collaboration**](https://arxiv.org/abs/2512.00797) | arXiv | 2025-11-30 | - |  |
| [**The Role of Consequential and Functional Sound in Human-Robot Interaction: Toward Audio Augmented Reality Interfaces**](https://arxiv.org/abs/2511.15956) | arXiv | 2025-11-20 | [Project](https://sites.google.com/berkeley.edu/rapl) |  |
| [**I've Changed My Mind: Robots Adapting to Changing Human Goals during Collaboration**](https://arxiv.org/abs/2511.15914) | RA-L 2025 | 2025-11-19 | - |  |
| [**Open-Ended Goal Inference through Actions and Language for Human-Robot Collaboration**](https://arxiv.org/abs/2512.04453) | HRI 2026 | 2025-12-04 | - |  |
| [**Maximizing Alignment with Minimal Feedback: Efficiently Learning Rewards for Visuomotor Robot Policy Alignment**](https://arxiv.org/abs/2412.04835) | arXiv | 2024-12-06 | [Project](https://sites.google.com/berkeley.edu/rapl) |  |
| [**Vocal Sandbox: Continual Learning and Adaptation for Situated Human-Robot Collaboration**](https://openreview.net/pdf?id=ypaYtV1CoG) | CoRL 2024 | 2024-09-06 | [Project](https://vocal-sandbox.github.io/) |  |
| [**APRICOT: Active Preference Learning and Constraint-Aware Task Planning with LLMs**](https://openreview.net/pdf?id=nQslM6f7dW) | CoRL 2024 | - | [Project](https://portal-cornell.github.io/apricot/) |  |
| [**Text2Interaction: Establishing Safe and Preferable Human-Robot Interaction**](https://arxiv.org/abs/2408.06105) | CoRL 2024 | 2024-08-12 | ![Star](https://img.shields.io/github/stars/JakobThumm/text2interaction?style=social&label=Star) [GitHub](https://github.com/JakobThumm/text2interaction) |  |
| [**GenH2R: Learning Generalizable Human-to-Robot Handover via Scalable Simulation, Demonstration, and Imitation**](https://arxiv.org/abs/2401.00929) | CVPR 2024 | 2024-01-01  | ![Star](https://img.shields.io/github/stars/chenjy2003/genh2r?style=social&label=Star) [GitHub](https://github.com/chenjy2003/genh2r)  |
| [KNOWNO: **Robots That Ask For Help: Uncertainty Alignment for Large Language Model Planners**](https://arxiv.org/abs/2307.01928) | CoRL 2023 | 2023-07-04 | [GitHub](https://github.com/google-research/google-research/tree/master/language_model_uncertainty) | |
| [LILAC: **Yell At Your Robot: Improving On-the-Fly from Language Corrections**](https://arxiv.org/abs/2403.12910) | RSS 2024 | 2024-03-19 | ![Star](https://img.shields.io/github/stars/yay-robot/yay_robot?style=social&label=Star) [GitHub](https://github.com/yay-robot/yay_robot) | |
| [YAY Robot: **"No, to the Right" -- Online Language Corrections for Robotic Manipulation via Shared Autonomy**](https://arxiv.org/abs/2301.02555) | HRI 2023 | 2023-01-06 | ![Star](https://img.shields.io/github/stars/Stanford-ILIAD/lilac?style=social&label=Star) [GitHub](https://github.com/Stanford-ILIAD/lilac) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>



## Safety
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**TAIL-Safe: Task-Agnostic Safety Monitoring for Imitation Learning Policies**](https://arxiv.org/abs/2605.01195) | arXiv | 2026-05-02 | ![Star](https://img.shields.io/github/stars/riadahmedunh/tail_safe?style=social&label=Star) [GitHub](https://github.com/riadahmedunh/tail_safe) |  |
| [**VLA-Forget: Vision-Language-Action Unlearning for Embodied Foundation Models**](https://arxiv.org/abs/2604.03956) | arXiv | 2026-04-05 | - |  |
| [**Provably Safe Trajectory Generation for Manipulators Under Motion and Environmental Uncertainties**](https://arxiv.org/abs/2603.09083) | arXiv | 2026-03-10 | - |  |
| [**SafeFlowMPC: Predictive and Safe Trajectory Planning for Robot Manipulators with Learning-based Policies**](https://arxiv.org/abs/2602.12794) | ICRA 2026 | 2026-02-13 | ![Star](https://img.shields.io/github/stars/TU-Wien-ACIN-CDS/SafeFlowMPC?style=social&label=Star) [GitHub](https://github.com/TU-Wien-ACIN-CDS/SafeFlowMPC) |  |
| [**SURE: Safe Uncertainty-Aware Robot-Environment Interaction using Trajectory Optimization**](https://arxiv.org/abs/2602.06864) | arXiv | 2026-02-06 | - |  |
| [**SyncTwin: Fast Digital Twin Construction and Synchronization for Safe Robotic Grasping**](https://arxiv.org/abs/2601.09920) | arXiv | 2026-01-14 | - |  |
| [**ContactRL: Safe Reinforcement Learning based Motion Planning for Contact based Human Robot Collaboration**](https://arxiv.org/abs/2512.03707) | arXiv | 2025-12-03 | ![Star](https://img.shields.io/github/stars/SMulkana/ContactRL?style=social&label=Star) [GitHub](https://github.com/SMulkana/ContactRL) |  |
| [**Gated Uncertainty-Aware Runtime Dual Invariants for Neural Signal-Controlled Robotics**](https://arxiv.org/abs/2511.20570) | NeurIPS 2025 | 2025-11-25 | - |  |
| [**Safe and Stable Neural Network Dynamical Systems for Robot Motion Planning**](https://arxiv.org/abs/2511.20593) | arXiv | 2025-11-25 | - |  |
| [**SM2ITH: Safe Mobile Manipulation with Interactive Human Prediction via Task-Hierarchical Bilevel Model Predictive Control**](https://arxiv.org/abs/2511.17798) | arXiv | 2025-11-21 | - |  |
| [**Safe and Optimal Variable Impedance Control via Certified Reinforcement Learning**](https://arxiv.org/abs/2511.16330) | arXiv | 2025-11-20 | - |  |
| [**What You Don't Know Can Hurt You: How Well do Latent Safety Filters Understand Partially Observable Safety Constraints?**](https://arxiv.org/abs/2510.06492) | arXiv | 2025-10-07 | [Project](https://cmu-intentlab.github.io/multisafe/) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>
