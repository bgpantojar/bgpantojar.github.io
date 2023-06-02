---
layout: post
title: "TOPO-Loss for continuity-preserving crack detection using deep learning"
subtitle: "Image crack segmentation in masonry buildings damaged by earthquake activity"
background: "/img/posts/post_cracks/tcd_4.png"
---

# TOPO-Loss for continuity-preserving crack detection using deep learning

![](https://youtu.be/QSlvpPg4bmE)

This post refers to a method for crack detection using topological loss function. The methodology hereby implemented was presented in the paper ["TOPO-Loss for continuity-preserving crack detection using deep learning" by Pantoja-Rosero et., al. (2022)](https://doi.org/10.1016/j.conbuildmat.2022.128264). The repository containing the codes related with the method is publicly available in [Topo crack detection](https://github.com/bgpantojar/topo_crack_detection). Datasets used in the publication can be downloaded at [Topo crack detection dataset](https://zenodo.org/record/6769028#.YvUrXGFByEI)

![IMDb page](/img/posts/post_cracks/tcd_3.png)

## Abstract

We present a method for segmenting cracks in images of masonry buildings damaged by earthquakes. Existing
methods of crack detection fail to preserve the continuity of cracks, and their performance deteriorates
with imprecise training labels. We address these problems by adapting an approach previously proposed
for reconstructing roads in aerial images, in which a Convolutional Neural Network is trained with a loss
function specifically designed to encourage the continuity of thin structures and to accommodate imprecise
annotations. We evaluate combinations of three loss functions (the Mean Squared Error, the Dice loss and the
new connectivity-oriented loss) on two datasets using TernausNet, a deep network shown to attain state-of-the-
art accuracy in crack detection. We herein show that combining these three losses significantly improves the
topology of the predictions quantitatively and qualitatively. We also propose a new continuity metric, named
Cracks Per Patch (CPP), and share a new dataset of images of earthquake-affected urban scenes accompanied by
crack annotations. The dataset and implementations are publicly available for future studies and benchmarking
(https://github.com/eesd-epfl/topo_crack_detection and https://doi.org/10.5281/zenodo.6769028).
