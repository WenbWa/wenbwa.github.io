---
title: 'MobileManiBench: Simplifying Model Verification for Mobile Manipulation'

summary: 'Wenbo Wang, Fangyun Wei, QiXiu Li, Xi Chen, Yaobo Liang, Chang Xu, Jiaolong Yang, Baining Guo.'

tags:
  - ECCV 2026
date: "2026-06-18T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: https://dexhand.github.io/MobileManiBench/

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart
  display: original

# links:
# - name: Arxiv Link
#   url: https://arxiv.org/pdf/2412.02699/
# - name: Project Website
#   url: https://dexhand.github.io/UniGraspTransformer/
# - name: CVPR 2025

---

Vision-language-action models have advanced robotic manipulation but remain constrained by reliance on the large, teleoperation-collected datasets dominated by the static, tabletop scenes. We propose a simulation-first framework to verify VLA architectures before real-world deployment and introduce MobileManiBench, a large-scale benchmark for mobile-based robotic manipulation. Built on NVIDIA Isaac Sim and powered by reinforcement learning, our pipeline autonomously generates diverse manipulation trajectories with rich annotations (language instructions, multi-view RGB-depth-segmentation images, synchronized object/robot states and actions). MobileManiBench features 2 mobile platforms (parallel-gripper and dexterous-hand robots), 2 synchronized cameras (head and right wrist), 630 objects in 20 categories, 5 skills (open, close, pull, push, pick) with over 100 tasks performed in 100 realistic scenes, yielding 300K trajectories. This design enables controlled, scalable studies of robot embodiments, sensing modalities, and policy architectures, accelerating research on data efficiency and generalization. We benchmark representative VLA models and report insights into perception, reasoning, and control in complex simulated environments.
