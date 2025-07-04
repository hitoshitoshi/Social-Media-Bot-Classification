# Social Media Bot Classification

## 1. Introduction

This project explores the effectiveness of tree-based and neural-based models for classifying social media accounts as either "user" or "bot". Using a public dataset from VK.com, we implement and compare an XGBoost model and a simple Neural Network to understand their performance on this binary classification task.

## 2. Experimental Question

How does replacing missing values with zeroes or the most common value for that feature affect model performance in neural networks compared to decision tree models?

## 3. Dataset

The data for this project comes from the "Users vs Bots Classification" dataset on Kaggle, which can be found here:
[https://www.kaggle.com/datasets/juice0lover/users-vs-bots-classification/data](https://www.kaggle.com/datasets/juice0lover/users-vs-bots-classification/data)

## 4. Methods and Models

We implemented and compared two primary models:

1.  **XGBoost**: A gradient-boosted decision tree model known for its performance in classification tasks.
2.  **Neural Network**: A simple feed-forward neural network with 6 linear layers built for binary classification.

Data was preprocessed to handle categorical features and missing values to test our central experimental question.

## 5. How to Run This Project

1.  **Open Bot-Classification-Analysis.ipnyb in Google Collab**
2.  **Make a copy of the project**
3.  **Set the train flag to True to retrain it**

## 6. Key Results

Our analysis showed that the **XGBoost model achieved the highest testing accuracy of 0.98**. The neural network, while also effective, performed slightly lower. The primary limitation was the handling of categorical features, which were more naturally handled by XGBoost.
