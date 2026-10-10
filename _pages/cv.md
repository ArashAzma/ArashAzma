---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education
* B.Sc. in Computer Engineering, Ferdowsi University of Mashhad (FUM), 2022 - 2026
  * GPA: 3.9/4.0
  * Ranked among the top 5% in the Department of Computer Engineering and top 10% in the Faculty of Engineering
  * Selected Member, Iran's National Elites Foundation (INEF)

## Experience
* 2025-02 - present: Data Scientist, [C1Tech Group](https://github.com/ArashAzma)
  * Develop a high-performance Persian STT system using PyTorch and distributed fine-tuning across 3 GPUs, reducing CER from 0.28 to 0.025
  * Open-source the resulting Whisper models on Hugging Face (1,200+ monthly downloads); release an accompanying benchmark dataset and leaderboard for reproducible Persian ASR evaluation
  * Design and implement an automated audio annotation pipeline leveraging ensembles of open-source AI models, curating over 5,000 hours of high-quality speech data
  * Fine-tune Qwen and Gemma large language models for intent detection and slot-filling in conversational AI systems, improving domain-specific intent classification accuracy by 18% (0.94 F1-score)
  * Design and deploy an end-to-end voice assistant integrating STT, LLM, and TTS with Node-RED-orchestrated AI agent workflows

* 2024-07 - present: Robotics Research Intern, Robot Perception Laboratory
  * Develop an end-to-end visual odometry pipeline using SIFT and ORB feature extraction paired with PnP for 3D-to-2D pose tracking
  * Evaluate and benchmark VO performance on the KITTI autonomous driving vision dataset
  * Develop a novel, plug-and-play convolutional attention module that improves spatial and channel-wise feature representation across diverse vision backbones

* 2023-09 - 2024-09: React Native Developer, GAP Company
  * Engineer and scale a production-grade social media platform (Twitter clone) onboarding and serving 100,000+ active users
  * Optimize mobile application performance and overhaul state management architecture, reducing app latency
  * Fast-tracked from a 3-month intensive internship to a full-time developer role

## Academic experience
* 2026-06 - present: Research Collaboration, FUM - Serverless Function Optimization
  * Collaborating with Dr. Saeid Abrishami and a PhD student on optimizing serverless cloud function placement using graph neural networks and large language models
  * Design a Heterogeneous Graph Transformer (HGT) encoder learning embeddings over the function-resource dependency graph
  * Condition Qwen3-8B on the HGT embeddings; train with LoRA supervised fine-tuning followed by GRPO reinforcement learning to optimize placement against cost and latency objectives

* 2025-11 - present: Research Project, FUM - Manuscript under review
  * Co-authoring a research manuscript with a Senior Researcher, currently under review at a top-tier computer vision venue, proposing a novel attention mechanism for deep neural networks
  * Investigating spatial and channel-wise feature dependencies to improve the robustness and interpretability of vision backbones

* 2024-09 - 2025-02: Research Assistant, FUM - Human Trajectory Forecasting
  * End-to-end computer vision pipeline for human detection and spatial-temporal trajectory prediction in high-altitude aerial imagery
  * Fine-tune and evaluate YOLOv11 object detection on the Stanford Drone Dataset (SDD) using OpenCV and Ultralytics
  * Benchmark generative and heatmap-based forecasting architectures (YNet vs Social-GAN); YNet lowers ADE to 11.49 and FDE to 20.23 for a 4-second prediction window

* 2025-02 - present: Teaching Assistant, FUM - Fundamentals of AI
  * Design and assess coursework and assignments on Q-learning and policy-based reinforcement learning
  * Facilitate RL tutorials and supervise undergraduate student projects
  * Mentor students in implementing AI algorithms and debugging machine learning workflows

* 2026-01 - present: Teaching Assistant, FUM - Computational Intelligence
  * Supervise projects focused on SVMs and Decision Tree algorithms
  * Mentor students in implementing machine learning algorithms from scratch and with industry-standard libraries

* 2023-09 - 2025-07: Lab Instructor, FUM - Fundamentals of Programming
  * Provide academic instruction and mentorship to 100+ undergraduate students in C programming
  * Deliver technical guidance on pointers, memory management, and algorithmic problem-solving
  * Facilitate laboratory sessions and evaluate programming assignments

## Skills
* **Artificial Intelligence & Machine Learning:** PyTorch, PyTorch Lightning, Hugging Face Transformers, LLMs, PEFT (LoRA), LangChain, vLLM, Reinforcement Learning, Computer Vision, Speech Recognition (STT), Text-to-Speech (TTS), GNN
* **Programming & Software Development:** Python, C++, React Native, React, FastAPI, OOP, Data Structures & Algorithms
* **Tools & Infrastructure:** Docker, Linux, Git/GitHub, Jira, Agile/Scrum Methodologies, Raspberry Pi, Multi-GPU Training Pipelines
* **Languages:** Fluent in English (TOEFL iBT: 102)
* **Soft Skills:** Cross-cultural communication and collaboration, problem-solving, critical thinking, project planning and management

## Publications
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Talks
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

## Teaching
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## References
* **Dr. Saeid Abrishami** - Faculty Member, Computer Engineering Department, Ferdowsi University of Mashhad - [s-abrishami@um.ac.ir](mailto:s-abrishami@um.ac.ir)
* **Dr. Fazl Ersi** - Faculty Member, Computer Engineering Department, Ferdowsi University of Mashhad - [ehsan.fazl@gmail.com](mailto:ehsan.fazl@gmail.com)
* **Dr. Ahad Harati** - Research Supervisor, Robot Perception Laboratory - [a.harati@um.ac.ir](mailto:a.harati@um.ac.ir)
* **Dr. Ali Mehrizi** - Research Supervisor, Human Trajectory Forecasting Project - [mehrizi@um.ac.ir](mailto:mehrizi@um.ac.ir)
