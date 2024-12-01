# Optimizing-Retrieval-Metrics-RAG-
Evaluated retrieval metrics in RAG systems using the Meta Llama-3 model and HotpotQA dataset. Identified limitations of syntax-based metrics like BLEU and proposed strategies to improve semantic correctness, enhancing performance in nuanced question-answering scenarios. Provides insights for optimizing RAG pipelines.


This project evaluates the performance of retrieval metrics in Retrieval-Augmented Generation (RAG) systems, focusing on the Meta Llama-3 model with the HotpotQA dataset. The goal was to uncover limitations of commonly used syntax-based metrics and develop strategies to improve semantic correctness for nuanced question-answering scenarios.

**Key Features**:

**Dataset**: Utilized the HotpotQA dataset to benchmark retrieval performance on complex, multi-hop questions.

**Model**: Integrated the Meta Llama-3 model to assess the interaction between retrieval and generation components.

**Evaluation** : Analyzed syntax-based metrics such as BLEU and ROUGE, identifying their inadequacy for capturing semantic nuances.

**Enhancements**: Proposed and tested novel metric strategies, improving semantic alignment in retrieved results.

**Outcomes**:

Demonstrated the need for semantic-aware metrics in RAG systems to handle nuanced question types effectively.
Provided actionable insights into optimizing retrieval pipelines for enhanced performance.

**Technologies Used**:
Python, PyTorch
Meta Llama-3 Model
HotpotQA Dataset
Numpy, Pandas, Matplotlib

**Future Work**:
Extend evaluation to other generative models and datasets.
Develop and implement a novel semantic-aware metric for end-to-end RAG evaluation.
This repository aims to contribute to advancing the effectiveness of RAG systems in real-world applications.
