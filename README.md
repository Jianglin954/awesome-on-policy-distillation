awesome-on-policy-distillation
==============================

> A curated list of papers and resources on **on-policy distillation (OPD)**.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

On-policy distillation broadly refers to distilling a student policy **using trajectories sampled from the student itself**, while using a teacher as supervision (e.g., token-level KL, cross-entropy, or more general KL-constrained RL objectives). This list focuses on methods where the *student’s own rollouts* are central to the training signal.

**Disclaimer:** This is a curated but **not exhaustive** list. Please open issues or PRs to add missing work (see Contributing).

---

## Contents

- [Papers (ordered by year, ascending)](#papers-ordered-by-year-ascending)
- [Blog Posts and Tutorials](#blog-posts-and-tutorials)
- [Contributing](#contributing)

---

## Papers (ordered by year)

- [*arXiv 2026*] **Fast and Effective On-policy Distillation from Reasoning Prefixes** [[PDF](https://arxiv.org/pdf/2602.15260)]

- [*arXiv 2026*] **Learning beyond Teacher: Generalized On-Policy Distillation with Reward Extrapolation** [[PDF](https://arxiv.org/abs/2602.12125)][[Code](https://github.com/RUCBM/G-OPD)]

- [*CoG 2025*] **Bootstrap Your Own Teacher: Online Policy Distillation for Multi-Game Reinforcement Learning** [[PDF](https://ieeexplore.ieee.org/document/11114408)]

- [*AISTATS 2019*] **Distilling Policy Distillation** [[PDF](https://proceedings.mlr.press/v89/czarnecki19a/czarnecki19a.pdf)]

- [*arXiv 2018*] **Kickstarting Deep Reinforcement Learning** [[PDF](https://arxiv.org/abs/1803.03835)]

- [*arXiv 2015*] **Policy Distillation** [[PDF](https://arxiv.org/abs/1511.06295)]

---

## Blog Posts and Tutorials

- **On-Policy Distillation** (Thinking Machines Lab blog)  
  Overview article explaining the intuition behind **on-policy distillation**, its advantages over off-policy fine-tuning (denser feedback from student trajectories, better distribution matching), and how OPD relates to KL-constrained RL.  
  [[Blog](https://thinkingmachines.ai/blog/on-policy-distillation/)]

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