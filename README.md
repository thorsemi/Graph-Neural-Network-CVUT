# Assigement 1 (Home work 1.pdf)
The final assignment 1 has been sumbitted as PDF report, with all the figures and Cypher querys that i used in Neo4j. 

# Assignment 2 (GNN-2025-Homework2.ipynb)
Task 2 involved analyzing the network of negativity within a dataset that includes the `LINK_SENTIMENT` attribute, which indicates whether a reference post is positive/neutral (+1) or negative (-1). A subgraph containing only the negative links (-1) was created, and its structure was analyzed using Python.

# Assignment 3 (GNN-2025-Homework3.ipynb)
In this assignment, I look into implementing Graph Neural Networks for node classification and link prediction on the Cora dataset. First, we loaded the dataset and defined a 2-layer GCN model for node classification. We trained the model and evaluated its accuracy. Then, for link prediction, i removed edges to create a train/test split, built a GraphSAGE embedding model and a link predictor, and trained it to distinguish between real and fake edges. Results were summarized in a table comparing different model configurations. I used Google Colab in the assignment because of issues with the "dgl" library. 

# Final Project (GNN_Final_Report) + Video
In this project, I explored node classification on the PubMed citation network using Graph Convolutional Networks (GCNs). The goal was to predict the subject category of scientific publications based on graph structure and node features. I implemented a two-layer GCN using PyTorch Geometric, applied standard preprocessing, and conducted experiments involving model training, hyperparameter tuning, and embedding visualization. The project also includes analysis using t-SNE, confusion matrices, and inspection of individual prediction cases.
