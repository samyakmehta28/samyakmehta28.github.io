---
layout: page
title: Tranformer Encoder and Decoder Tasks
description: This project involves developing a transformer encoder for politician speech prediction, training a GPT-like decoder for speech generation, and experimenting with architecture variations to enhance model accuracy and perplexity.
img: assets/img/project_6.png
importance: 6
category: ML & AI
---

This was my project for the course Statistical NLP, completed under the guidance of Professor Ndapa Nakashole, during the SP24 quarter of my graduate studies at the University of California, San Diego.
The project report can be found [here](https://github.com/samyakmehta28/CSE256_PA2/blob/master/CSE256_PA2_report.pdf) and the code can be found in the github repository [here](https://github.com/samyakmehta28/CSE256_PA2).

# Encoder and Decoder Transformer Architecture

This project involves developing a transformer encoder for politician speech prediction and training a GPT-like decoder for speech generation.
This project evaluates different positional encoding techniques and tokenization strategies in transformer models, focusing on their impact on language modeling and classification tasks. The study aims to improve model performance by experimenting with alternative architectures and hyper-parameter tuning.

### Introduction:

Transformers have revolutionized natural language processing by effectively handling sequences. This project explores three positional encoding strategies: Absolute Positional Encoding, Non-Positional Embedding (NOPE), and AliBi Embedding. Additionally, it investigates the effect of varying tokenization methods on model performance. The goal is to enhance the model's ability to handle tasks requiring a deep understanding of sequences and contextual relationships.

### Datasets:

- Language Modeling Task: Training and testing datasets consisting of speeches from different presidents, including George W. Bush, Barack Obama, and others.
- Classification Task: Datasets used for comparing the performance of models with different positional encodings on tasks such as sentiment analysis.

### Methodology:

The study involved:

- Encoder and Decoder Models: Evaluating models with different positional encodings across multiple epochs.
- Tokenization Strategies: Comparing performance using default and custom tokenizers.
- Hyper-parameter Tuning: Fine-tuning parameters such as learning rates, number of layers, and tokenization methods to optimize model performance.

### Key Findings:

- Positional Encoding:

  - AliBi: Enhanced long-range dependency understanding, outperforming traditional Absolute Positional Encoding in language modeling tasks.
  - NOPE: Focused on token semantics, leading to better results in classification tasks.

- Tokenization:
  Custom Tokenizer: Improved model accuracy and performance, achieving a final test accuracy of 86.67%.
- Hyper-parameter Tuning:
  Fine-tuning led to smoother training curves and better model generalization across different tasks.

### Analysis and Categorization of Errors:

- Errors were categorized into:

  - Positional Misinterpretation: Challenges with long sequences in Absolute Positional Encoding.
  - Tokenization Issues: Difficulties in handling diverse text structures due to suboptimal tokenization.

### Conclusion:

The project demonstrates the significance of choosing appropriate positional encodings and tokenization methods in transformer models. The findings highlight the potential of alternative embeddings like AliBi and NOPE in improving model performance for specific tasks. The study provides valuable insights for future enhancements in natural language processing models.
