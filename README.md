# Customer Segmentation for Car Insurance Cold Calls

## Overview

## Dataset
[Download the dataset from Kaggle](https://www.kaggle.com/datasets/kondla/carinsurance)

### Problem Statement
In the banking sector, offering services like car insurance requires targeted marketing. Identifying potential customers interested in these services is crucial for optimizing campaigns and resource allocation.

### Project Objective
This project focuses on classifying existing bank customers based on their likelihood to purchase or own a car. Leveraging data mining techniques, we aim to predict customer behavior during cold calls, aiding in efficient campaign planning.

## Project Structure

### 1. Data Exploration
Explore customer attributes, analyze trends, and visualize key features:
- **Customer Age vs. Account Balance**
- **Distribution of Customers by Age**
- **Marital Status of Customers**
- **Qualification of People Who Bought Car Insurance**

### 2. Feature Engineering
Refine the dataset by eliminating irrelevant parameters to enhance model performance.

### 3. Model Selection
Implement various machine learning models to classify customers:
- **K-Nearest Neighbour (KNN)**
- **Naive-Bayes**
- **Classification And Regression Tree (CART)**
- **Random Forest**
- **Logistic Regression**
- **Neural Network**
- **Linear Discriminant Analysis (LDA)**

### 4. Model Performance Evaluation
Evaluate model performance using metrics such as accuracy, F1 score, and ROC curves.

## Models Considered

1. **K-Nearest Neighbour (KNN)**
   - Optimal K: 11, Testing Accuracy: 79.05%, F1 Score: 71.06%

2. **Naive-Bayes**
   - Training and Testing Accuracy: 65%, 66%

3. **Classification And Regression Tree (CART)**
   - Pruned Tree, Max Depth: 3, Balanced Accuracy

4. **Random Forest**
   - Training Accuracy: 81%, Testing Accuracy: 79%

5. **Logistic Regression**
   - Training Accuracy: 79.93%, Testing Accuracy: 77.95%

6. **Neural Network**
   - Testing Accuracy: 79.97%, Linearly Separable Data

7. **Linear Discriminant Analysis (LDA)**
   - Training Accuracy: 77.87%, Testing Accuracy: 77.15%, F1 Score: 67.53%

## Model Comparison and Recommendation

### Best-Performing Models
Logistic Regression

In crafting this marketing campaign, we prioritize minimizing False Negatives (FN) to ensure optimal customer retention, given the assumption that marketing costs are outweighed by potential customer loss. Setting the Logistic Regression threshold at 0.1 significantly improves the recall score from 64% to 98%. We'll determine the optimum threshold aligned with business requirements, factoring in our marketing budget constraints.

## Summary

Explore the code and findings to gain insights into predicting customer behavior for car insurance purchases. Clone the repository, run the code, and feel free to reach out with questions or suggestions.
