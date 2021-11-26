---
title: Towards Adversarially Robust and Domain Generalizable Stereo Matching by
  Rethinking DNN Feature Backbones
publication_types:
  - "3"
authors:
  - Kelvin Cheng
  - Christopher Healey
  - Tianfu Wu
abstract: Stereo matching has recently witnessed remarkable progress using Deep
  Neural Networks (DNNs). But, how robust are they? Although it has been
  well-known that DNNs often suffer from adversarial vulnerability with a
  catastrophic drop in performance, the situation is even worse in stereo
  matching. This paper first shows that a type of weak white-box attacks can
  overwhelm state-of-the-art methods. The attack is learned by a proposed
  stereo-constrained projected gradient descent (PGD) method in stereo matching.
  This observation raises serious concerns for the deployment of DNN-based
  stereo matching. Parallel to the adversarial vulnerability, DNN-based stereo
  matching is typically trained under the so-called simulation to reality
  pipeline, and thus domain generalizability is an important problem. This paper
  proposes to rethink the learnable DNN-based feature backbone towards
  adversarially-robust and domain generalizable stereo matching by completely
  removing it for matching. In experiments, the proposed method is tested in the
  SceneFlow dataset and the KITTI2015 benchmark, with promising results. We
  compute the matching cost volume using the classic multi-scale census
  transform (i.e., local binary pattern) of the raw input stereo images,
  followed by a stacked Hourglass head sub-network solving the matching problem.
  It significantly improves the adversarial robustness, while retaining accuracy
  performance comparable to state-of-the-art methods. It also shows better
  generalizability from simulation (SceneFlow) to real (KITTI) datasets when no
  fine-tuning is used.
draft: false
featured: true
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
date: 2021-11-26T23:29:28.151Z
---
