awesome-on-policy-distillation
==============================

> A curated list of papers and resources on **on-policy distillation (OPD)**.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

On-policy distillation broadly refers to distilling a student policy **using trajectories sampled from the student itself**, while using a teacher as supervision (e.g., token-level KL, cross-entropy, or more general KL-constrained RL objectives). This list focuses on methods where the *student’s own rollouts* are central to the training signal.

**Disclaimer:** This is a curated but **not exhaustive** list. Please open issues or PRs to add missing work (see Contributing).

---

## Contents

- [Contributing](#contributing)
- [Papers](#papers)
- [Survey](#survey)
- [Blog Posts and Tutorials](#blog-posts-and-tutorials)

---

## Contributing

Contributions to this repository are very welcome! If you have come across relevant resources, feel free to open an [Issue](https://github.com/Jianglin954/awesome-on-policy-distillation/issues) or submit a [Pull Request](https://github.com/Jianglin954/awesome-on-policy-distillation/pulls).

**Suggested format for new entries:**

```
- [*Conference/Journal Year*] **paper_name** [[PDF](link)][[Code](link)]
```

---


## Papers

> Grouped by the **year in each line’s tag** (arXiv announcement date as `YYYY/MM/DD`, or the venue year for conference entries). Within each group, newer dates appear first.

### 2026
- [*arXiv 2026/04/09*] **On-Policy Distillation of Language Models for Autonomous Vehicle Motion Planning** [[PDF](https://arxiv.org/pdf/2604.07944)]
- [*arXiv 2026/04/09*] **PACED: Distillation and On-Policy Self-Distillation at the Frontier of Student Competence** [[PDF](https://arxiv.org/pdf/2603.11178)]
- [*arXiv 2026/04/06*] **DP-OPD: Differentially Private On-Policy Distillation for Language Models** [[PDF](https://arxiv.org/pdf/2604.04461)]
- [*arXiv 2026/04/04*] **SODA: Semi On-Policy Black-Box Distillation for Large Language Models** [[PDF](https://arxiv.org/pdf/2604.03873)]
- [*arXiv 2026/04/02*] **Unifying Group-Relative and Self-Distillation Policy Optimization via Sample Routing** [[PDF](https://arxiv.org/pdf/2604.02288)]
- [*arXiv 2026/04/02*] **CRISP: Compressed Reasoning via Iterative Self-Policy Distillation** [[PDF](https://arxiv.org/pdf/2603.05433)]
- [*arXiv 2026/03/30*] **X-OPD: Cross-Modal On-Policy Distillation for Capability Alignment in Speech LLMs** [[PDF](https://arxiv.org/pdf/2603.24596)]
- [*arXiv 2026/03/27*] **VLA-OPD: Bridging Offline SFT and Online RL for Vision-Language-Action Models via On-Policy Distillation** [[PDF](https://arxiv.org/pdf/2603.26666)]
- [*arXiv 2026/03/26*] **Revisiting On-Policy Distillation: Empirical Failure Modes and Simple Fixes** [[PDF](https://arxiv.org/pdf/2603.25562)]
- [*arXiv 2026/03/24*] **HDPO: Hybrid Distillation Policy Optimization via Privileged Self-Distillation** [[PDF](https://arxiv.org/pdf/2603.23871)]
- [*arXiv 2026/03/23*] **On-Policy Context Distillation for Language Models** [[PDF](https://arxiv.org/pdf/2602.12275)]
- [*arXiv 2026/03/21*] **Enhancing Vision-Based Policies with Omni-View and Cross-Modality Knowledge Distillation for Mobile Robots** [[PDF](https://arxiv.org/pdf/2603.20679)]
- [*arXiv 2026/03/21*] **Nemotron-Cascade 2: Post-Training LLMs with Cascade RL and Multi-Domain On-Policy Distillation** [[PDF](https://arxiv.org/pdf/2603.19220)]
- [*arXiv 2026/03/20*] **Self-Distilled Reasoner: On-Policy Self-Distillation for Large Language Models** [[PDF](https://arxiv.org/pdf/2601.18734)]
- [*arXiv 2026/03/17*] **WPT: World-to-Policy Transfer via Online World Model Distillation** [[PDF](https://arxiv.org/pdf/2511.20095)]
- [*arXiv 2026/03/15*] **GoldenStart: Q-Guided Priors and Entropy Control for Distilling Flow Policies** [[PDF](https://arxiv.org/pdf/2603.14245)]
- [*arXiv 2026/03/12*] **One-Step Flow Policy: Self-Distillation for Fast Visuomotor Policies** [[PDF](https://arxiv.org/pdf/2603.12480)]
- [*arXiv 2026/03/12*] **GUIDES: Guidance Using Instructor-Distilled Embeddings for Pre-trained Robot Policy Enhancement** [[PDF](https://arxiv.org/pdf/2511.03400)]
- [*arXiv 2026/03/11*] **Scaling Reasoning Efficiently via Relaxed On-Policy Distillation** [[PDF](https://arxiv.org/pdf/2603.11137)]
- [*arXiv 2026/03/10*] **From Flow to One Step: Real-Time Multi-Modal Trajectory Policies via Implicit Maximum Likelihood Estimation-based Distribution Distillation** [[PDF](https://arxiv.org/pdf/2603.09415)]
- [*arXiv 2026/03/07*] **Entropy-Aware On-Policy Distillation of Language Models** [[PDF](https://arxiv.org/pdf/2603.07079)]
- [*arXiv 2026/03/04*] **IPD: Boosting Sequential Policy with Imaginary Planning Distillation in Offline Reinforcement Learning** [[PDF](https://arxiv.org/pdf/2603.04289)]
- [*arXiv 2026/03/04*] **X-Loco: Towards Generalist Humanoid Locomotion Control via Synergetic Policy Distillation** [[PDF](https://arxiv.org/pdf/2603.03733)]
- [*arXiv 2026/02/26*] **Learning beyond Teacher: Generalized On-Policy Distillation with Reward Extrapolation** [[PDF](https://arxiv.org/pdf/2602.12125)][[Code](https://github.com/RUCBM/G-OPD)]![GitHub Repo stars](https://img.shields.io/github/stars/RUCBM/G-OPD?style=social)
- [*arXiv 2026/02/19*] **pi-Flow: Policy-Based Few-Step Generation via Imitation Distillation** [[PDF](https://arxiv.org/pdf/2510.14974)]
- [*arXiv 2026/02/16*] **Fast and Effective On-policy Distillation from Reasoning Prefixes** [[PDF](https://arxiv.org/pdf/2602.15260)]
- [*arXiv 2026/02/05*] **Multi-Token Prediction via Self-Distillation** [[PDF](https://arxiv.org/pdf/2602.06019)]
- [*arXiv 2026/02/04*] **Privileged Information Distillation for Language Models** [[PDF](https://arxiv.org/pdf/2602.04942)]
- [*arXiv 2026/02/04*] **Reinforced Attention Learning** [[PDF](https://arxiv.org/pdf/2602.04884)]
- [*arXiv 2026/02/02*] **Video-OPD: Efficient Post-Training of Multimodal Large Language Models for Temporal Video Grounding via On-Policy Distillation** [[PDF](https://arxiv.org/pdf/2602.02994)]
- [*arXiv 2026/02/02*] **Expanding the Capabilities of Reinforcement Learning via Text Feedback** [[PDF](https://arxiv.org/pdf/2602.02482)][[Code](https://github.com/lili-chen/rltf)][[Website](https://rl-textfeedback.github.io/)]![GitHub Repo stars](https://img.shields.io/github/stars/lili-chen/rltf?style=social)
- [*arXiv 2026/01/30*] **Traversal-as-Policy: Log-Distilled Gated Behavior Trees as Externalized, Verifiable Policies for Safe, Robust, and Efficient Agents** [[PDF](https://arxiv.org/pdf/2603.05517)]
- [*arXiv 2026/01/29*] **Continual Policy Distillation from Distributed Reinforcement Learning Teachers** [[PDF](https://arxiv.org/pdf/2601.22475)]
- [*arXiv 2026/01/29*] **OVD: On-policy Verbal Distillation** [[PDF](https://arxiv.org/pdf/2601.21968)][[Code](https://ovd.github.io/)]
- [*arXiv 2026/01/28*] **Reinforcement Learning via Self-Distillation** [[PDF](https://arxiv.org/pdf/2601.20802)][[Code](https://github.com/lasgroup/SDPO)][[Website](https://self-distillation.github.io/SDPO)]![GitHub Repo stars](https://img.shields.io/github/stars/lasgroup/SDPO?style=social)
- [*arXiv 2026/01/28*] **Progressive-Resolution Policy Distillation: Leveraging Coarse-Resolution Simulations for Time-Efficient Fine-Resolution Policy Learning** [[PDF](https://arxiv.org/pdf/2412.07477)]
- [*arXiv 2026/01/27*] **Self-Distillation Enables Continual Learning** [[PDF](https://arxiv.org/pdf/2601.19897)][[Code](https://github.com/idanshen/Self-Distillation)]![GitHub Repo stars](https://img.shields.io/github/stars/idanshen/Self-Distillation?style=social)
- [*arXiv 2026/01/27*] **Practical Policy Distillation for Reinforcement Learning in Radio Access Networks** [[PDF](https://arxiv.org/pdf/2511.06563)]
- [*arXiv 2026/01/23*] **CORD: Bridging the Audio-Text Reasoning Gap via Weighted On-policy Cross-modal Distillation** [[PDF](https://arxiv.org/pdf/2601.16547)]
- [*arXiv 2026/01/11*] **Stable On-Policy Distillation through Adaptive Target Reformulation** [[PDF](https://arxiv.org/pdf/2601.07155)]
- [*arXiv 2026/01/08*] **Black-Box On-Policy Distillation of Large Language Models** [[PDF](https://arxiv.org/pdf/2511.10643)][[Code](https://github.com/microsoft/LMOps/tree/main/gad)]

### 2025
- [*arXiv 2025/12/29*] **LiveTalk: Real-Time Multimodal Interactive Video Diffusion via Improved On-Policy Distillation** [[PDF](https://arxiv.org/pdf/2512.23576)]
- [*arXiv 2025/12/27*] **Driving Beyond Privilege: Distilling Dense-Reward Knowledge into Sparse-Reward Policies** [[PDF](https://arxiv.org/pdf/2512.04279)]
- [*arXiv 2025/12/24*] **Thinking-Free Policy Initialization Makes Distilled Reasoning Models More Effective and Efficient Reasoners** [[PDF](https://arxiv.org/pdf/2509.26226)]
- [*arXiv 2025/11/17*] **Explainable RL Policies by Distilling to Locally-Specialized Linear Policies with Voronoi State Partitioning** [[PDF](https://arxiv.org/pdf/2511.13322)]
- [*arXiv 2025/10/28*] **VOLD: Reasoning Transfer from LLMs to Vision-Language Models via On-Policy Distillation** [[PDF](https://arxiv.org/pdf/2510.23497)][[Code](https://walidbousselham.com/VOLD/)]
- [*arXiv 2025/10/23*] **How Ensembles of Distilled Policies Improve Generalisation in Reinforcement Learning** [[PDF](https://arxiv.org/pdf/2505.16581)]
- [*arXiv 2025/10/11*] **Can Compact Language Models Search Like Agents? Distillation-Guided Policy Optimization for Preserving Agentic RAG Capabilities** [[PDF](https://arxiv.org/pdf/2508.20324)]
- [*arXiv 2025/10/08*] **Advantages of Global Entanglement-Distillation Policies in Quantum Repeater Chains** [[PDF](https://arxiv.org/pdf/2510.06737)]
- [*arXiv 2025/09/29*] **ORPO-Distill: Mixed-Policy Preference Optimization for Cross-Architecture LLM Distillation** [[PDF](https://arxiv.org/pdf/2509.25100)]
- [*arXiv 2025/09/24*] **Parse-Augment-Distill: Learning Generalizable Bimanual Visuomotor Policies from Single Human Video** [[PDF](https://arxiv.org/pdf/2509.20286)]
- [*arXiv 2025/08/08*] **Language-Driven Policy Distillation for Cooperative Driving in Multi-Agent Reinforcement Learning** [[PDF](https://arxiv.org/pdf/2410.24152)]
- [*arXiv 2025/08/04*] **Refined Policy Distillation: From VLA Generalists to RL Experts** [[PDF](https://arxiv.org/pdf/2503.05833)]
- [*arXiv 2025/07/30*] **UniLegs: Universal Multi-Legged Robot Control through Morphology-Agnostic Policy Distillation** [[PDF](https://arxiv.org/pdf/2507.22653)]
- [*arXiv 2025/07/29*] **"So, Tell Me About Your Policy...": Distillation of interpretable policies from Deep Reinforcement Learning agents** [[PDF](https://arxiv.org/pdf/2507.07848)]
- [*arXiv 2025/07/23*] **AlignDistil: Token-Level Language Model Alignment as Adaptive Policy Distillation** [[PDF](https://arxiv.org/pdf/2503.02832)]
- [*CoG 2025*] **Bootstrap Your Own Teacher: Online Policy Distillation for Multi-Game Reinforcement Learning** [[PDF](https://ieeexplore.ieee.org/document/11114408)]
- [*arXiv 2025/06/26*] **EgoAdapt: Adaptive Multisensory Distillation and Policy Learning for Efficient Egocentric Perception** [[PDF](https://arxiv.org/pdf/2506.21080)]
- [*arXiv 2025/06/06*] **Proximal Policy Distillation** [[PDF](https://arxiv.org/pdf/2407.15134)]
- [*arXiv 2025/06/02*] **KDRL: Post-Training Reasoning LLMs via Unified Knowledge Distillation and Reinforcement Learning** [[PDF](https://arxiv.org/pdf/2506.02208)]
- [*arXiv 2025/05/16*] **Parkour in the Wild: Learning a General and Extensible Agile Locomotion Policy Using Multi-expert Distillation and RL Fine-tuning** [[PDF](https://arxiv.org/pdf/2505.11164)]
- [*ICLR 2025*] **Speculative Knowledge Distillation: Bridging the Teacher-Student Gap Through Interleaved Sampling** [[PDF](https://arxiv.org/pdf/2410.11325)][[Code](https://github.com/google-research/google-research/tree/master/speculative_kd)]
- [*arXiv 2025/03/11*] **Evaluating Interpretable Reinforcement Learning by Distilling Policies into Programs** [[PDF](https://arxiv.org/pdf/2503.08322)]
- [*arXiv 2025/03/04*] **UniGraspTransformer: Simplified Policy Distillation for Scalable Dexterous Robotic Grasping** [[PDF](https://arxiv.org/pdf/2412.02699)]
- [*arXiv 2025/02/07*] **Exploring the Generalizability of Geomagnetic Navigation: A Deep Reinforcement Learning approach with Policy Distillation** [[PDF](https://arxiv.org/pdf/2502.05069)]
- [*arXiv 2025/02/02*] **FedHPD: Heterogeneous Federated Reinforcement Learning via Policy Distillation** [[PDF](https://arxiv.org/pdf/2502.00870)]
- [*COLING 2025*] **Distilling Rule-based Knowledge into Large Language Models** [[PDF](https://aclanthology.org/2025.coling-main.61.pdf)][[Code](https://github.com/RUCBM/rule-distillation)]![GitHub Repo stars](https://img.shields.io/github/stars/RUCBM/rule-distillation?style=social)

### 2024
- [*arXiv 2024/12/19*] **Score and Distribution Matching Policy: Advanced Accelerated Visuomotor Policies via Matched Distillation** [[PDF](https://arxiv.org/pdf/2412.09265)]
- [*arXiv 2024/12/12*] **RLDG: Robotic Generalist Policy Distillation via Reinforcement Learning** [[PDF](https://arxiv.org/pdf/2412.09858)]
- [*arXiv 2024/11/25*] **Continual Deep Reinforcement Learning with Task-Agnostic Policy Distillation** [[PDF](https://arxiv.org/pdf/2411.16532)]
- [*arXiv 2024/10/28*] **One-Step Diffusion Policy: Fast Visuomotor Policies via Diffusion Distillation** [[PDF](https://arxiv.org/pdf/2410.21257)]
- [*arXiv 2024/10/18*] **Variational Distillation of Diffusion Policies into Mixture of Experts** [[PDF](https://arxiv.org/pdf/2406.12538)]
- [*arXiv 2024/06/28*] **Consistency Policy: Accelerated Visuomotor Policies via Consistency Distillation** [[PDF](https://arxiv.org/pdf/2405.07503)]
- [*arXiv 2024/06/08*] **Online Policy Distillation with Decision-Attention** [[PDF](https://arxiv.org/pdf/2406.05488)]
- [*ICLR 2024*] **On-Policy Distillation of Language Models: Learning from Self-Generated Mistakes** [[PDF](https://arxiv.org/pdf/2306.13649)]
- [*ICLR 2024*] **MiniLLM: On-Policy Distillation of Large Language Models** [[PDF](https://arxiv.org/pdf/2306.08543)][[Code](https://github.com/microsoft/LMOps/tree/main/minillm)]
- [*arXiv 2024/04/26*] **An Explainable Deep Reinforcement Learning Model for Warfarin Maintenance Dosing Using Policy Distillation and Action Forging** [[PDF](https://arxiv.org/pdf/2404.17187)]
- [*arXiv 2024/04/05*] **Continual Policy Distillation of Reinforcement Learning-based Controllers for Soft Robotic In-Hand Manipulation** [[PDF](https://arxiv.org/pdf/2404.04219)]
- [*arXiv 2024/03/21*] **Distilling Reinforcement Learning Policies for Interpretable Robot Locomotion: Gradient Boosting Machines and Symbolic Regression** [[PDF](https://arxiv.org/pdf/2403.14328)]

### 2023 and earlier
- [*arXiv 2023/12/07*] **RL Dreams: Policy Gradient Optimization for Score Distillation based 3D Generation** [[PDF](https://arxiv.org/pdf/2312.04806)]
- [*arXiv 2023/12/02*] **Visual-Policy Learning through Multi-Camera View to Single-Camera View Knowledge Distillation for Robot Manipulation Tasks** [[PDF](https://arxiv.org/pdf/2303.07026)]
- [*arXiv 2023/10/12*] **PolyTask: Learning Unified Policies through Behavior Distillation** [[PDF](https://arxiv.org/pdf/2310.08573)]
- [*arXiv 2023/10/07*] **Counterfactual Explainer Framework for Deep Reinforcement Learning Models Using Policy Distillation** [[PDF](https://arxiv.org/pdf/2305.16532)]
- [*arXiv 2023/09/27*] **Distillation Policy Optimization** [[PDF](https://arxiv.org/pdf/2302.00533)]
- [*arXiv 2023/07/24*] **Theoretically Guaranteed Policy Improvement Distilled from Model-Based Planning** [[PDF](https://arxiv.org/pdf/2307.12933)]
- [*arXiv 2023/04/21*] **Wasserstein Auto-encoded MDPs: Formal Verification of Efficiently Distilled RL Policies with Many-sided Guarantees** [[PDF](https://arxiv.org/pdf/2303.12558)]
- [*arXiv 2023/04/10*] **Cyclic Policy Distillation: Sample-Efficient Sim-to-Real Reinforcement Learning with Domain Randomization** [[PDF](https://arxiv.org/pdf/2207.14561)]
- [*arXiv 2023/03/07*] **MAP-Elites with Descriptor-Conditioned Gradients and Archive Distillation into a Single Policy** [[PDF](https://arxiv.org/pdf/2303.03832)]
- [*arXiv 2022/12/21*] **Contrastive Distillation Is a Sample-Efficient Self-Supervised Loss Policy for Transfer Learning** [[PDF](https://arxiv.org/pdf/2212.11353)]
- [*arXiv 2022/09/30*] **Improving Policy Learning via Language Dynamics Distillation** [[PDF](https://arxiv.org/pdf/2210.00066)]
- [*arXiv 2022/09/30*] **Learning by Distilling Context** [[PDF](https://arxiv.org/pdf/2209.15189)]
- [*arXiv 2022/09/19*] **MSVIPER: Improved Policy Distillation for Reinforcement-Learning-Based Robot Navigation** [[PDF](https://arxiv.org/pdf/2209.09079)]
- [*arXiv 2022/06/14*] **Distillation of RL Policies with Formal Guarantees via Variational Abstraction of Markov Decision Processes (Technical Report)** [[PDF](https://arxiv.org/pdf/2112.09655)]
- [*arXiv 2022/05/17*] **Policy Distillation with Selective Input Gradient Regularization for Efficient Interpretability** [[PDF](https://arxiv.org/pdf/2205.08685)]
- [*arXiv 2022/03/01*] **Keeping Minimal Experience to Achieve Efficient Interpretable Policy Distillation** [[PDF](https://arxiv.org/pdf/2203.00822)]
- [*arXiv 2021/11/11*] **Distilling Motion Planner Augmented Policies into Visual Control Policies for Robot Manipulation** [[PDF](https://arxiv.org/pdf/2111.06383)]
- [*arXiv 2021/08/16*] **Neural-to-Tree Policy Distillation with Policy Improvement Criterion** [[PDF](https://arxiv.org/pdf/2108.06898)]
- [*arXiv 2021/04/06*] **Distilling a Hierarchical Policy for Planning and Control via Representation and Reinforcement Learning** [[PDF](https://arxiv.org/pdf/2011.08345)]
- [*arXiv 2021/01/28*] **Universal Trading for Order Execution with Oracle Policy Distillation** [[PDF](https://arxiv.org/pdf/2103.10860)]
- [*arXiv 2020/06/07*] **Dual Policy Distillation** [[PDF](https://arxiv.org/pdf/2006.04061)]
- [*arXiv 2020/05/12*] **Hierarchical Decomposition of Nonlinear Dynamics and Control for System Identification and Policy Distillation** [[PDF](https://arxiv.org/pdf/2005.01432)]
- [*arXiv 2020/04/30*] **Evolutionary Stochastic Policy Distillation** [[PDF](https://arxiv.org/pdf/2004.12909)]
- [*arXiv 2020/01/27*] **Developing Multi-Task Recommendations with Long-Term Rewards via Policy Distilled Reinforcement Learning** [[PDF](https://arxiv.org/pdf/2001.09595)]
- [*arXiv 2019/12/29*] **Real-time Policy Distillation in Deep Reinforcement Learning** [[PDF](https://arxiv.org/pdf/1912.12630)]
- [*arXiv 2019/10/21*] **A New Framework for Multi-Agent Reinforcement Learning -- Centralized Training and Exploration with Decentralized Execution via Policy Distillation** [[PDF](https://arxiv.org/pdf/1910.09152)]
- [*arXiv 2019/07/11*] **DisCoRL: Continual Reinforcement Learning via Policy Distillation** [[PDF](https://arxiv.org/pdf/1907.05855)]
- [*arXiv 2019/06/11*] **Continual Reinforcement Learning deployed in Real-life using Policy Distillation and Sim2Real Transfer** [[PDF](https://arxiv.org/pdf/1906.04452)]
- [*arXiv 2019/06/07*] **Random Expert Distillation: Imitation Learning via Expert Policy Support Estimation** [[PDF](https://arxiv.org/pdf/1905.06750)]
- [*arXiv 2019/04/30*] **Distillation Strategies for Proximal Policy Optimization** [[PDF](https://arxiv.org/pdf/1901.08128)]
- [*AISTATS 2019*] **Distilling Policy Distillation** [[PDF](https://proceedings.mlr.press/v89/czarnecki19a/czarnecki19a.pdf)]
- [*arXiv 2019/03/15*] **Policy Distillation and Value Matching in Multiagent Reinforcement Learning** [[PDF](https://arxiv.org/pdf/1903.06592)]
- [*arXiv 2018/09/24*] **Low Precision Policy Distillation with Application to Low-Power, Real-time Sensation-Cognition-Action Loop with Neuromorphic Computing** [[PDF](https://arxiv.org/pdf/1809.09260)]
- [*arXiv 2018/03/12*] **Policy Optimization by Genetic Distillation** [[PDF](https://arxiv.org/pdf/1711.01012)]
- [*arXiv 2018/03/10*] **Kickstarting Deep Reinforcement Learning** [[PDF](https://arxiv.org/pdf/1803.03835)]
- [*arXiv 2015/11/19*] **Policy Distillation** [[PDF](https://arxiv.org/pdf/1511.06295)]

---

## Survey

- [*arXiv 2026/04/01*] **A Survey of On-Policy Distillation for Large Language Models** [[PDF](https://arxiv.org/pdf/2604.00626)]



---


## Blog Posts and Tutorials

- **On-Policy Distillation** (Thinking Machines Lab blog) [[Blog](https://thinkingmachines.ai/blog/on-policy-distillation/)]

- **Unlocking On-Policy Distillation for Any Model Family** (HuggingFace blog) [[Blog](https://huggingface.co/spaces/HuggingFaceH4/on-policy-distillation)]
---





## License

This list is released under the **MIT License**.
