---
layout: post
title: "Automatic Removal of Non-Architectural Elements in 3D Models of Historic Buildings with Language Embedded Radiance Fields"
subtitle: "Removal of building elements with LeRF"
background: "/img/posts/post_lerf/lerf_01.png"
---

# Automatic Removal of Non-Architectural Elements in 3D Models of Historic Buildings with Language Embedded Radiance Fields

This post refers to a method for removing non-architectural elements from 3D models of historic buildings using Language Embedded Radiance Fields (LeRF). The methodology was presented in the paper ["Automatic Removal of Non-Architectural Elements in 3D Models of Historic Buildings with Language Embedded Radiance Fields" by Rusnak et., al. (2024)](https://doi.org/10.3390/heritage7060157). 

![IMDb page](/img/posts/post_lerf/lerf_02.jpg)

## Abstract

Neural radiance fields have emerged as a dominant paradigm for creating complex 3D environments incorporating synthetic novel views. However, 3D object removal applications utilizing neural radiance fields have lagged behind in effectiveness, particularly when open set queries are necessary for determining the relevant objects. One such application area is in architectural heritage preservation, where the automatic removal of non-architectural objects from 3D environments is necessary for many downstream tasks. Furthermore, when modeling occupied buildings, it is crucial for modeling techniques to be privacy preserving by default; this also motivates the removal of non-architectural elements. In this paper, we propose a pipeline for the automatic creation of cleaned, architectural structure only point clouds utilizing a language embedded radiance field (LERF) with a specific application toward generating suitable point clouds for the structural integrity assessment of occupied buildings. We then validated the efficacy of our approach on the rooms of the historic Sion hospital, a national historic monument in Valais, Switzerland. By using our automatic removal pipeline on the point clouds of rooms filled with furniture, we decreased the average earth mover’s distance (EMD) to the ground truth point clouds of the physically emptied rooms by 31 percent. The success of our research points the way toward new paradigms in architectural modeling and cultural preservation.

![IMDb page](/img/posts/post_lerf/lerf_04.jpg)
![IMDb page](/img/posts/post_lerf/lerf_03.jpg)