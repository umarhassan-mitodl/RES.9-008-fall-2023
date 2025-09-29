---
content_type: page
description: Tutorial contents.
draft: false
title: Tutorial on Statistical Inference on Representational Geometries
uid: e7e9e217-72b6-483e-8468-272f181a80e8
---
**Taught by:** *Heiko Schütt, NYU (October 25, 2022)*

**Video:** [Tutorial on Statistical Inference on Representational Geometries](https://youtu.be/AxbfqIBFTT8)

**Description:** Representational similarity analysis (RSA) is a popular method for comparing representations when a mapping between them is not available. One important comparison RSA is used for is between neuronal measurements and models of brain computation like deep neural networks. RSA is a two-step process. First, a matrix of pairwise dissimilarities between conditions is computed. This matrix is then a summary of the representational geometry, which can be compared directly between different representations as it has the same dimensions. In the first half of this tutorial, I will go through some recent advancements for RSA that improve the reliability and statistical accuracy of RSA substantially: First, I will explain the reasoning for cross-validated distance measures for computing the dissimilarity matrix and for whitened similarity measures to compare them to each other. Then, I will explain why simultaneous generalization to new subjects and new stimuli is hard and a solution based on bootstrapping. Finally, I will explain the necessary cross-validation-based extensions for flexible models. In the second half of this tutorial, I will give a guide on how to run these analyses using our new *rsatoolbox* in Python by going through demo notebooks that illustrate the functionality.

**Additional Resources**:

Relevant papers:

- Schütt et al., 2021: ["Statistical Inference on Representational Geometries."](https://arxiv.org/abs/2112.09200) arXiv:2112.09200.
- Walther et al., 2016: ["Reliability of Dissimilarity Measures for Multi-voxel Pattern Analysis."](https://pubmed.ncbi.nlm.nih.gov/26707889/) *Neuroimage* 137: 188–200.
- Diedrichsen et al., 2021: ["Comparing Representational Geometries Using Whitened Unbiased-Distance-Matrix Similarity."](https://arxiv.org/abs/2007.02789) arXiv:2007.02789.

GitHub Repositories:

- [GitHub repository](https://github.com/rsagroup/rsatoolbox/)
- [GitHub demo repository](https://github.com/rsagroup/rsatoolbox/tree/main/demos)