---
layout: post
title: "Damage-augmented digital twins towards the automated inspection of buildings"
subtitle: "Damage augmented digital twins for buildings damage assessment"
background: "/img/posts/post_LOD3/dadt_02.png"
---

# Generating LOD3 building models from structure-from-motion and semantic segmentation

This post refers to a method for computing damage augmented digital twins as 3D models for buildings. The hereby methodology was presented in the paper ["Damage-augmented digital twins towards the automated inspection of buildings" by Pantoja-Rosero et., al. (2023)](https://doi.org/10.1016/j.autcon.2023.104842). The repository containing the codes related with the method is publicly available in [DADT_buildings](https://github.com/bgpantojar/DADT_buildings). Datasets used in the publication can be downloaded at [DADT_buildings dataset](https://doi.org/10.5281/zenodo.7767478)

![IMDb page](/img/posts/post_LOD3/dadt_01.png)

## Abstract

Current procedures for the rapid inspection of buildings and infrastructure are subjective, time-consuming, and cumbersome to document, necessitating new technologies to automate the process and eliminate these shortcomings. Fortunately, recent developments in imaging devices and artificial intelligence, such as computer vision, provide the necessary tools for this, though they are not yet integrated into infrastructure applications. In this paper, we propose an end-to-end pipeline that generates damage-augmented digital twins for buildings at LOD3, including geometrical information as well as data pertaining to damage condition and its characterization. Our framework incorporates multiple-view images to (1) create a level of detail model, (2) segment damage information, and (3) characterize damage. The core of the method is the structure from motion, which is used to reconstruct the building scene, and machine-learning models that segment and characterize damage. In contrast to current practices, our method does not require manual intervention, generates lightweight models, and can be applied to a wide range of assets. The results generated with our pipeline represent a significant step towards an automated infrastructure damage assessment. We intend to expand our work in the future to include real-time applications and applications to other types of infrastructure. Codes and data sets are publicly available (https://github.com/eesd-epfl/DADT_buildings and https://doi.org/10.5281/zenodo.7767478).
