---
title: "Making LLMs Worth Every Penny: Resource-Limited Text Classification in Banking"
collection: publications
category: conferences
permalink: /publication/llms_finance
excerpt: 'Index Terms— **Large Language Models, Finance**'
date: 2023-11-10
venue: '4th ACM International Conference on Artificial Intelligence in Finance (ICAIF)'
paperurl: 'http://gody10.github.io/files/llms_finance.pdf'
citation: '2023, L. Loukas, I. Stogiannidis, O. Diamantopoulos, P. Malakasiotis, and S. Vassos, "Making LLMs Worth Every Penny: Resource-Limited Text Classification in Banking", 4th ACM International Conference on Artificial Intelligence in Finance (ICAIF), Accepted'
---
Standard Full-Data classifiers in NLP demand thousands of labeled examples, which is impractical in data-limited domains. Few-shot methods offer an alternative, utilizing contrastive learning techniques that can be effective with as little as 20 examples per class. Similarly, Large Language Models (LLMs) like GPT-4 can perform effectively with just 1-5 examples per class. However, the performance-cost trade-offs of these methods remain underexplored, a critical concern for budget-limited organizations. Our work addresses this gap by studying the aforementioned approaches over the Banking77 financial intent detection dataset, including the evaluation of cutting-edge LLMs by OpenAI, Cohere, and Anthropic in a comprehensive set of few-shot scenarios. We complete the picture with two additional methods: first, a cost-effective querying method for LLMs based on retrieval-augmented generation (RAG), able to reduce operational costs multiple times compared to classic few-shot approaches, and second, a data augmentation method using GPT-4, able to improve performance in data-limited scenarios. Finally, to inspire future research, we provide a human expert's curated subset of Banking77, along with extensive error analysis.