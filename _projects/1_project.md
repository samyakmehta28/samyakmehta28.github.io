---
layout: page
title: Final Year Bachelor's Thesis
category: ML & AI
importance: 1
description: Experimenting with different OCR models on various datasets, implemented a line segmentation and text classification module, and developed an NLP-based post-processing approach that significantly reduces character and word error rates in OCR outputs.
img: assets/img/project_1.png
---

This was my thesis project completed under the guidance of Dr. Anirban Dasgupta, in collaboration with my batchmate Aishik Rakshit, during the final year of my undergraduate studies at the Indian Institute of Technology, Guwahati.
The [paper](https://arxiv.org/pdf/2307.04245) for this project is available in IEEE Xplore Library for all the latest papers relating to NeRF-SLAM.

# [A Novel Pipeline for Improving Optical Character Recognition through Post-processing Using Natural Language Processing](https://arxiv.org/pdf/2307.04245)

The paper proposes a novel pipeline for improving optical character recognition (OCR) accuracy through post-processing using natural language processing (NLP) techniques.
While many OCR solutions have improved with deep learning, achieving both high accuracy and real-time performance on unconstrained datasets remains challenging. Issues like variations in font, similar-looking characters, and case sensitivity can lead to errors. The paper aims to address these limitations by combining OCR with NLP post-processing.

### Module A: OCR Engine

This module handles:

- Line segmentation - Breaking multi-line documents into single lines
- Text classification - Classifying each line as printed or handwritten
- OCR model - Performing OCR on each line using an appropriate model

We evaluate two popular OCR models:

- Transformer-based OCR (Tr-OCR)
- PaddlePaddle OCR (PP-OCR)

These OCR models are tested on various datasets including:

- Born-Digital Images
- Incidental Scene Text
- License Plates
- Single Line Handwritten Text

### Module B: NLP Engine

This module applies NLP techniques to post-process and improve the OCR output:

- ByT5 - A byte-level transformer model
- BART - A denoising autoencoder for sequence-to-sequence tasks
- Alpaca-LORA - An instruction-tuned LLM

The NLP models are trained on synthetic OCR-degraded text generated from the OSCAR corpus.

### Key innovations

- Applying NLP models to correct OCR errors
- An end-to-end pipeline combining segmentation, classification, OCR and post-processing

Results show significant reductions in character error rate (CER) and word error rate (WER) compared to baseline OCR outputs.
The paper demonstrates how combining computer vision and NLP techniques can improve OCR accuracy while maintaining real-time performance. This approach could enable more robust digitization of handwritten and printed documents across various applications.
