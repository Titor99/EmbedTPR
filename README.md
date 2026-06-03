# EmbedTPR: Open-Vocabulary Fine-Grained Person Retrieval

## 📄 Abstract

Text-based person retrieval (TPR) is essential for video surveillance, but existing methods rely on closed vocabularies and identity-centric evaluation, limiting their real-world applicability.

We address the Open‑Vocabulary Fine‑Grained TPR (OV‑FG‑TPR) setting, where queries may contain unseen terms such as brand names, subculture slang, or subjective descriptions. We propose EmbedTPR, an information fusion framework that combines three complementary sources: semantic parsing from a frozen multimodal large language model (MLLM), visual embeddings from a pre‑trained cross‑modal encoder, and explicit attribute matching.

To enable systematic evaluation, we introduce a three‑level protocol: conventional closed‑set benchmarks, a new fine‑grained test set (FineGrained‑1282) with 1,282 images across 23 categories (actions, logos, styles), and human expert assessment.

Experiments show that EmbedTPR achieves competitive closed‑set performance (e.g., 62.8% Rank‑1 on CUHK‑PEDES) while substantially outperforming zero‑shot baselines like CLIP on open‑vocabulary fine‑grained queries—improving mAP from 6.2% to 46.2% and Mean Opinion Score from 2.1 to 4.2 out of 5.

## 📢 Open Source Release Plan

> ⏳ **The code, models, the FineGrained‑1282 dataset, and the MRAG‑PED benchmark will be fully open‑sourced upon acceptance of the corresponding journal paper.**

We are committed to reproducible research. Until the official release, please watch this repository for updates or check the current preprint for technical details.
