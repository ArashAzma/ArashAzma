---
title: "Serverless Function Placement with GNN-Conditioned Language Models"
collection: publications
category: manuscripts
permalink: /publication/2026-06-serverless-hgt-qwen
excerpt: 'A Heterogeneous Graph Transformer encoder learns embeddings over the function-resource dependency graph to condition Qwen3-8B, trained with LoRA SFT + GRPO for cost- and latency-optimal serverless placement.'
date: 2026-06-01
venue: 'Manuscript in preparation (ongoing research, FUM)'
paperurl: ''
citation: 'Azma, A., Abrishami, S., et al. (2026). "Serverless Function Placement with GNN-Conditioned Language Models." <i>In preparation</i>.'
---

Ongoing research collaboration with Dr. Saeid Abrishami and a PhD student on optimizing serverless cloud function placement using graph neural networks and large language models.

A Heterogeneous Graph Transformer (HGT) encoder learns embeddings over the function-resource dependency graph, capturing structural and type-specific relationships between functions, triggers, and compute resources. The HGT-produced embeddings condition Qwen3-8B, which is then trained with LoRA supervised fine-tuning followed by GRPO reinforcement learning to optimize placement decisions against cost and latency objectives.
