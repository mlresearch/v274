---
year: '2024'
title: Learning to learn without forgetting using attention
abstract: Continual learning (CL) refers to the ability to continually learn over
  time by accommodating new knowledge while retaining previously learned experience.
  While this concept is inherent in human learning, current machine learning methods
  are highly prone to overwrite previously learned patterns and thus forget past experience.
  Instead, model parameters should be updated selectively and carefully, avoiding
  unnecessary forgetting while optimally leveraging previously learned patterns to
  accelerate future learning. Since hand-crafting effective update mechanisms is difficult,
  we propose meta-learning a transformer-based optimizer to enhance CL. This meta-learned
  optimizer uses attention to learn the complex relationships between model parameters
  across a stream of tasks, and is designed to generate effective weight updates for
  the current task while preventing catastrophic forgetting on previously encountered
  tasks. Evaluations on benchmark datasets like SplitMNIST, RotatedMNIST, and SplitCIFAR-100
  affirm the efficacy of the proposed approach in terms of both forward and backward
  transfer, even on small sets of labeled data, highlighting the advantages of integrating
  a meta-learned optimizer within the continual learning framework.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vettoruzzo25a
month: 0
tex_title: Learning to learn without forgetting using attention
firstpage: 285
lastpage: 300
page: 285-300
order: 285
cycles: false
bibtex_author: Vettoruzzo, Anna and Vanschoren, Joaquin and Bouguelia, Mohamed-Rafik
  and R{\"{o}}gnvaldsson, Thorsteinn S.
author:
- given: Anna
  family: Vettoruzzo
- given: Joaquin
  family: Vanschoren
- given: Mohamed-Rafik
  family: Bouguelia
- given: Thorsteinn S.
  family: Rögnvaldsson
date: 2025-02-17
address:
container-title: Proceedings of The 3rd Conference on Lifelong Learning Agents
volume: '274'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 2
  - 17
pdf: https://raw.githubusercontent.com/mlresearch/v274/main/assets/vettoruzzo25a/vettoruzzo25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
