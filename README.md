Graph Neural Networks for Node Classification

This repository contains the implementation and evaluation of Graph Neural Networks (GNNs) for node classification tasks using PyTorch Geometric. The project explores two popular GNN architectures: Graph Convolutional Network (GCN) and Graph Attention Network (GAT).

Project Overview

Node classification is a critical task in graph-based machine learning, where the goal is to predict the labels of nodes in a graph based on their features and graph structure. This project demonstrates how GNNs can effectively learn node representations by aggregating information from neighboring nodes.

Key Features:

GCN and GAT Architectures: Implementation of deep GCN and GAT layers with dropout and activation functions.
Training and Validation: Models are trained and validated with accuracy metrics to measure performance.
Class Imbalance Analysis: Exploration of label distribution to identify and address challenges.

Test Predictions: Saves test results for evaluation or submission.

Results

Validation Accuracy: The GCN model achieved a validation accuracy of 81.82%.
Training Accuracy: The model achieved a perfect 100% accuracy on the training set.
Class Distribution: Predicted labels showed an imbalance, with the largest proportion in Class 2 (28.95%).
