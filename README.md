
# Sentiment Analysis and Clustering on Product Reviews

This repository contains code for performing sentiment analysis and clustering on a product review dataset. The dataset consists of customer reviews along with star ratings ranging from 1 to 5.

## Sentiment Analysis

### Preprocessing
1. Cleaned the text by removing punctuation.
2. Preprocessed the text by removing stop words and performing stemming.

### Bag of Words (BoW) Features
1. Created BoW features using word counts.
2. Selected relevant words as features to optimize performance.

### Evaluation Metrics
1. Split the dataset into training and testing sets using the provided train-test split indices.
2. Evaluated the performance of the sentiment analysis model using metrics such as accuracy, precision, recall, and F1 score.
3. Reported interesting observations based on the evaluation results.

### TF-IDF Features
1. Repeated the sentiment analysis task using TF-IDF features.
2. Evaluated the model performance using similar metrics.

## Clustering

### KMeans Clustering
1. Performed KMeans clustering using sklearn with various values for the number of clusters (k).
2. Plotted the elbow curve to determine the optimal number of clusters.
3. Plotted Within-Cluster Sum of Square (WCSS) for each value of k.

### Cluster Initialization Methods
1. Repeated the clustering task with different cluster initialization methods: k-means++ and Forgy (random in sklearn).
2. Evaluated the clustering using metrics like purity, NMI (Normalized Mutual Information), and Rand score.

## Dependencies

- Python 3.x
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn

## Contribution

Contributions to improve the code, add new features, or fix issues are welcome. Please open a pull request or raise an issue to discuss potential changes.
