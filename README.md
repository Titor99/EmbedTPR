# EmbedTPR: Open-Vocabulary Fine-Grained Person Retrieval

## 📄 Abstract

Text-based person retrieval (TPR) is crucial for video surveillance and public safety, yet existing methods suffer from **closed‑vocabulary assumptions**, **identity‑centric metrics**, and **underutilization of multimodal large language models (MLLMs)**. In this work, we focus on the challenging **Open‑Vocabulary Fine‑Grained TPR (OV‑FG‑TPR)** setting, where queries contain novel terms (brand names, subculture slang, subjective descriptions) never seen during training.

We propose **EmbedTPR**, an **information fusion framework** that integrates three complementary sources:  
1. Semantic parsing from a **frozen MLLM** (zero‑shot understanding of open‑vocabulary concepts).  
2. Visual embeddings from a **trainable cross‑modal encoder**.  
3. Explicit **attribute matching** scores for fine‑grained alignment.  

To properly evaluate this setting, we introduce a **three‑level evaluation protocol**:  
- Level 1: Conventional closed‑set benchmarks.  
- Level 2: **FineGrained‑1282**, a newly constructed test set with 1,282 images across 23 fine‑grained categories (Actions, Logos, Styles).  
- Level 3: Human expert assessment (Mean Opinion Score).  

Experiments show that EmbedTPR dramatically outperforms strong CLIP‑based baselines on open‑vocabulary fine‑grained queries (**e.g., 92.5% vs. 47.83% FG‑Hit@5**), while maintaining competitive closed‑set performance.

## 📢 Open Source Release Plan

> ⏳ **The code, models, the FineGrained‑1282 dataset, and the MRAG‑PED benchmark will be fully open‑sourced upon acceptance of the corresponding journal paper.**

We are committed to reproducible research. Until the official release, please watch this repository for updates or check the current preprint for technical details.
