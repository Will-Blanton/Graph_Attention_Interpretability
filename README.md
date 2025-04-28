# Attention Graph Analysis for Graph Transformers

This repository contains the code for our project for **CSE 5245: Network Science**.  
We explore and extend the attention graph framework introduced by Batu et al. (2025) for interpreting Graph Transformers. In particular, we adapt the framework to an inductive learning setting (PPI dataset) and perform a deeper analysis of the relationship between learned attention graphs and the original graph structures using centrality metrics.

Original Paper: [Understanding the Inductive Biases of GNNs](https://github.com/batu-el/understanding-inductive-biases-of-gnns)

## Authors

- Will Blanton
- Sal Hargis 
- Austin Usher

## Project Structure

- **Training.ipynb**  
  Code to train Graph Transformer models on single-graph datasets following the original paper's setup.

- **Training_PPI.ipynb**  
  Code to train and evaluate Graph Transformer models on the PPI dataset in the inductive setting. (Author: Will Blanton)

- **Analysis.ipynb**  
  Contains original analysis code adapted from the paper, along with modifications for centrality metric-based analysis of attention graphs. (Author: Sal Hargis)

- **Attention Analysis.ipynb**  
  Additional code for analyzing metric correlations between original graphs and learned attention graphs. (Author: Austin Usher)

- **heterogeneous_training.ipynb**  
  Initial exploration of applying Graph Transformers to heterogeneous graphs before pivoting to the current project focus. (Author: Will Blanton)

## Notes
- The repository builds upon and adapts code from the original authors.
- This project focuses on interpretability rather than achieving state-of-the-art predictive performance.

---

*This project was completed as part of the coursework for CSE 5245.*
