---
title: 'TextClass Benchmark: Evaluation of LLMs and transformers for text classification in social sciences'
date: '2025-03-16'
authors: ["bgonzalezbustamante"]
image:
  caption: 'Picture credits: [**TextClass Benchmark**](https://textclass-benchmark.com/)'
  focal_point: 'smart'
pager: true
commentable: true
show_related: false
show_breadcrumb: true
draft: false
tags:
- blog
---

In November 2024, I started working on the [TextClass Benchmark](https://textclass-benchmark.com/) project, a dynamic, ongoing benchmarking initiative designed to evaluate Large Language Models (LLMs) and transformers for text classification tasks. The project's focus on social sciences is significant as it addresses the growing need for effective text classification tools in this field. The current coverage includes domains such as digital incivility, policy agenda classification and an incipient classification on misinformation. The project has tested 98 models, including the novels GPT-4.5-preview, DeepSeek-R1 and Gemma 3, almost 3,500 times.

<!--more-->

The project features leaderboards with performance metrics and relative rankings using a tailored Elo rating system, updated with each cycle to include new models and unseen test data to assess generalisation power. The project's main idea is not only to emphasise the continuous testing of LLMs, highlighting their variable performance across different languages and tasks, but also to address the limitations that have emerged from the combination of rapid advancements in AI and machine learning with the traditional slow peer-review processes. This approach ensures that the project remains relevant and impactful in the face of rapid technological change. Materials and real-time updates on the Elo ratings are accessible on the [project's GitHub](https://github.com/bgonzalezbustamante/TextClass-Benchmark) and web interface at [textclass-benchmark.com](https://textclass-benchmark.com/). 

The Elo rating system benchmarks models through pairwise comparisons, while the Meta-Elo rating combines domain-specific scores for a comprehensive evaluation. Using a balanced dataset, the first cycle's task involved toxicity classification in Chinese, English, German and Russian. Further details are available in this [working paper](https://doi.org/10.48550/arXiv.2412.00539). It also offers a Meta-Elo indicator that combines and weights domain-specific leaderboards, accounting for task complexity, language data scarcity, and absolute performance. This indicator provides a more nuanced understanding of model performance across different classification tasks, making it a valuable tool for researchers and practitioners in the social sciences.

In sum, the [TextClass Benchmark](https://textclass-benchmark.com/) project is an interesting contribution because it provides a dynamic and fair evaluation of LLMs and transformers for text classification tasks across various common domains in social sciences and languages. This continuous benchmarking process is relevant to understanding how these models perform in different contexts, particularly in social sciences, where the rapid evolution of machine learning and AI technologies can make traditional evaluation methods obsolete. By offering a comprehensive benchmarking system, this project plays a crucial role in keeping researchers and practitioners up to date with the latest advancements, ensuring they use the most effective tools for their specific tasks. Using a tailored Elo rating system and introducing Meta-Elo add layers of robustness and generalisation to the evaluation, making it a valuable resource for ongoing research and application in NLP and text-as-data approaches.
