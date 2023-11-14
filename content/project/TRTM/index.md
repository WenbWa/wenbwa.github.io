---
title: 'TRTM: Template-based Reconstruction and Target-oriented Manipulation of Cloths'
summary: An example of using the in-built project page.

summary: 'Wenbo Wang, Gen Li, Miguel Zamora, Stelian Coros. (ICRA 2024 Under Review)'
tags:
  - Computer Vision
date: "2023-09-12T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: https://wenbwa.github.io/TRTM/

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart


links:
- name: Arxiv Link
  url: https://arxiv.org/abs/2308.04670
- name: Project Website
  url: https://wenbwa.github.io/TRTM/


# # links:
# #   - icon: twitter
# #     icon_pack: fab
# #     name: Follow
# #     url: https://twitter.com/georgecushen
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''

# # Slides (optional).
# #   Associate this project with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
# #   Otherwise, set `slides = ""`.
# slides: example
---

abstract: Achieving precise reconstruction and manipulation of the crumpled cloths is challenging due to the high dimensionality of cloth models, as well as the limited observation at self-occluded regions. We leverage the recent progress in the field of single-view human reconstruction to template-based reconstruct crumpled cloths from their top-view depth observations only, with our proposed sim-real registration protocols. In contrast to previous implicit cloth representations, our reconstruction mesh explicitly describes the positions and visibilities of the entire cloth mesh vertices, enabling more efficient dual-arm and single-arm target-oriented manipulations. Experiments demonstrate that our TRTM system can be applied to daily cloths that have similar topologies as our template mesh, but with different shapes, sizes, patterns, and physical properties.