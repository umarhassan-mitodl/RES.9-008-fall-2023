---
content_type: page
description: Seminar contents.
draft: false
title: 'GLMsingle: A Toolbox for Improving Single-Trial fMRI Response Estimates'
uid: bb9c9cf5-1575-46d8-9603-b8c97adb26dc
---
**Taught by:** *Jacob Prince, MIT (April 28, 2022)*

**Video:** {{% resource_link "f1aa51c0-e66b-4fb5-a650-3c7ca2ad351b" "GLMsingle: A Toolbox for Improving Single-Trial fMRI Response Estimates" %}}

**Description:** Advances in modern artificial intelligence have inspired a paradigm shift in human neuroscience, yielding large-scale functional magnetic resonance imaging (fMRI) datasets that provide high-resolution brain responses to tens of thousands of naturalistic visual stimuli. Because such experiments necessarily involve brief stimulus durations and few repetitions of each stimulus, achieving sufficient signal-to-noise ratio can be a major challenge. This tutorial will introduce GLMsingle, a scalable, user-friendly toolbox available in MATLAB and Python that enables accurate estimation of single-trial fMRI responses ({{% resource_link "bf936eaa-297e-44ec-8744-cadf86b63738" "glmsingle.org" %}}). Requiring only fMRI time-series data and a design matrix as inputs, GLMsingle integrates three techniques for improving the accuracy of trial-wise general linear model (GLM) beta estimates. First, for each voxel, a custom hemodynamic response function (HRF) is identified from a library of candidate functions. Second, cross-validation is used to derive a set of noise regressors from voxels unrelated to the experimental paradigm. Third, to improve the stability of beta estimates for closely spaced trials, betas are regularized on a voxel-wise basis using ridge regression. Validation analyses show that GLMsingle substantially improves the reliability of beta estimates across a visually responsive cortex and that these improvements translate into tangible benefits for higher-level analyses relevant to systems and cognitive neuroscience. 

This tutorial will provide a practical overview of GLMsingle, aimed at making the toolbox accessible to a wide range of fMRI users. We will review key concepts in GLM modeling of fMRI data, discuss how the different components of GLMsingle seek to optimize different steps in the signal estimation procedure and walk users through a Google Colab demo illustrating the ease of applying GLMsingle to example fMRI data.

**Additional Resources:**

- {{% resource_link "424d66bd-f1b2-4256-8a1c-055a31faa6b8" "Slides" %}}
- {{% resource_link "f2f37acf-d96c-4341-813c-6c66bbcff817" "GitHub repository" %}}
- {{% resource_link "b80b5a67-b719-47c8-90b7-39f7eb04abbd" "Preprint" %}}
- {{% resource_link "1ac603e8-bb79-45c7-aaf2-e93ff2f22cda" "Example scripts" %}}