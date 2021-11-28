---
title: A Neural Network for Detailed Human Depth Estimation from a Single Image
publication_types:
  - "1"
authors:
  - Sicong Tang
  - Feitong Tan
  - Kelvin Cheng
  - Zhaoyang Li
  - Siyu Zhu
  - Ping Tan
author_notes:
  - Equal contribution
  - Equal contribution
publication: In *Proceedings of the IEEE/CVF International Conference on
  Computer Vision 2019*
publication_short: In *ICCV 2019*
abstract: This paper presents a neural network to estimate a detailed depth map
  of the foreground human in a single RGB image. The result captures geometry
  details such as cloth wrinkles, which are important in visualization
  applications. To achieve this goal, we separate the depth map into a smooth
  base shape and a residual detail shape and design a network with two branches
  to regress them respectively. We design a training strategy to ensure both
  base and detail shapes can be faithfully learned by the corresponding network
  branches. Furthermore, we introduce a novel network layer to fuse a rough
  depth map and surface normals to further improve the final result.
  Quantitative comparison with fused ground truth captured by real depth cameras
  and qualitative examples on unconstrained Internet images demonstrate the
  strength of the proposed method.
draft: false
featured: true
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
date: 2019-10-27T15:40:21.337Z
---
