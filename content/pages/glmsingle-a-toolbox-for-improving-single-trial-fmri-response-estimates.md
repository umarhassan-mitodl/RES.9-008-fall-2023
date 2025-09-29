---
content_type: page
description: Seminar contents.
draft: false
title: 'GLMsingle: A Toolbox for Improving Single-Trial fMRI Response Estimates'
uid: bb9c9cf5-1575-46d8-9603-b8c97adb26dc
---
**Taught by:** *Jacob Prince, MIT (April 28, 2022)*

**Video:** [GLMsingle: A Toolbox for Improving Single-Trial fMRI Response Estimates](https://youtu.be/OvxOUn0-tn0)

**Description:** Advances in modern artificial intelligence have inspired a paradigm shift in human neuroscience, yielding large-scale functional magnetic resonance imaging (fMRI) datasets that provide high-resolution brain responses to tens of thousands of naturalistic visual stimuli. Because such experiments necessarily involve brief stimulus durations and few repetitions of each stimulus, achieving sufficient signal-to-noise ratio can be a major challenge. This tutorial will introduce GLMsingle, a scalable, user-friendly toolbox available in MATLAB and Python that enables accurate estimation of single-trial fMRI responses ([glmsingle.org](https://github.com/cvnlab/GLMsingle#readme)). Requiring only fMRI time-series data and a design matrix as inputs, GLMsingle integrates three techniques for improving the accuracy of trial-wise general linear model (GLM) beta estimates. First, for each voxel, a custom hemodynamic response function (HRF) is identified from a library of candidate functions. Second, cross-validation is used to derive a set of noise regressors from voxels unrelated to the experimental paradigm. Third, to improve the stability of beta estimates for closely spaced trials, betas are regularized on a voxel-wise basis using ridge regression. Validation analyses show that GLMsingle substantially improves the reliability of beta estimates across a visually responsive cortex and that these improvements translate into tangible benefits for higher-level analyses relevant to systems and cognitive neuroscience. 

This tutorial will provide a practical overview of GLMsingle, aimed at making the toolbox accessible to a wide range of fMRI users. We will review key concepts in GLM modeling of fMRI data, discuss how the different components of GLMsingle seek to optimize different steps in the signal estimation procedure and walk users through a Google Colab demo illustrating the ease of applying GLMsingle to example fMRI data.

**Additional Resources:**

- [Slides](https://osf.io/7q5y3/)
- [GitHub repository](https://github.com/cvnlab/GLMsingle)
- [Preprint](https://www.biorxiv.org/content/10.1101/2022.01.31.478431v1)
- [Example scripts](https://github.com/cvnlab/GLMsingle/tree/main/examples)