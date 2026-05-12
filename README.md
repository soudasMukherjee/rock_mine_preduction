# Rock & Mine Classification

Rock vs Mine Classification Using Logistic Regression. This project implements a machine learning solution to classify sonar signals as either rocks or mines using Logistic Regression. It demonstrates the complete pipeline of a predictive modeling project, from data preprocessing to model evaluation and real-world predictions.

## Project Overview

The model is trained on sonar data containing 60 frequency attributes collected from naval sonar systems. Each signal is labeled as either 'M' (Mine) or 'R' (Rock). The project uses scikit-learn's Logistic Regression algorithm to build a binary classification model that can accurately distinguish between these two categories.

## Key Features

**Data Processing:** The project begins with comprehensive exploratory data analysis (EDA), including data shape inspection, statistical summaries, and class distribution analysis to understand the dataset characteristics.

**Model Architecture:** Implements a Logistic Regression classifier, a robust algorithm suitable for binary classification tasks. The model is trained on 90% of the dataset and evaluated on the remaining 10%.

**Performance Metrics:** The model achieves strong accuracy scores on both training and test datasets, demonstrating good generalization without significant overfitting.

**Predictive System:** Includes a practical prediction system that can classify new sonar signals in real-time using the trained model.

## Technical Stack

- **Python Libraries:** pandas, numpy, scikit-learn
- **Machine Learning:** Logistic Regression, train-test split with stratification
- **Evaluation Metrics:** Accuracy score

## How to Use

1. Load the sonar dataset
2. The notebook preprocesses and explores the data
3. Train the Logistic Regression model
4. Evaluate performance on test data
5. Make predictions on new sonar signals using the trained model

## Dataset

The sonar dataset contains 208 instances with 60 numerical features representing different frequency bands of sonar signals. Each record is labeled as either a mine or a rock, making this a classic binary classification problem in naval defense applications.

## Results

The model successfully classifies sonar signals with high accuracy, making it a reliable tool for distinguishing between underwater mines and natural rock formations.
