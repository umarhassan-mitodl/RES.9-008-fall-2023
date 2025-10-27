---
content_type: page
description: Seminar contents.
draft: false
title: Unsupervised Discovery of Temporal Sequences in High-Dimensional Datasets
uid: 0079c2df-b4a5-4482-a01f-5909bbf1c319
---
**Taught by:** *Emily Mackevicius and Andrew Bahle, MIT*

**Video:** {{% resource_link "ac33590f-c0cd-45d7-b583-e4b901733f42" "Unsupervised Discovery of Temporal Sequences in High-Dimensional Datasets" %}} (1:14:24)

**Description:** The ability to identify interpretable, low-dimensional features that capture the dynamics of large-scale neural recordings is a major challenge in neuroscience. Dynamics that include repeated temporal patterns (which we call sequences), are not succinctly captured by traditional dimensionality reduction techniques such as principal components analysis (PCA) and non-negative matrix factorization (NMF). The presence of neural sequences is commonly demonstrated using visual display of trial-averaged firing rates. However, the field suffers from a lack of task-independent, unsupervised tools for consistently identifying sequences directly from neural data, and cross-validating these sequences on held-out data. This tutorial introduces a tool called seqNMF, for unsupervised discovery of temporal sequences in high-dimensional datasets, which extends a convolutional NMF technique. It provides a framework for extracting sequences from a dataset and is easily cross-validated to assess the significance of each extracted factor. This tutorial provides code to apply seqNMF to several neural and behavioral datasets and provides demo code.

**Slides:** {{% resource_link "f91ac7f7-d9a3-4b1e-97a5-d0dc5923d2af" "Unsupervised Discovery of Neural Sequences in Large-Scale Recordings (PDF)" %}}

**Additional Resources:**

- GitHub: {{% resource_link "08486716-6b74-40c7-baca-f519ebd93998" "Code and datasets" %}} for seqNMF tool and its application to neural data
- Mackevicius, E. L., Bahle, A. H., Williams, A. H., Gu, S., Denissenko, N. I., Goldman, M. S., and Fee, M. S. (2018) {{% resource_link "869e64ff-bbed-4737-a6c3-27476a534ba4" "\"Unsupervised Discovery of Temporal Sequences in High-Dimensional Datasets, With Applications to Neuroscience.\"" %}} {{% resource_link "374b1cdf-a655-4425-a120-233a667ddf5f" "Early version of paper" %}}.