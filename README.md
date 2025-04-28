# gnn-project
This project is for my CSE-597 #4 Graph Mining class.
---

# Wikipedia Article Classification with GraphSAGE

This project analyzes the structure and relationships within Wikipedia by modeling articles as a graph, where nodes are articles and edges are hyperlinks. Using the [Wiki-CS dataset](https://github.com/pmernyei/wiki-cs-dataset) and a Graph Neural Network (GraphSAGE), the notebook performs node classification to automatically categorize articles based on both their content and link patterns.

## Features

- **Graph Construction:** Wikipedia articles as nodes, hyperlinks as edges
- **Node Features:** 300-dimensional GloVe-based text embeddings per article
- **Node Classification:** Predicts article categories using GraphSAGE
- **Community Detection:** Reveals clusters and semantic relationships between articles
- **Visualization:** t-SNE plot of learned node embeddings

## Results

- Achieves high accuracy in categorizing Wikipedia articles
- Visualizes semantic communities and central articles

## Dataset

- [Wiki-CS: A Wikipedia-based Benchmark for Graph Neural Networks](https://github.com/pmernyei/wiki-cs-dataset)


