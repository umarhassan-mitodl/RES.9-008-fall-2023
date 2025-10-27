---
content_type: page
description: Seminar contents.
draft: false
title: Adversarial Examples and Human-ML Alignment
uid: 97376f81-d49c-4d8c-bbba-a6e7d4d325a2
---
**Taught by:** *Shibani Santurkar, MIT (July 23, 2020)*

**Video:** {{% resource_link "e7096730-f24d-4742-a2a9-20aa26c7e021" "Adversarial Examples and Human-ML Alignment" %}}

**Description:**

Machine learning models today achieve impressive performance on challenging benchmark tasks. Yet these models remain remarkably brittle—small perturbations of natural inputs, known as adversarial examples, can severely degrade their behavior.

Why is this the case?

In this tutorial, we take a closer look at this question and demonstrate that the observed brittleness can be largely attributed to the fact that our models tend to solve classification tasks quite differently from humans. Specifically, viewing neural networks as feature extractors, we study how features extracted by neural networks may diverge from those used by humans, and how adversarially robust models can help to make progress towards bridging this gap.

**Speaker Bio:** Shibani Santurkar is a PhD student in the MIT EECS Department, advised by Aleksander Mądry and Nir Shavit. Her research has been focused on two broad themes: developing a precise understanding of widely-used deep learning techniques; and avenues to make machine learning methods robust and reliable. Prior to joining MIT, she received a bachelor's degree in electrical engineering from IIT Bombay. She is a recipient of the Google Fellowship in Machine Learning.

**Additional Resources:**

The tutorial will include demos—we will use Colab notebooks so please bring laptops along. In these demos, we will explore the brittleness of standard ML models by crafting adversarial perturbations, and use these as a lens to inspect the features models rely on.

{{% resource_link "3aee498b-76c4-4a58-8c6f-b16865981a6e" "Github link for demos" %}}

Suggested reading (in order of importance):

- {{% resource_link "59c87cab-ef2b-4e49-bdb8-55cdb9485240" "Adversarial examples" %}}
- {{% resource_link "2b7077ba-789b-4f0a-8795-f2c71492c458" "Training robust models" %}}
- {{% resource_link "28a6beaa-d0fc-48a6-a8d2-ebda545189af" "ML models rely on imperceptible features" %}}
- Robustness as a feature prior
    - {{% resource_link "3598c341-6e16-4c5a-90b9-83ba4723781b" "*Robustness may be at odds with accuracy*" %}}
    - {{% resource_link "5991914f-cdf1-4e0d-b1bb-06b1304d2c10" "*Adversarial robustness as a prior for learned representations*" %}}