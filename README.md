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

```
NyayaRAG/
│
├── data/
│   └── raw/
│       └── pdf/
│           └── year=2024/
│               └── english/
│
├── notebooks/
│   ├── 01_Dataset_Acquisition.ipynb
│   ├── 02_Metadata_Exploration.ipynb
│   ├── 03_PDF_Exploration.ipynb
│   ├── 04_Text_Extraction.ipynb
│   ├── 05_Corpus_Preprocessing.ipynb
│   ├── 06_Corpus_EDA.ipynb
│   ├── 07_Text_Chunking.ipynb
│   └── 08_Comparative_Retrieval_Models.ipynb
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
- Retrieval model implementation in progress

---

## Future Work

- Dense embedding generation
- Hybrid retrieval implementation
- ChromaDB indexing
- RAG pipeline development
- LLaMA integration
- Evaluation using Precision@k, Recall@k, MRR, MAP and nDCG

---

## Author

**Harshali Chowdhary**

Doctoral Scholar in Artificial Intelligence and Machine Learning

Research Area:
Retrieval-Augmented Generation for Legal Question Answering over Indian Supreme Court Judgments
