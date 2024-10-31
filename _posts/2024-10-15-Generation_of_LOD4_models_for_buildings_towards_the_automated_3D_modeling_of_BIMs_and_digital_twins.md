---
layout: post
title: "Generation of LOD4 models for buildings towards the automated 3D modeling of BIMs and digital twins"
subtitle: "Generation LOD4 models of buildings from images"
background: "/img/posts/post_LOD4/lod4_01.png"
---

# Generation of LOD4 models for buildings towards the automated 3D modeling of BIMs and digital twins

This post refers to a method for generating LOD4 models of buildings using images, structure from motion, semantinc segmentation and 3D registration. The methodology was presented in the paper ["Generation of LOD4 models for buildings towards the automated 3D modeling of BIMs and digital twins" by Pantoja-Rosero et., al. (2024)](https://doi.org/10.1016/j.autcon.2024.105822). 

![IMDb page](/img/posts/post_LOD4/lod4_02.png)

## Abstract

An image-based methodology is presented for the automatic generation of geometric building models at LOD4, incorporating both interior and exterior geometrical information. Existing approaches often focus on simplified geometries for either exteriors or interiors, leading to integration challenges due to data complexity and processing demands. This methodology addresses these challenges by utilizing three structure-from-motion models: one for the building exterior, one for the interior, and one for the entrance. The exterior and interior data are processed separately using planar primitives, and the models are subsequently aligned through a 3D point cloud registration method based on 2D image features. This ensures a unified coordinate system and accurate generation of the LOD4 model. The framework achieved a mean relative error of 3.06% and a mean absolute error of 0.05 m, underscoring its robustness for applications such as numerical modeling, construction management, and structural health monitoring, making it valuable for further advancements in building information models and digital twins. 

![IMDb page](/img/posts/post_LOD4/lod4_03.png)
![IMDb page](/img/posts/post_LOD4/lod4_04.png)