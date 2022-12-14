---
layout: post
title: "Image-based geometric digital twinning for stone masonry elements"
subtitle: "Generating models for numerical simulation of stonme masonry elements built in laboratory"
background: "/img/posts/post_gdt_sme/gdt_sme_0.png"
---

# Generating LOD3 building models from structure-from-motion and semantic segmentation

This post refers to a method for generating geometrical digital twins for stone masonry elements using multiple-view images. The methodology hereby implemented was presented in the paper ["Image-based geometric digital twinning for stone masonry elements" by Pantoja-Rosero et., al. (2022)](https://doi.org/10.1016/j.autcon.2022.104632). The repository containing the codes related with the method is publicly available in [Stone masonry GDT](https://github.com/eesd-epfl/stone_masonry_GDT). Datasets used in the publication can be downloaded at [Stone masonry GDT dataset](https://doi.org/10.5281/zenodo.7266587)

![IMDb page](/img/posts/post_gdt_sme/gdt_sme_1.gif)

![IMDb page](/img/posts/post_gdt_sme/gdt_sme_2.gif)

## Abstract

We present an image-based pipeline for generating geometrical digital twins (GDTs) of stone masonry elements with detail down to the stone level. For this purpose, we acquire RGB images of the individual stones and of the wall during the construction phase. In our framework, we use structure from motion (SfM) to first generate 3D source and destination models, which are then registered to form the GDT through non-linear least squares and 2D point feature correspondences detected on the SfM images. This method contrasts with traditional techniques that register point clouds using 3D point descriptors. Because of the robustness of image feature descriptors, we found that using 2D instead of 3D point features facilitates the automation of the GDT generation. To benchmark our algorithm, we compared the results through an Euclidean–distance-based proposed metric with a known 3D textured model from which images were synthetically generated. We show the robustness and feasibility of our method for full size elements, wherein GDTs were generated for dry-stone and stone-mortar systems. This study allows researchers to produce accurate representations of the 3D geometry of walls built for experimental research, reducing therefore uncertainties related to the stone size, shape and arrangement to a minimum when comparing 3D numerical simulations of these walls to experimental results. Codes and data sets are publicly available (https://github.com/eesd-epfl/stone_masonry_GDT and https://doi.org/10.5281/zenodo.7266587).

![IMDb page](/img/posts/post_gdt_sme/gdt_sme_3.png)

![IMDb page](/img/posts/post_gdt_sme/gdt_sme_4.png)

![IMDb page](/img/posts/post_gdt_sme/gdt_sme_5.png)
