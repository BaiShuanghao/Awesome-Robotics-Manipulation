<h2 id="table-of-contents">🏠 Table of Contents</h2>

- High-level Planner
    - [Task Planning](#task-planning)
    - [Code Generation](#code-generation)
    - [Multimodal Reasoning](#multimodal-reasoning)
    - [Motion Planning](#motion-planning)
    <!-- - [Affordance Learning](#affordance-learning)
        - [Geometric Affordance](#geometric-affordance)
        - [Visual Affordance](#visual-affordance)
        - [Semantic Affordance](#semantic-affordance)
        - [Multimodal Affordance](#multimodal-affordance) -->
    - [3D Representation as Planner](#3d-representation-as-planner)



## Task Planning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Reinforced Embodied Planning with Verifiable Reward for Real-World Robotic Manipulation**](https://arxiv.org/abs/2509.25852) | arXiv | 2025-09-30 | - |  |
| [**PhysiAgent: An Embodied Agent Framework in Physical World**](https://arxiv.org/abs/2509.24524) | arXiv | 2025-09-29 | - |  |
| [**LLM-Guided Task- and Affordance-Level Exploration in Reinforcement Learning**](https://arxiv.org/abs/2509.24524) | arXiv | 2025-09-20 | ![Star](https://img.shields.io/github/stars/llm-tale/llm_tale?style=social&label=Star) [Github](https://github.com/llm-tale/llm_tale) |  |
| [**AssemMate: Graph-Based LLM for Robotic Assembly Assistance**](https://arxiv.org/abs/2509.11617) | arXiv | 2025-09-15 | ![Star](https://img.shields.io/github/stars/cristina304/AssemMate?style=social&label=Star) [Github](https://github.com/cristina304/AssemMate) |  |
| [**ConceptBot: Enhancing Robot's Autonomy through Task Decomposition with Large Language Models and Knowledge Graph**](https://arxiv.org/abs/2509.00570) | arXiv | 2025-08-30 | [Project](https://sites.google.com/view/conceptbot) |  |
| [**Mixed-Initiative Dialog for Human-Robot Collaborative Manipulation**](https://www.arxiv.org/abs/2508.05535) | arXiv | 2025-08-12 | [Project](https://robin-lab.cs.utexas.edu/MicoBot/) |  |
| [**DEMONSTRATE: Zero-shot Language to Robotic Control via Multi-task Demonstration Learning**](https://arxiv.org/abs/2507.12855) | arXiv | 2025-07-17 | - |  |
| [**Imagine, Verify, Execute: Memory-Guided Agentic Exploration with Vision-Language Models**](https://arxiv.org/abs/2505.07815) | arXiv | 2025-05-12 | [Project](https://ive-robot.github.io/) |  |
| [**MALMM: Multi-Agent Large Language Models for Zero-Shot Robotics Manipulation**](https://arxiv.org/abs/2411.17636) | arXiv | 2024-11-26 | [Project](https://malmm1.github.io/) |  |
| [**Socratic Planner: Inquiry-Based Zero-Shot Planning for Embodied Instruction Following**](https://arxiv.org/abs/2404.15190) | arXiv | 2024-04-21 | - | |
| [**APRICOT: Active Preference Learning and Constraint-Aware Task Planning with LLMs**](https://openreview.net/forum?id=nQslM6f7dW) | CoRL 2024 | 2024-09-06 | [Project](https://portal-cornell.github.io/apricot/) |  |
| [**Text2Interaction: Establishing Safe and Preferable Human-Robot Interaction**](https://arxiv.org/abs/2408.06105) | CoRL 2024 | 2024-08-12 | ![Star](https://img.shields.io/github/stars/JakobThumm/text2interaction?style=social&label=Star) [Github](https://github.com/JakobThumm/text2interaction) |  |
| [**Polaris: Open-ended Interactive Robotic Manipulation via Syn2Real Visual Grounding and Large Language Models**](https://arxiv.org/abs/2408.07975) | IROS 2024 | 2024-08-15 | [Project](https://star-uu-wang.github.io/Polaris/) |  |
| [PG-InstructBLIP: **Physically Grounded Vision-Language Models for Robotic Manipulation**](https://arxiv.org/abs/2309.02561) | ICRA 2024 | 2023-09-05 | [Project](https://iliad.stanford.edu/pg-vlm/) |  |
| [**RoCo: Dialectic Multi-Robot Collaboration with Large Language Models**](https://arxiv.org/abs/2307.04738) | ICRA 2024 | 2023-07-10 | ![Star](https://img.shields.io/github/stars/MandiZhao/robot-collab?style=social&label=Star) [Github](https://github.com/MandiZhao/robot-collab) | |
| [KNOWNO: **Robots That Ask For Help: Uncertainty Alignment for Large Language Model Planners**](https://arxiv.org/abs/2307.01928) | CoRL 2023 | 2023-07-04 | [Github](https://github.com/google-research/google-research/tree/master/language_model_uncertainty) | |
| [**REFLECT: Summarizing Robot Experiences for Failure Explanation and Correction**](https://arxiv.org/abs/2306.15724) | CoRL 2023 | 2023-06-27 | ![Star](https://img.shields.io/github/stars/real-stanford/reflect?style=social&label=Star) [Github](https://github.com/real-stanford/reflect) | |
| [Saycan: **Do As I Can, Not As I Say: Grounding Language in Robotic Affordances**](https://arxiv.org/abs/2204.01691) | CoRL 2023 | 2022-04-04 | ![Star](https://img.shields.io/github/stars/google-research/google-research?style=social&label=Star) [Github](https://github.com/google-research/google-research/tree/master/saycan) | |
| [**LLM+P: Empowering Large Language Models with Optimal Planning Proficiency**](https://arxiv.org/abs/2304.11477) | arXiv | 2023-04-22 | ![Star](https://img.shields.io/github/stars/Cranial-XIX/llm-pddl?style=social&label=Star) [Github](https://github.com/Cranial-XIX/llm-pddl) | |
| [**Inner Monologue: Embodied Reasoning through Planning with Language Models**](https://arxiv.org/abs/2207.05608) | CoRL 2022 | 2022-07-12 | [Project](https://innermonologue.github.io/) | |
| [SHOWTELL: **Teaching Robots with Show and Tell: Using Foundation Models to Synthesize Robot Policies from Language and Visual Demonstrations**](https://openreview.net/pdf?id=G8UcwxNAoD) | CoRL 2024 | 2024-09-06 | [Project](https://robo-showtell.github.io/) |  |
| [GIRAF: **Gesture-Informed Robot Assistance via Foundation Models**](https://arxiv.org/abs/2309.02721) | CoRL 2023 | 2023-09-06 | [Project](https://sites.google.com/view/giraf23) | |
| [**LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models**](https://arxiv.org/abs/2212.04088) | ICCV 2023 | 2022-12-08 | ![Star](https://img.shields.io/github/stars/OSU-NLP-Group/LLM-Planner?style=social&label=Star) [Github](https://github.com/OSU-NLP-Group/LLM-Planner/) |  |
| [**PaLM-E: An Embodied Multimodal Language Model**](https://arxiv.org/abs/2303.03378) | ICML 2023 | 2023-03-06 | ![Star](https://img.shields.io/github/stars/kyegomez/PALM-E?style=social&label=Star) [Github](https://github.com/kyegomez/PALM-E) |  |
| [**Continuous Relaxation of Symbolic Planner for One-Shot Imitation Learning**](https://arxiv.org/abs/1908.06769) | IROS 2019 | 2019-08-16 | - | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>


## Code Generation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**RoboPilot: Generalizable Dynamic Robotic Manipulation with Dual-thinking Modes**](https://arxiv.org/abs/2510.00154) | arXiv | 2025-09-30 | - | |
| [**Growing with Your Embodied Agent: A Human-in-the-Loop Lifelong Code Generation Framework for Long-Horizon Manipulation Skills**](https://arxiv.org/abs/2509.18597) | arXiv | 2025-09-23 | - | |
| [**Agentic Scene Policies: Unifying Space, Semantics, and Affordances for Robot Action**](https://arxiv.org/abs/2509.19571) | arXiv | 2025-09-23 | [Project](https://montrealrobotics.ca/agentic-scene-policies.github.io/) | |
| [**Long-Horizon Visual Imitation Learning via Plan and Code Reflection**](https://arxiv.org/abs/2509.05368) | arXiv | 2025-09-04 | - | |
| [**HyCodePolicy: Hybrid Language Controllers for Multimodal Monitoring and Decision in Embodied Agents**](https://arxiv.org/abs/2508.02629) | ICCVW 2025 | 2025-08-04 | - | |
| [**T-Rex: Task-Adaptive Spatial Representation Extraction for Robotic Manipulation with Vision-Language Models**](https://arxiv.org/abs/2506.19498) | arXiv | 2025-06-24 | - | |
| [**Robotic Programmer: Video Instructed Policy Code Generation for Robotic Manipulation**](https://arxiv.org/abs/2501.04268) | arXiv | 2025-01-08 | [Project](https://video2code.github.io/RoboPro-website/) | |
| [**Don't Let Your Robot be Harmful: Responsible Robotic Manipulation**](https://arxiv.org/abs/2411.18289) | arXiv | 2024-11-27 | ![Star](https://img.shields.io/github/stars/kodenii/Responsible-Robotic-Manipulation?style=social&label=Star) [Github](https://github.com/kodenii/Responsible-Robotic-Manipulation) | |
| [**Vocal Sandbox: Continual Learning and Adaptation for Situated Human-Robot Collaboration**](https://openreview.net/forum?id=ypaYtV1CoG) | CoRL 2024 | 2024-09-06 | [Project](https://vocal-sandbox.github.io/) |  |
| [**Demo2Code: From Summarizing Demonstrations to Synthesizing Code via Extended Chain-of-Thought**](https://arxiv.org/abs/2305.16744) | NeurIPS 2023 | 2023-05-26 | [Project](https://portal-cornell.github.io/demo2code/) | |
| [**Instruct2Act: Mapping Multi-modality Instructions to Robotic Actions with Large Language Model**](https://arxiv.org/abs/2305.11176) | arXiv | 2023-05-18 | ![Star](https://img.shields.io/github/stars/OpenGVLab/Instruct2Act?style=social&label=Star) [Github](https://github.com/OpenGVLab/Instruct2Act) | LLMs, VLMs, Code Generation |
| [**RobotGPT: Robot Manipulation Learning from ChatGPT**](https://arxiv.org/abs/2312.01421) | RA-L 2024 | 2023-12-03 | - |  |
| [**ChatGPT Empowered Long-Step Robot Control in Various Environments: A Case Application**](https://arxiv.org/abs/2304.03893) | IEEE Acess 2023 | 2023-04-08 | ![Star](https://img.shields.io/github/stars/microsoft/ChatGPT-Robot-Manipulation-Prompts?style=social&label=Star) [Github](https://github.com/microsoft/ChatGPT-Robot-Manipulation-Prompts) | |
| [**ChatGPT for Robotics: Design Principles and Model Abilities**](https://arxiv.org/abs/2306.17582) | IEEE Access 2023 | 2023-02-20 | ![Star](https://img.shields.io/github/stars/microsoft/PromptCraft-Robotics?style=social&label=Star) [Github](https://github.com/microsoft/PromptCraft-Robotics) | LLMs, Code Generation |
| [**ProgPrompt: Generating Situated Robot Task Plans using Large Language Models**](https://arxiv.org/abs/2209.11302) | ICRA 2023 | 2022-09-22 | ![Star](https://img.shields.io/github/stars/NVlabs/progprompt-vh?style=social&label=Star) [Github](https://github.com/NVlabs/progprompt-vh) | LLMs, Code Generation |
| [**Code as Policies: Language Model Programs for Embodied Control**](https://arxiv.org/abs/2209.07753) | ICRA 2023 | 2022-09-16 | ![Star](https://img.shields.io/github/stars/google-research/google-research?style=social&label=Star) [Github](https://github.com/google-research/google-research/tree/master/code_as_policies) | LLMs, Code Generation |
| [**Statler: State-Maintaining Language Models for Embodied Reasoning**](https://arxiv.org/abs/2306.17840) | ICRA 2024 | 2023-06-30 | ![Star](https://img.shields.io/github/stars/ripl/statler?style=social&label=Star) [Github](https://github.com/ripl/statler) | LLMs, Code Generation |
| [**InterPreT: Interactive Predicate Learning from Language Feedback for Generalizable Task Planning**](https://arxiv.org/abs/2405.19758) | RSS 2024 | 2023-05-30 | ![Star](https://img.shields.io/github/stars/hmz-15/interactive-predicate-learning?style=social&label=Star) [Github](https://github.com/hmz-15/interactive-predicate-learning) | Code Generation, Task Planning, PDDL |
| [**Text2Motion: From Natural Language Instructions to Feasible Plans**](https://arxiv.org/abs/2303.12153) | Autonomous Robots 2023 | 2023-03-21 | [Project](https://sites.google.com/stanford.edu/text2motion) |  |
| [**Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language**](https://arxiv.org/abs/2204.00598) | ICLR 2023 | 2022-04-01 | [Project](https://github.com/google-research/google-research/tree/master/socraticmodels) |  |
| [**Translating Natural Language Instructions to Computer Programs for Robot Manipulation**](https://arxiv.org/abs/2012.13695) | IROS 2021 | 2020-12-26 | [Project](https://sites.google.com/stanford.edu/text2motion) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>



## Multimodal Reasoning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| _Common Reasoning_ |
| [**From Grounding to Manipulation: Case Studies of Foundation Model Integration in Embodied Robotic Systems**](https://arxiv.org/abs/2505.15685) | arXiv | 2025-05-21 | - | |
| [**From Foresight to Forethought: VLM-In-the-Loop Policy Steering via Latent Alignment**](https://arxiv.org/abs/2502.01828) | arXiv | 2025-02-03 | - |  |
| [Matcha: **Chat with the Environment: Interactive Multimodal Perception Using Large Language Models**](https://arxiv.org/abs/2303.08268) | IROS 2023 | 2023-03-14 | ![Star](https://img.shields.io/github/stars/xf-zhao/Matcha-agent?style=social&label=Star) [Github](https://github.com/xf-zhao/Matcha-agent) |  |
| _Unified Reasoning_ |
| [**RynnEC: Bringing MLLMs into Embodied World**](https://arxiv.org/abs/2508.14160) | arXiv | 2025-08-23 | ![Star](https://img.shields.io/github/stars/alibaba-damo-academy/RynnEC?style=social&label=Star) [Github](https://github.com/alibaba-damo-academy/RynnEC) |  |
| [**Embodied-R1: Reinforced Embodied Reasoning for General Robotic Manipulation**](https://arxiv.org/abs/2508.13998) | arXiv | 2025-08-19 | ![Star](https://img.shields.io/github/stars/pickxiguapi/Embodied-R1?style=social&label=Star) [Github](https://github.com/pickxiguapi/Embodied-R1) |  |
| [**ThinkAct: Vision-Language-Action Reasoning via Reinforced Visual Latent Planning**](https://arxiv.org/abs/2507.16815) | NeurIPS 2025 | 2025-07-22 | [Project](https://jasper0314-huang.github.io/thinkact-vla/) |  |
| [**RoboBrain 2.0 Technical Report**](https://arxiv.org/abs/2507.02029) | arXiv | 2025-07-02 | ![Star](https://img.shields.io/github/stars/FlagOpen/RoboBrain2.0?style=social&label=Star) [Github](https://github.com/FlagOpen/RoboBrain2.0) |  |
| [FSD: **From Seeing to Doing: Bridging Reasoning and Decision for Robotic Manipulation**](https://arxiv.org/abs/2505.08548) | arXiv | 2025-05-13 | [Project](https://embodied-fsd.github.io/) | |
| [**RoboBrain: A Unified Brain Model for Robotic Manipulation from Abstract to Concrete**](https://arxiv.org/abs/2502.21257) | CVPR 2025 | 2025-02-28 | [Project](https://superrobobrain.github.io/) |  |
| _Spatial Reasoning_ |
| [**EmbodiedVSR: Dynamic Scene Graph-Guided Chain-of-Thought Reasoning for Visual Spatial Tasks**](https://arxiv.org/abs/2503.11089) | arXiv | 2025-03-14 | - |  |
| [**SoFar: Language-Grounded Orientation Bridges Spatial Reasoning and Object Manipulation**](https://arxiv.org/abs/2502.13143) | arXiv | 2025-02-18 | ![Star](https://img.shields.io/github/stars/qizekun/SoFar?style=social&label=Star) [Github](https://github.com/qizekun/SoFar) |  |
| [**RoboRefer: Towards Spatial Referring with Reasoning in Vision-Language Models for Robotics**](https://arxiv.org/abs/2506.04308) | NeurIPS 2025 | 2025-06-28 | ![Star](https://img.shields.io/github/stars/Zhoues/RoboRefer?style=social&label=Star) [Github](https://github.com/Zhoues/RoboRefer) |  |
| [**RoboSpatial: Teaching Spatial Understanding to 2D and 3D Vision-Language Models for Robotics**](https://arxiv.org/abs/2411.16537) | CVPR 2025 | 2024-11-25 | ![Star](https://img.shields.io/github/stars/NVlabs/RoboSpatial?style=social&label=Star) [Github](https://github.com/NVlabs/RoboSpatial) |  |
| [**SpatialBot: Precise Spatial Understanding with Vision Language Models**](https://arxiv.org/abs/2406.13642) | ICRA 2025 | 2024-06-19 | ![Star](https://img.shields.io/github/stars/BAAI-DCAI/SpatialBot?style=social&label=Star)  [Github](https://github.com/BAAI-DCAI/SpatialBot) |  |
| [**SpatialVLM: Endowing Vision-Language Models with Spatial Reasoning Capabilities**](https://arxiv.org/abs/2401.12168) | CVPR 2024 | 2024-01-22 | ![Star](https://img.shields.io/github/stars/remyxai/VQASynth?style=social&label=Star) [Github](https://github.com/remyxai/VQASynth) |  |
| _Affordance Reasoning_ |
| [**ManipGPT: Is Affordance Segmentation by Large Vision Models Enough for Articulated Object Manipulation?**](https://arxiv.org/abs/2412.10050) | arXiv | 2024-12-13 | - | Part-based |
| [**UniAff: A Unified Representation of Affordances for Tool Usage and Articulation with Vision-Language Models**](https://arxiv.org/abs/2409.20551) | ICRA 2025 | 2024-09-16 | [Project](https://sites.google.com/view/uni-aff/home) | Part-based & Object-level |
| [**FMimic: Foundation Models are Fine-grained Action Learners from Human Videos**](https://arxiv.org/abs/2507.20622) | IJRR 2025 | 2025-07-28 | [Project](https://fmimic-page.github.io/) | |
| [**VLMimic: Vision Language Models are Visual Imitation Learner for Fine-grained Actions**](https://arxiv.org/abs/2410.20927) | NeurIPS 2024 | 2024-10-28 | [Project](https://vlmimic.github.io/) |  |
| [**AIC MLLM: Autonomous Interactive Correction MLLM for Robust Robotic Manipulation**](https://arxiv.org/abs/2406.11548) | CoRL 2024 | 2024-06-17 | [Project](https://sites.google.com/view/aic-mllm) |  |
| [**RoboPoint: A Vision-Language Model for Spatial Affordance Prediction for Robotics**](https://arxiv.org/abs/2406.10721) | CoRL 2024 | 2024-06-15 | ![Star](https://img.shields.io/github/stars/wentaoyuan/RoboPoint?style=social&label=Star) [Github](https://github.com/wentaoyuan/RoboPoint) | Keypoint  |
| [**A3VLM: Actionable Articulation-Aware Vision Language Model**](https://arxiv.org/abs/2406.07549) | CoRL 2024 | 2024-06-14 | ![Star](https://img.shields.io/github/stars/changhaonan/A3VLM?style=social&label=Star) [Github](https://github.com/changhaonan/A3VLM) | BBox |
| [**MOKA: Open-World Robotic Manipulation through Mark-Based Visual Prompting**](https://arxiv.org/abs/2403.03174) | RSS 2024 | 2024-03-05 | ![Star](https://img.shields.io/github/stars/moka-manipulation/moka?style=social&label=Star) [Github](https://github.com/moka-manipulation/moka) | affordance |
| [**SAGE: Bridging Semantic and Actionable Parts for Generalizable Manipulation of Articulated Objects**](https://arxiv.org/abs/2312.01307) | RSS 2024 | 2023-12-03 | ![Star](https://img.shields.io/github/stars/geng-haoran/SAGE?style=social&label=Star) [Github](https://github.com/geng-haoran/SAGE) | Keypoint |
| [**ManipLLM: Embodied Multimodal Large Language Model for Object-Centric Robotic Manipulation**](https://arxiv.org/abs/2312.16217) | CVPR 2024 | 2023-12-24 | ![Star](https://img.shields.io/github/stars/clorislili/ManipLLM?style=social&label=Star) [Github](https://github.com/clorislili/ManipLLM) |  |
| [**Kinematic-aware Prompting for Generalizable Articulated Object Manipulation with LLMs**](https://arxiv.org/abs/2311.02847) | ICRA 2024 | 2023-11-06 | ![Star](https://img.shields.io/github/stars/GeWu-Lab/LLM_articulated_object_manipulation?style=social&label=Star) [Github](https://github.com/GeWu-Lab/LLM_articulated_object_manipulation) | Part-based |
| _Video Prediction_ |
| [**SAMPO:Scale-wise Autoregression with Motion PrOmpt for Generative World Models**](https://arxiv.org/abs/2509.15536) | arXiv | 2025-09-19 | - |  |
| _Failure Reasoning_ |
| [**I-FailSense: Towards General Robotic Failure Detection with Vision-Language Models**](https://arxiv.org/abs/2509.16072) | arXiv | 2025-09-19 | ![Star](https://img.shields.io/github/stars/clemgris/I-FailSense?style=social&label=Star) [Github](https://github.com/clemgris/I-FailSense) |  |
| [**Can We Detect Failures Without Failure Data? Uncertainty-Aware Runtime Failure Detection for Imitation Learning Policies**](https://arxiv.org/abs/2503.08558) | arXiv | 2025-03-11 | [Project](https://cxu-tri.github.io/FAIL-Detect-Website/) |  |
| [**Code-as-Monitor: Constraint-aware Visual Programming for Reactive and Proactive Robotic Failure Detection**](https://arxiv.org/abs/2412.04455) | CVPR 2025 | 2024-12-05 | [Project](https://zhoues.github.io/Code-as-Monitor/) | Failure Detection |
| [**AHA: A Vision-Language-Model for Detecting and Reasoning Over Failures in Robotic Manipulation**](https://arxiv.org/abs/2410.00371) | ICLR 2025 | 2024-10-01 | [Project](https://aha-vlm.github.io/) | Failure Detection |
| [**Learning Manipulation Skills through Robot Chain-of-Thought with Sparse Failure Guidance**](https://arxiv.org/abs/2405.13573) | IROS 2025 | 2024-05-22 | [Project](https://aha-vlm.github.io/) | Failure Detection |
| _Success Reasoning_ |
| [λ-Repformer: **Task Success Prediction for Open-Vocabulary Manipulation Based on Multi-Level Aligned Representations**](https://arxiv.org/abs/2410.00436) | CoRL 2024 | 2024-10-01 | [Project](https://lambda-repformer-project-pa-eziy1.kinsta.page/) | Success Prediction |
| _Adversarial_ |
| [**TrojanRobot: Backdoor Attacks Against LLM-based Embodied Robots in the Physical World**](https://arxiv.org/abs/2411.11683) | arXiv | 2024-11-18 | [Project](https://trojanrobot.github.io/) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>



## Motion Planning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| _Grasp Planning_ |
| [**CoPa: General Robotic Manipulation through Spatial Constraints of Parts with Foundation Models**](https://arxiv.org/abs/2403.08248) | IROS 2024 | 2024-03-13 | ![Star](https://img.shields.io/github/stars/HaoxuHuang/copa?style=social&label=Star) [Github](https://github.com/HaoxuHuang/copa) | Motion Planning |
| _Path Planning_|
| [LACO: **Language-Conditioned Path Planning**](https://arxiv.org/abs/2308.16893) | CoRL 2023 | 2024-08-31 | ![Star](https://img.shields.io/github/stars/amberxie88/lapp?style=social&label=Star) [Github](https://github.com/amberxie88/lapp) |  |
| _Motion Planning_|
| [**In-Context Iterative Policy Improvement for Dynamic Manipulation**](https://arxiv.org/abs/2508.15021) | CoRL 2025 | 2025-08-20 | - | LLM Learn parameters |
| [**Prompting with the Future: Open-World Model Predictive Control with Interactive Digital Twins**](https://arxiv.org/abs/2506.13761) | RSS 2025 | 2025-06-16 | ![Star](https://img.shields.io/github/stars/TritiumR/Prompting-with-the-Future?style=social&label=Star) [Github](https://github.com/TritiumR/Prompting-with-the-Future) |  |
| [**GeoManip: Geometric Constraints as General Interfaces for Robot Manipulation**](https://arxiv.org/abs/2501.09783) | arXiv | 2025-01-16 | ![Star](https://img.shields.io/github/stars/CUHKWilliam/GeoManip-release?style=social&label=Star)  [Github](https://github.com/CUHKWilliam/GeoManip-release) | TAMP |
| [**A Real-to-Sim-to-Real Approach to Robotic Manipulation with VLM-Generated Iterative Keypoint Rewards**](https://arxiv.org/abs/2502.08643) | ICRA 2025 | 2025-02-12 | ![Star](https://img.shields.io/github/stars/shivanshpatel35/IKER?style=social&label=Star) [Github](https://github.com/shivanshpatel35/IKER) | Motion Planning |
| [**DiffusionSeeder: Seeding Motion Optimization with Diffusion for Rapid Motion Planning**](https://arxiv.org/abs/2410.16727) | CoRL 2024 | 2024-10-22 | [Project](https://diffusion-seeder.github.io/) | Motion Planning  |
| [**ReKep: Spatio-Temporal Reasoning of Relational Keypoint Constraints for Robotic Manipulation**](https://arxiv.org/abs/2409.01652) | CoRL 2024 | 2024-09-03 | ![Star](https://img.shields.io/github/stars/huangwl18/ReKep?style=social&label=Star) [Github](https://github.com/huangwl18/ReKep) | Motion Planning |
| [Elastic-DS: **Task Generalization with Stability Guarantees via Elastic Dynamical System Motion Policies**](https://arxiv.org/abs/2309.01884) | CoRL 2023 | 2023-09-05 | ![Star](https://img.shields.io/github/stars/tonylitianyu/Elastic-DS?style=social&label=Star) [Github](https://github.com/tonylitianyu/Elastic-DS) | IL, LfD, Motion |
| _Trajectory Optimization_|
| [**Geometry-aware 4D Video Generation for Robot Manipulation**](https://arxiv.org/abs/2507.01099) | arXiv | 2025-07-01 | ![Star](https://img.shields.io/github/stars/lzylucy/4dgen?style=social&label=Star) [Github](https://github.com/lzylucy/4dgen) |  |
| [**Robotic Manipulation by Imitating Generated Videos Without Physical Demonstrations**](https://arxiv.org/abs/2507.00990) | arXiv | 2025-07-01 | ![Star](https://img.shields.io/github/stars/shivanshpatel35/rigvid?style=social&label=Star) [Github](https://github.com/shivanshpatel35/rigvid) |  |
| [**ORION: Vision-based Manipulation from Single Human Video with Open-World Object Graphs**](https://arxiv.org/abs/2405.20321) | arXiv | 2024-05-30 | [Project](https://ut-austin-rpl.github.io/ORION-release/) |  |
| [**RoboTAP: Tracking Arbitrary Points for Few-Shot Visual Imitation**](https://arxiv.org/abs/2308.15975) | ICRA 2024 | 2023-08-30 | ![Star](https://img.shields.io/github/stars/google-deepmind/tapnet?style=social&label=Star) [Github](https://github.com/google-deepmind/tapnet/blob/main/colabs/tapir_clustering.ipynb) |  |
| [**VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models**](https://arxiv.org/abs/2307.05973) | CoRL 2023 | 2023-07-12 | ![Star](https://img.shields.io/github/stars/huangwl18/VoxPoser?style=social&label=Star)  [Github](https://github.com/huangwl18/VoxPoser) |  |
| [**LATTE: LAnguage Trajectory TransformEr**](https://arxiv.org/abs/2208.02918) | ICRA 2023 | 2022-08-04 | ![Star](https://img.shields.io/github/stars/arthurfenderbucker/LaTTe-Language-Trajectory-TransformEr?style=social&label=Star) [Github](https://github.com/arthurfenderbucker/LaTTe-Language-Trajectory-TransformEr) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>



## 3D Representation as Planner
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Point Cloud_ |
| [**O<sup>3</sup>Afford: One-Shot 3D Object-to-Object Affordance Grounding for Generalizable Robotic Manipulation**](https://arxiv.org/abs/2509.06233) | CoRL 2025 | 2025-09-07 | ![Star](https://img.shields.io/github/stars/Tongxuan259/O3Afford?style=social&label=Star)  [Github](https://github.com/Tongxuan259/O3Afford) |  |
| [**Planning from Point Clouds over Continuous Actions for Multi-object Rearrangement**](https://arxiv.org/abs/2509.04645) | CoRL 2025 | 2025-09-04 | ![Star](https://img.shields.io/github/stars/kallol-saha/SPOT?style=social&label=Star)  [Github](https://github.com/kallol-saha/SPOT) |  |
| [**PartInstruct: Part-level Instruction Following for Fine-grained Robot Manipulation**](https://arxiv.org/abs/2505.21652) | RSS 2025 | 2025-05-27 | ![Star](https://img.shields.io/github/stars/SCAI-JHU/PartInstruct?style=social&label=Star)  [Github](https://github.com/SCAI-JHU/PartInstruct) | Part-based |
| [**IMAGINATION POLICY: Using Generative Point Cloud Models for Learning Manipulation Policies**](https://arxiv.org/abs/2406.11740) | CoRL 2024 | 2024-06-17 | [Project](https://haojhuang.github.io/imagine_page/) |  |
| [**RoboEXP: Action-Conditioned Scene Graph via Interactive Exploration for Robotic Manipulation**](https://arxiv.org/abs/2402.15487) | CoRL 2024 | 2024-02-23 | ![Star](https://img.shields.io/github/stars/Jianghanxiao/RoboEXP?style=social&label=Star) [Github](https://github.com/Jianghanxiao/RoboEXP) | 3D scene graph |
| [**PartManip: Learning Cross-Category Generalizable Part Manipulation Policy from Point Cloud Observations**](https://arxiv.org/abs/2303.16958) | CVPR 2023 | 2023-03-29 | ![Star](https://img.shields.io/github/stars/PKU-EPIC/PartManip?style=social&label=Star)  [Github](https://github.com/PKU-EPIC/PartManip) | Part-based |
| [**GAPartNet: Cross-Category Domain-Generalizable Object Perception and Manipulation via Generalizable and Actionable Parts**](https://arxiv.org/abs/2211.05272) | CVPR 2023 | 2022-11-10 | ![Star](https://img.shields.io/github/stars/PKU-EPIC/GAPartNet?style=social&label=Star) [Github](https://github.com/PKU-EPIC/GAPartNet) | Part-based |
| _Field_ |
| [**D<sup>3</sup>Fields: Dynamic 3D Descriptor Fields for Zero-Shot Generalizable Rearrangement**](https://arxiv.org/abs/2309.16118) | CoRL 2024 | 2023-09-28 | ![Star](https://img.shields.io/github/stars/WangYixuan12/d3fields?style=social&label=Star) [Github](https://github.com/WangYixuan12/d3fields) |  
| [F3RM: **Distilled Feature Fields Enable Few-Shot Language-Guided Manipulation**](https://arxiv.org/abs/2308.07931) | CoRL 2023 | 2023-07-27 | ![Star](https://img.shields.io/github/stars/f3rm/f3rm?style=social&label=Star) [Github](https://github.com/f3rm/f3rm) | NeRF |
| [R-NDF: **SE(3)-Equivariant Relational Rearrangement with Neural Descriptor Fields**](https://arxiv.org/abs/2211.09786) | CORL 2022 | 2022-11-17 | ![Star](https://img.shields.io/github/stars/anthonysimeonov/relational_ndf?style=social&label=Star)  [Github](https://github.com/anthonysimeonov/relational_ndf) |  |
| [**Ditto: Building Digital Twins of Articulated Objects from Interaction**](https://arxiv.org/abs/2202.08227) | CVPR 2022 | 2022-08-16 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/Ditto?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/Ditto) | Part-based |
| [NDF: **Neural Descriptor Fields: SE(3)-Equivariant Object Representations for Manipulation**](https://arxiv.org/abs/2112.05124) | ICRA 2022 | 2021-12-09 | ![Star](https://img.shields.io/github/stars/anthonysimeonov/ndf_robot?style=social&label=Star) [Github](https://github.com/anthonysimeonov/ndf_robot) |  |
| _3DGS_ |
| [**ScrewSplat: An End-to-End Method for Articulated Object Recognition**](https://www.arxiv.org/abs/2508.02146) | CoRL 2025 | 2025-08-04 | - | |
| [RoboSplat: **Novel Demonstration Generation with Gaussian Splatting Enables Robust One-Shot Manipulation**](https://arxiv.org/abs/2504.13175) | RSS 2025 | 2025-04-17 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/robosplat?style=social&label=Star) [Github](https://github.com/OpenRobotLab/robosplat) | |
| [**MSGField: A Unified Scene Representation Integrating Motion, Semantics, and Geometry for Robotic Manipulation**](https://arxiv.org/abs/2410.15730) | arXiv | 2024-10-21 | ![Star](https://img.shields.io/github/stars/ShengYu724/MSGField?style=social&label=Star) [Github](https://github.com/ShengYu724/MSGField) | 2DGS |
| [**Splat-MOVER: Multi-Stage, Open-Vocabulary Robotic Manipulation via Editable Gaussian Splatting**](https://arxiv.org/abs/2405.04378) | CoRL 2024 | 2024-05-07 | ![Star](https://img.shields.io/github/stars/StanfordMSL/Splat-MOVER?style=social&label=Star) [Github](https://github.com/StanfordMSL/Splat-MOVER) | 3DGS |
| [**Physically Embodied Gaussian Splatting: A Realtime Correctable World Model for Robotics**](https://arxiv.org/abs/2406.10788) | CoRL 2024 | 2024-06-16 | [Project](https://embodied-gaussians.github.io/) | 3DGS |
| [**Object-Aware Gaussian Splatting for Robotic Manipulation**](https://openreview.net/pdf?id=gdRI43hDgo) | ICRAW 2024 | 2024-04-24 | [Project](https://object-aware-gaussian.github.io/) | 3DGS |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>
