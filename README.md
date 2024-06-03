# COVID-19 Topic Clustering Project

## Overview

This repository is dedicated to a topic clustering and modeling project using the CORD-19 dataset, which consists of scientific articles about COVID-19. The project is inspired by advances in text mining and natural language processing, specifically utilizing the BERT model integrated with clustering techniques to discover significant topics within the dataset.

## Project Goal

The primary goal of this project is to cluster the COVID-19 dataset into meaningful topics using advanced NLP techniques. By implementing the methods outlined in the article "BERT and clustering integrated modeling topic improved framework," we aim to uncover significant relationships between the variables in the dataset.

## Covered Topics
- Topic Clustering Modeling
- Machine Learning
- Natural Language Processing (NLP)

## Dataset

The dataset used in this project is the first published version of the CORD-19 dataset, maintained by the Allen Institute for AI. This dataset includes titles and abstracts of articles, which are key parameters for our analysis.

## Project Stages

### 1. Input File
- **Dataset**: CORD-19 dataset available through the Scholar Semantic team at the Allen Institute.
- **Reading Material**: Research Open COVID-19 Dataset (CORD-19).

### 2. Data Preprocessing
- **Cleaning**: Remove duplicate data and handle null values.
- **Text Preprocessing**: Implement text cleaning techniques such as stemming, stop-word removal, and lemmatization.

### 3. Feature Extraction
- **Techniques**: Convert textual data into numerical vectors using at least two of the following methods:
  - Word2Vec
  - TF-IDF
  - GloVe
  - Bag-of-Words (BOW)

### 4. LDA - Modeling Topic
- **Description**: Use Latent Dirichlet Allocation (LDA) for unsupervised classification of texts based on their word distributions.

### 5. Dimensionality Reduction
- **Methods**: Apply dimensionality reduction techniques to enhance analysis speed and accuracy:
  - PCA (Principal Component Analysis)
  - LDA (Linear Discriminant Analysis)
  - GDA (Generalized Discriminant Analysis)

### 6. Choosing the Clustering Model
- **Selection**: Employ the Elbow method to determine the optimal number of clusters.
- **Clustering Algorithms**: Implement at least two clustering methods to organize the data.

### 7. Conclusion
- **Evaluation**: Use the Silhouette score to assess the performance of different clustering models.
- **Analysis**:
  - Determine which feature extraction method and clustering model performed best and explain why.
  - Analyze the types of topics each cluster represents.
  - Visualize the data in two dimensions using different colors for each cluster to illustrate the distinctions.
