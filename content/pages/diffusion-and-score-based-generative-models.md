---
content_type: page
description: Seminar contents.
draft: false
title: Diffusion and Score-Based Generative Models
uid: 598642c1-8028-4197-a3d1-a0f65ee79c52
---
**Taught by:** *Yang Song, Stanford University (December 12, 2022)*

**Video:** [Diffusion and Score-Based Generative Models](https://youtu.be/wMmqCMwuM2Q)

**Description:** Generating data with complex patterns, such as images, audio, and molecular structures, requires fitting very flexible statistical models to the data distribution. Even in the age of deep neural networks, building such models is difficult because they typically require an intractable normalization procedure to represent a probability distribution. To address this challenge, we consider modeling the vector field of gradients of the data distribution (known as the score function), which does not require normalization and therefore can take full advantage of the flexibility of deep neural networks. I will show how to (1) estimate the score function from data with flexible deep neural networks and efficient statistical methods, (2) generate new data using stochastic differential equations and Markov chain Monte Carlo, and even (3) evaluate probability values accurately as in a traditional statistical model. The resulting method, called score-based generative modeling or diffusion modeling, achieves record performance in applications including image synthesis, text-to-speech generation, time series prediction, and point cloud generation, challenging the long-time dominance of generative adversarial networks (GANs) on many of these tasks. Furthermore, score-based generative models are particularly suitable for Bayesian reasoning tasks such as solving ill-posed inverse problems, yielding superior performance on several tasks in medical image reconstruction.