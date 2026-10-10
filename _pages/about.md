---
permalink: /
title: "Arash Azma - Robotics, Computer Vision and AI"
layout: home
author_profile: true
interests:
  - Computer vision
  - Large language models
  - Speech processing
  - Robotics
redirect_from:
  - /about/
  - /about.html
---

{% include home-publications.html %}

<section class="home__section" aria-labelledby="research">
<h2 id="research">Research</h2>
<ul class="home__list">
{% include home-project-items.html slugs="persian-whisper-stt" %}
<li>
<a class="home__item-title" href="{{ site.baseurl }}/portfolio/visual-odometry/">Robotics and visual odometry</a>
<p class="home__item-meta">Computer Vision Engineer, Robot Perception Lab &middot; Nov 2024 - present</p>
<p class="home__item-desc">Research on robust trajectory reconstruction, supervised by Dr. Ahad Harati. I built an end-to-end visual odometry pipeline that pairs SIFT and ORB feature extraction with Perspective-n-Point (PnP) for 3D-to-2D pose tracking, benchmarked on the KITTI autonomous driving dataset. I also co-developed LUSA, a plug-and-play channel-spatial attention module for vision backbones, accepted at ICCKE 2026. Robotics is the direction I want to build my graduate research around.</p>
</li>
{% include home-project-items.html slugs="persian-tts-models" %}
<li>
<a class="home__item-title" href="{{ site.baseurl }}/publication/2026-06-serverless-hgt-qwen/">Serverless function optimization with GNNs and LLMs</a>
<p class="home__item-meta">Research collaboration with Dr. Saeid Abrishami, FUM &middot; 2026 - present</p>
<p class="home__item-desc">Placing serverless cloud functions using graph neural network (HGT) embeddings that condition a Qwen3-8B LLM, trained with LoRA supervised fine-tuning and GRPO reinforcement learning against cost and latency objectives.</p>
</li>
<li>
<a class="home__item-title" href="{{ site.baseurl }}/portfolio/human-trajectory-forecasting/">Trajectory forecasting</a>
<p class="home__item-meta">Research Assistant, FUM &middot; 2024 - 2025</p>
<p class="home__item-desc">An end-to-end computer vision pipeline for human detection and trajectory prediction in aerial imagery: YOLOv11 detection on the Stanford Drone Dataset and a comparison of YNet and Social-GAN forecasting, with YNet reaching ADE 11.49 / FDE 20.23 for a 4-second prediction window.</p>
</li>
</ul>
</section>

<section class="home__section" aria-labelledby="experience">
<h2 id="experience">Work experience</h2>
<ul class="home__list">
<li>
<a class="home__item-title" href="https://c1tech.co/">AI R&amp;D Engineer, C1Tech Group</a>
<p class="home__item-meta">Full-time &middot; Apr 2025 - present</p>
<p class="home__item-desc">Built a full-stack Persian voice assistant deployed on Raspberry Pi. Used PyTorch distributed training to reduce the speech-to-text character error rate to 0.025 and optimized VibeVoice TTS. Curated a large-scale speech dataset with automated AI pipelines, and fine-tuned Qwen and Gemma LLMs to reach a 0.94 F1-score in intent detection.</p>
</li>
<li>
<span class="home__item-title">Computer Vision Engineer, Robot Perception Lab</span>
<p class="home__item-meta">Part-time &middot; Mashhad, Iran (remote) &middot; Nov 2024 - present</p>
<p class="home__item-desc">Worked in a computer vision lab specializing in visual odometry, implementing algorithms for motion estimation, pose recovery and 3D trajectory reconstruction from image sequences. Co-authored LUSA, a plug-and-play convolutional attention module for vision backbones, accepted at ICCKE 2026.</p>
</li>
<li>
<span class="home__item-title">React Native Developer, Gap Messenger</span>
<p class="home__item-meta">Full-time &middot; Hybrid &middot; Sep 2023 - Sep 2024</p>
<p class="home__item-desc">Contributed to the development and software design of a high-performance, Twitter-like microblogging platform using React Native, serving 100,000+ active users.</p>
</li>
</ul>
</section>

{% include home-teaching.html %}

<section class="home__section home__section--quiet" markdown="1">

## At a glance

* **Education:** B.Sc. in Computer Engineering, Ferdowsi University of Mashhad - GPA 3.9/4.0, top 5% of department, selected member of Iran's National Elites Foundation (INEF).
* **Skills:** PyTorch, PyTorch Lightning, Hugging Face Transformers, PEFT (LoRA), LangChain, vLLM, reinforcement learning, computer vision, STT/TTS, GNNs, Python, C++, React Native, Docker, multi-GPU training pipelines.

My full [CV]({{ site.baseurl }}/files/ArashAzma_CV.pdf) is available as a PDF.

</section>

<section class="home__section home__section--quiet" markdown="1">

## Contact

Email: [{{ site.author.email }}](mailto:{{ site.author.email }})

</section>
