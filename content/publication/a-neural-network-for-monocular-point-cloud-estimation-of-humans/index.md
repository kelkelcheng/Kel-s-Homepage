---
title: A Neural Network for Monocular Point Cloud Estimation of Humans
publication_types:
  - "7"
authors:
  - Kelvin Cheng
abstract: This work introduces a neural network for estimating the detailed 3D
  structure of the foreground human in a single RGB image, which can capture
  geometry details like cloth wrinkles. The outputs of the network can
  potentially be fused together for various applications, such as telepresence
  and 3D scanning. The neural network is designed with the insight of separating
  the 3D shape into a smooth base shape and a residual detail shape such that
  each component is trained by an independent sub-network. For training the
  neural network, we also capture our own data and apply non-rigid registration
  techniques for post-processing. Furthermore, we introduce a novel refinement
  technique based on non-rigid alignment to improve the temporal consistency of
  the final results. Quantitative comparison with fused ground truth captured by
  real depth cameras and qualitative examples on test images demonstrate the
  strength of the proposed method.
draft: false
featured: false
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
date: 2019-05-01T14:49:27.292Z
---
