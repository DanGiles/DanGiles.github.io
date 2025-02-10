---
title: "Tensor-Var: Variational Data Assimilation in Tensor Product Feature Space"
collection: publications
permalink: /publications/Tensor-Var
excerpt: ''
date: 2024-11-18
venue: 'arxiv'
paperurl: 'https://doi.org/10.48550/arXiv.2501.13312'
citation: 'Yang, Y., et al.: Tensor-Var: Variational Data Assimilation in Tensor Product Feature Space, 2025.'
---
<!-- This paper is about the number 1. The number 2 is left for future work. -->

[Download preprint here](https://doi.org/10.48550/arXiv.2501.13312)

## Abstract 
Variational data assimilation estimates the dynamical system states by minimizing a cost function that fits the numerical models with observational data. The widely used method, four-dimensional variational assimilation (4D-Var), has two primary challenges: (1) computationally demanding for complex nonlinear systems and (2) relying on state-observation mappings, which are often not perfectly known. Deep learning (DL) has been used as a more expressive class of efficient model approximators to address these challenges. However, integrating such models into 4D-Var remains challenging due to their inherent nonlinearities and the lack of theoretical guarantees for consistency in assimilation results. In this paper, we propose \textit{Tensor-Var} to address these challenges using kernel Conditional Mean Embedding (CME). Tensor-Var improves optimization efficiency by characterizing system dynamics and state-observation mappings as linear operators, leading to a convex cost function in the feature space. Furthermore, our method provides a new perspective to incorporate CME into 4D-Var, offering theoretical guarantees of consistent assimilation results between the original and feature spaces. To improve scalability, we propose a method to learn deep features (DFs) using neural networks within the Tensor-Var framework. Experiments on chaotic systems and global weather prediction with real-time observations show that Tensor-Var outperforms conventional and DL hybrid 4D-Var baselines in accuracy while achieving efficiency comparable to the static 3D-Var method.

Recommended citation: Yang, Y., et al.: Tensor-Var: Variational Data Assimilation in Tensor Product Feature Space, arxiv, 10.48550/arXiv.2501.13312, 2025.