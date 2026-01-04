# Retrieval-Augmented-QA-with-Sparse-Dense-Retrieval

This repository contains a Jupyter notebook that implements and evaluates a Retrieval-Augmented Generation (RAG) pipeline for question answering. The project compares multiple QA settings, including a vanilla LLM baseline, an oracle (gold-context) upper bound, and retrieval-augmented approaches.

Two retrieval strategies are explored:

- Sparse retrieval based on token overlap / TF-IDF-style scoring

- Dense retrieval using a BERT-based encoder with cosine similarity

The system is evaluated using Exact Match (EM), F1, and ROUGE-2 metrics across different top-k retrieved contexts. Incorporating retrieval substantially improves performance, increasing Exact Match from 7.2% (vanilla LLM) to 31.2% (RAG) on the benchmark dataset.
