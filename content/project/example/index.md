---
slides: example
url_pdf: ""
summary: Master Thesis on robustness in deep learning and semantic segmentation.
authors: []
url_video: ""
date: 2023-11-24T19:31:07.319Z
external_link: ""
url_slides: ""
title: Master Thesis: Robust Techniques to Enhance Label Propagation in Noisy Oversegmented
  Point clouds and 2D Images
subtitle: Master Thesis
tags:
  - Deep Learning
  - Computer Vision
  - Semantic Segmentation
  - Learning with limited supervision
  - Learning with multi-modal data
  - Thesis
links:
  - icon: pdf
    icon_pack: fab
    name: Thesis
image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart
url_code: ""
---

Semantic segmentation of point clouds plays a crucial role in 3D scene understanding, but obtaining large annotated datasets for this task is time-consuming and error-prone. To address this challenge, weakly supervised learning techniques have been explored, focusing mainly on the 3D domain while neglecting the potential of incorporating complementary information from the 2D domain. In this master’s thesis, we adopt an approach that integrates both 2D images and 3D point clouds to enhance weakly supervised point cloud semantic segmentation. By bidirectionally interacting features from these modalities, we leverage the fine-grained texture in 2D images and the geometric information in 3D point clouds to benefit each other. To incorporate additional supervisory signals, we begin by oversegmenting the point clouds and images and assigning unique labels to the resulting supervoxels and superpixels based on our
proposed initial label assignment strategy. We then propagate these labels to unlabeled points or pixels within the corresponding supervoxel or superpixel. However, the oversegmented regions suffer from imprecise object boundaries, leading to inaccuracies in the propagated labels and label noise. To address this issue, we introduce a novel noise-robust framework that integrates robust loss functions and innovative loss adjustment strategies. These techniques enhance the learning capacity of the network and enable robust learning with limited annotations. Additionally, we incorporate multi-modality and develop a novel point/pixel-wise confidence calculation
algorithm in the oversegmented point clouds and images to obtain reliable labels based on distance metrics. This approach effectively handles challenges related to ambiguous object boundaries and significantly improves the robustness of the framework even with sparse labels. We conduct extensive experiments under various weakly supervised schemes on benchmark datasets, including ScanNetV2 and 2D-3D-S. The results demonstrate that our noise-robust framework outperforms baseline methods both quantitatively and qualitatively, showcasing its effectiveness in addressing the limitations of weakly supervised point cloud semantic segmentation.
