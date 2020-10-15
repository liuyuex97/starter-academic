---
title: Point Cloud Based Window Frame and Other Indoor Objects Detection
date: 2020-10-10T06:27:04.754Z
draft: false
featured: false
external_link: https://github.com/liuyuex97/24787-Final-Project
image:
  filename: inainting.png
  focal_point: Smart
  preview_only: false
---
In this project we present a complete pipeline to work directly with noisy raw point cloud data for classification and semantic segmentation tasks. The pipeline consists of two main components. The first component iteratively denoises the raw data based on Constrained Nonlinear Least Squares (NLSQ) normal estimation. The estimated surface normal is used to relocate noisy points in order to reduce outliers along the surface normals. The refined point cloud data produces finer surfaces and in turn further improves denoising and normal estimation results upon subsequent iterations. Our denoising algorithm successfully removed most outliers, while still retained important features of the point cloud data such as edges, corners, etc.
