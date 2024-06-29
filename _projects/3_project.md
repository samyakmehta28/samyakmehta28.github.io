---
layout: page
title: Analysis Study on LLMs
description: This project evaluates GPT-3.5-turbo's ability to solve complex reasoning tasks using Zero-shot-CoT prompting, achieving notable success in arithmetic problems but facing challenges in logical and positional reasoning.
img: assets/img/project_3.jpeg
importance: 3
category: ML & AI
---

The project report can be found [here](https://github.com/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks/blob/master/report.pdf) and the code can be found in the github repository [here](https://github.com/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks)

# Analysis Study: Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks

### Overview:

This project focuses on evaluating and analyzing the performance of GPT-3.5-turbo, a state-of-the-art large language model, on various complex reasoning tasks that involve logical and positional thinking. The primary aim is to identify the strengths and weaknesses of the model in solving multi-step reasoning problems without the need for task-specific examples.

### Introduction:

Large language models (LLMs) have shown impressive capabilities in natural language understanding, but their proficiency in complex reasoning tasks has been limited. These tasks, such as multi-step arithmetic and logical problems, require a systematic approach to break down problems into smaller, manageable steps. The project builds on the concept of Zero-shot Chain of Thought (Zero-shot-CoT) prompting, which uses simple prompts like "Let's think step by step" to encourage multi-step reasoning in LLMs without requiring specific task examples. This approach has significantly improved performance on various benchmarks, such as the MultiArith dataset, where accuracy increased from 17.7% to 78.7%.

### Datasets:

- MultiArith Dataset:
  A collection of mathematical word problems designed to test arithmetic reasoning capabilities. Each problem involves multiple steps and requires interpreting and performing a series of calculations based on textual descriptions.

- Family Relationship Puzzle Dataset:
  This dataset consists of approximately 50 questions that require deducing relationships between family members, often presented in the form of family trees or descriptive statements. It was manually created through web scraping.

- Seating Arrangement Dataset:
  This dataset contains around 200 questions related to arranging people in specific positions based on given clues, such as linear, circular, square, and triangular arrangements. It was also manually created through web scraping.

### Methodology:

The study employs Zero-shot-CoT prompting to assess GPT-3.5-turbo's performance on the aforementioned datasets. The methodology involves:

- Using consistent prompts to evaluate performance.
- Measuring accuracy and categorizing errors.
- Comparing results with previous models and identifying specific areas where the model struggles.

### Key Findings:

- MultiArith Dataset:
  GPT-3.5-turbo achieved an accuracy of 96.83%, significantly higher than previous models like text-davinci002, which achieved 78.7%. The model performed well on structured arithmetic problems but struggled with ambiguous questions.

- Family Relationship Puzzles:
  The model achieved an accuracy of 36.58%. It performed well on simple, well-structured questions but struggled with complex, multi-step reasoning tasks involving multiple layers of relationships.

- Seating Arrangement Dataset:
  GPT-3.5-turbo achieved an accuracy of 24.87% on this dataset. It found it particularly challenging to handle relative directions in seating arrangements and complex positional clues.

### Analysis and Categorization of Errors:

The errors were categorized into several types, highlighting specific weaknesses of the model:

- Ambiguous Text Misinterpretation: The model often misunderstood questions due to vague wording.
- Multi-layered Relationship Challenges: The model struggled with problems that required identifying multiple intermediate relationships.
- Significance of Key Words: The model sometimes overlooked crucial words like "only," which significantly impacted the relationship mapping.
- Complex Positional Reasoning: The model had difficulty with questions that involved relative positioning and multiple constraints.

### Conclusion:

The project demonstrates that while GPT-3.5-turbo shows remarkable improvements in handling structured arithmetic problems, it still faces challenges with complex logical and positional reasoning tasks. The insights gained from this analysis provide valuable directions for further improvements in LLMs, particularly in enhancing their ability to handle multi-step reasoning and complex queries.
