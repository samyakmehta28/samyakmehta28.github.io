---
layout: page
title: Logicator
description: Logicator is a proposed model to improve logical reasoning in large language models by using structured data and Retrieval-Augmented Generation (RAG), significantly enhancing performance on family relationship puzzles and seating arrangements compared to baseline models like GPT-3.5-turbo.
img: assets/img/project_5.jpg
importance: 5
category: ML & AI
---

This was my course project for the course Advanced Data Driven Text Mining, completed under the guidance of Professor Jingbo Shang, in collaboration with my batchmates Kashish Jain and Smruthi Gowtham, during the SP24 of my graduate studies at the University of California, San Diego.
The report for this project is available [here](https://drive.google.com/file/d/1plrzqbWJn1GdyKax8QPFQxQfhHGs0SU6/view?usp=sharing).

# [Logicator: Enhancing Logical Reasoning in Large Language Models through Structured Problem Representation](https://drive.google.com/file/d/1plrzqbWJn1GdyKax8QPFQxQfhHGs0SU6/view?usp=sharing)

The Logicator framework aims to improve the logical reasoning abilities of large language models (LLMs), particularly in tasks like family relationship puzzles and seating arrangements. The approach involves converting unstructured questions into a standardized format using Named Entity Recognition (NER) and Relationship Extraction (RE). A Retrieval-Augmented Generation (RAG) framework is then used to provide relevant facts. Logicator outperforms baseline models such as GPT-3.5-turbo, achieving 98.70% accuracy on structured family puzzles and 52.38% on unstructured ones.

### Related Work:

The report references significant contributions in the field, such as SAT-Aided Language Models (SATLM) and LOGIC-LM, which integrate LLMs with symbolic solvers to enhance logical reasoning. The report also mentions the "Zero-shot-CoT" method, which uses prompts to improve multi-step reasoning in LLMs.

### Dataset:

- Family Relationship Puzzle Dataset: Contains two types of questions:
  - Type-1: Structured questions with a fixed format.
  - Type-2: Unstructured questions with varying formats, converted into a structured format.
- Seating Arrangement Dataset: Focuses on positional reasoning tasks involving linear and circular arrangements.

### Methodology:

- Dataset Preparation: Creation of complex family tree logical reasoning tasks.
- NER and RE: Identification and extraction of relevant entities and their relationships.
- Standardization: Conversion of data into a consistent format.
- RAG Framework: Retrieval of relevant context and instructions from a large corpus.
- Prompting GPT-3.5-Turbo: Generation of answers using the retrieved and standardized data.
- Evaluation: Assessment of the generated answers against correct responses.

### Entity Recognition:

The framework uses NLTK for recognizing proper nouns and a fine-tuned RoBERTa model for identifying both proper nouns and generic entities. The fine-tuned RoBERTa model shows superior performance in recognizing diverse entities.

### Relationship Extraction and Sentence Reformation:

Logicator employs a zero-shot approach using the OpenAI API to extract and standardize relationships between entities. This process involves identifying relationships from sentences and reformulating them into a structured format suitable for further processing.

### Retrieval Augmented Generation (RAG):

The RAG framework enhances the model's reasoning ability by providing ground truth facts relevant to the task at hand. This approach includes creating a dataset of rules, exploring retrievers, and post-processing the retrieved information to improve the model's performance.

### Conclusion:

The Logicator framework significantly improves the performance of LLMs on complex reasoning tasks by providing a structured representation and fact augmentation. The potential applications of this framework extend to various domains requiring enhanced logical reasoning capabilities.
