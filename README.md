awesome-on-policy-distillation
==============================

> A curated list of papers and resources on **on-policy distillation (OPD)**.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

On-policy distillation broadly refers to distilling a student policy **using trajectories sampled from the student itself**, while using a teacher as supervision (e.g., token-level KL, cross-entropy, or more general KL-constrained RL objectives). This list focuses on methods where the *student’s own rollouts* are central to the training signal.

**Disclaimer:** This is a curated but **not exhaustive** list. Please open issues or PRs to add missing work (see Contributing).

---

## Contents

- [Papers (ordered by year)](#papers-ordered-by-year-ascending)
- [Blog Posts and Tutorials](#blog-posts-and-tutorials)
- [Contributing](#contributing)

---

## Papers (ordered by year)

- [*arXiv 2026*] **Fast and Effective On-policy Distillation from Reasoning Prefixes** [[PDF](https://arxiv.org/pdf/2602.15260)]

- [*arXiv 2026*] **Learning beyond Teacher: Generalized On-Policy Distillation with Reward Extrapolation** [[PDF](https://arxiv.org/pdf/2602.12125)][[Code](https://github.com/RUCBM/G-OPD)]

- [*arXiv 2026*] **On-Policy Context Distillation for Language Models** [[PDF](https://arxiv.org/pdf/2602.12275)]

- [*arXiv 2026*] **Multi-Token Prediction via Self-Distillation** [[PDF](https://arxiv.org/pdf/2602.06019)]

- [*arXiv 2026*] **Privileged Information Distillation for Language Models** [[PDF](https://arxiv.org/pdf/2602.04942)]

- [*arXiv 2026*] **OVD: On-policy Verbal Distillation** [[PDF](https://arxiv.org/pdf/2601.21968v1)][[Code](https://ovd.github.io/)]

- [*arXiv 2026*] **Reinforcement Learning via Self-Distillation** [[PDF](https://arxiv.org/pdf/2601.20802)][[Code](https://github.com/lasgroup/SDPO)]

- [*arXiv 2026*] **Self-Distillation Enables Continual Learning** [[PDF](https://arxiv.org/pdf/2601.19897)][[Code](https://github.com/idanshen/Self-Distillation)]

- [*arXiv 2026*] **Self-Distilled Reasoner: On-Policy Self-Distillation for Large Language Models** [[PDF](https://arxiv.org/pdf/2601.18734)]

- [*arXiv 2026*] **Stable On-Policy Distillation through Adaptive Target Reformulation** [[PDF](https://arxiv.org/pdf/2601.07155)]

- [*arXiv 2026*] **Black-Box On-Policy Distillation of Large Language Models** [[PDF](https://arxiv.org/pdf/2511.10643)][[Code](https://github.com/microsoft/LMOps/tree/main/gad)]


- [*arXiv 2025*] **VOLD: Reasoning Transfer from LLMs to Vision-Language Models via On-Policy Distillation** [[PDF](https://arxiv.org/pdf/2510.23497)][[Code](https://walidbousselham.com/VOLD/)]

- [*COLING 2025*] **Distilling Rule-based Knowledge into Large Language Models** [[PDF](https://aclanthology.org/2025.coling-main.61.pdf)][[Code](https://github.com/RUCBM/rule-distillation)]

- [*CoG 2025*] **Bootstrap Your Own Teacher: Online Policy Distillation for Multi-Game Reinforcement Learning** [[PDF](https://ieeexplore.ieee.org/document/11114408)]

- [*ICLR 2024*] **MiniLLM: On-Policy Distillation of Large Language Models** [[PDF](https://arxiv.org/pdf/2306.08543)][[Code](https://github.com/microsoft/LMOps/tree/main/minillm)]

- [*ICLR 2024*] **On-Policy Distillation of Language Models: Learning from Self-Generated Mistakes** [[PDF](https://arxiv.org/pdf/2306.13649)]

- [*AISTATS 2019*] **Distilling Policy Distillation** [[PDF](https://proceedings.mlr.press/v89/czarnecki19a/czarnecki19a.pdf)]

- [*arXiv 2018*] **Kickstarting Deep Reinforcement Learning** [[PDF](https://arxiv.org/pdf/1803.03835)]

- [*arXiv 2015*] **Policy Distillation** [[PDF](https://arxiv.org/pdf/1511.06295)]

---

## Blog Posts and Tutorials

- **On-Policy Distillation** (Thinking Machines Lab blog) [[Blog](https://thinkingmachines.ai/blog/on-policy-distillation/)]

- **Unlocking On-Policy Distillation for Any Model Family** (HuggingFace blog) [[Blog](https://huggingface.co/spaces/HuggingFaceH4/on-policy-distillation)]
---

## Contributing

Contributions to this repository are very welcome! 

If you have come across relevant resources, feel free to open an [Issue](https://github.com/Jianglin954/awesome-on-policy-distillation/issues), or submit a [Pull Requests](https://github.com/Jianglin954/awesome-on-policy-distillation/pulls):

```
- [*Conference/Journal Year*] **paper_name** [[PDF](link)][[Code](link)]
```

---



## License

This list is released under the **MIT License**.