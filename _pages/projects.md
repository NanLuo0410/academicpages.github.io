---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## VisionCube: 3D-Aware Vision-Language Model for Multi-Step Spatial Reasoning

**Role:** Co-first author  
**Period:** February 2025 – April 2025  
**Keywords:** 3D reconstruction, vision-language models, spatial reasoning, embodied planning, robotics simulation

VisionCube is a multimodal 3D perception and reasoning system designed for multi-step spatial reasoning in Rubik's Cube solving. The system integrates 3D-aware visual representations, language-based reasoning, and embodied action planning.

- Led the development of the **Cube3D** pipeline, using **Instant-NGP** and **Point Transformer** to reconstruct structured 3D representations from multi-view image datasets.
- Implemented a **Dual-loop VisionCoT** framework to integrate 3D-aware visual embeddings into **LLaMA**, enabling long-horizon spatial reasoning.
- Designed and implemented the **CubeCoT** benchmark, which contains structured Rubik's Cube states and multi-step reasoning trajectories.
- Achieved **100% / 100% / 90% accuracy** across different difficulty levels, outperforming baseline vision-language models including GPT-4V and Qwen2-VL.
- Deployed the system in the **RoboGuide** simulation environment with a robotic arm, demonstrating embodied planning ability in spatial reasoning and manipulation tasks.

[View publication]({{ site.baseurl }}/publication/2025-06-17-visioncube)

---

## Intelligent Shopping Guide System based on LLM and RAG

**Role:** Developer  
**Period:** February 2024 – May 2024  
**Keywords:** LLM, RAG, dialogue system, recommendation, full-stack development, vector database

This project is an e-commerce conversational AI system developed as my undergraduate thesis. The system aims to provide context-aware product recommendations and product question answering through multi-turn dialogue.

- Built a full-stack multi-turn conversational AI system by integrating a **LoRA-fine-tuned ChatGLM3-6B** model with a **Retrieval-Augmented Generation (RAG)** pipeline.
- Developed a **BERT-based intent recognition module** for query classification, achieving **97.3% accuracy** and supporting dynamic multi-intent dialogue management.
- Built an automated data pipeline using **Python** and **Selenium** to crawl, clean, and process more than **1,000 product entries**.
- Designed the backend using **Flask** and **PostgreSQL**, including product knowledge management, semantic retrieval, dialogue history, shopping cart, and order management modules.
- Used **BGE embeddings**, vector-based retrieval, and re-ranking strategies to improve the relevance of retrieved product information.
- Developed a responsive web interface using **Vue.js**, enabling interactive dialogue visualization and smooth integration with backend services.

---

## Human-centric 3D Reconstruction for Sports Videos

**Role:** Current research project  
**Period:** 2026 – present  
**Keywords:** computer vision, 3D reconstruction, human motion understanding, sports video analysis, multi-view reconstruction

This is my current research project on reconstructing and analyzing human motion from multi-view sports videos. The project focuses on human-centric 3D reconstruction under challenging sports scenarios, where the subject moves quickly and the available views are limited.

- Exploring methods for **human-centric 3D reconstruction** from multi-view sports video data.
- Investigating temporal consistency and reconstruction stability for moving humans in dynamic scenes.
- Analyzing how 3D structure and motion information can support downstream tasks such as human motion understanding and sports performance analysis.
- Currently experimenting with reconstruction pipelines and evaluating failure cases caused by viewpoint changes, motion blur, and inconsistent geometry.