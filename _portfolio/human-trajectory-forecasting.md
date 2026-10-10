---
title: "Trajectory Forecasting"
excerpt: "YOLOv11 detection on the Stanford Drone Dataset + YNet forecasting (ADE 11.49 / FDE 20.23, 4-second window)."
collection: portfolio
order: 4
---

An end-to-end computer vision pipeline for automated human detection and spatial-temporal trajectory prediction in high-altitude aerial imagery.

* Fine-tuned and evaluated YOLOv11 object detection models on the Stanford Drone Dataset (SDD), utilizing OpenCV and the Ultralytics framework for streamlined frame extraction and dataset preprocessing
* Benchmarked generative and heatmap-based forecasting architectures (YNet vs Social-GAN) for multi-modal path prediction in crowded environments
* Achieved significant improvement with YNet, capturing long-term temporal dependencies to lower the Average Displacement Error (ADE) to 11.49 and Final Displacement Error (FDE) to 20.23 for a 4-second prediction window
