# KnowMap - Cross-Domain Knowledge Graph

A Natural Language Processing (NLP) project that creates a knowledge graph from unstructured news articles. This repository contains the production code, milestone deliverables, and the final presentation developed during the Infosys Springboard Virtual Internship 6.0 (August - October 2025).

## Project Overview
- **Domain:** Artificial Intelligence / Natural Language Processing
- **Objective:** Extract entities and relationships from cross-domain unstructured text to build a queryable knowledge graph.
- **Mentor:** Mr. Ajay Kumar

## Repository Structure
- `Final Knowledge Graph Code/`: Final production code for the NLP pipeline and graph generation presented to the Infosys team.
- `Milestone 2/`, `Milestone 3/`, `Milestone 4/`: Incremental project deliverables.
- `Final Presentation - Cross Domain Knowledge Graph without flatten pdf.pdf`: The final presentation deck.


Architecture: Spacy (NER & Relation Extraction) + Sentence-Transformers (Embeddings)
Graph Engine: NetworkX & PyVis for interactive visualization
Algorithm: Louvain Method for community detection/clustering
Interface: Streamlit web application for real-time graph generation
Key Features: Cross-domain entity linking, relationship mapping, and interactive node filtering.
Install dependencies:
   ```bash
   pip install -r requirements.txt
