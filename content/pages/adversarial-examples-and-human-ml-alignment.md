---
content_type: page
description: Seminar contents.
draft: false
title: Adversarial Examples and Human-ML Alignment
uid: 97376f81-d49c-4d8c-bbba-a6e7d4d325a2
---
**Taught by:** *Shibani Santurkar, MIT (July 23, 2020)*

**Video:** [Adversarial Examples and Human-ML Alignment](https://youtu.be/fzusr-VdPxw)

**Description:**

Machine learning models today achieve impressive performance on challenging benchmark tasks. Yet these models remain remarkably brittle—small perturbations of natural inputs, known as adversarial examples, can severely degrade their behavior.

Why is this the case?

In this tutorial, we take a closer look at this question and demonstrate that the observed brittleness can be largely attributed to the fact that our models tend to solve classification tasks quite differently from humans. Specifically, viewing neural networks as feature extractors, we study how features extracted by neural networks may diverge from those used by humans, and how adversarially robust models can help to make progress towards bridging this gap.

**Speaker Bio:** Shibani Santurkar is a PhD student in the MIT EECS Department, advised by Aleksander Mądry and Nir Shavit. Her research has been focused on two broad themes: developing a precise understanding of widely-used deep learning techniques; and avenues to make machine learning methods robust and reliable. Prior to joining MIT, she received a bachelor's degree in electrical engineering from IIT Bombay. She is a recipient of the Google Fellowship in Machine Learning.

**Additional Resources:**

The tutorial will include demos—we will use Colab notebooks so please bring laptops along. In these demos, we will explore the brittleness of standard ML models by crafting adversarial perturbations, and use these as a lens to inspect the features models rely on.

[Github link for demos](https://github.com/MadryLab/AdvEx_Tutorial)

Suggested reading (in order of importance):

- [Adversarial examples](https://arxiv.org/abs/1412.6572)
- [Training robust models](https://arxiv.org/abs/1706.06083)
- [ML models rely on imperceptible features](https://arxiv.org/abs/1905.02175)
- Robustness as a feature prior
    - [*Robustness may be at odds with accuracy*](https://arxiv.org/abs/1805.12152)
    - [*Adversarial robustness as a prior for learned representations*](https://arxiv.org/abs/1906.00945)