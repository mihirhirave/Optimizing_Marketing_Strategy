# Optimizing Marketing Strategy

## Overview
This project analyzes customer data to predict response rates to marketing campaigns. It employs various machine learning models, including decision trees, random forests, k-nearest neighbors, and logistic regression.

## Dataset
The dataset includes customer information such as:
- Order frequency
- Revenue in the last 24 months
- Time since last purchase
- Other relevant metrics

## Analysis Steps

1. **Data Preprocessing**
   - Transformed skewed variables (n24, rev24, revlast) using logistic transformation
   - Standardized variables for KNN model

2. **Model Development and Evaluation**
   - Decision Trees
   - Random Forests
   - K-Nearest Neighbors
   - Logistic Regression

3. **Model Comparison**
   - Used 10-fold cross-validation for model evaluation
   - Compared models based on accuracy scores

4. **Lapsing Customer Analysis**
   - Analyzed model performance on lapsing customers (last purchase 13-24 months ago)

## Key Findings

- Random Forest model (50 trees, depth 3) performed best with 71.2% accuracy
- Logistic Regression model showed better performance for lapsing customers
- Decision Tree with depth 1 had high accuracy but limited practical use

## Tools and Libraries Used

- Python
- Scikit-learn
- Matplotlib (for visualizations)

## Future Work

- Explore additional features for improving model accuracy
- Investigate other performance metrics beyond accuracy
- Develop strategies for addressing class imbalance in the dataset
