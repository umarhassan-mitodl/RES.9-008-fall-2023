---
content_type: page
description: Seminar contents.
draft: false
title: 'Continuous-Time Deconvolutional Regression: A Method for Studying Continuous
  Dynamics in Naturalistic Data'
uid: 06d05b47-9a1c-4d16-a9a1-2fe643c158fe
---
**Taught by:** *Cory Shain, MIT (Feb 28, 2022)*

**Video:** {{% resource_link "fb689962-b096-4c70-8fa9-b621b88c9f4d" "Continuous-Time Deconvolutional Regression: A Method for Studying Continuous Dynamics in Naturalistic Data" %}}

**Abstract:** Naturalistic experiments are of growing interest to neuroscientists and cognitive scientists. Naturalistic data can be hard to analyze because critical events can occur at irregular intervals, and measured responses to those events can overlap and interact in complex ways. For example, words come quickly enough during naturalistic reading and listening that the brain responses to words likely overlap in time, and inherent variability in word durations can make these responses difficult to identify from data. In this tutorial, I will present continuous-time deconvolutional regression (CDR), a new approach to analyzing naturalistic time series. CDR uses machine learning to estimate impulse response functions from data, but, unlike established methods like finite impulse response modeling, these functions are defined in continuous time. CDR can therefore directly estimate event-related responses in a range of naturalistic experiment types, including fMRI, EEG/MEG, and behavioral measures. The tutorial will demonstrate how to define, fit, and evaluate CDR models, how to test hypotheses in the CDR framework, how to visualize patterns with CDR, and how CDR can be used to relax a range of assumptions about time series data. These steps can be run from the command line using an open-source Python library, with no need for users to write any code.

**Additional Resources:**

- {{% resource_link "a4b5a43d-18e0-497f-8c61-4c238f0854e6" "Sample data and models for the CDR tutorial" %}}. The files data.zip and models.zip need to be downloaded and extracted.
- CDR can be installed with either Anaconda or python+pip. To install with pip, run: [pip install]( https://github.com/coryshain/cdr/archive/refs/tags/v0.5.3.tar.gz).
- Conda installation instructions are available in {{% resource_link "b1a52789-3226-4f65-98ac-70ceb2a8c75b" "the readme" %}}.