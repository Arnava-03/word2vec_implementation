# Word2Vec Embeddings for Healthcare Domain

## Project Overview
This project involves implementing the Word2Vec model from scratch based on the research paper *"Efficient Estimation of Word Representations in Vector Space"* by Mikolov et al. The focus is on creating domain-specific word embeddings for healthcare, using a dataset of medical texts, and demonstrating their application in real-world tasks.

The project showcases a smaller-scale but functional version of the Word2Vec algorithm.
---

## Features
1. **Custom Word2Vec Implementation**:
   - Built from scratch using Python and NumPy.
   - Supports Skip-Gram with Negative Sampling.
2. **Domain-Specific Training**:
   - Trained on a healthcare dataset (e.g., PubMed abstracts).
   - Preprocessing pipeline for cleaning and tokenizing medical texts.
3. **Evaluation**:
   - Intrinsic tasks like word similarity, word analogies etc.
4. **Visualization**:
   - PCA plots to visualize word clusters.
   - Heatmaps for word similarity.
5. Python script with **object oriented** design, wherein the core functionalities are encapsulated in myWord2Vec class.
   - Methods such as process_data(tokenise, build vocab), generate_training_data, train, save_embeddings and load embeddings are implemented.
   - Tunable parameters like embedding_dim, window_size, learning_rate, epochs etc.
---
