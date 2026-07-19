# Machine Learning & Data Science Concepts

This README contains concise answers to fundamental questions across Machine Learning, Algorithms, Deep Learning, and Data Evaluation.


## 1/ Basic

**Types of Machine Learning?**  
The three main types are Supervised Learning, Unsupervised Learning, and Reinforcement Learning.

**Difference between AI, ML, and Deep Learning?**  
- **AI (Artificial Intelligence):** The broad concept of machines mimicking human intelligence.
- **ML (Machine Learning):** A subset of AI where algorithms learn patterns from data without explicit programming.
- **Deep Learning:** A subset of ML that uses multi-layered artificial neural networks to solve complex problems.

**What is supervised learning?**  
Training a model on labeled data, meaning the input data is paired with the correct output/target.

**What is unsupervised learning?**  
Training a model on unlabeled data, allowing the algorithm to find hidden patterns or groupings on its own.

**What is reinforcement learning?**  
A type of ML where an agent learns to make decisions by performing actions in an environment to maximize cumulative rewards (trial and error).

**What is overfitting?**  
When a model learns the training data too well, including its noise and outliers, resulting in poor performance on unseen/new data.

**What is underfitting?**  
When a model is too simple to capture the underlying patterns in the data, performing poorly on both training and testing data.

**What is bias and variance?**  
- **Bias:** Error introduced by approximating a real-world problem with a too-simple model (high bias leads to underfitting).
- **Variance:** Error introduced by a model's sensitivity to small fluctuations in the training set (high variance leads to overfitting).

**What is train-test split?**  
Dividing a dataset into two subsets: one to train the model (training set) and one to evaluate its performance on unseen data (testing set).

---

## 2/ Algorithms & Models

**What is Linear Regression?**  
A supervised algorithm used for predicting a continuous numerical output by fitting a straight line (or hyperplane) that minimizes the error between predicted and actual values.

**What is Logistic Regression?**  
A supervised algorithm used for binary classification tasks, predicting the probability that an instance belongs to a specific class using a logistic curve.

**Difference between classification and regression?**  
- **Classification:** Predicts discrete class labels (e.g., Spam or Not Spam).
- **Regression:** Predicts continuous numerical values (e.g., House prices).

**What is Decision Tree?**  
A flowchart-like model that splits data into branches based on feature values, leading to a final decision/prediction at the leaves.

**What is Random Forest?**  
An ensemble learning method that builds multiple decision trees and merges their outputs to get a more accurate and stable prediction.

**What is KNN (K-Nearest Neighbors)?**  
An algorithm that classifies a new data point based on the majority class among its 'K' closest neighbors in the feature space.

**What is SVM (Support Vector Machine)?**  
A classification algorithm that finds the optimal hyperplane which maximizes the margin (distance) between different classes.

**What is Naive Bayes?**  
A probabilistic classifier based on Bayes' Theorem, assuming that all features are independent of each other given the class label.

**What is K-Means clustering?**  
An unsupervised algorithm that partitions unlabeled data into 'K' distinct clusters based on feature similarity and distance to cluster centroids.

**What is PCA (Principal Component Analysis)?**  
A dimensionality reduction technique that transforms a large set of features into a smaller one while retaining as much variance (information) as possible.

---

## 3/ Deep Learning & Neural Networks

**What is Deep Learning?**  
A specialized subset of machine learning based on artificial neural networks with multiple layers (deep networks) capable of learning complex representations from vast amounts of data.

**What is a Neural Network?**  
A computational model inspired by the human brain, consisting of interconnected layers of artificial neurons (nodes) that process information.

**What is gradient descent?**  
An optimization algorithm used to minimize the model's loss function by iteratively adjusting weights in the opposite direction of the gradient.

**What is backpropagation?**  
The core mechanism in neural networks that calculates the gradient of the loss function backwards through the network layers to update the weights.

**What are activation functions?**  
Mathematical equations attached to each neuron that introduce non-linearity into the network, allowing it to learn complex patterns.

**Difference between ReLU and Sigmoid?**  
- **Sigmoid:** Maps outputs to a range between 0 and 1. Prone to the vanishing gradient problem.
- **ReLU (Rectified Linear Unit):** Outputs the input directly if positive, else outputs zero. It is faster to compute and helps mitigate the vanishing gradient problem.

**What is CNN (Convolutional Neural Network)?**  
A type of deep neural network optimized for processing grid-like data, predominantly used for image recognition and computer vision tasks.

**What is RNN (Recurrent Neural Network)?**  
A type of neural network designed for sequential data (like text or time series) because it has internal memory loops to remember previous inputs.

**What is transfer learning?**  
A technique where a model developed for one task is reused as the starting point for a model on a second, related task, saving computational resources and training time.

**What is dropout?**  
A regularization technique in neural networks where randomly selected neurons are ignored ("dropped out") during training to prevent overfitting.

---

## 4/ Data Processing & Evaluation

**What is data preprocessing?**  
The process of cleaning, transforming, and organizing raw data into a format that is understandable and usable by machine learning algorithms.

**What is feature engineering?**  
The process of using domain knowledge to select, modify, or create new variables (features) from raw data to improve model performance.

**How do you handle missing values?**  
Common methods include removing the missing rows/columns, or imputing them with the mean, median, mode, or using advanced predictive imputation techniques.

**What is normalization?**  
Scaling numerical data so that all values fall within a specific range, typically between 0 and 1 (Min-Max scaling).

**What is standardization?**  
Scaling numerical data so that it has a mean of 0 and a standard deviation of 1 (Z-score scaling), handling outliers better than normalization.

**What is accuracy?**  
An evaluation metric representing the ratio of correctly predicted observations to the total observations.

**What is precision?**  
The ratio of correctly predicted positive observations to the total predicted positives. It answers: "Of all instances predicted as positive, how many were actually positive?"

**What is recall?**  
The ratio of correctly predicted positive observations to all actual positives. It answers: "Of all actual positive instances, how many did we correctly identify?"

**What is F1-score?**  
The harmonic mean of Precision and Recall.It is especially useful for imbalanced datasets where you need a balance between precision and recall.

**What is confusion matrix?**  
A table used to describe the performance of a classification model, displaying True Positives, True Negatives, False Positives,and False Negatives.
=======
The harmonic mean of Precision and Recall. It is especially useful for imbalanced datasets where you need a balance between precision and recall.

**What is confusion matrix?**  
A table used to describe the performance of a classification model, displaying True Positives, True Negatives, False Positives, and False Negatives.
=======
Note that you need to download the labs files to be manage to access it from the repo.
