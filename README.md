awesome-on-policy-distillation
==============================

> A curated list of papers and resources on **on-policy distillation (OPD)**.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

On-policy distillation broadly refers to distilling a student policy **using trajectories sampled from the student itself**, while using a teacher as supervision (e.g., token-level KL, cross-entropy, or more general KL-constrained RL objectives). This list focuses on methods where the *student’s own rollouts* are central to the training signal.

**Disclaimer:** This is a curated but **not exhaustive** list. Please open issues or PRs to add missing work.

---

## Contents

- [Papers (ordered by year, ascending)](#papers-ordered-by-year-ascending)
- [Blog Posts and Tutorials](#blog-posts-and-tutorials)
- [Contributing](#contributing)

---

## Papers (ordered by year, ascending)

- **Fast and Effective On-policy Distillation from Reasoning Prefixes** — *2026*  
  *Dongxu Zhang, Zhichao Yang, Sepehr Janghorbani, Jun Han, Andrew Ressler II, Qian Qian, Gregory D. Lyng, Sanjit Singh Batra, Robert E. Tillman*  
  [[arXiv](https://arxiv.org/abs/2602.15260)]

- **Learning beyond Teacher: Generalized On-Policy Distillation with Reward Extrapolation (G-OPD / ExOPD)** — *2026*  
  *Wenkai Yang, Weijie Liu, Ruobing Xie, Kai Yang, Saiyong Yang, Yankai Lin*  
  [[arXiv](https://arxiv.org/abs/2602.12125)]

- **Bootstrap Your Own Teacher: Online Policy Distillation for Multi-Game Reinforcement Learning** — *2025*  
  *Authors as listed on IEEE Xplore*  
  [[IEEE Xplore](https://ieeexplore.ieee.org/document/11114408)]

- **Distilling Policy Distillation** — *2019*  
  *Wojciech M. Czarnecki, Razvan Pascanu, Simon Osindero, Siddhant M. Jayakumar, Grzegorz Świrszcz, Max Jaderberg*  
  AISTATS 2019.  
  [[PDF / PMLR](https://proceedings.mlr.press/v89/czarnecki19a/czarnecki19a.pdf)]

- **Kickstarting Deep Reinforcement Learning** — *2018*  
  *Simon Schmitt, Jonathan J. Judson, Augustin Zidek, et al.*  
  [[arXiv](https://arxiv.org/abs/1803.03835)]

- **Policy Distillation** — *2015*  
  *Andrei A. Rusu, Sergio Gomez Colmenarejo, Caglar Gulcehre, et al.*  
  [[arXiv](https://arxiv.org/abs/1511.06295)]

---

## Blog Posts and Tutorials

- **On-Policy Distillation** (Thinking Machines Lab blog)  
  Overview article explaining the intuition behind **on-policy distillation**, its advantages over off-policy fine-tuning (denser feedback from student trajectories, better distribution matching), and how OPD relates to KL-constrained RL.  
  [[Blog](https://thinkingmachines.ai/blog/on-policy-distillation/)]

---

## Contributing

Contributions are very welcome!

- **Add missing papers**: especially new OPD variants, applications, or large-scale empirical studies.
- **Improve categorization**: better tags (e.g., RL vs LMs, theory vs empirical, multi-teacher vs single-teacher).

Please:

- Follow the existing **markdown style** and section structure.
- Prefer **official links**.

---



## License

This list is released under the **MIT License**.