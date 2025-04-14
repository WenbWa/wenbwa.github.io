---
title: 'Gaussian Garments: Reconstructing Simulation-Ready Clothing with Photo-Realistic Appearance from Multi-View Video'

summary: Boxiang Rong*, Artur Grigorev*, Wenbo Wang, Michael J. Black, Bernhard Thomaszewski, Christina Tsalicoglou, Otmar Hilliges.

tags:
  - Computer Vision
date: "2024-09-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: https://eth-ait.github.io/Gaussian-Garments/

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- name: Arxiv Link
  url: https://arxiv.org/abs/2409.08189/
- name: Project Website
  url: https://eth-ait.github.io/Gaussian-Garments/
- name: 3DV 2025

---

We introduce Gaussian Garments, a novel approach for reconstructing realistic-looking, simulation-ready garment assets from multi-view videos. Our method represents garments with a combination of a 3D mesh and a Gaussian texture that encodes both the color and high-frequency surface details. This representation enables accurate registration of garment geometries to multi-view videos and helps disentangle albedo textures from lighting effects. Furthermore, we demonstrate how a pre-trained Graph Neural Network (GNN) can be fine-tuned to replicate the real behavior of each garment. The reconstructed Gaussian Garments can be automatically combined into multi-garment outfits and animated with the fine-tuned GNN.
