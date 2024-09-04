---
title: "Uncertainty Quantification of Pre-Trained and Fine-Tuned Surrogate Models using Conformal Prediction"
collection: publications
permalink: /publications/Conformal_prediction
excerpt: ''
date: 2024-08-19
venue: 'arXiv'
paperurl: 'https://doi.org/10.48550/arXiv.2408.09881'
citation: 'Gopakumar, V., et al.: Uncertainty Quantification of Pre-Trained and Fine-Tuned Surrogate Models using Conformal Prediction, 2024.'
---
<!-- This paper is about the number 1. The number 2 is left for future work. -->

[Download preprint here](https://doi.org/10.48550/arXiv.2408.09881)

## Abstract 
Data-driven surrogate models have shown immense potential as quick, inexpensive approximations to complex numerical and experimental modelling tasks. However, most surrogate models characterising physical systems do not quantify their uncertainty, rendering their predictions unreliable, and needing further validation. Though Bayesian approximations offer some solace in estimating the error associated with these models, they cannot provide they cannot provide guarantees, and the quality of their inferences depends on the availability of prior information and good approximations to posteriors for complex problems. This is particularly pertinent to multi-variable or spatio-temporal problems. Our work constructs and formalises a conformal prediction framework that satisfies marginal coverage for spatio-temporal predictions in a model-agnostic manner, requiring near-zero computational costs. The paper provides an extensive empirical study of the application of the framework to ascertain valid error bars that provide guaranteed coverage across the surrogate model's domain of operation. The application scope of our work extends across a large range of spatio-temporal models, ranging from solving partial differential equations to weather forecasting. Through the applications, the paper looks at providing statistically valid error bars for deterministic models, as well as crafting guarantees to the error bars of probabilistic models. The paper concludes with a viable conformal prediction formalisation that provides guaranteed coverage of the surrogate model, regardless of model architecture, and its training regime and is unbothered by the curse of dimensionality.

Recommended citation: Gopakumar, V., et al.: Uncertainty Quantification of Pre-Trained and Fine-Tuned Surrogate Models using Conformal Prediction, arXiv, 10.48550/arXiv.2408.09881, 2024.