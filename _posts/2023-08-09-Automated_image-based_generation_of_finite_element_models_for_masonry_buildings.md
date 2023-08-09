---
layout: post
title: "Automated image-based generation of finite element models for masonry buildings"
subtitle: "Finite element models for buildings"
background: "/img/posts/post_fem/fem_02.png"
---

# Automated image-based generation of finite element models for masonry buildings

[![Watch the video](/img/posts/post_fem/video_p5.png)](https://youtu.be/M8GGQnfmEdA)

This post refers to a method for computing finite element models for masonry buildings using solid and macro-elements. The hereby methodology was presented in the paper ["Automated image-based generation of finite element models for masonry buildings" by Pantoja-Rosero et., al. (2023)](https://doi.org/10.1007/s10518-023-01726-7). The repository containing the codes related with the method is publicly available in [FEM_buildings](https://github.com/bgpantojar/FEM_buildings). Datasets used in the publication can be downloaded at [FEM_buildings dataset](https://doi.org/10.5281/zenodo.8094306)

![IMDb page](/img/posts/post_fem/fem_01.png)

## Abstract

To predict the response of masonry buildings to various types of loads, engineers use finite element models, specifically solid-element and macro-element models. For predicting masonry responses to seismic events in particular, equivalent frame models—a subcategory of macro-element models—are a common choice because of their low computational cost. However, an existing bottleneck in modeling pipelines is generating the geometry of the model, which is currently a slow and laborious process that is done manually using computer-aided design tools. In this paper, we address this by automating the modelling process using recent advancements in computer vision and machine learning. We present an image-based end-to-end pipeline that automatically generates finite element meshes for solid-element and equivalent-frame models of the outer walls of free-standing historical masonry buildings. As the input, our framework requires RGB images of the buildings that are processed using structure-from-motion algorithms, which create 3D geometries, and convolutional neural networks, which segment the openings and their corners. These layers are then combined to generate level of detail models. We tested our pipeline on structures with irregular surface geometries and opening layouts. While generating the solid element mesh from the level of detail model is straightforward, generating equivalent frame models required algorithms for segmenting the façade and the meshing. Experts in the field analyzed the generated equivalent frame models and determined them to be useful for numerical modeling. These finite element geometries will be invaluable for future predictions of the seismic response of damaged and undamaged buildings. The codes and dataset are publicly available for future studies and benchmarking (https://github.com/eesd-epfl/FEM_buildings and https://doi.org/10.5281/zenodo.8094306).

![IMDb page](/img/posts/post_fem/fem_02.png)

![IMDb page](/img/posts/post_fem/fem_03.png)
