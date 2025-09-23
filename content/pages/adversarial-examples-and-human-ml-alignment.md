---
content_type: page
description: Seminar contents.
draft: false
title: Adversarial Examples and Human-ML Alignment
uid: 97376f81-d49c-4d8c-bbba-a6e7d4d325a2
---
**Taught by:** *Shibani Santurkar, MIT (July 23, 2020)*

**Video:** {{% resource_link "aed4fe68-3275-43d2-a9aa-2530a6c3978b" "Adversarial Examples and Human-ML Alignment" %}}

**Description:**

Machine learning models today achieve impressive performance on challenging benchmark tasks. Yet these models remain remarkably brittle—small perturbations of natural inputs, known as adversarial examples, can severely degrade their behavior.

Why is this the case?

In this tutorial, we take a closer look at this question and demonstrate that the observed brittleness can be largely attributed to the fact that our models tend to solve classification tasks quite differently from humans. Specifically, viewing neural networks as feature extractors, we study how features extracted by neural networks may diverge from those used by humans, and how adversarially robust models can help to make progress towards bridging this gap.

**Speaker Bio:** Shibani Santurkar is a PhD student in the MIT EECS Department, advised by Aleksander Mądry and Nir Shavit. Her research has been focused on two broad themes: developing a precise understanding of widely-used deep learning techniques; and avenues to make machine learning methods robust and reliable. Prior to joining MIT, she received a bachelor's degree in electrical engineering from IIT Bombay. She is a recipient of the Google Fellowship in Machine Learning.

**Additional Resources:**

The tutorial will include demos—we will use Colab notebooks so please bring laptops along. In these demos, we will explore the brittleness of standard ML models by crafting adversarial perturbations, and use these as a lens to inspect the features models rely on.

{{% resource_link "069656ec-6c80-4fac-912f-eec3d1f6eb8a" "Github link for demos" %}}

Suggested reading (in order of importance):

- {{% resource_link "b63639e0-a9b9-4a17-88df-1f3b9700f281" "Adversarial examples" %}}
- {{% resource_link "e243a26a-56ac-48ca-83cc-0376d5f20e31" "Training robust models" %}}
- {{% resource_link "6232a863-567a-4f1c-96fd-b5688f062283" "ML models rely on imperceptible features" %}}
- Robustness as a feature prior
    - {{% resource_link "4a35c874-d3a7-4324-b146-b0a1bb87f32f" "*Robustness may be at odds with accuracy*" %}}
    - {{% resource_link "40b88911-2a2b-4890-b6a6-780457284146" "*Adversarial robustness as a prior for learned representations*" %}}