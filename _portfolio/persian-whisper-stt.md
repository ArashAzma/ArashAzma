---
title: "Persian Whisper Models (Persian STT)"
excerpt: "Open-source Persian Whisper models fine-tuned at C1Tech Group (CER 0.28 → 0.025). Whisper small ranks first on all four benchmarks of the Open Persian ASR Leaderboard, and the 74M-parameter Whisper base outperforms Whisper large-v3. 1,200+ monthly downloads, with a benchmark dataset and leaderboard."
collection: portfolio
order: 1
featured: true
home: research
figure: true
image: 'whisper-base-common-voice.png'
image_alt: 'Bar chart of word and character error rate on the Common Voice dataset: C1Tech Whisper base scores far lower than OpenAI Whisper large-v3, Vosk 0.5, NVIDIA FastConformer and OpenAI Whisper base and small.'
links:
  - label: "Whisper small"
    url: "https://huggingface.co/C1Tech/whisper_small_persian"
  - label: "Whisper base"
    url: "https://huggingface.co/C1Tech/whisper_base_persian"
  - label: "Benchmark dataset"
    url: "https://huggingface.co/datasets/C1Tech/Persian-ASR-Benchmark"
  - label: "Leaderboard"
    url: "https://huggingface.co/spaces/C1Tech/Open_Persian_ASR_Leaderboard"
---

A high-performance Persian speech recognition system built at C1Tech Group using PyTorch and distributed fine-tuning of Whisper across 3 GPUs, reducing the character error rate from 0.28 to 0.025. The models are open-source on [Hugging Face](https://huggingface.co/C1Tech) and reach 1,200+ monthly downloads.

**Results.** On the Open Persian ASR Leaderboard, which is maintained by C1Tech Group, Whisper small ranks first on all four benchmarks (Persian-ASR-Benchmark, FLEURS, Common Voice and MANA). The much smaller Whisper base (74M parameters) also outperforms OpenAI Whisper large-v3 (1,550M parameters) on all four.

| Word error rate (lower is better) | Parameters | Persian-ASR-Benchmark | FLEURS | Common Voice | MANA |
| --- | --- | --- | --- | --- | --- |
| **C1Tech Whisper small** | 244M | **0.071** | **0.072** | **0.042** | **0.093** |
| C1Tech Whisper base | 74M | 0.162 | 0.103 | 0.082 | 0.108 |
| OpenAI Whisper large-v3 | 1,550M | 0.228 | 0.178 | 0.238 | 1.649 |
| Best other open Persian model | - | 0.214 | 0.106 | 0.065 | 0.152 |

* Trained on an automated audio annotation pipeline that uses ensembles of open-source AI models and curated over 5,000 hours of high-quality speech data
* Released with the [Persian-ASR-Benchmark](https://huggingface.co/datasets/C1Tech/Persian-ASR-Benchmark) dataset: 3 hours of 16 kHz audio from audiobooks, YouTube and other public sources, collected recently to avoid overlap with training data, with normalized Persian text
* Released with the [Open Persian ASR Leaderboard](https://huggingface.co/spaces/C1Tech/Open_Persian_ASR_Leaderboard) for reproducible Persian ASR evaluation
