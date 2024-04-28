---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

## Prompt-based Image Generation
- **Technologies:** Diffusion model, CLIP, PyTorch, Kubernetes
- **Duration:** Apr 2024 -- Present
- Implemented Transformer and the Denoising Diffusion Probabilistic Model (DDPM) from scratch using PyTorch.
- Leveraging CLIP to condition the generation of images based on textual prompts.

## Image Inpainting using GAN
- **Technologies:** Computer Vision, CNNs, PyTorch
- **Duration:** Apr 2023 -- Jun 2023
- Developed an algorithm inspired by Google’s MagicEraser to remove specified objects from images.
- Utilized instance segmentation and Pix2Pix model for image reconstruction, achieving background recovery.
- [GitHub](https://github.com/rkg266/instance-eraser-Pix2Pix)

## Tensor Library in C++
- **Technologies:** OpenCL, High-Performance Computing, Object-Oriented
- **Duration:** Mar 2024 -- Present
- Created a simple tensor library with core operations mirroring PyTorch tensors, including tensor indexing and slicing.
- Engineered memory-efficient broadcasting for matrix and vector operations, by avoiding data duplication.
- Utilized OpenCL and Intel oneAPI framework for parallel programming, accelerating matrix multiplication and aiming to introduce computation graph support for machine learning models.
- [GitHub](https://github.com/rkg266/Tensors-FromScratch-Cpp)

## Haptic Game Controller
- **Technologies:** Haptic Interfaces, HW-SW co-design, low-latency, C#, Unity
- **Duration:** Nov 2023 -- Dec 2023
- Led a collaborative effort to build a 2-DoF game controller from inception to completion.
- Integrated Unity with Arduino to enable realistic force feedback from interacting with a 3D virtual environment.
- Demonstrated adeptness in HW-SW co-design, reducing latency and delivering a seamless gaming experience.
- [GitHub](https://github.com/rkg266/haptic-steer)

## Super-Resolution from Limited Measurements
- **Technologies:** Generative models, MATLAB, Python
- **Duration:** Dec 2023 -- Apr 2024
- Improved the spike sequence-search speed by 54% by incorporating Median-split Search Tree.
- Developing a model to estimate neuron firing rates from low-rate calcium fluorescence data, overcoming imaging equipment limitations, by leveraging downsampling within a Bayesian generative model framework.
- Applying expectation-maximization algorithm for the model's parameter estimation, where the posterior probability is approximated using variational inference.

## SLAM & Motion Planning
- **Technologies:** Perception, Sensor fusion, Constrained and Unconstrained Optimization, Python, Object-oriented
- **Duration:** Jan 2023 - May 2023
- Implemented sensor fusion with IMU and camera data from a mobile vehicle, using Extended Kalman Filter. [GitHub](https://github.com/rkg266/visual-inertial-slam)
- Implemented Particle Filter-Based SLAM, leveraging LIDAR data for environment mapping. [GitHub](https://github.com/rkg266/particle-filter-slam)
- Implemented dynamic programming for dynamic 2D environments for shortest path and obstacle avoidance. [GitHub](https://github.com/rkg266/robot-shortest-path-dynamic-programming)
- Implemented and compared A* and RRT algorithms for generating optimized safe paths in complex environments. [GitHub](https://github.com/rkg266/robot-motion-planning)
