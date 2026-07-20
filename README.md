# NYAYaRAG
### A Retrieval-Augmented Generation Framework for Legal Question Answering over Indian Supreme Court Judgments

## Overview

NYAYaRAG is a Retrieval-Augmented Generation (RAG) framework designed to support legal question answering using Indian Supreme Court judgments.

The project evaluates multiple retrieval approaches, including:

- TF-IDF
- BM25
- E5 Embeddings
- BGE Embeddings
- InLegalBERT
- Hybrid Retrieval

These retrieval models are integrated with a Large Language Model (LLM) to generate citation-grounded legal answers.

The framework is being developed as part of a Doctorate in Artificial Intelligence and Machine Learning.

---

## Objectives

The objectives of this project are to:

- Build a legal Retrieval-Augmented Generation (RAG) framework.
- Compare traditional, semantic, and hybrid retrieval models.
- Generate accurate, citation-grounded legal answers.
- Evaluate retrieval performance using standard information retrieval metrics.
- Support responsible AI through abstention when relevant legal information is unavailable.

---

## Dataset

**Source:** Open Indian Supreme Court Judgments Dataset

**Court:** Supreme Court of India

**Coverage:** Judgments delivered during 2024

**Number of Judgments:** 782

**Format:** PDF

The original judgments are preserved in their raw form within this repository.

---

## Repository Structure

```text
NyayaRAG/
│
├── data/
│   └── raw/
│       └── pdf/
│           └── year=2024/
│               └── english/
│
├── notebooks/
│   ├── 01_NYAYaRAG_Data_Preparation_and_Indexing.ipynb
│   └── 02_NYAYaRAG_Model_Evaluation_and_Statistical_Analysis.ipynb
│
├── README.md
└── .gitignore
```

---

## Current Status

- Dataset acquisition completed
- Repository created
- Metadata exploration completed
- Text extraction completed
- Corpus preprocessing completed
- Exploratory Data Analysis completed
- Text chunking completed
- Dense embedding generation completed
- ChromaDB vector database created
- Retrieval model evaluation in progress

---

## Future Work


- Sample size calculation and statistical justification
- Benchmark dataset collection and annotation
- Retrieval model evaluation
- Hybrid retrieval implementation
- Prompt engineering for answer generation and safe abstention
- End-to-end RAG pipeline development
- LLaMA integration
- Statistical analysis of retrieval performance
- Evaluation using Precision@k, Recall@k, MRR, MAP, nDCG, Answer Relevancy, Faithfulness, Context Precision, Context Recall, and Abstention Accuracy
- Final capstone experiments and result analysis

---

## Author

**Harshali Chowdhary**

Doctoral Scholar in Artificial Intelligence and Machine Learning

Research Interests:

- Artificial Intelligence

- Natural Language Processing

- Retrieval-Augmented Generation (RAG)

- Legal AI

- Explainable and Responsible AI
