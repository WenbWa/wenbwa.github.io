---
title: 'UniGraspTransformer: Simplified Policy Distillation for Scalable Dexterous Robotic Grasping - CVPR 2025'

summary: '**Wenbo Wang**, Fangyun Wei, Lei Zhou, Xi Chen, Lin Luo, Xiaohan Yi, Yizhong Zhang, Yaobo Liang, Chang Xu, Yan Lu, Jiaolong Yang, Baining Guo.'

tags:
  - Robotics
date: "2025-03-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: https://dexhand.github.io/UniGraspTransformer/

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart
  display: original

links:
- name: Arxiv Link
  url: https://arxiv.org/pdf/2412.02699/
- name: Project Website
  url: https://dexhand.github.io/UniGraspTransformer/
- name: CVPR 2025

---

We introduce UniGraspTransformer, a universal Transformer-based network for dexterous robotic grasping that simplifies training while enhancing scalability and performance. Unlike prior methods such as UniDexGrasp++, which require complex, multi-step training pipelines, UniGraspTransformer follows a streamlined process: first, dedicated policy networks are trained for individual objects using reinforcement learning to generate successful grasp trajectories; then, these trajectories are distilled into a single, universal network. Our approach enables UniGraspTransformer to scale effectively, incorporating up to 12 self-attention blocks for handling thousands of objects with diverse poses. Additionally, it generalizes well to both idealized and real-world inputs, evaluated in state-based and vision-based settings. Notably, UniGraspTransformer generates a broader range of grasping poses for objects in various shapes and orientations, resulting in more diverse grasp strategies. Experimental results demonstrate significant improvements over state-of-the-art, UniDexGrasp++, across various object categories, achieving success rate gains of 3.5%, 7.7%, and 10.1% on seen objects, unseen objects within seen categories, and completely unseen objects, respectively, in the vision-based setting.