---
content_type: page
description: Tutorial contents.
draft: false
title: Tutorial on Statistical Inference on Representational Geometries
uid: e7e9e217-72b6-483e-8468-272f181a80e8
---
**Taught by:** *Heiko Schütt, NYU (October 25, 2022)*

**Video:** {{% resource_link "3c26adbc-2bd8-4812-ac03-4c79dc874142" "Tutorial on Statistical Inference on Representational Geometries" %}}

**Description:** Representational similarity analysis (RSA) is a popular method for comparing representations when a mapping between them is not available. One important comparison RSA is used for is between neuronal measurements and models of brain computation like deep neural networks. RSA is a two-step process. First, a matrix of pairwise dissimilarities between conditions is computed. This matrix is then a summary of the representational geometry, which can be compared directly between different representations as it has the same dimensions. In the first half of this tutorial, I will go through some recent advancements for RSA that improve the reliability and statistical accuracy of RSA substantially: First, I will explain the reasoning for cross-validated distance measures for computing the dissimilarity matrix and for whitened similarity measures to compare them to each other. Then, I will explain why simultaneous generalization to new subjects and new stimuli is hard and a solution based on bootstrapping. Finally, I will explain the necessary cross-validation-based extensions for flexible models. In the second half of this tutorial, I will give a guide on how to run these analyses using our new *rsatoolbox* in Python by going through demo notebooks that illustrate the functionality.

**Additional Resources**:

Relevant papers:

- Schütt et al., 2021: {{% resource_link "adbdf12b-9676-49eb-add0-434351eef101" "\"Statistical Inference on Representational Geometries.\"" %}} arXiv:2112.09200.
- Walther et al., 2016: {{% resource_link "7050f254-51be-4478-9aa0-48fe70274e8e" "\"Reliability of Dissimilarity Measures for Multi-voxel Pattern Analysis.\"" %}} *Neuroimage* 137: 188–200.
- Diedrichsen et al., 2021: {{% resource_link "2ea136b4-1f4c-4aee-9b00-cd7997be1103" "\"Comparing Representational Geometries Using Whitened Unbiased-Distance-Matrix Similarity.\"" %}} arXiv:2007.02789.

GitHub Repositories:

- {{% resource_link "8f5c413d-6ad8-401c-8e87-efc16fd17cff" "GitHub repository" %}}
- {{% resource_link "220a706f-c6f5-4592-a515-faffdc533481" "GitHub demo repository" %}}