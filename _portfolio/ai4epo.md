---
title: "AI4EPO: European Patent Office Codefest Winning Project"
excerpt: "In this project a end-to-end pipeline was built where it downloaded data from the European Patent Office database, preprocessed it and developed ways to classify them to the corresponding categories [(github repository)](https://github.com/gody10/epo_codefest): **Large Language Models, Embeddings, Deep Machine Learning, Natural Language Processing** <br/><img src='/images/ai4epo.png' width='700'>"
collection: portfolio
---

## Classifying Patents using State-of-the-Art technologies

### Description
The European Patent Office (EPO) commitee gave each team 1 month to create their dataset and come up with a solution that would help or replace human actors in classifying patents. Our team decided to create a dataset which includes patents of many different language origins in order to make the setting more realistic. To translate the non-English patents we used the latest translator models provided by Google. After the translating process, we evaluated different Large Language models and different methods to summarize the content of the patents in order to create better Embeddings that would allow our dataset quality to improve. Finally, we trained a Deep Neural Network with ReLU activation functions and Batch Normalization to categorize our data. We tested it in two different levels of categories (higher and lower leve) where it performed extremely well. All in all, our pipeline showed its capability to potentially replace human agents in the field of patent classification, which led to [our team winning the codefest](https://helvia.ai/blog/the-ai4epo-team-winner-of-epo-codefest/).

### Technologies Used

- **Deep Machine Learning** – Experimented with advanced Machine Learning Models to classify the patents
- **Data Preprocessing** – Preprocessed huge volumes and extremely diverse data and managed to create optimal datasets that allowed the model to properly learn and improve
- **LLM and Embedding Pipeline** – Got hands on experience on fine tuning and prompting state-of-the-art LLMs and used state-of-the-art Embedding models
- **Translated Different Language** – Translated patents from various European language to English using Google models and LLMs in order to increase the size of the corpus