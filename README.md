# Question 2: Smart Data Explorer

## Project Overview
This project is a data analysis and machine learning system that applies clustering and Artificial Neural Network techniques on a dataset. The goal is to analyze patterns in data and compare the performance of clustering, ANN, and clustering combined with ANN.

## Dataset
The project uses a simple structured or image-based dataset with:
- 100 to 500 samples
- 2 to 5 features
- Suitable data for clustering and classification

Example datasets can include:
- Student performance dataset
- Customer segmentation dataset
- Basic medical dataset
- Small MNIST digit subset

## Main Features
- Dataset loading and preprocessing
- K-Means clustering
- Optional K-Medoids clustering
- Cluster visualization
- ANN / MLP model training
- Comparison between clustering only, ANN only, and clustering + ANN
- Accuracy, loss, and training time analysis

## AI / ML Techniques Used

### 1. K-Means Clustering
K-Means groups similar data points into clusters based on distance from centroids. Different values of K are tested to find better grouping.

### 2. K-Medoids Clustering
K-Medoids is used as an optional comparison. It is similar to K-Means but uses actual data points as cluster centers.

### 3. ANN / MLP
A simple neural network is trained for classification. It uses:
- Input layer
- Hidden layer/layers
- Activation functions
- Forward pass
- Backpropagation
- Learning rate tuning

## Cluster Usage
The clustering result is used in one of two ways:
1. Cluster IDs are used as pseudo-labels
2. Cluster IDs are added as an extra feature for ANN training

## Experiments
The project performs three main experiments:
1. Clustering only
2. ANN only
3. Clustering + ANN

## Evaluation
The system is evaluated using:
- Accuracy
- Loss curves
- Training time
- Cluster plots
- Intra-cluster similarity
- Inter-cluster separation

## Expected Output
The final output shows whether clustering improves ANN performance and how the value of K affects the results.
