---
layout: post
title: "Generating LOD3 building models from structure-from-motion and semantic segmentation"
subtitle: "Geometrical digital twins for masonry buildings"
background: "/img/posts/post_LOD3/lod3_01.png"
---

# Generating LOD3 building models from structure-from-motion and semantic segmentation

[![Watch the video](/img/posts/post_LOD3/video_p3.png)](https://youtu.be/OdnjHHdyhlw)

This post refers to a method for computing geometrical digital twins as LOD3 models for buildings using a structure from motion and semantic segmentation. The methodology hereby implements was presented in the paper [Generating LOD3 building models from structure-from-motion and semantic segmentation" by Pantoja-Rosero et., al. (2022)](https://doi.org/10.1016/j.autcon.2022.104430). The repository containing the codes related with the method is publicly available in [LOD3_buildings](https://github.com/bgpantojar/LOD3_buildings). Datasets used in the publication can be downloaded at [LOD3_buildings dataset](https://zenodo.org/record/6651663#.YvUh-GFByEI)

![IMDb page](/img/posts/post_LOD3/lod3_02.png)

## Abstract

This paper describes a pipeline for automatically generating level of detail (LOD) models (digital twins), spe-
cifically LOD2 and LOD3, from free-standing buildings. Our approach combines structure from motion (SfM)
with deep-learning-based segmentation techniques. Given multiple-view images of a building, we compute a
three-dimensional (3D) planar abstraction (LOD2 model) of its point cloud using SfM techniques. To obtain LOD3
models, we use deep learning to perform semantic segmentation of the openings in the two-dimensional (2D)
images. Unlike existing approaches, we do not rely on complex input, pre-defined 3D shapes or manual inter-
vention. To demonstrate the robustness of our method, we show that it can generate 3D building shapes from a
collection of building images with no further input. For evaluating reconstructions, we also propose two novel
metrics. The first is a Euclidean–distance-based correlation of the 3D building model with the point cloud. The
second involves re-projecting 3D model facades onto source photos to determine dice scores with respect to the
ground-truth masks. Finally, we make the code, the image datasets, SfM outputs, and digital twins reported in
this work publicly available in https://github.com/eesd-epfl/LOD3_buildings and https://doi.org/10.5281/zenodo.6651663.
With this work we aim to contribute research in applications such as construction management, city planning,
and mechanical analysis, among others.
