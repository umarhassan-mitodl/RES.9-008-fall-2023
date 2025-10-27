---
content_type: page
description: Seminar contents.
draft: false
title: 'GLMsingle: A Toolbox for Improving Single-Trial fMRI Response Estimates'
uid: bb9c9cf5-1575-46d8-9603-b8c97adb26dc
---
**Taught by:** *Jacob Prince, MIT (April 28, 2022)*

**Video:** {{% resource_link "4d6d9d5b-ccac-463a-844b-a3b717ba2492" "GLMsingle: A Toolbox for Improving Single-Trial fMRI Response Estimates" %}}

**Description:** Advances in modern artificial intelligence have inspired a paradigm shift in human neuroscience, yielding large-scale functional magnetic resonance imaging (fMRI) datasets that provide high-resolution brain responses to tens of thousands of naturalistic visual stimuli. Because such experiments necessarily involve brief stimulus durations and few repetitions of each stimulus, achieving sufficient signal-to-noise ratio can be a major challenge. This tutorial will introduce GLMsingle, a scalable, user-friendly toolbox available in MATLAB and Python that enables accurate estimation of single-trial fMRI responses ({{% resource_link "dab47367-ad17-44cc-bfd4-411e3e0e97fc" "glmsingle.org" %}}). Requiring only fMRI time-series data and a design matrix as inputs, GLMsingle integrates three techniques for improving the accuracy of trial-wise general linear model (GLM) beta estimates. First, for each voxel, a custom hemodynamic response function (HRF) is identified from a library of candidate functions. Second, cross-validation is used to derive a set of noise regressors from voxels unrelated to the experimental paradigm. Third, to improve the stability of beta estimates for closely spaced trials, betas are regularized on a voxel-wise basis using ridge regression. Validation analyses show that GLMsingle substantially improves the reliability of beta estimates across a visually responsive cortex and that these improvements translate into tangible benefits for higher-level analyses relevant to systems and cognitive neuroscience. 

This tutorial will provide a practical overview of GLMsingle, aimed at making the toolbox accessible to a wide range of fMRI users. We will review key concepts in GLM modeling of fMRI data, discuss how the different components of GLMsingle seek to optimize different steps in the signal estimation procedure and walk users through a Google Colab demo illustrating the ease of applying GLMsingle to example fMRI data.

**Additional Resources:**

- {{% resource_link "11d53086-fe2f-4aee-9794-2359a476d44d" "Slides" %}}
- {{% resource_link "5f33d5b9-cf7f-4d0b-b6f2-6bbd0b46dcdd" "GitHub repository" %}}
- {{% resource_link "ad04a574-cfbc-4db1-b495-3b981e929d25" "Preprint" %}}
- {{% resource_link "744e86fd-16d8-4e28-bdf8-5740a7dd6e9e" "Example scripts" %}}