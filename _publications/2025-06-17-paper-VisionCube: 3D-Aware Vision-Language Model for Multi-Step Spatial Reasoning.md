---
title: "VisionCube: 3D-Aware Vision-Language Model for Multi-Step Spatial Reasoning"
collection: publications
category: conferences
permalink: /publication/2025-06-17-paper-VisionCube:3D-Aware Vision-Language Model for Multi-Step Spatial Reasoning
excerpt: 'This paper introduces VisionCube, a 3D-aware vision-language model that solves Rubik’s Cube by integrating multi-view spatial reasoning, task decomposition, and memory-guided decision-making, achieving exceptional accuracy and real-time robotic execution.'
date: 2025-06-17
venue: 'CVPR Workshops'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2025W/eLVM/papers/Wang_VisionCube_3D-Aware_Vision-Language_Model_for_Multi-Step_Spatial_Reasoning_CVPRW_2025_paper.pdf'
citation: 'Feiyang Wang, <strong>Nan Luo</strong>, Wangyu Wu; <i>Proceedings of the Computer Vision and Pattern Recognition Conference (CVPR) Workshops</i>, 2025, pp. 3270-3279'
---

Solving Rubik's Cube efficiently requires advanced spatial reasoning, sequential planning, and adaptive decision-making. Traditional solvers rely on predefined algorithms and hand-crafted heuristics, limiting their generalizability across diverse cube states. In this work, we introduce VisionCube, a multimodal embodied AI system designed for Rubik's Cube solving. VisionCube incorporates multi-view spatial reasoning, geometric priors, and cross-modal fusion to enhance its understanding of 3D cube transformations. To support this, we construct CubeCoT, a dataset containing annotated Rubik's Cube states and structured multi-step solving trajectories at three difficulty levels. VisionCube employs a Dual-Loop VisionCoT framework for iterative reasoning and a Memory Stream to improve long-horizon planning.We integrate 3D feature extraction via Instant-NGP, PointNet, and Point Transformer, ensuring robust spatial perception. Our model achieves 100% accuracy on low- and medium-difficulty tasks and 80% on high-difficulty tasks, significantly outperforming MiniGPT-4 and LLaVA by (35--60% in accuracy for complex multi-step planning).

