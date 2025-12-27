Critical Minerals Knowledge Graph (CMKG) – CMiO Jupyter Notebook

Overview

This repository contains a Jupyter notebook implementing the Critical Minerals Knowledge Graph (CMKG), an AI-driven framework for semantic exploration and question answering over critical mineral datasets. The project integrates sample-level geochemical, mineralogical, and lithological data with deposit-level information from the Critical Minerals in Ores (CMiO) database.
The CMKG combines knowledge graphs, vector embeddings, and large language models (LLMs) to support intelligent, transparent, and domain-aware question answering for critical mineral research and exploration.

Key Features

Ontology-grounded knowledge graph representation of critical mineral data
Deterministic querying using graph databases (Neo4j)
Semantic retrieval using vector embeddings and FAISS
Hybrid Graph Retrieval-Augmented Generation (Graph-RAG) architecture
Interactive Jupyter-based question answering interface
Support for both structured queries and natural-language questions

Requirements

Python 3.9+
Jupyter Notebook
Neo4j
FAISS
OpenAI-compatible embedding and LLM APIs


Usage

Clone this repository
Open the Jupyter notebook
Follow the notebook cells sequentially to:
Load and process the CMiO data
Build the knowledge graph
Generate embeddings and indexes
Run interactive question answering examples
Reproducibility

All data processing, graph construction, and evaluation steps are fully implemented in the notebook to support **
