---
year: '2024'
title: A Contrastive Symmetric Forward-Forward Algorithm (SFFA) for Continual Learning
  Tasks
abstract: The so-called Forward-Forward Algorithm (FFA) has recently gained momentum
  as an alternative to the conventional back-propagation algorithm for neural network
  learning, yielding competitive performance across various modeling tasks. By replacing
  the backward pass of gradient back-propagation with two contrastive forward passes,
  the FFA avoids several shortcomings undergone by its predecessor (e.g., vanishing/exploding
  gradient) by enabling layer-wise training heuristics. In classification tasks, this
  contrastive method has been proven to effectively create a latent sparse representation
  of the input data, ultimately favoring discriminability. However, FFA exhibits an
  inherent asymmetric gradient behavior due to an imbalanced loss function between
  positive and negative data, adversely impacting on the model’s generalization capabilities
  and leading to an accuracy degradation. To address this issue, this work proposes
  the Symmetric Forward-Forward Algorithm (SFFA), a novel modification of the original
  FFA which partitions each layer into positive and negative neurons. This allows
  the local fitness function to be defined as the ratio between the activation of
  positive neurons and the overall layer activity, resulting in a symmetric loss landscape
  during the training phase. To evaluate the enhanced convergence of our method, we
  conduct several experiments using multiple image classification benchmarks, comparing
  the accuracy of models trained with SFFA to those trained with its FFA counterpart.
  As a byproduct of this reformulation, we explore the advantages of using a layer-wise
  training algorithm for Continual Learning (CL) tasks. The specialization of neurons
  and the sparsity of their activations induced by layer-wise training algorithms
  enable efficient CL strategies that incorporate new knowledge (classes) into the
  neural network, while preventing catastrophic forgetting of previously learned concepts.
  Experiments in three CL scenarios (Class, Domain, and Task Incremental) using multiple
  well-known CL techniques (EWC, SI, MAS, Replay and GEM) are discussed to analyze
  the differences between our SFFA model and a model trained using back-propagation.
  Our results demonstrate that the herein proposed SFFA achieves competitive levels
  of accuracy when compared to the off-the-shelf FFA, maintaining sparse latent activity,
  and resulting in a more precise goodness function. Our findings support the effectiveness
  of SFFA in CL tasks, highlighting its natural complementarity with techniques devised
  for this modeling paradigm.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: terres-escudero25a
month: 0
tex_title: A Contrastive Symmetric Forward-Forward Algorithm (SFFA) for Continual
  Learning Tasks
firstpage: 49
lastpage: 69
page: 49-69
order: 49
cycles: false
bibtex_author: Terres-Escudero, Erik B and Ser, Javier Del and Garcia-Bringas, Pablo
author:
- given: Erik B
  family: Terres-Escudero
- given: Javier Del
  family: Ser
- given: Pablo
  family: Garcia-Bringas
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
pdf: https://raw.githubusercontent.com/mlresearch/v274/main/assets/terres-escudero25a/terres-escudero25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
