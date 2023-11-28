---
abstract: >
  Semantic segmentation of point clouds plays a crucial role in 3D scene
  understanding,

  but obtaining large annotated datasets for this task is time-consuming and error-prone.

  To address this challenge, weakly supervised learning techniques have been explored,

  focusing mainly on the 3D domain while neglecting the potential of incorporating

  complementary information from the 2D domain. In this master’s thesis, we adopt

  an approach that integrates both 2D images and 3D point clouds to enhance weakly

  supervised point cloud semantic segmentation. By bidirectionally interacting features

  from these modalities, we leverage the fine-grained texture in 2D images and the geometric information in 3D point clouds to benefit each other. To incorporate additional

  supervisory signals, we begin by oversegmenting the point clouds and images and

  assigning unique labels to the resulting supervoxels and superpixels based on our

  proposed initial label assignment strategy. We then propagate these labels to unlabeled

  points or pixels within the corresponding supervoxel or superpixel. However, the

  oversegmented regions suffer from imprecise object boundaries, leading to inaccuracies in the propagated labels and label noise. To address this issue, we introduce

  a novel noise-robust framework that integrates robust loss functions and innovative

  loss adjustment strategies. These techniques enhance the learning capacity of the

  network and enable robust learning with limited annotations. Additionally, we incorporate multi-modality and develop a novel point/pixel-wise confidence calculation

  algorithm in the oversegmented point clouds and images to obtain reliable labels based

  on distance metrics. This approach effectively handles challenges related to ambiguous object boundaries and significantly improves the robustness of the framework

  even with sparse labels. We conduct extensive experiments under various weakly

  supervised schemes on benchmark datasets, including ScanNetV2 and 2D-3D-S. The

  results demonstrate that our noise-robust framework outperforms baseline methods

  both quantitatively and qualitatively, showcasing its effectiveness in addressing the

  limitations of weakly supervised point cloud semantic segmentation.
slides: ""
url_pdf: https://mervekarali.com/publication/conference-paper/conference-paper.pdf
publication_types:
  - "7"
authors:
  - Fatma Merve Karali
author_notes: []
publication: ""
summary: This master's thesis explores weakly supervised point cloud semantic
  segmentation by integrating information from both 2D images and 3D point
  clouds. The approach leverages bidirectional feature interaction between
  modalities, overcoming challenges of sparse annotations by incorporating
  supervisory signals through oversegmentation. To mitigate label noise, a novel
  noise-robust framework is introduced, integrating robust loss functions and
  innovative loss adjustment strategies. The proposed approach, validated on
  benchmark datasets like ScanNetV2 and 2D-3D-S, demonstrates superior
  quantitative and qualitative performance, showcasing its efficacy in enhancing
  weakly supervised point cloud semantic segmentation.
url_dataset: https://github.com/ScanNet/ScanNet
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: Robust Techniques to Enhance Label Propagation in Noisy Oversegmented
  Point Clouds and 2D Images
subtitle: Master Thesis
doi: ""
featured: true
tags:
  - Deep Learning
  - Computer Vision
  - Master Thesis
  - Robustness
  - Multi-modal data
  - Learning With Limited Supervision
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: featured.png
date: 2023-08-03T00:00:00.000Z
url_slides: ""
publishDate: 2023-08-03T00:00:00.000Z
url_poster: ""
url_code: ""
---
