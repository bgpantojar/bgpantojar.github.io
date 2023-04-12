---
layout: post
title: "Determining crack kinematics from imaged crack patterns"
subtitle: "Defining propagation mode 1 or 2 in cracks based on its kinematics"
background: "/img/posts/post_kinematics/ck_02.png"
---

# Determining crack kinematics from imaged crack patterns

This post refers to a method for computing crack kinematics using a binary mask that represents a segmented crack. The methodoly hereby implementes was presented in the paper ["Determing crack kinematics from imaged crack patterns"](https://doi.org/10.1016/j.conbuildmat.2022.128054) by Pantoja-Rosero et., al. The repository containing the codes related with the method is publicly available in [Crack Kinematics](https://github.com/bgpantojar/crack_kinematics). Datasets used in the publication can be downloaded at [Crack Kinematics dataset](https://zenodo.org/record/6632071#.YvUu0GFByEI)

![IMDb page](/img/posts/post_kinematics/ck_01.png)
![IMDb page](/img/posts/post_kinematics/ck_02.png)

## Abstract

Determining the relationship between the cause of damage and the subsequent structural behavior of infrastructure systems requires an accurate characterization of the propagation of cracks, which represents the evolution of the damage state. When no information about the cause of damage is available, kinematic approaches can be used to describe the motion of crack contours. Current image-based approaches to derive crack kinematics use digital image correlation (DIC) on a set of sequential images as the crack propagates. However, DIC is invasive in that the structure surfaces must be painted with random speckle patterns, limiting its use primarily to controlled experiments. In this paper, we propose a novel image-based methodology for computing crack opening in Mode I or Mode II. As an input, this method takes a binary image from a semantic segmentation of an image of a crack pattern. This binary image is used to detect the opposite edges along the crack, which are then registered using an optimization algorithm based on the Euclidean transformation model and non-linear least squares. As a final output, this method produces displacement maps in the tangential and normal directions to the crack skeleton. To demonstrate its performance, we validate our methodology first with synthetic crack patterns and then with real crack patterns. Because this methodology for determining crack openings requires only simple data (just a binary crack pattern image), it is straightforward, robust, and adaptable, thus contributing to the development of structural image-based damage assessments. The computational codes and datasets are available to the public for future research and benchmarking on https://github.com/eesd-epfl/crack_kinematics and https://doi.org/10.5281/zenodo.6632071.

![IMDb page](/img/posts/post_kinematics/ck_08.png)
![IMDb page](/img/posts/post_kinematics/ck_09.png)
