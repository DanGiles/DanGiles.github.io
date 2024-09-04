---
title: "Scalable Data Assimilation with Message Passing"
collection: publications
permalink: /publications/Message_passing
excerpt: ''
date: 2024-04-19
venue: 'arXiv'
paperurl: 'https://doi.org/10.48550/arXiv.2404.12968'
citation: 'Key, O., et al.: Scalable Data Assimilation with Message Passing, 2024.'
---
<!-- This paper is about the number 1. The number 2 is left for future work. -->

[Download preprint here](https://doi.org/10.48550/arXiv.2404.12968)

## Abstract 
Data assimilation is a core component of numerical weather prediction systems. The large quantity of data processed during assimilation requires the computation to be distributed across increasingly many compute nodes, yet existing approaches suffer from synchronisation overhead in this setting. In this paper, we exploit the formulation of data assimilation as a Bayesian inference problem and apply a message-passing algorithm to solve the spatial inference problem. Since message passing is inherently based on local computations, this approach lends itself to parallel and distributed computation. In combination with a GPU-accelerated implementation, we can scale the algorithm to very large grid sizes while retaining good accuracy and compute and memory requirements.

Recommended citation: Key, O., et al.: Scalable Data Assimilation with Message Passing, arXiv, 10.48550/arXiv.2404.12968, 2024.