---
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
slides: ""
url_pdf: ""
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
publication: In *Proceedings of the IEEE/CVF International Conference on Computer Vision*
summary: ""
url_dataset: ""
url_project: ""
publication_short: In *ICCV*
url_source: ""
url_video: ""
title: A neural network for detailed human depth estimation from a single image
doi: ""
featured: true
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: iccv_img.png
date: 2013-07-01T00:00:00Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
