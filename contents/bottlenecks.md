<h2 id="table-of-contents">🏠 Table of Contents</h2>

- Bottlenecks
    - [Data Collection and Utilization](#data-collection-and-utilization)
        - [Data Collection](#data-collection)
            - [Human Teleoperation](#human-teleoperation)
            - [Human-in-the-Loop Enhancement](#human-in-the-Loop-enhancement)
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
            - [Incremental Learning](#incremental-learning)
            - [Test-Time Adaptation](#test-time-adaptation)
        - [Environment Generalization](#environment-generalization)
            - [Sim2Real or Real2Sim2Real Generalization](#sim2real-or-real2sim2real-generalization)
            - [SE(3)/SIM(3)-Equivariance (View Changes)](#se3sim3-equivariance-view-changes)
            - [Lighting/background/distractor Changes](#lightingbackgrounddistractor-changes)
        - [Cross-Embodiment Generalization](#cross-embodiment-generalization)
    - [Human-Robot Interaction and Collaboration](#human-robot-interaction-and-collaboration)



## Data Collection and Utilization

<!-- Data Collection -->
<div align="center">

### <i>Data Collection</i>

</div>

### Human Teleoperation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**RAPID: Reconfigurable, Adaptive Platform for Iterative Design**](https://arxiv.org/abs/2602.06653) | arXiv | 2026-02-06 | ![Star](https://img.shields.io/github/stars/aod321/rapid?style=social&label=Star) [Github](https://github.com/aod321/rapid) |  |
| [**A Closed-Form Geometric Retargeting Solver for Upper Body Humanoid Robot Teleoperation**](https://arxiv.org/abs/2602.01632) | arXiv | 2026-02-02 | [Project](https://sew-mimic.com/) |  |
| [**A Multimodal Data Collection Framework for Dialogue-Driven Assistive Robotics to Clarify Ambiguities: A Wizard-of-Oz Pilot Study**](https://arxiv.org/abs/2601.16870) | arXiv | 2026-01-23 | - |  |
| [**In-the-Wild Compliant Manipulation with UMI-FT**](https://arxiv.org/abs/2601.09988) | arXiv | 2026-01-15 | ![Star](https://img.shields.io/github/stars/real-stanford/UMI-FT?style=social&label=Star) [Github](https://github.com/real-stanford/UMI-FT) |  |
| [**UniBiDex: A Unified Teleoperation Framework for Robotic Bimanual Dexterous Manipulation**](https://arxiv.org/abs/2601.04629) | arXiv | 2026-01-08 | - |  |
| [**Coordinated Humanoid Manipulation with Choice Policies**](https://arxiv.org/abs/2512.25072) | arXiv | 2025-12-31 | ![Star](https://img.shields.io/github/stars/x-robotics-lab/modular-teleop?style=social&label=Star) [Github](https://github.com/x-robotics-lab/modular-teleop) |  |
| [**ACE-F: A Cross Embodiment Foldable System with Force Feedback for Dexterous Teleoperation**](https://arxiv.org/abs/2511.20887) | arXiv | 2025-11-25 | ![Star](https://img.shields.io/github/stars/ACEFoldable/acef_software?style=social&label=Star) [Github](https://github.com/ACEFoldable/acef_software) |  |
| [**Dexterity from Smart Lenses: Multi-Fingered Robot Manipulation with In-the-Wild Human Demonstrations**](https://arxiv.org/abs/2511.16661) | arXiv | 2025-11-20 | ![Star](https://img.shields.io/github/stars/irmakguzey/AINA?style=social&label=Star) [Github](https://github.com/irmakguzey/AINA) |  |
| [**TWIST2: Scalable, Portable, and Holistic Humanoid Data Collection System**](https://arxiv.org/abs/2511.02832) | arXiv | 2025-11-04 | ![Star](https://img.shields.io/github/stars/amazon-far/TWIST2?style=social&label=Star) [Github](https://github.com/amazon-far/TWIST2) |  |
| [**Open TeleDex: A Hardware-Agnostic Teleoperation System for Imitation Learning based Dexterous Manipulation**](https://arxiv.org/abs/2510.14771) | arXiv | 2025-10-16 | - |  |
| [**ActiveUMI: Robotic Manipulation with Active Perception from Robot-Free Human Demonstrations**](https://arxiv.org/abs/2510.01607) | arXiv | 2025-10-02 | [Project](https://activeumi.github.io/) |  |
| [**Prometheus: Universal, Open-Source Mocap-Based Teleoperation System with Force Feedback for Dataset Collection in Robot Learning**](https://arxiv.org/abs/2510.01023) | arXiv | 2025-10-01 | ![Star](https://img.shields.io/github/stars/Eterwait/Prometheus?style=social&label=Star) [Github](https://github.com/Eterwait/Prometheus) |  |
| [**LeVR: A Modular VR Teleoperation Framework for Imitation Learning in Dexterous Manipulation**](https://arxiv.org/abs/2509.14349) | arXiv | 2025-09-17 | ![Star](https://img.shields.io/github/stars/wengmister/LeFranX?style=social&label=Star) [Github](https://github.com/wengmister/LeFranX) |  |
| [**U-ARM: Ultra Low-Cost General Teleoperation Interface for Robot Manipulation**](https://arxiv.org/abs/2509.02437) | arXiv | 2025-09-02 | ![Star](https://img.shields.io/github/stars/MINT-SJTU/LeRobot-Anything-U-Arm?style=social&label=Star) [Github](https://github.com/MINT-SJTU/LeRobot-Anything-U-Arm) |  |
| [**BEAVR: Bimanual, multi-Embodiment, Accessible, Virtual Reality Teleoperation System for Robots**](https://arxiv.org/abs/2508.09606) | ICCR 2025 | 2025-08-13 | ![Star](https://img.shields.io/github/stars/ARCLab-MIT/BEAVR-Bot?style=social&label=Star) [Github](https://github.com/ARCLab-MIT/BEAVR-Bot) |  |
| [**XRoboToolkit: A Cross-Platform Framework for Robot Teleoperation**](https://arxiv.org/abs/2508.00097) | arXiv | 2025-07-31 | [Github](https://github.com/XR-Robotics) |  |
| [**Fast Bilateral Teleoperation and Imitation Learning Using Sensorless Force Control via Accurate Dynamics Model**](https://arxiv.org/abs/2507.06174) | arXiv | 2025-07-08 | - |  |
| [**Dexterous Teleoperation of 20-DoF ByteDexter Hand via Human Motion Retargeting**](https://arxiv.org/abs/2507.03227) | arXiv | 2025-07-04 | [Project](https://byte-dexter.github.io/) |  |
| [**TypeTele: Releasing Dexterity in Teleoperation by Dexterous Manipulation Types**](https://arxiv.org/abs/2507.01857) | arXiv | 2025-07-02 | [Project](https://isee-laboratory.github.io/TypeTele/) |
| [**mimic-one: a Scalable Model Recipe for General Purpose Robot Dexterity**](https://arxiv.org/abs/2506.11916) | arXiv | 2025-06-13 | [Project](https://mimicrobotics.github.io/mimic-one/) |  |
| [**ExoStart: Efficient Learning for Dexterous Manipulation with Sensorized Exoskeleton Demonstrations**](https://arxiv.org/abs/2506.11775) | arXiv | 2025-06-13 | [Project](https://sites.google.com/view/exostart) | Exoskeleton Gloves |
| [**FreeTacMan: Robot-free Visuo-Tactile Data Collection System for Contact-rich Manipulation**](https://arxiv.org/abs/2506.01941) | arXiv | 2025-06-02 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/FreeTacMan?style=social&label=Star) [Github](https://github.com/OpenDriveLab/FreeTacMan) |
| [**Bootstrapping Imitation Learning for Long-horizon Manipulation via Hierarchical Data Collection Space**](https://arxiv.org/abs/2505.17389) | arXiv | 2025-05-23 | [Project](https://hd-space-robotics.github.io/) |  |
| [**Adversarial Data Collection: Human-Collaborative Perturbations for Efficient and Robust Robotic Imitation Learning**](https://arxiv.org/abs/2503.11646) | arXiv | 2025-03-14 | [Project](https://sites.google.com/view/adc-robot) |  |
| [**Kaiwu: A Multimodal Manipulation Dataset and Framework for Robot Learning and Human-Robot Interaction**](https://arxiv.org/abs/2503.05231) | arXiv | 2025-03-07 | - |  |
| [**AirExo-2: Scaling up Generalizable Robotic Imitation Learning with Low-Cost Exoskeletons**](https://arxiv.org/abs/2503.03081) | arXiv | 2025-03-05 | [Project](https://airexo.tech/airexo2/) |  |
| [**AVR: Active Vision-Driven Robotic Precision Manipulation with Viewpoint and Focal Length Optimization**](https://arxiv.org/abs/2503.01439) | arXiv | 2025-03-03 | [Project](https://avr-robot.github.io/) |  |
| [**DexUMI: Using Human Hand as the Universal Manipulation Interface for Dexterous Manipulation**](https://arxiv.org/abs/2505.21864) | RSSW 2025 | 2025-05-28 | ![Star](https://img.shields.io/github/stars/real-stanford/DexUMI?style=social&label=Star) [Github](https://github.com/real-stanford/DexUMI) |  |
| [**Reactive Diffusion Policy: Slow-Fast Visual-Tactile Policy Learning for Contact-Rich Manipulation**](https://arxiv.org/abs/2503.02881) | RSS 2025 | 2025-03-04 | ![Star](https://img.shields.io/github/stars/xiaoxiaoxh/reactive_diffusion_policy?style=social&label=Star) [Github](https://github.com/xiaoxiaoxh/reactive_diffusion_policy) | |
| [**ALPHA-α and Bi-ACT Are All You Need: Importance of Position and Force Information/Control for Imitation Learning of Unimanual and Bimanual Robotic Manipulation with Low-Cost System**](https://arxiv.org/abs/2411.09942) | IEEE Access 2025 | 2024-11-15 | [Project](https://mertcookimg.github.io/alpha-biact/) |  |
| [**ARCap: Collecting High-quality Human Demonstrations for Robot Learning with Augmented Reality Feedback**](https://arxiv.org/abs/2410.08464) | ICRA 2025 | 2024-10-11 | ![Star](https://img.shields.io/github/stars/Ericcsr/ARCap?style=social&label=Star) [Github](https://github.com/Ericcsr/ARCap) |  |
| [**Bunny-VisionPro: Real-Time Bimanual Dexterous Teleoperation for Imitation Learning**](https://arxiv.org/abs/2407.03162) | arXiv | 2024-07-03 | ![Star](https://img.shields.io/github/stars/Dingry/BunnyVisionPro?style=social&label=Star) [Github](https://github.com/Dingry/BunnyVisionPro) |  |
| [**A Perspective on AI-Guided Molecular Simulations in VR: Exploring Strategies for Imitation Learning in Hyperdimensional Molecular Systems**](https://arxiv.org/abs/2409.07189) | ECAIW 2024 | 2024-09-11 | - |  |
| [**GELLO: A General, Low-Cost, and Intuitive Teleoperation Framework for Robot Manipulators**](https://arxiv.org/abs/2309.13037) | IROS 2024 | 2023-09-22 | ![Star](https://img.shields.io/github/stars/wuphilipp/gello_software?style=social&label=Star) [Github](https://github.com/wuphilipp/gello_software) |  |
| [**EgoMimic: Scaling Imitation Learning via Egocentric Video**](https://arxiv.org/abs/2410.24221) | CoRLW 2024 | 2024-10-31 | ![Star](https://img.shields.io/github/stars/SimarKareer/EgoMimic?style=social&label=Star) [Github](https://github.com/SimarKareer/EgoMimic) | Bi, Aria Glasses |
| [**Active Vision Might Be All You Need: Exploring Active Vision in Bimanual Robotic Manipulation**](https://arxiv.org/abs/2409.17435) | CoRLW 2024 | 2024-09-26 | ![Star](https://img.shields.io/github/stars/soltanilara/av-aloha?style=social&label=Star) [Github](https://github.com/soltanilara/av-aloha) | Bi, VR |
| [**OPEN TEACH: A Versatile Teleoperation System for Robotic Manipulation**](https://arxiv.org/abs/2403.07870) | CoRL 2024 | 2024-03-12 | ![Star](https://img.shields.io/github/stars/aadhithya14/Open-Teach?style=social&label=Star) [Github](https://github.com/aadhithya14/Open-Teach) | |
| [**DexCap: Scalable and Portable Mocap Data Collection System for Dexterous Manipulation**](https://arxiv.org/abs/2403.07788) | CoRL 2024 | 2024-03-12 | ![Star](https://img.shields.io/github/stars/j96w/DexCap?style=social&label=Star) [Github](https://github.com/j96w/DexCap) | |
| [**Tilde: Teleoperation for Dexterous In-Hand Manipulation Learning with a DeltaHand**](https://arxiv.org/abs/2405.18804) | RSS 2024 | 2024-05-29 | ![Star](https://img.shields.io/github/stars/iamlab-cmu/DeltaHands?style=social&label=Star) [Github](https://github.com/iamlab-cmu/DeltaHands) | |
| [**Universal Manipulation Interface: In-The-Wild Robot Teaching Without In-The-Wild Robots**](https://arxiv.org/abs/2402.10329) | RSS 2024 | 2024-02-15 | ![Star](https://img.shields.io/github/stars/real-stanford/universal_manipulation_interface?style=social&label=Star) [Github](https://github.com/real-stanford/universal_manipulation_interface) | |
| [**TeleMoMa: A Modular and Versatile Teleoperation System for Mobile Manipulation**](https://arxiv.org/abs/2403.07869) | ICRAW 2024 | 2024-03-12 | ![Star](https://img.shields.io/github/stars/UT-Austin-RobIn/telemoma?style=social&label=Star) [Github](https://github.com/UT-Austin-RobIn/telemoma) | |
| [**AirExo: Low-Cost Exoskeletons for Learning Whole-Arm Manipulation in the Wild**](https://arxiv.org/abs/2309.14975) | ICRA 2024 | 2023-09-26 | ![Star](https://img.shields.io/github/stars/AirExo/collector?style=social&label=Star) [Github](https://github.com/AirExo/collector) | |
| [**AnyTeleop: A General Vision-Based Dexterous Robot Arm-Hand Teleoperation System**](https://arxiv.org/abs/2307.04577) | RSS 2023 | 2023-07-10 | [Project](https://yzqin.github.io/anyteleop/)  | |
| [**Training Robots without Robots: Deep Imitation Learning for Master-to-Robot Policy Transfer**](https://arxiv.org/abs/2202.09574) | RA-L 2023 | 2022-02-19 | - |  |
| [**Visual Imitation Made Easy**](https://arxiv.org/abs/2008.04899) | CoRL 2021 | 2020-8-11 | ![Star](https://img.shields.io/github/stars/sarahisyoung/Visual-Imitation-Made-Easy?style=social&label=Star) [Github](https://github.com/sarahisyoung/Visual-Imitation-Made-Easy) |  |
| [**Deep Imitation Learning for Complex Manipulation Tasks from Virtual Reality Teleoperation**](https://arxiv.org/abs/1710.04615) | ICRA 2018 | 2017-10-12 | - |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Human-in-the-Loop Enhancement
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**CUPID: Curating Data your Robot Loves with Influence Functions**](https://arxiv.org/abs/2506.19121) | arXiv | 2025-06-23 | [Project](https://cupid-curation.github.io/) |  |
| [**Compliant Residual DAgger: Improving Real-World Contact-Rich Manipulation with Human Corrections**](https://arxiv.org/abs/2506.16685) | arXiv | 2025-06-20 | [Project](https://compliant-residual-dagger.github.io/) |  |
| [**IntervenGen: Interventional Data Generation for Robust and Data-Efficient Robot Imitation Learning**](https://arxiv.org/abs/2405.01472) | IROS 2024 | 2024-05-02 | [Project](https://sites.google.com/view/intervengen2024) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Automatic Generation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**ExoGS: A 4D Real-to-Sim-to-Real Framework for Scalable Manipulation Data Collection**](https://arxiv.org/abs/2601.18629) | arXiv | 2026-01-26 | ![Star](https://img.shields.io/github/stars/zaixiabalala/ExoGS?style=social&label=Star) [Github](https://github.com/zaixiabalala/ExoGS) |  |  
| [**One-Shot Real-World Demonstration Synthesis for Scalable Bimanual Manipulation**](https://arxiv.org/abs/2512.09297) | arXiv | 2025-12-10 | [Project](https://hnuzhy.github.io/projects/BiDemoSyn/) |  |  
| [**AOMGen: Photoreal, Physics-Consistent Demonstration Generation for Articulated Object Manipulation**](https://arxiv.org/abs/2512.18396) | arXiv | 2025-12-20 | - |  |  
| [**AnyTask: an Automated Task and Data Generation Framework for Advancing Sim-to-Real Policy Learning**](https://arxiv.org/abs/2512.17853) | arXiv | 2025-12-19 | [Project](https://anytask.rai-inst.com/) |  |  
| [**Iterative Compositional Data Generation for Robot Control**](https://arxiv.org/abs/2512.10891) | arXiv | 2025-12-11 | - |  |  
| [**IGen: Scalable Data Generation for Robot Learning from Open-World Images**](https://arxiv.org/abs/2512.01773) | arXiv | 2025-12-01 | ![Star](https://img.shields.io/github/stars/ChenghaoGu/IGen_Robot?style=social&label=Star) [Github](https://github.com/ChenghaoGu/IGen_Robot) |  |  
| [**Robot-Powered Data Flywheels: Deploying Robots in the Wild for Continual Data Collection and Foundation Model Adaptation**](https://arxiv.org/abs/2511.19647) | arXiv | 2025-11-24 | [Project](https://scanford-robot.github.io/) |  |  
| [**InternData-A1: Pioneering High-Fidelity Synthetic Data for Pre-training Generalist Policy**](https://arxiv.org/abs/2511.16651) | arXiv | 2025-11-20 | [Project](https://internrobotics.github.io/interndata-a1.github.io/) |  |  
| [**DynaMimicGen: A Data Generation Framework for Robot Learning of Dynamic Tasks**](https://arxiv.org/abs/2511.16223) | arXiv | 2025-11-20 | ![Star](https://img.shields.io/github/stars/Fautomation-robotics-machines/DynaMimicGen?style=social&label=Star) [Github](https://github.com/automation-robotics-machines/DynaMimicGen) |  |  
| [**FieldGen: From Teleoperated Pre-Manipulation Trajectories to Field-Guided Data Generation**](https://arxiv.org/abs/2510.20774) | arXiv | 2025-10-23 | ![Star](https://img.shields.io/github/stars/FieldGen/FieldGen?style=social&label=Star) [Github](https://github.com/FieldGen/FieldGen) |  |  
| [**MoMaGen: Generating Demonstrations under Soft and Hard Constraints for Multi-Step Bimanual Mobile Manipulation**](https://arxiv.org/abs/2510.18316) | arXiv | 2025-10-21 | ![Star](https://img.shields.io/github/stars/ChengshuLi/MoMaGen?style=social&label=Star) [Github](https://github.com/ChengshuLi/MoMaGen) |  |  
| [**DexFlyWheel: A Scalable and Self-improving Data Generation Framework for Dexterous Manipulation**](https://arxiv.org/abs/2509.23829) | NeurIPS 2025 | 2025-09-28 | [Project](https://dexflywheel.github.io/) |  |  
| [**LLM Trainer: Automated Robotic Data Generating via Demonstration Augmentation using LLMs**](https://arxiv.org/abs/2509.20070) | arXiv | 2025-09-24 | [Project](https://sites.google.com/andrew.cmu.edu/llm-trainer) |  |  
| [**RaC: Robot Learning for Long-Horizon Tasks by Scaling Recovery and Correction**](https://arxiv.org/abs/2509.07953) | CoRL 2025 | 2025-09-09 | [Project](https://rac-scaling-robot.github.io/) |  |  
| [**Fail2Progress: Learning from Real-World Robot Failures with Stein Variational Inference**](https://arxiv.org/abs/2509.01746) | CoRL 2025 | 2025-08-11 | [Project](https://sites.google.com/view/fail2progress) |  |  
| [**Constraint-Preserving Data Generation for Visuomotor Policy Learning**](https://arxiv.org/abs/2508.03944) | CoRL 2025 | 2025-08-11 | [Project](https://cp-gen.github.io/) |  |  
| [**HybridGen: VLM-Guided Hybrid Planning for Scalable Data Generation of Imitation Learning**](https://arxiv.org/abs/2503.13171) | arXiv | 2025-03-17 | - |  |  
| [**Physics-Driven Data Generation for Contact-Rich Manipulation via Trajectory Optimization**](https://arxiv.org/abs/2502.20382) | RSS 2025 | 2025-02-27 | [Project](https://lujieyang.github.io/physicsgen/) |  |  
| [**DemoGen: Synthetic Demonstration Generation for Data-Efficient Visuomotor Policy Learning**](https://arxiv.org/abs/2502.16932) | RSS 2025 | 2025-02-24 | ![Star](https://img.shields.io/github/stars/TEA-Lab/DemoGen?style=social&label=Star) [Github](https://github.com/TEA-Lab/DemoGen) |  |  
| [**Re<sup>3</sup>Sim: Generating High-Fidelity Simulation Data via 3D-Photorealistic Real-to-Sim for Robotic Manipulation**](https://arxiv.org/abs/2502.08645) | arXiv | 2025-02-12 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/Re3Sim?style=social&label=Star) [Github](https://github.com/OpenRobotLab/Re3Sim) |  |
| [**ARMADA: Augmented Reality for Robot Manipulation and Robot-Free Data Acquisition**](https://arxiv.org/abs/2412.10631) | arXiv | 2024-12-14 | [Project](https://nataliya.dev/armada) |  |
| [**DexMimicGen: Automated Data Generation for Bimanual Dexterous Manipulation via Imitation Learning**](https://arxiv.org/abs/2410.24185) | ICRA 2025 | 2024-10-31 | ![Star](https://img.shields.io/github/stars/NVlabs/dexmimicgen?style=social&label=Star) [Github](https://github.com/NVlabs/dexmimicgen) |  |  
| [**ARCADE: Scalable Demonstration Collection and Generation via Augmented Reality for Imitation Learning**](https://arxiv.org/abs/2410.15994) | IROS 2024 | 2024-10-21 | ![Star](https://img.shields.io/github/stars/YY-GX/ARCADE?style=social&label=Star) [Github](https://github.com/YY-GX/ARCADE/tree/Unity_ROS) |  |  
| [**MILES: Making Imitation Learning Easy with Self-Supervision**](https://arxiv.org/abs/2410.19693) | CoRL 2024 | 2024-10-25 | ![Star](https://img.shields.io/github/stars/gpapagiannis/miles-imitation?style=social&label=Star) [Github](https://github.com/gpapagiannis/miles-imitation) |  |
| [**SkillMimicGen: Automated Demonstration Generation for Efficient Skill Learning and Deployment**](https://arxiv.org/abs/2410.18907) | CoRL 2024 | 2024-10-24 | [Project](https://skillgen.github.io/) |  |
| [NILS: **Scaling Robot Policy Learning via Zero-Shot Labeling with Foundation Models**](https://arxiv.org/abs/2410.17772) | CoRL 2024 | 2024-10-23 | [Project](https://robottasklabeling.github.io/) |  |
| [SOAR: **Autonomous Improvement of Instruction Following Skills via Foundation Models**](https://arxiv.org/abs/2407.20635) | CoRL 2024 | 2024-07-30 | ![Star](https://img.shields.io/github/stars/rail-berkeley/soar?style=social&label=Star) [Github](https://github.com/rail-berkeley/soar) |  |
| [**Manipulate-Anything: Automating Real-World Robots using Vision-Language Models**](https://arxiv.org/abs/2406.18915) | CoRL 2024 | 2024-06-27 | [Project](https://robot-ma.github.io/) | |
| [**SPRINT: Scalable Policy Pre-Training via Language Instruction Relabeling**](https://arxiv.org/abs/2306.11886) | ICRA 2024 | 2023-06-20 | ![Star](https://img.shields.io/github/stars/clvrai/sprint?style=social&label=Star) [Github](https://github.com/clvrai/sprint) | |
| [**Offline Imitation Learning with Variational Counterfactual Reasoning**](https://arxiv.org/abs/2310.04706) | NeurIPS 2023 | 2023-10-07 | ![Star](https://img.shields.io/github/stars/ZexuSun/OILCA-NeurIPS23?style=social&label=Star) [Github](https://github.com/ZexuSun/OILCA-NeurIPS23) |  |
| [**MimicGen: A Data Generation System for Scalable Robot Learning using Human Demonstrations**](https://arxiv.org/abs/2310.17596) | CoRL 2023 | 2023-10-26 | ![Star](https://img.shields.io/github/stars/NVlabs/mimicgen?style=social&label=Star) [Github](https://github.com/NVlabs/mimicgen) |  |
| [**Scaling Up and Distilling Down: Language-Guided Robot Skill Acquisition**](https://arxiv.org/abs/2307.14535) | CoRL 2023 | 2023-07-26 | ![Star](https://img.shields.io/github/stars/real-stanford/scalingup?style=social&label=Star) [Github](https://github.com/real-stanford/scalingup) |  |
| [**RoboCat: A Self-Improving Generalist Agent for Robotic Manipulation**](https://arxiv.org/abs/2306.11706) | TMLR 2023 | 2023-06-20 | ![Star](https://img.shields.io/github/stars/kyegomez/RoboCAT?style=social&label=Star) [Github](https://github.com/kyegomez/RoboCAT) | |
| [DIAL: **Robotic Skill Acquisition via Instruction Augmentation with Vision-Language Models**](https://arxiv.org/abs/2211.11736) | RSS 2023 | 2022-11-21 | [Project](https://instructionaugmentation.github.io/) |  |
| [**SEIL: Simulation-augmented Equivariant Imitation Learning**](https://arxiv.org/abs/2211.00194) | ICRA 2023 | 2022-11-26 | ![Star](https://img.shields.io/github/stars/SaulBatman/SEIL?style=social&label=Star) [Github](https://github.com/SaulBatman/SEIL) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Crowdsourcing
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**EgoZero: Robot Learning from Smart Glasses**](https://arxiv.org/abs/2505.20290) | arXiv | 2025-05-26 | ![Star](https://img.shields.io/github/stars/vliu15/egozero?style=social&label=Star) [Github](https://github.com/vliu15/egozero) | Aria Glasses |  
| [**AR2-D2:Training a Robot Without a Robot**](https://arxiv.org/abs/2306.13818) | CoRL 2023 | 2023-06-23 | ![Star](https://img.shields.io/github/stars/jiafei1224/AR2-D2?style=social&label=Star) [Github](https://github.com/jiafei1224/AR2-D2) |  |
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
| [**RoboVIP: Multi-View Video Generation with Visual Identity Prompting Augments Robot Manipulation**](https://arxiv.org/abs/2601.05241) | arXiv | 2026-01-08 | ![Star](https://img.shields.io/github/stars/RoboVIP/RoboVIP_VDM?style=social&label=Star) [Github](https://github.com/RoboVIP/RoboVIP_VDM) |  |
| [**MOVE: A Simple Motion-Based Data Collection Paradigm for Spatial Generalization in Robotic Manipulation**](https://arxiv.org/abs/2512.04813) | arXiv | 2025-12-04 | ![Star](https://img.shields.io/github/stars/lucywang720/MOVE?style=social&label=Star) [Github](https://github.com/lucywang720/MOVE) |  |
| [**Restoring  Noisy Demonstration for Imitation Learning With Diffusion Models**](https://arxiv.org/abs/2510.14467) | TNNLS 2025 | 2025-10-16 | - |  |
| [**R2RGEN: Real-to-Real 3D Data Generation for Spatially Generalized Manipulationr**](https://arxiv.org/abs/2510.08547) | arXiv | 2025-10-09 | [Project](https://r2rgen.github.io/) |  |
| [**EMMA: Generalizing Real-World Robot Manipulation via Generative Visual Transfer**](https://arxiv.org/abs/2509.22407) | arXiv | 2025-09-26 | [Project](https://egodemogen.github.io/) |  |
| [**EgoDemoGen: Novel Egocentric Demonstration Generation Enables Viewpoint-Robust Manipulation**](https://arxiv.org/abs/2509.22578) | arXiv | 2025-09-26 | [Project](https://egodemogen.github.io/) |  |
| [**DataPlatter: Boosting Robotic Manipulation Generalization with Minimal Costly Data**](https://arxiv.org/abs/2503.19516) | arXiv | 2025-03-25 | ![Star](https://img.shields.io/github/stars/notFoundThisPerson/RoboTron-Craft?style=social&label=Star) [Github](https://github.com/notFoundThisPerson/RoboTron-Craft) |  |
| [**TASTE-Rob: Advancing Video Generation of Task-Oriented Hand-Object Interaction for Generalizable Robotic Manipulation**](https://arxiv.org/abs/2503.11423) | CVPR 2025 | 2025-03-14 | ![Star](https://img.shields.io/github/stars/GAP-LAB-CUHK-SZ/TASTE-Rob?style=social&label=Star) [Github](https://github.com/GAP-LAB-CUHK-SZ/TASTE-Rob) | Video Generation |
| [**Diff-DAgger: Uncertainty Estimation with Diffusion Policy for Robotic Manipulation**](https://arxiv.org/abs/2410.14868) | ICRA 2025 | 2024-10-18 | ![Star](https://img.shields.io/github/stars/sean1295/DiffDAgger?style=social&label=Star) [Github](https://github.com/sean1295/DiffDAgger) |  |
| [**JUICER: Data-Efficient Imitation Learning for Robotic Assembly**](https://arxiv.org/abs/2507.06219) | IROS 2024 | 2024-04-04 | ![Star](https://img.shields.io/github/stars/ankile/imitation-juicer?style=social&label=Star) [Github](https://github.com/ankile/imitation-juicer) |  |
| [**Learning Category-Level Generalizable Object Manipulation Policy via Generative Adversarial Self-Imitation Learning from Demonstrations**](https://arxiv.org/abs/2203.02107) | RA-L 2022 | 2022-03-04 | ![Star](https://img.shields.io/github/stars/wkwan7/Category_Level_Manipulation?style=social&label=Star) [Github](https://github.com/wkwan7/Category_Level_Manipulation) | GAIL |
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
| [**Towards Balanced Behavior Cloning from Imbalanced Datasets**](https://arxiv.org/abs/2508.06319) | arXiv | 2025-08-08 | [Project](https://collab.me.vt.edu/data_curation/) |  |
| [**Policy Learning from Large Vision-Language Model Feedback without Reward Modeling**](https://arxiv.org/abs/2507.23391) | IROS 2025 | 2025-07-31 | ![Star](https://img.shields.io/github/stars/tunglm2203/plare?style=social&label=Star) [Github](https://github.com/tunglm2203/plare) |  |
| [**Feasibility-aware Imitation Learning from Observations through a Hand-mounted Demonstration Interface**](https://arxiv.org/abs/2503.09018) | arXiv | 2025-03-12 | - |  |
| [**Imitation Learning by Estimating Expertise of Demonstrators**](https://arxiv.org/abs/2202.01288) | ICML 2022 | 2022-02-02 | ![Star](https://img.shields.io/github/stars/Stanford-ILIAD/ILEED?style=social&label=Star) [Github](https://github.com/Stanford-ILIAD/ILEED) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Data Selection
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Dynamic Test-Time Compute Scaling in Control Policy: Difficulty-Aware Stochastic Interpolant Policy**](https://arxiv.org/abs/2511.20906) | arXiv | 2025-11-25 | - |  |
| [**Using Temperature Sampling to Effectively Train Robot Learning Policies on Imbalanced Datasets**](https://arxiv.org/abs/2510.19373) | arXiv | 2025-10-22 | [Project](https://basavasagarkp.github.io/temp_samp/) |  |
| [**Shortcut Learning in Generalist Robot Policies: The Role of Dataset Diversity and Fragmentation**](https://arxiv.org/abs/2508.06426) | CoRL 2025 | 2025-08-08 | [Project](https://lucky-light-sun.github.io/proj/shortcut-learning-in-grps/) |  |
| [**Is Diversity All You Need for Scalable Robotic Manipulation?**](https://arxiv.org/abs/2507.06219) | arXiv | 2025-07-08 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/AgiBot-World?style=social&label=Star) [Github](https://github.com/OpenDriveLab/AgiBot-World) |  |
| [**SCIZOR: A Self-Supervised Approach to Data Curation for Large-Scale Imitation Learning**](https://arxiv.org/abs/2505.22626) | arXiv | 2025-05-28 | [Project](https://ut-austin-rpl.github.io/SCIZOR/) |  |
| [**DataMIL: Selecting Data for Robot Imitation Learning with Datamodels**](https://arxiv.org/abs/2505.09603) | arXiv | 2025-05-14 | [Project](https://robin-lab.cs.utexas.edu/datamodels4imitation/) |  |
| [**Guiding Data Collection via Factored Scaling Curves**](https://arxiv.org/abs/2505.07728) | arXiv | 2025-05-12 | [Project](https://factored-data-scaling.github.io/) |  |  
| [**Robot Data Curation with Mutual Information Estimators**](https://arxiv.org/abs/2502.08623) | arXiv | 2025-02-12 | [Project](https://joeyhejna.com/demonstration-info/) |  |
| [**What Matters in Learning from Large-Scale Datasets for Robot Manipulation**](https://openreview.net/forum?id=LqhorpRLIm) | ICLR 2025 | 2025-01-23 | [Project](https://mimiclabs-iclr.github.io/) |  |
| [**How to Train Your Robots? The Impact of Demonstration Modality on Imitation Learning**](https://arxiv.org/abs/2503.07017) | ICRA 2025 | 2025-03-10 | - |  |
| [AMF: **Active Fine-Tuning of Generalist Policies**](https://arxiv.org/abs/2410.05026) | arXiv | 2024-10-07 | - |  |
| [**Re-Mix: Optimizing Data Mixtures for Large Scale Imitation Learning**](https://arxiv.org/abs/2408.14037) | CoRL 2024 | 2024-08-26 | ![Star](https://img.shields.io/github/stars/jhejna/remix?style=social&label=Star) [Github](https://github.com/jhejna/remix) |  |
| [**How to Leverage Diverse Demonstrations in Offline Imitation Learning**](https://arxiv.org/abs/2405.17476) | ICML 2024 | 2024-05-24 | ![Star](https://img.shields.io/github/stars/HansenHua/ILID-ICML24?style=social&label=Star) [Github](https://github.com/HansenHua/ILID-ICML24) |  |
| [**Learning from Imperfect Demonstrations with Self-Supervision for Robotic Manipulation**](https://arxiv.org/abs/2401.08957) | arXiv | 2024-01-17 | - | |
| [**Learning to Discern: Imitating Heterogeneous Human Demonstrations with Preference and Representation Learning**](https://arxiv.org/abs/2310.14196) | CoRL 2023 | 2023-10-22 | - |  |
| [**Data Quality in Imitation Learning**](https://arxiv.org/abs/2306.02437) | NeurIPS 2023 | 2023-06-04 | - |  |
| [**An Unbiased Look at Datasets for Visuo-Motor Pre-Training**](https://arxiv.org/abs/2310.09289) | CoRL 2023 | 2023-10-13 | ![Star](https://img.shields.io/github/stars/SudeepDasari/data4robotics?style=social&label=Star) [Github](https://github.com/SudeepDasari/data4robotics) |  |
| [**Extraneousness-Aware Imitation Learning**](https://arxiv.org/abs/2210.01379) | ICRA 2023 | 2022-10-04 | ![Star](https://img.shields.io/github/stars/zhengrc19/eil-code?style=social&label=Star) [Github](https://github.com/zhengrc19/eil-code) |  |
| [**Eliciting Compatible Demonstrations for Multi-Human Imitation Learning**](https://arxiv.org/abs/2210.08073) | CoRL 2022 | 2022-10-14 | ![Star](https://img.shields.io/github/stars/kanishkg/elicit?style=social&label=Star) [Github](https://github.com/kanishkg/elicit) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Data Retrieval
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Dejavu: Post-Deployment Learning for Embodied Agents via Experience Feedback**](https://arxiv.org/abs/2510.10181) | arXiv | 2025-10-11 | - | |
| [**Self-evolved Imitation Learning in Simulated World**](https://arxiv.org/abs/2509.194602) | arXiv | 2025-09-23 | ![Star](https://img.shields.io/github/stars/Jasper-aaa/SEIL?style=social&label=Star) [Github](https://github.com/Jasper-aaa/SEIL) | |
| [**Retrieve-Augmented Generation for Speeding up Diffusion Policy without Additional Training**](https://arxiv.org/abs/2507.21452) | arXiv | 2025-07-29 | - | |
| [**Data Retrieval with Importance Weights for Few-Shot Imitation Learning**](https://arxiv.org/abs/2509.01657) | CoRL 2025 | 2025-09-01 | ![Star](https://img.shields.io/github/stars/jhejna/importance-retrieval?style=social&label=Star) [Github](https://github.com/jhejna/importance-retrieval) | |
| [**COLLAGE: Adaptive Fusion-based Retrieval for Augmented Policy Learning**](https://arxiv.org/abs/2508.01131) | CoRL 2025 | 2025-08-11 | [Project](https://robin-lab.cs.utexas.edu/COLLAGE/) | |
| [**Let Me Show You: Learning by Retrieving from Egocentric Video for Robotic Manipulation**](https://arxiv.org/abs/2511.05199) | IROS 2025 | 2025-11-07 | - | |
| [**STRAP: Robot Sub-Trajectory Retrieval for Augmented Policy Learning**](https://arxiv.org/abs/2412.15182) | ICLR 2025 | 2024-12-19 | [Project](https://weirdlabuw.github.io/strap/) | |
| [**FlowRetrieval: Flow-Guided Data Retrieval for Few-Shot Imitation Learning**](https://arxiv.org/abs/2408.16944) | CoRL 2024 | 2024-08-29 | ![Star](https://img.shields.io/github/stars/lihenglin/bridge_training_code?style=social&label=Star) [Github](https://github.com/lihenglin/bridge_training_code) | |
| [**Offline Imitation Learning Through Graph Search and Retrieval**](https://arxiv.org/abs/2407.15403) | RSS 2024 | 2024-07-22 | [Project](https://zhaohengyin.github.io/gsr/) | |
| [**Retrieval-Augmented Embodied Agents**](https://arxiv.org/abs/2404.11699) | CVPR 2024 | 2024-04-17 | - | |
| [**DINOBot: Robot Manipulation via Retrieval and Alignment with Vision Foundation Models**](https://arxiv.org/abs/2402.13181) | ICRA 2024 | 2024-02-20 | [GitHub Gist](https://gist.github.com/normandipalo/fbc21f23606fbe3d407e22c363cb134e) | |
| [**On the Effectiveness of Retrieval, Alignment, and Replay in Manipulation**](https://arxiv.org/abs/2312.12345) | RA-L 2024 | 2023-12-19 | [Project](https://www.robot-learning.uk/retrieval-alignment-replay) | |
| [**Behavior Retrieval: Few-Shot Imitation Learning by Querying Unlabeled Datasets**](https://arxiv.org/abs/2304.08742) | RSS 2023 | 2023-04-08 | ![Star](https://img.shields.io/github/stars/MaxDu17/BehaviorRetrieval?style=social&label=Star) [Github](https://github.com/MaxDu17/BehaviorRetrieval) | |
| [**Learning and Retrieval from Prior Data for Skill-based Imitation Learning**](https://arxiv.org/abs/2210.11435) | CoRL 2022 | 2022-10-20 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/sailor?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/sailor) | |
| [**The Surprising Effectiveness of Representation Learning for Visual Imitation**](https://arxiv.org/abs/2112.01511) | RSS 2022 | 2021-12-02 | ![Star](https://img.shields.io/github/stars/jyopari/VINN?style=social&label=Star) [Github](https://github.com/jyopari/VINN) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Data Augmentation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**RoboPaint: From Human Demonstration to Any Robot and Any View**](https://arxiv.org/abs/2602.05325) | arXiv | 2026-02-05 | - |  |
| [**M<sup>3</sup>A Policy: Mutable Material Manipulation Augmentation Policy through Photometric Re-rendering**](https://arxiv.org/abs/2512.01446) | arXiv | 2025-12-01 | - |  |
| [**Improving Robotic Manipulation Robustness via NICE Scene Surgery**](https://arxiv.org/abs/2511.22777) | arXiv | 2025-11-27 | - |  |
| [**A Study on Enhancing the Generalization Ability of Visuomotor Policies via Data Augmentation**](https://arxiv.org/abs/2511.09932) | arXiv | 2025-11-13 | - |  |
| [**RESample: A Robust Data Augmentation Framework via Exploratory Sampling for Robotic Manipulation**](https://arxiv.org/abs/2510.17640) | arXiv | 2025-10-20 | - |  |
| [**Fidelity-Aware Data Composition for Robust Robot Generalization**](https://arxiv.org/abs/2509.24797) | arXiv | 2025-09-29 | - |  |
| [**ROPA: Synthetic Robot Pose Generation for RGB-D Bimanual Data Augmentation**](https://arxiv.org/abs/2509.19454) | arXiv | 2025-09-23 | [Project](https://ropaaug.github.io/) |  |
| [**Learning in ImaginationLand: Omnidirectional Policies through 3D Generative Models (OP-Gen)**](https://arxiv.org/abs/2509.06191) | arXiv | 2025-09-07 | [Project](https://www.robot-learning.uk/op-gen) |  |
| [**Masquerade: Learning from In-the-wild Human Videos using Data-Editing**](https://arxiv.org/abs/2508.09976) | arXiv | 2025-08-13 | [Project](https://masquerade-robot.github.io/) |  |
| [**Shortcut Learning in Generalist Robot Policies: The Role of Dataset Diversity and Fragmentation**](https://arxiv.org/abs/2508.06426) | CoRL 2025 | 2025-08-08 | [Project](https://lucky-light-sun.github.io/proj/shortcut-learning-in-grps/) |  |
| [**RoboPearls: Editable Video Simulation for Robot Manipulation**](https://arxiv.org/abs/2506.22756) | ICCV 2025 | 2025-06-28 | [Project](https://tangtaogo.github.io/RoboPearls/) |  |
| [**ControlTac: Force- and Position-Controlled Tactile Data Augmentation with a Single Reference Image**](https://arxiv.org/abs/2505.20498) | arXiv | 2025-05-26 | [Project](https://dongyuluo.github.io/controltac/) |
| [**H2R: A Human-to-Robot Data Augmentation for Robot Pre-training from Videos**](https://arxiv.org/abs/2505.11920) | CVPRW 2025 | 2025-05-17 | - |  |
| [**Robust Offline Imitation Learning Through State-level Trajectory Stitching**](https://arxiv.org/abs/2503.22524) | arXiv | 2025-03-28 | - |  |
| [**RoboEngine: Plug-and-Play Robot Data Augmentation with Semantic Robot Segmentation and Background Generation**](https://arxiv.org/abs/2503.18738) | arXiv | 2025-03-24 | ![Star](https://img.shields.io/github/stars/michaelyuancb/roboengine?style=social&label=Star) [Github](https://github.com/michaelyuancb/roboengine) |  |
| [**Predictive Red Teaming: Breaking Policies Without Breaking Robots**](https://arxiv.org/abs/2502.06575) | arXiv | 2025-02-10 | [Project](https://predictive-red-team.github.io/) |  |
| [**RoCoDA: Counterfactual Data Augmentation for Data-Efficient Robot Learning from Demonstrations**](https://arxiv.org/abs/2411.16959) | arXiv | 2024-11-25 | [Project](https://rocoda.github.io/) |  |
| [**Stem-OB: Generalizable Visual Imitation Learning with Stem-Like Convergent Observation through Diffusion Inversion**](https://arxiv.org/abs/2411.04919) | arXiv | 2024-11-07 | ![Star](https://img.shields.io/github/stars/hukz18/Stem-Ob-Code?style=social&label=Star) [Github](https://github.com/hukz18/Stem-Ob-Code) |  |
| [**DABI: Evaluation of Data Augmentation Methods Using Downsampling in Bilateral Control-Based Imitation Learning with Images**](https://arxiv.org/abs/2410.04370) | ICRA 2025 | 2024-10-06 | [Project](https://mertcookimg.github.io/dabi/) |  |
| [**Towards Effective Utilization of Mixed-Quality Demonstrations in Robotic Manipulation via Segment-Level Selection and Optimization**](https://arxiv.org/abs/2409.19917) | ICRA 2025 | 2024-09-30 | ![Star](https://img.shields.io/github/stars/junxix/s2i?style=social&label=Star) [Github](https://github.com/junxix/s2i) |  |
| [**Green Screen Augmentation Enables Scene Generalisation in Robotic Manipulation**](https://arxiv.org/abs/2407.07868) | arXiv | 2024-07-10 | ![Star](https://img.shields.io/github/stars/eugeneteoh/greenaug?style=social&label=Star) [Github](https://github.com/eugeneteoh/greenaug) |  |
| [**View-Invariant Policy Learning via Zero-Shot Novel View Synthesis**](https://arxiv.org/abs/2409.03685) | CoRL 2024 | 2024-09-05 | ![Star](https://img.shields.io/github/stars/s-tian/VISTA?style=social&label=Star) [Github](https://github.com/s-tian/VISTA) |  |
| [**RoVi-Aug: Robot and Viewpoint Augmentation for Cross-Embodiment Robot Learning**](https://arxiv.org/abs/2409.03403) | CoRL 2024 | 2024-09-05 | [Project](https://rovi-aug.github.io/) |  |
| [GENIMA: **Generative Image as Action Models**](https://arxiv.org/abs/2407.07875) | CoRL 2024 | 2024-07-10 | ![Star](https://img.shields.io/github/stars/MohitShridhar/genima?style=social&label=Star)  [Github](https://github.com/MohitShridhar/genima) |  |
| [**RT-Sketch: Goal-Conditioned Imitation Learning from Hand-Drawn Sketches**](https://arxiv.org/abs/2403.02709) | CoRL 2024 | 2024-03-05 | [Project](https://rt-sketch.github.io/) | Sketch |
| [**Diffusion Augmented Agents: A Framework for Efficient Exploration and Transfer Learning**](https://arxiv.org/abs/2407.20798) | CoLLAs 2024 | 2024-07-30 | [Project](https://sites.google.com/view/diffusion-augmented-agents/) |  |
| [**Diffusion Meets DAgger: Supercharging Eye-in-hand Imitation Learning**](https://arxiv.org/abs/2402.17768) | RSS 2024 | 2023-02-27 | ![Star](https://img.shields.io/github/stars/ErinZhang1998/dmd_diffusion?style=social&label=Star) [Github](https://github.com/ErinZhang1998/dmd_diffusion) | |
| [**Offline Imitation Learning with Variational Counterfactual Reasoning**](https://arxiv.org/abs/2310.04706) | NeurIPSS 2023 | 2023-10-07 | ![Star](https://img.shields.io/github/stars/ZexuSun/OILCA-NeurIPS23?style=social&label=Star) [Github](https://github.com/ZexuSun/OILCA-NeurIPS23) |  |
| [ROSIE: **Scaling Robot Learning with Semantically Imagined Experience**](https://arxiv.org/abs/2302.11550) | RSS 2023 | 2023-02-22 | [Project](https://diffusion-rosie.github.io/) |  |
| [**GenAug: Retargeting behaviors to unseen situations via Generative Augmentation**](https://arxiv.org/abs/2302.06671) | RSS 2023 | 2023-02-13 | ![Star](https://img.shields.io/github/stars/genaug/genaug?style=social&label=Star) [Github](https://github.com/genaug/genaug) |  |
| [**Identifying Expert Behavior in Offline Training Datasets Improves Behavioral Cloning of Robotic Manipulation Policies**](https://arxiv.org/abs/2301.13019) | RA-L 2023 | 2023-01-30 | ![Star](https://img.shields.io/github/stars/genaug/genaug?style=social&label=Star) [Github](https://github.com/genaug/genaug) |  |
| [**Data Augmentation for Manipulation**](https://arxiv.org/abs/2205.02886) | RSS 2022 | 2022-05-05 | ![Star](https://img.shields.io/github/stars/UM-ARM-Lab/data-augmentation-for-manipulation?style=social&label=Star) [Github](https://github.com/UM-ARM-Lab/data-augmentation-for-manipulation) |  |
| [**Goal-conditioned Imitation Learning**](https://arxiv.org/abs/1906.05838) | NeurIPS 2019 | 2019-06-13 | ![Star](https://img.shields.io/github/stars/dingyiming0427/goalgail?style=social&label=Star) [Github](https://github.com/dingyiming0427/goalgail) |  |

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
| [**Efficient Data Collection for Robotic Manipulation via Compositional Generalization**](https://arxiv.org/abs/2403.05110) | RSS 2024 | 2024-03-08 | [Project](https://iliad.stanford.edu/robot-data-comp/) | Compositional Generalization |
| [PROGRAMPORT: **Programmatically Grounded, Compositionally Generalizable Robotic Manipulation**](https://arxiv.org/abs/2304.13826) | ICLR 2023 | 2023-04-26 | [Project](https://progport.github.io/) | Compositional Generalization |
| [**Policy Architectures for Compositional Generalization in Control**](https://arxiv.org/abs/2203.05960) | NeurIPSW 2022 | 2022-03-10 | ![Star](https://img.shields.io/github/stars/facebookresearch/entity-factored-rl?style=social&label=Star) [Github](https://github.com/facebookresearch/entity-factored-rl) | Compositional Generalization |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Long-horizon Generalization
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Offline Discovery of Interpretable Skills from Multi-Task Trajectories**](https://arxiv.org/abs/2602.01018) | arXiv | 2026-02-01 | ![Star](https://img.shields.io/github/stars/ChongyuZhu/LOKI?style=social&label=Star) [Github](https://github.com/ChongyuZhu/LOKI) | |
| [**Learning a Thousand Tasks in a Day**](https://arxiv.org/abs/2511.10110) | SR 2025 | 2025-11-13 | ![Star](https://img.shields.io/github/stars/kamil-dreczkowski/learning_thousand_tasks?style=social&label=Star) [Github](https://github.com/kamil-dreczkowski/learning_thousand_tasks) | |
| [**Symskill: Symbol and Skill Co-Invention for Data-Efficient and Real-Time Long-Horizon Manipulation**](https://arxiv.org/abs/2510.01661) | CoRLW 2025 | 2025-10-02 | ![Star](https://img.shields.io/github/stars/shaoyifei96/Symskill?style=social&label=Star) [Github](https://github.com/shaoyifei96/Symskill) | |
| [**SARM: Stage-Aware Reward Modeling for Long Horizon Robot Manipulation**](https://arxiv.org/abs/2509.25358) | arXiv | 2025-09-29 | [Project](https://qianzhong-chen.github.io/sarm.github.io/) | |
| [**Compose by Focus: Scene Graph-based Atomic Skills**](https://arxiv.org/abs/2509.16053) | arXiv | 2025-09-19 | [Project](https://computationalrobotics.seas.harvard.edu/SkillComposition/) | |
| [**ManiLong-Shot: Interaction-Aware One-Shot Imitation Learning for Long-Horizon Manipulation**](https://arxiv.org/abs/2512.16302) | AAAI 2026 | 2025-12-18 | [Project](https://sites.google.com/view/manilong-shot) | |
| [**BT-TL-DMPs: A Novel Robot TAMP Framework Combining Behavior Tree, Temporal Logic and Dynamical Movement Primitives**](https://arxiv.org/abs/2507.14582) | arXiv | 2025-07-19 | - | |
| [**Bootstrapping Imitation Learning for Long-horizon Manipulation via Hierarchical Data Collection Space**](https://arxiv.org/abs/2505.17389) | arXiv | 2025-05-23 | [Project](https://hd-space-robotics.github.io/) | |
| [**Look Before You Leap: Using Serialized State Machine for Language Conditioned Robotic Manipulation**](https://arxiv.org/abs/2503.05114) | arXiv | 2025-03-07 | [Project](https://hd-space-robotics.github.io/) | |
| [**Long-VLA: Unleashing Long-Horizon Capability of Vision Language Action Model for Robot Manipulation**](https://arxiv.org/abs/2508.19958) | CoRL 2025 | 2025-08-27 | [Project](https://long-vla.github.io/) | |
| [**RoboHorizon: An LLM-Assisted Multi-View World Model for Long-Horizon Robotic Manipulation**](https://arxiv.org/abs/2501.06605) | arXiv | 2025-01-11 | - | |
| [**The Art of Imitation: Learning Long-Horizon Manipulation Tasks from Few Demonstrations**](https://arxiv.org/abs/2407.13432) | arXiv | 2024-07-18 | ![Star](https://img.shields.io/github/stars/robot-learning-freiburg/TAPAS?style=social&label=Star) [Github](https://github.com/robot-learning-freiburg/TAPAS) |  |
| [**DexSkills: Skill Segmentation Using Haptic Data for Learning Autonomous Long-Horizon Robotic Manipulation Tasks**](https://arxiv.org/abs/2405.03476) | arXiv | 2024-05-06 | ![Star](https://img.shields.io/github/stars/ARQ-CRISP/DexSkills?style=social&label=Star) [Github](https://github.com/ARQ-CRISP/DexSkills) |  |
| [**What's the Move? Hybrid Imitation Learning via Salient Points**](https://arxiv.org/abs/2412.05426) | ICLR 2025 | 2024-12-06 | ![Star](https://img.shields.io/github/stars/priyasundaresan/sphinx?style=social&label=Star) [Github](https://github.com/priyasundaresan/sphinx) | |
| [**Hierarchical Hybrid Learning for Long-Horizon Contact-Rich Robotic Assembly**](https://arxiv.org/abs/2409.16451) | arXiv | 2024-09-24 | [Project](https://long-horizon-assembly.github.io/) | |
| [TBBF: **A Backbone for Long-Horizon Robot Task Understanding**](https://arxiv.org/abs/2408.01334) | RA-L 2025 | 2024-08-02 | [Project](https://sites.google.com/view/therbligsbasedbackbone/home) | |
| [**SCaR: Refining Skill Chaining for Long-Horizon Robotic Manipulation via Dual Regularization**](https://openreview.net/forum?id=RnxJc4vTVi) | NeurIPS 2024 | 2024-09-26 | [Project](https://sites.google.com/view/scar8297) | |
| [ManipGen: **Local Policies Enable Zero-shot Long-horizon Manipulation**](https://arxiv.org/abs/2410.22332) | CoRLW 2024 | 2024-10-29 | [Project](https://mihdalal.github.io/manipgen/) | |
| [**SPIRE: Synergistic Planning, Imitation, and Reinforcement for Long-Horizon Manipulation**](https://arxiv.org/abs/2410.18065) | CoRL 2024 | 2024-10-23 | [Project](https://sites.google.com/view/spire-corl-2024) |  |
| [BLADE: **Learning Compositional Behaviors from Demonstration and Language**](https://arxiv.org/abs/2505.21981) | CoRL 2024 | 2025-05-28 | [Project](https://blade-bot.github.io/) | IL, RepL, Poliy Head, Few-Shot Policy Adaptation |
| [PALO: **Policy Adaptation via Language Optimization: Decomposing Tasks for Few-Shot Imitation**](https://arxiv.org/abs/2408.16228) | CoRL 2024 | 2024-08-29 | ![Star](https://img.shields.io/github/stars/vivekmyers/palo?style=social&label=Star) [Github](https://github.com/vivekmyers/palo) | Fine-grained Atom Action |
| [PSL: **Plan-Seq-Learn: Language Model Guided RL for Solving Long Horizon Robotics Tasks**](https://arxiv.org/abs/2405.01534) | ICLR 2024 | 2024-05-02 | ![Star](https://img.shields.io/github/stars/mihdalal/planseqlearn?style=social&label=Star) [Github](https://github.com/mihdalal/planseqlearn) | |
| [**Hierarchical Human-to-Robot Imitation Learning for Long-Horizon Tasks via Cross-Domain Skill Alignment**](https://ieeexplore.ieee.org/document/10610084) | ICRA 2024 | 2024-08-08 | - | |
| [**PRIME: Scaffolding Manipulation Tasks with Behavior Primitives for Data-Efficient Imitation Learning**](https://arxiv.org/abs/2403.00929) | RA-L 2024 | 2024-03-01 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/PRIME?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/PRIME) |  |
| [**GO-DICE: Goal-Conditioned Option-Aware Offline Imitation Learning via Stationary Distribution Correction Estimation**](https://arxiv.org/abs/2312.10802) | AAAI 2024 | 2023-12-17 | - |  |
| [**Actor-Critic for Continuous Action Chunks: A Reinforcement Learning Framework for Long-Horizon Robotic Manipulation with Sparse Reward**](https://arxiv.org/abs/2508.11143) | arXiv | 2023-08-15 | - |  |
| [**Hybrid Hierarchical Learning for Solving Complex Sequential Tasks Using the Robotic Manipulation Network ROMAN**](https://arxiv.org/abs/2307.00125) | NMI 2023 | 2023-07-30 | - |  |
| [BOSS: **Bootstrap Your Own Skills: Learning to Solve New Tasks with Large Language Model Guidance**](https://arxiv.org/abs/2310.10021) | CoRL 2023 | 2023-12-16 | ![Star](https://img.shields.io/github/stars/clvrai/boss?style=social&label=Star) [Github](https://github.com/clvrai/boss) | Skill Bootstrapping |
| [**HYDRA: Hybrid Robot Actions for Imitation Learning**](https://arxiv.org/abs/2306.17237) | CoRL 2023 | 2023-06-29 | [Project](https://sites.google.com/view/hydra-il-2023) |  |
| [**STAP: Sequencing Task-Agnostic Policies**](https://arxiv.org/abs/2210.12250) | ICRA 2023 | 2022-10-21 | ![Star](https://img.shields.io/github/stars/agiachris/STAP?style=social&label=Star) [Github](https://github.com/agiachris/STAP) |  |
| [**Divide & Conquer Imitation Learning**](https://arxiv.org/abs/2204.07404) | IROS 2022 | 2022-02-15 | - |  |
| [**Bottom-Up Skill Discovery from Unsegmented Demonstrations for Long-Horizon Robot Manipulation**](https://arxiv.org/abs/2109.13841) | RA-L 2022 | 2021-09-28 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/BUDS?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/BUDS) |  |
| [**Adversarial Skill Chaining for Long-Horizon Robot Manipulation via Terminal State Regularization**](https://arxiv.org/abs/2111.07999) | CoRL 2021 | 2021-11-15 | ![Star](https://img.shields.io/github/stars/clvrai/skill-chaining?style=social&label=Star) [Github](https://github.com/clvrai/skill-chaining) |  |
| [**Sequential Robot Imitation Learning from Observations**](https://journals.sagepub.com/doi/abs/10.1177/02783649211032721) | IJRR 2021 | 2021-08-06 | - |  |
| [**SQUIRL: Robust and Efficient Learning from Video Demonstration of Long-Horizon Robotic Manipulation Tasks**](https://arxiv.org/abs/2003.04956) | IROS 2020 | 2020-03-10 | [Project](https://crlab.cs.columbia.edu/squirl/) |  |
| [**Learning to Generalize Across Long-Horizon Tasks from Human Demonstrations**](https://arxiv.org/abs/2003.06085) | RSS 2020 | 2020-03-13 | [Project](https://sites.google.com/view/gti2020/) |  |
| [**Learning to Combine Primitive Skills: A Step towards Versatile Robotic Manipulation**](https://arxiv.org/abs/1908.00722) | ICRA 2020 | 2019-08-02 | ![Star](https://img.shields.io/github/stars/rstrudel/rlbc?style=social&label=Star) [Github](https://github.com/rstrudel/rlbc) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Few-shot Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**UMIGen: A Unified Framework for Egocentric Point Cloud Generation and Cross-Embodiment Robotic Imitation Learning**](https://arxiv.org/abs/2511.09302) | arXiv | 2025-11-12 | - |  |
| [**EmbodiSwap for Zero-Shot Robot Imitation Learning**](https://arxiv.org/abs/2510.03706) | arXiv | 2025-10-04 | - |  |
| [**Annotation-Free One-Shot Imitation Learning for Multi-Step Manipulation Tasks**](https://arxiv.org/abs/2509.24972) | arXiv | 2025-09-29 | ![Star](https://img.shields.io/github/stars/vijja-w/AF-OSIL-MS?style=social&label=Star) [Github](https://github.com/vijja-w/AF-OSIL-MS) |  |
| [**TReF-6: Inferring Task-Relevant Frames from a Single Demonstration for One-Shot Skill Generalization**](https://arxiv.org/abs/2509.00310) | arXiv | 2025-08-30 | - |  |
| [**Elastic Motion Policy: An Adaptive Dynamical System for Robust and Efficient One-Shot Imitation Learning**](https://arxiv.org/abs/2503.08029) | IROS 2025 | 2025-03-11 | [Project](https://elastic-motion-policy.github.io/EMP/) |  |
| [**VidBot: Learning Generalizable 3D Actions from In-the-Wild 2D Human Videos for Zero-Shot Robotic Manipulation**](https://arxiv.org/abs/2503.07135) | CVPR 2025 | 2025-03-10 | [Project](https://hanzhic.github.io/vidbot-project/) |  |
| [**One-Shot Dual-Arm Imitation Learning**](https://arxiv.org/abs/2503.06831) | ICRA 2025 | 2025-03-10 | [Project](https://www.robot-learning.uk/one-shot-dual-arm) |  |
| [**You Only Teach Once: Learn One-Shot Bimanual Robotic Manipulation from Video Demonstrations**](https://arxiv.org/abs/2501.14208) | RSS 2025 | 2025-01-24 | ![Star](https://img.shields.io/github/stars/hnuzhy/YOTO?style=social&label=Star) [Github](https://github.com/hnuzhy/YOTO) |  |
| [**Zero-Shot Offline Imitation Learning via Optimal Transport**](https://arxiv.org/abs/2410.08751) | arXiv | 2024-10-11 | ![Star](https://img.shields.io/github/stars/martius-lab/zilot?style=social&label=Star) [Github](https://github.com/martius-lab/zilot) |  |
| [**Vision-based Manipulation from Single Human Video with Open-World Object Graphs**](https://arxiv.org/abs/2405.20321) | CoRLW 2024 | 2024-05-30 | [Project](https://ut-austin-rpl.github.io/ORION-release/) |  |
| [**DITTO: Demonstration Imitation by Trajectory Transformation**](https://arxiv.org/abs/2403.15203) | IROS 2024 | 2024-03-22 | ![Star](https://img.shields.io/github/stars/robot-learning-freiburg/DITTO?style=social&label=Star) [Github](https://github.com/robot-learning-freiburg/DITTO) |  
| [**CoBT: Collaborative Programming of Behaviour Trees from One Demonstration for Robot Manipulation**](https://arxiv.org/abs/2404.05870) | ICRA 2024 | 2024-04-08 | ![Star](https://img.shields.io/github/stars/jainaayush2006/CoBT?style=social&label=Star) [Github](https://github.com/jainaayush2006/CoBT) |  
| [**Zero-Shot Visual Generalization in Robot Manipulation**](https://arxiv.org/abs/2505.11719) | arXiv | 2022-05-16 | [Project](https://sites.google.com/view/vis-gen-robotics/home) |  |
| [**One-Shot Domain-Adaptive Imitation Learning via Progressive Learning**](https://arxiv.org/abs/2204.11251) | TASE 2022 | 2022-04-24 | - |  |
| [**Demonstrate Once, Imitate Immediately (DOME): Learning Visual Servoing for One-Shot Imitation Learning**](https://arxiv.org/abs/2204.02863) | IROS 2022 | 2022-04-06 | [Project](https://www.robot-learning.uk/dome) |  |
| [**Coarse-to-Fine Imitation Learning: Robot Manipulation from a Single Demonstration**](https://arxiv.org/abs/2105.06411) | ICRA 2021 | 2021-05-13 | [Project](https://www.robot-learning.uk/coarse-to-fine-imitation-learning) |  |
| [**SOZIL: Self-Optimal Zero-Shot Imitation Learning**](https://ieeexplore.ieee.org/document/9552943) | TCDS 2021 | 2021-09-30 | - |  |
| [**Zero-Shot Visual Imitation**](https://arxiv.org/abs/1804.08606) | ICLR 2018  | 2018-04-23 | ![Star](https://img.shields.io/github/stars/pathak22/zeroshot-imitation?style=social&label=Star) [Github](https://github.com/pathak22/zeroshot-imitation) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Meta Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Few-Shot Vision-Language Action-Incremental Policy Learning**](https://arxiv.org/abs/2504.15517) | arXiv | 2025-04-22 | ![Star](https://img.shields.io/github/stars/codeshop715/FSAIL?style=social&label=Star) [Github](https://github.com/codeshop715/FSAIL) |  |
| [**Learning Generalizable 3D Manipulation With 10 Demonstrations**](https://arxiv.org/abs/2411.10203) | arXiv | 2024-11-15 | ![Star](https://img.shields.io/github/stars/renyu2016/Generalized-3D-Manipulation?style=social&label=Star) [Github](https://github.com/renyu2016/Generalized-3D-Manipulation) |  |
| [**One-Shot Imitation Learning with Invariance Matching for Robotic Manipulation**](https://arxiv.org/abs/2405.13178) | RSS 2024 | 2024-05-21 | ![Star](https://img.shields.io/github/stars/mlzxy/imop?style=social&label=Star) [Github](https://github.com/mlzxy/imop) | |
| [**One-Shot Imitation Learning With Graph Neural Networks for Pick-and-Place Manipulation Tasks**](https://ieeexplore.ieee.org/document/10202200/) | RA-L 2023 | 2023-08-02 | - |
| [**One-Shot Imitation Learning: A Pose Estimation Perspective**](https://arxiv.org/pdf/2310.12077) | CoRL 2023 | 2023-10-18 | [Project](https://www.robot-learning.uk/pose-estimation-perspective) |  |
| [**One-shot Imitation Learning via Interaction Warping**](https://arxiv.org/abs/2306.12392) | CoRL 2023 | 2023-06-21 | ![Star](https://img.shields.io/github/stars/ondrejbiza/shapewarping?style=social&label=Star) [Github](https://github.com/ondrejbiza/shapewarping) |
| [**Teach a Robot to FISH: Versatile Imitation from One Minute of Demonstrations**](https://arxiv.org/abs/2303.01497) | RSS 2023 | 2023-03-02 | ![Star](https://img.shields.io/github/stars/siddhanthaldar/FISH?style=social&label=Star) [Github](https://github.com/siddhanthaldar/FISH) |
| [**Meta-Reinforcement Learning via Language Instructions**](https://arxiv.org/abs/2209.04924) | ICRA 2023 | 2022-09-11 | ![Star](https://img.shields.io/github/stars/yaoxt3/MILLION?style=social&label=Star) [Github](https://github.com/yaoxt3/MILLION) |
| [**Transfering Hierarchical Structure with Dual Meta Imitation Learning**](https://arxiv.org/abs/2201.11981) | CoRL 2022 | 2022-01-28 | - |
| [**Towards More Generalizable One-shot Visual Imitation Learning**](https://arxiv.org/abs/2110.13423) | ICRA 2022 | 2021-10-26 | ![Star](https://img.shields.io/github/stars/rll-research/mosaic?style=social&label=Star) [Github](https://github.com/rll-research/mosaic) | | 
| [**Attentive One-Shot Meta-Imitation Learning From Visual Demonstration**](https://ieeexplore.ieee.org/document/9812281) | ICRA 2022 | 2021-07-12 | - | | 
| [**Meta-Imitation Learning by Watching Video Demonstrations**](https://openreview.net/forum?id=KTPuIsx4pmo) | ICLR 2022 | 2022-01-29 | - | | 
| [**Visual Goal-Directed Meta-Learning with Contextual Planning Networks**](https://arxiv.org/abs/2111.09908) | CVPRW 2021 | 2021-11-18 | - | | 
| [**Watch, Try, Learn: Meta-Learning from Demonstrations and Reward**](https://arxiv.org/abs/1906.03352) | ICLR 2020 | 2019-06-07 | - | | 
| [**One-Shot Hierarchical Imitation Learning of Compound Visuomotor Tasks**](https://arxiv.org/abs/1810.11043) | arXiv | 2018-10-08 | [Project](https://sites.google.com/view/one-shot-hil) | | 
| [**Task-Embedded Control Networks for Few-Shot Imitation Learning**](https://arxiv.org/abs/1810.03237) | CoRL 2018 | 2018-10-08 | ![Star](https://img.shields.io/github/stars/stepjam/TecNets?style=social&label=Star) [Github](https://github.com/stepjam/TecNets) | | 
| [**One-Shot Imitation from Observing Humans via Domain-Adaptive Meta-Learning**](https://arxiv.org/abs/1802.01557) | RSS 2018 | 2018-02-05 | ![Star](https://img.shields.io/github/stars/tianheyu927/mil?style=social&label=Star) [Github](https://github.com/tianheyu927/mil) | | 
| [**One-Shot Visual Imitation Learning via Meta-Learning**](https://arxiv.org/abs/1709.04905) | CoRL 2017 | 2017-09-14 | ![Star](https://img.shields.io/github/stars/tianheyu927/mil?style=social&label=Star) [Github](https://github.com/tianheyu927/mil) | | 
| [**One-Shot Imitation Learning**](https://arxiv.org/abs/1703.07326) | NeurIPS 2017 | 2017-03-21 | [Project](https://sites.google.com/view/nips2017-one-shot-imitation/home) | | 

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Lifelong/Continual/Incremental Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Policy Compatible Skill Incremental Learning via Lazy Learning Interface**](https://arxiv.org/abs/2509.20612) | arXiv | 2025-09-24 | ![Star](https://img.shields.io/github/stars/L2dulgi/SIL-C?style=social&label=Star) [Github](https://github.com/L2dulgi/SIL-C) |  |
| [**T2S: Tokenized Skill Scaling for Lifelong Imitation Learning**](https://arxiv.org/abs/2508.01167) | arXiv | 2025-08-12 | - |  |
| [**Dynamic Mixture of Progressive Parameter-Efficient Expert Library for Lifelong Robot Learning**](https://arxiv.org/abs/2506.05985) | arXiv | 2025-06-06 | - |  |
| [**SPECI: Skill Prompts based Hierarchical Continual Imitation Learning for Robot Manipulation**](https://arxiv.org/abs/2504.15561) | arXiv | 2025-04-22 | - |  |
| [**Think Small, Act Big: Primitive Prompt Learning for Lifelong Robot Manipulation**](https://arxiv.org/abs/2504.00420) | CVPR 2025 | 2025-04-01 | - |  |
| [**iManip: Skill-Incremental Learning for Robotic Manipulation**](https://arxiv.org/abs/2503.07087) | arXiv | 2025-03-10 | - |  |
| [**M2Distill: Multi-Modal Distillation for Lifelong Imitation Learning**](https://arxiv.org/abs/2410.00064) | ICRA 2025 | 2024-10-30 | - |  |
| [**LOTUS: Continual Imitation Learning for Robot Manipulation Through Unsupervised Skill Discovery**](https://arxiv.org/abs/2311.02058) | ICRA 2024 | 2023-11-03 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/Lotus?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/Lotus) |  |
| [**CRIL: Continual Robot Imitation Learning via Generative and Prediction Model**](https://arxiv.org/abs/2106.09422) | IROS 2021 | 2021-06-17 | ![Star](https://img.shields.io/github/stars/HeegerGao/CRIL?style=social&label=Star) [Github](https://github.com/HeegerGao/CRIL) |  |

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
| [**Real2Edit2Real: Generating Robotic Demonstrations via a 3D Control Interface**](https://arxiv.org/abs/2512.19402) | arXiv | 2025-12-22 | ![Star](https://img.shields.io/github/stars/Real2Edit2Real/Real2Edit2Real?style=social&label=Star) [Github](https://github.com/Real2Edit2Real/Real2Edit2Real) |  |
| [**TwinAligner: Visual-Dynamic Alignment Empowers Physics-aware Real2Sim2Real for Robotic Manipulation**](https://arxiv.org/abs/2512.19390) | arXiv | 2025-12-22 | ![Star](https://img.shields.io/github/stars/TwinAligner/TwinAligner?style=social&label=Star) [Github](https://github.com/TwinAligner/TwinAligner) |  |
| [**PolaRiS: Scalable Real-to-Sim Evaluations for Generalist Robot Policies**](https://arxiv.org/abs/2512.16881) | arXiv | 2025-12-18 | ![Star](https://img.shields.io/github/stars/arhanjain/PolaRiS?style=social&label=Star) [Github](https://github.com/arhanjain/PolaRiS) |  |
| [**Phys2Real: Fusing VLM Priors with Interactive Online Adaptation for Uncertainty-Aware Sim-to-Real Manipulation**](https://arxiv.org/abs/2510.11689) | arXiv | 2025-10-13 | [Project](https://phys2real.github.io/) |  |
| [**High-Fidelity Simulated Data Generation for Real-World Zero-Shot Robotic Manipulation Learning with Gaussian Splatting**](https://arxiv.org/abs/2510.10637) | arXiv | 2025-10-12 | ![Star](https://img.shields.io/github/stars/Maxwell-Zhao/RoboSimGS?style=social&label=Star) [Github](https://github.com/Maxwell-Zhao/RoboSimGS) |  |
| [**A Recipe for Efficient Sim-to-Real Transfer in Manipulation with Online Imitation-Pretrained World Models**](https://arxiv.org/abs/2510.02538) | arXiv | 2025-10-02 | - |  |
| [**FUNCanon: Learning Pose-Aware Action Primitives via Functional Object Canonicalization for Generalizable Robotic Manipulation**](https://arxiv.org/abs/2509.19102) | arXiv | 2025-09-23 | [Project](https://sites.google.com/view/funcanon) |  |
| [**Robot Learning from Any Images**](https://arxiv.org/abs/2509.22970) | arXiv | 2025-09-26 | ![Star](https://img.shields.io/github/stars/sihengz02/RoLA?style=social&label=Star) [Github](https://github.com/sihengz02/RoLA) |  |
| [**Generalizable Domain Adaptation for Sim-and-Real Policy Co-Training**](https://arxiv.org/abs/2509.186313) | arXiv | 2025-09-23 | - |  |
| [**RoboSeek: You Need to Interact with Your Objects**](https://arxiv.org/abs/2509.17783) | arXiv | 2025-09-22 | [Project](https://russderrick.github.io/Roboseek/) |  |
| [**Manipulation as in Simulation: Enabling Accurate Geometry Perception in Robots**](https://arxiv.org/abs/2509.02530) | arXiv | 2025-09-17 | ![Star](https://img.shields.io/github/stars/ByteDance-Seed/manip-as-in-sim-suite?style=social&label=Star) [Github](https://github.com/ByteDance-Seed/manip-as-in-sim-suite) |  |
| [**Real2Render2Real: Scaling Robot Data Without Dynamics Simulation or Robot Hardware**](https://arxiv.org/abs/2505.09601) | arXiv | 2025-05-14 | [Project](https://real2render2real.com/) |  |
| [**Sim-and-Real Co-Training: A Simple Recipe for Vision-Based Robotic Manipulation**](https://arxiv.org/abs/2405.10020) | arXiv | 2025-03-31 | [Project](https://co-training.github.io/) |  |
| [**Robot Policy Evaluation for Sim-to-Real Transfer: A Benchmarking Perspective**](https://arxiv.org/abs/2508.11117) | RSSW 2025 | 2025-08-14 | - |  |
| [**ScissorBot: Learning Generalizable Scissor Skill for Paper Cutting via Simulation, Imitation, and Sim2Real**](https://arxiv.org/abs/2409.13966) | CoRL 2024 | 2024-09-21 | ![Star](https://img.shields.io/github/stars/jiangranlv/ScissorBot?style=social&label=Star) [Github](https://github.com/jiangranlv/ScissorBot) |  |
| [Maniwhere: **Learning to Manipulate Anywhere: A Visual Generalizable Framework For Reinforcement Learning**](https://arxiv.org/abs/2407.15815) | CoRL 2024 | 2024-07-22 | [Project](https://gemcollector.github.io/maniwhere/) |  |
| [**Natural Language Can Help Bridge the Sim2Real Gap**](https://arxiv.org/abs/2405.10020) | RSS 2024 | 2024-05-16 | ![Star](https://img.shields.io/github/stars/UT-Austin-RobIn/lang4sim2real?style=social&label=Star) [Github](https://github.com/UT-Austin-RobIn/lang4sim2real) |  |
| [RialTo: **Reconciling Reality through Simulation: A Real-to-Sim-to-Real Approach for Robust Manipulation**](https://arxiv.org/abs/2403.03949) | RSS 2024 | 2024-03-06 | ![Star](https://img.shields.io/github/stars/real-to-sim-to-real/RialToPolicyLearning?style=social&label=Star) [Github](https://github.com/real-to-sim-to-real/RialToPolicyLearning) |  |
| [**Practical Visual Deep Imitation Learning via Task-Level Domain Consistency**](https://ieeexplore.ieee.org/document/10161202) | ICRA 2023 | 2023-07-04 | - |  |
| [**RetinaGAN: An Object-aware Approach to Sim-to-Real Transfer**](https://arxiv.org/abs/2011.03148) | ICRA 2021 | 2020-11-06 | [Project](https://retinagan.github.io/) |  |
| [**Self-Supervised Sim-to-Real Adaptation for Visual Robotic Manipulation**](https://arxiv.org/abs/1910.09470) | ICRA 2020 | 2019-10-21 | - |  |
| [**Transferring Visuomotor Learning from Simulation to the Real World for Robotics Manipulation Tasks**](https://ieeexplore.ieee.org/document/8594519) | IROS 2018 | 2019-01-06 | - |  |
| [**Sim-to-Real Transfer of Robotic Control with Dynamics Randomization**](https://arxiv.org/abs/1710.06537) | ICRA 2018 | 2017-10-18 | - |  |
| [Domain Randomization: **Sim-to-Real Transfer of Robotic Control with Dynamics Randomization**](https://arxiv.org/abs/1710.06537) | ICRA 2018 | 2017-10-18 | - |  |
| [**Transferring End-to-End Visuomotor Control from Simulation to Real World for a Multi-Stage Task**](https://arxiv.org/abs/1710.06537) | CoRL 2017 | 2017-07-07 | - |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### SE(3)/SIM(3)-Equivariance (View Changes)
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**EquiForm: Noise-Robust SE(3)-Equivariant Policy Learning from 3D Point Clouds**](https://arxiv.org/abs/2601.17486) | arXiv | 2026-01-24 | [Project](https://zhangzhiyuanzhang.github.io/equiform-website/) | |
| [**Sim2real Image Translation Enables Viewpoint-Robust Policies from Fixed-Camera Datasets**](https://arxiv.org/abs/2601.09605) | arXiv | 2026-01-14 | [Project](https://sites.google.com/view/sim2real-viewpoints) | |
| [**Learning to Act Robustly with View-Invariant Latent Actions**](https://arxiv.org/abs/2601.02994) | arXiv | 2026-01-06 | [Project](https://joon-stack.github.io/VILA/) | |
| [**Bridging Simulation and Reality: Cross-Domain Transfer with Semantic 2D Gaussian Splatting**](https://arxiv.org/abs/2512.04731) | arXiv | 2025-12-04 | - | |
| [**Eq.Bot: Enhance Robotic Manipulation Learning via Group Equivariant Canonicalization**](https://arxiv.org/abs/2511.15194) | arXiv | 2025-11-19 | - | |
| [**EgoMI: Learning Active Vision and Whole-Body Manipulation from Egocentric Human Demonstrations**](https://arxiv.org/abs/2511.00153) | arXiv | 2025-10-31 | [Project](https://egocentric-manipulation-interface.github.io/) | |
| [**Do You Know Where Your Camera Is? View-Invariant Policy Learning with Camera Conditioning**](https://arxiv.org/abs/2510.02268) | arXiv | 2025-10-02 | [Project](https://ripl.github.io/know_your_camera/) | |
| [**ManiVID-3D: Generalizable View-Invariant Reinforcement Learning for Robotic Manipulation via Disentangled 3D Representations**](https://arxiv.org/abs/2509.11125) | arXiv | 2025-09-14 | [Project](https://zheng-joe-lee.github.io/manivid3d/) |  |
| [**Vision in Action: Learning Active Perception from Human Demonstrations**](https://arxiv.org/abs/2506.15666) | arXiv | 2025-06-18 | ![Star](https://img.shields.io/github/stars/haoyu-x/vision-in-action?style=social&label=Star) [Github](https://github.com/haoyu-x/vision-in-action) | |
| [**Imitation Learning for Active Neck Motion Enabling Robot Manipulation beyond the Field of View**](https://arxiv.org/abs/2506.17624) | arXiv | 2025-06-21 | - | View Changes |
| [**Adapt3R: Adaptive 3D Scene Representation for Domain Transfer in Imitation Learning**](https://arxiv.org/abs/2503.04877) | arXiv | 2025-03-06 | ![Star](https://img.shields.io/github/stars/pairlab/Adapt3R?style=social&label=Star) [Github](https://github.com/pairlab/Adapt3R) | View Changes & Cross-Embodiment |
| [**ET-SEED: Efficient Trajectory-Level SE(3) Equivariant Diffusion Policy**](https://arxiv.org/abs/2411.03990) | ICLR 2025 | 2024-11-06 | ![Star](https://img.shields.io/github/stars/yuechen0614/ET-SEED?style=social&label=Star) [Github](https://github.com/yuechen0614/ET-SEED) |  |
| [**EquiBot: SIM(3)-Equivariant Diffusion Policy for Generalizable and Data Efficient Learning**](https://arxiv.org/abs/2407.01479) | CoRL 2024 | 2024-07-01 | ![Star](https://img.shields.io/github/stars/yjy0625/equibot?style=social&label=Star) [Github](https://github.com/yjy0625/equibot) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Lighting/background/distractor Changes
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**PALM: Enhanced Generalizability for Local Visuomotor Policies via Perception Alignment**](https://arxiv.org/abs/2601.19514) | arXiv | 2026-01-27 | - |  |
| [**RoboView-Bias: Benchmarking Visual Bias in Embodied Agents for Robotic Manipulation**](https://arxiv.org/abs/2509.22356) | arXiv | 2025-09-26 | - |  |
| [**Towards Exploratory and Focused Manipulation with Bimanual Active Perception: A New Problem, Benchmark and Strategy**](https://arxiv.org/abs/2602.01939) | ICRA 2026 | 2026-02-02 | [Project](https://efmanipulation.github.io/) |  |
| [**Physically-based Lighting Augmentation for Robotic Manipulation**](https://www.arxiv.org/abs/2508.01442) | arXiv | 2025-08-02 | - | Lighting Changes |
| [**Is an object-centric representation beneficial for robotic manipulation?**](https://arxiv.org/abs/2506.19408) | arXiv | 2025-06-24 | - |  |
| [**SwitchVLA: Execution-Aware Task Switching for Vision-Language-Action Models**](https://arxiv.org/abs/2506.03574) | arXiv | 2025-06-04 | [Project](https://switchvla.github.io/) | |
| [**Diffusion-VLA: Scaling Robot Foundation Models via Unified Diffusion and Autoregression**](https://arxiv.org/abs/2412.03293) | ICML 2025 | 2024-12-14 | [Project](https://diffusion-vla.github.io/) |  |
| [**Decomposing the Generalization Gap in Imitation Learning for Visual Robotic Manipulation**](https://arxiv.org/abs/2307.03659) | ICRA 2024 | 2024-02-29 | ![Star](https://img.shields.io/github/stars/RLAgent/factor-world?style=social&label=Star) [Github](https://github.com/RLAgent/factor-world) | 
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
| [**Sim-and-Human Co-training for Data-Efficient and Generalizable Robotic Manipulation**](https://arxiv.org/abs/2601.19406) | arXiv | 2026-01-27 | ![Star](https://img.shields.io/github/stars/kaipengfang/SimHum?style=social&label=Star) [Github](https://github.com/kaipengfang/SimHum) |  |
| [**CEI: A Unified Interface for Cross-Embodiment Visuomotor Policy Learning in 3D Space**](https://arxiv.org/abs/2601.09163) | RA-L 2026 | 2026-01-14 | [Project](https://cross-embodiment-interface.github.io/) |  |
| [**X-Diffusion: Training Diffusion Policies on Cross-Embodiment Human Demonstrations**](https://arxiv.org/abs/2511.04671) | arXiv | 2025-11-06 | [Project](https://portal-cornell.github.io/X-Diffusion/) |  |
| [**Trajectory Conditioned Cross-embodiment Skill Transfer**](https://arxiv.org/abs/2510.07773) | arXiv | 2025-10-09 | - |  |
| [**MV-UMI: A Scalable Multi-View Interface for Cross-Embodiment Learning**](https://arxiv.org/abs/2509.18757) | arXiv | 2025-09-23 | [Project](https://mv-umi.github.io/) |  |
| [**From Human Hands to Robot Arms: Manipulation Skills Transfer via Trajectory Alignment**](https://arxiv.org/abs/2510.00491) | arXiv | 2025-10-01 | [Project](https://anonymous.4open.science/w/Traj2Action-4A45/) |  |
| [**UniPrototype: Humn-Robot Skill Learning with Uniform Prototypes**](https://arxiv.org/abs/2509.23021) | arXiv | 2025-09-27 | - |  |
| [**Prepare Before You Act: Learning From Humans to Rearrange Initial States**](https://arxiv.org/abs/2509.18043) | arXiv | 2025-09-22 | [Project](https://reset2025paper.github.io/) |  |
| [**MotionTrans: Human VR Data Enable Motion-Level Learning for Robotic Manipulation Policies**](https://arxiv.org/abs/2509.17759) | arXiv | 2025-09-22 | ![Star](https://img.shields.io/github/stars/michaelyuancb/motiontrans?style=social&label=Star) [Github](https://github.com/michaelyuancb/motiontrans) |  |
| [**Tenma: Robust Cross-Embodiment Robot Manipulation with Diffusion Transformer**](https://arxiv.org/abs/2509.11865) | arXiv | 2025-09-15 | - |  |
| [**ImMimic: Cross-Domain Imitation from Human Videos via Mapping and Interpolation**](https://arxiv.org/abs/2509.10952) | arXiv | 2025-09-13 | [Project](https://sites.google.com/view/immimic) |  |
| [**3DFlowAction: Learning Cross-Embodiment Manipulation from 3D Flow World Model**](https://arxiv.org/abs/2506.06199) | arXiv | 2025-06-06 | ![Star](https://img.shields.io/github/stars/Hoyyyaard/3DFlowAction?style=social&label=Star) [Github](https://github.com/Hoyyyaard/3DFlowAction/) |  |
| [**RoboOS: A Hierarchical Embodied Framework for Cross-Embodiment and Multi-Agent Collaboration**](https://arxiv.org/abs/2505.03673) | arXiv | 2025-05-06 | ![Star](https://img.shields.io/github/stars/FlagOpen/RoboOS?style=social&label=Star) [Github](https://github.com/FlagOpen/RoboOS) |  |
| [**X-Sim: Cross-Embodiment Learning via Real-to-Sim-to-Real**](http://arxiv.org/abs/2505.07096) | arXiv | 2025-05-11 | ![Star](https://img.shields.io/github/stars/portal-cornell/X-Sim?style=social&label=Star) [Github](https://github.com/portal-cornell/X-Sim) |  |
| [**Crossing the Human-Robot Embodiment Gap with Sim-to-Real RL using One Human Demonstration**](https://arxiv.org/abs/2504.12609) | arXiv | 2025-04-17 | ![Star](https://img.shields.io/github/stars/tylerlum/human2sim2robot?style=social&label=Star) [Github](https://github.com/tylerlum/human2sim2robot) |  |
| [**EgoBridge: Domain Adaptation for Generalizable Imitation from Egocentric Human Data**](https://arxiv.org/abs/2509.19626) | CoRL 2025 | 2025-09-23 | [Project](https://ego-bridge.github.io/) |  |
| [**UniSkill: Imitating Human Videos via Cross-Embodiment Skill Representations**](https://arxiv.org/abs/2505.08787) | CoRL 2025 | 2025-05-13 | ![Star](https://img.shields.io/github/stars/KimHanjung/UniSkill?style=social&label=Star) [Github](https://github.com/KimHanjung/UniSkill) |  |
| [**AnyBimanual: Transferring Unimanual Policy for General Bimanual Manipulation**](https://arxiv.org/abs/2412.06779) | ICCV 2025 | 2024-12-09 | ![Star](https://img.shields.io/github/stars/Tengbo-Yu/AnyBimanual?style=social&label=Star) [Github](https://github.com/Tengbo-Yu/AnyBimanual) |  |
| [**LEGATO: Cross-Embodiment Imitation Using a Grasping Tool**](https://arxiv.org/abs/2411.03682) | RA-L 2025 | 2024-11-06 | ![Star](https://img.shields.io/github/stars/UT-HCRL/LEGATO?style=social&label=Star) [Github](https://github.com/UT-HCRL/LEGATO) | |
| [**Cross-Embodiment Robot Manipulation Skill Transfer using Latent Space Alignment**](https://arxiv.org/abs/2406.01968) | arXiv | 2024-06-04 | ![Star](https://img.shields.io/github/stars/ExistentialRobotics/cross_embodiment_transfer?style=social&label=Star) [Github](https://github.com/ExistentialRobotics/cross_embodiment_transfer) | |
| [HPT: **Scaling Proprioceptive-Visual Learning with Heterogeneous Pre-trained Transformers**](https://arxiv.org/abs/2409.20537) | NeurIPS 2024 | 2024-09-30 | ![Star](https://img.shields.io/github/stars/liruiw/HPT?style=social&label=Star) [Github](https://github.com/liruiw/HPT) |  |
| [CrossFormer: **Scaling Cross-Embodied Learning: One Policy for Manipulation, Navigation, Locomotion and Aviation**](https://arxiv.org/abs/2408.11812) | CoRL 2024 | 2024-08-21 | ![Star](https://img.shields.io/github/stars/rail-berkeley/crossformer?style=social&label=Star) [Github](https://github.com/rail-berkeley/crossformer) | Cross-Embodied |
| [**Pushing the Limits of Cross-Embodiment Learning for Manipulation and Navigation**](https://arxiv.org/abs/2402.19432) | RSS 2024 | 2024-02-29 | ![Star](https://img.shields.io/github/stars/JonathanYang0127/omnimimic?style=social&label=Star) [Github](https://github.com/JonathanYang0127/omnimimic) | |
| [**Mirage: Cross-Embodiment Zero-Shot Policy Transfer with Cross-Painting**](https://arxiv.org/abs/2402.19249) | RSS 2024 | 2024-02-29 | ![Star](https://img.shields.io/github/stars/BerkeleyAutomation/mirage?style=social&label=Star) [Github](https://github.com/BerkeleyAutomation/mirage) | |
| [**XSkill: Cross Embodiment Skill Discovery**](https://arxiv.org/abs/2307.09955) | CoRL 2023 | 2023-07-19 | ![Star](https://img.shields.io/github/stars/real-stanford/xskill?style=social&label=Star) [Github](https://github.com/real-stanford/xskill) | |
| [**Modularity through Attention: Efficient Training and Transfer of Language-Conditioned Policies for Robot Manipulation**](https://arxiv.org/abs/2212.04573) | CoRL 2022 | 2022-12-08 | ![Star](https://img.shields.io/github/stars/ir-lab/ModAttn?style=social&label=Star) [Github](https://github.com/ir-lab/ModAttn) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>



## Human-Robot Interaction and Collaboration
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Transforming Monolithic Foundation Models into Embodied Multi-Agent Architectures for Human-Robot Collaboration**](https://arxiv.org/abs/2512.00797) | arXiv | 2025-11-30 | - |  |
| [**The Role of Consequential and Functional Sound in Human-Robot Interaction: Toward Audio Augmented Reality Interfaces**](https://arxiv.org/abs/2511.15956) | arXiv | 2025-11-20 | [Project](https://sites.google.com/berkeley.edu/rapl) |  |
| [**I've Changed My Mind: Robots Adapting to Changing Human Goals during Collaboration**](https://arxiv.org/abs/2511.15914) | RA-L 2025 | 2025-11-19 | - |  |
| [**Open-Ended Goal Inference through Actions and Language for Human-Robot Collaboration**](https://arxiv.org/abs/2512.04453) | HRI 2026 | 2025-12-04 | - |  |
| [**Maximizing Alignment with Minimal Feedback: Efficiently Learning Rewards for Visuomotor Robot Policy Alignment**](https://arxiv.org/abs/2412.04835) | arXiv | 2024-12-06 | [Project](https://sites.google.com/berkeley.edu/rapl) |  |
| [**Vocal Sandbox: Continual Learning and Adaptation for Situated Human-Robot Collaboration**](https://openreview.net/pdf?id=ypaYtV1CoG) | CoRL 2024 | 2024-09-06 | [Project](https://vocal-sandbox.github.io/) |  |
| [**APRICOT: Active Preference Learning and Constraint-Aware Task Planning with LLMs**](https://openreview.net/pdf?id=nQslM6f7dW) | CoRL 2024 | - | [Project](https://portal-cornell.github.io/apricot/) |  |
| [**Text2Interaction: Establishing Safe and Preferable Human-Robot Interaction**](https://arxiv.org/abs/2408.06105) | CoRL 2024 | 2024-08-12 | ![Star](https://img.shields.io/github/stars/JakobThumm/text2interaction?style=social&label=Star) [Github](https://github.com/JakobThumm/text2interaction) |  |
| [**GenH2R: Learning Generalizable Human-to-Robot Handover via Scalable Simulation, Demonstration, and Imitation**](https://arxiv.org/abs/2401.00929) | CVPR 2024 | 2024-01-01  | ![Star](https://img.shields.io/github/stars/chenjy2003/genh2r?style=social&label=Star) [Github](https://github.com/chenjy2003/genh2r)  |
| [KNOWNO: **Robots That Ask For Help: Uncertainty Alignment for Large Language Model Planners**](https://arxiv.org/abs/2307.01928) | CoRL 2023 | 2023-07-04 | [Github](https://github.com/google-research/google-research/tree/master/language_model_uncertainty) | |
| [LILAC: **Yell At Your Robot: Improving On-the-Fly from Language Corrections**](https://arxiv.org/abs/2403.12910) | arXiv | 2024-03-19 | ![Star](https://img.shields.io/github/stars/yay-robot/yay_robot?style=social&label=Star) [Github](https://github.com/yay-robot/yay_robot) | |
| [YAY Robot: **"No, to the Right" -- Online Language Corrections for Robotic Manipulation via Shared Autonomy**](https://arxiv.org/abs/2301.02555) | HRI 2023 | 2023-01-06 | ![Star](https://img.shields.io/github/stars/Stanford-ILIAD/lilac?style=social&label=Star) [Github](https://github.com/Stanford-ILIAD/lilac) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>



## Safety
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**SURE: Safe Uncertainty-Aware Robot-Environment Interaction using Trajectory Optimization**](https://arxiv.org/abs/2602.06864) | arXiv | 2026-02-06 | - |  |
| [**SyncTwin: Fast Digital Twin Construction and Synchronization for Safe Robotic Grasping**](https://arxiv.org/abs/2601.09920) | arXiv | 2026-01-14 | - |  |
| [**ContactRL: Safe Reinforcement Learning based Motion Planning for Contact based Human Robot Collaboration**](https://arxiv.org/abs/2512.03707) | arXiv | 2025-12-03 | ![Star](https://img.shields.io/github/stars/SMulkana/ContactRL?style=social&label=Star) [Github](https://github.com/SMulkana/ContactRL) |  |
| [**Gated Uncertainty-Aware Runtime Dual Invariants for Neural Signal-Controlled Robotics**](https://arxiv.org/abs/2511.20570) | NeurIPS 2025 | 2025-11-25 | - |  |
| [**Safe and Stable Neural Network Dynamical Systems for Robot Motion Planning**](https://arxiv.org/abs/2511.20593) | arXiv | 2025-11-25 | - |  |
| [**SM2ITH: Safe Mobile Manipulation with Interactive Human Prediction via Task-Hierarchical Bilevel Model Predictive Control**](https://arxiv.org/abs/2511.17798) | arXiv | 2025-11-21 | - |  |
| [**Safe and Optimal Variable Impedance Control via Certified Reinforcement Learning**](https://arxiv.org/abs/2511.16330) | arXiv | 2025-11-20 | - |  |
| [**What You Don't Know Can Hurt You: How Well do Latent Safety Filters Understand Partially Observable Safety Constraints?**](https://arxiv.org/abs/2510.06492) | arXiv | 2025-10-07 | [Project](https://cmu-intentlab.github.io/multisafe/) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>
