---
title: "ParticleDA.jl v.1.0: a distributed particle-filtering data assimilation package"
collection: publications
permalink: /publications/ParticleDA
excerpt: ''
date: 2024-03-28
venue: 'Geoscientific Model Development'
paperurl: 'https://doi.org/10.5194/gmd-17-2427-2024'
citation: 'Giles, D., Graham, M. M., Giordano, M., Koskela, T., Beskos, A., and Guillas, S.: ParticleDA.jl v.1.0: a distributed particle-filtering data assimilation package, Geosci. Model Dev., 17, 2427–2445, 2024.'
---
<!-- This paper is about the number 1. The number 2 is left for future work. -->

[Download paper here](https://doi.org/10.5194/gmd-17-2427-2024)

## Abstract 
Digital twins of physical and human systems informed by real-time data are becoming ubiquitous across weather forecasting, disaster preparedness, and urban planning, but researchers lack the tools to run these models effectively and efficiently, limiting progress. One of the current challenges is to assimilate observations in highly non-linear dynamical systems, as the practical need is often to detect abrupt changes. We have developed a software platform to improve the use of real-time data in non-linear system representations where non-Gaussianity limits the applicability of data assimilation algorithms such as the ensemble Kalman filter and variational methods. Particle-filter-based data assimilation algorithms have been implemented within a user-friendly open-source software platform in Julia – ParticleDA.jl. To ensure the applicability of the developed platform in realistic scenarios, emphasis has been placed on numerical efficiency and scalability on high-performance computing systems. Furthermore, the platform has been developed to be forward-model agnostic, ensuring that it is applicable to a wide range of modelling settings, for instance unstructured and non-uniform meshes in the spatial domain or even state spaces that are not spatially organized. Applications to tsunami and numerical weather prediction demonstrate the computational benefits and ease of using the high-level Julia interface with the package to perform filtering in a variety of complex models.

Recommended citation: Giles, D., Graham, M. M., Giordano, M., Koskela, T., Beskos, A., and Guillas, S.: ParticleDA.jl v.1.0: a distributed particle-filtering data assimilation package, Geosci. Model Dev., 17, 2427–2445, https://doi.org/10.5194/gmd-17-2427-2024, 2024.