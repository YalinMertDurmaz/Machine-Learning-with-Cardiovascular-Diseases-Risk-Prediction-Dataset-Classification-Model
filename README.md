# Machine Learning with Cardiovascular Diseases Risk Prediction Dataset - Classification Model

Welcome to the Cardiovascular Diseases Risk Prediction project! This repository contains a machine learning model designed to predict the risk of cardiovascular diseases using classification algorithms. The dataset used for this project is the **Cardiovascular Diseases Risk Prediction Dataset**, which contains various health-related metrics that contribute to assessing heart disease risk.

## Project Overview

The goal of this project is to analyze and predict the risk of cardiovascular diseases using machine learning techniques. The model takes patient data as input and provides a classification result indicating the likelihood of cardiovascular disease.

### Dataset

- **Source**: [Cardiovascular Diseases Risk Prediction Dataset](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset)
- **Rows Used**: 50,000 samples
- **Features**:
  - Age
  - Gender
  - Blood pressure
  - Cholesterol levels
  - Smoking habits
  - Physical activity
  - Other relevant health metrics

### Notebooks

This repository contains Jupyter Notebooks for data preprocessing, feature engineering, and model building.

1. **Data Exploration and Cleaning**: Initial analysis and cleaning of the dataset.
2. **Model Building**: Applying various classification algorithms such as Logistic Regression, Decision Trees, Random Forest, and evaluating their performance.
3. **Model Evaluation**: Performance metrics such as accuracy, precision, recall, and F1-score are calculated to evaluate model efficacy.

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries:
  ```bash
  pip install numpy pandas scikit-learn matplotlib seaborn

## Results

The model achieved the following performance metrics:

- **Accuracy**: 0.85
- **Precision**: 0.82
- **Recall**: 0.78
- **F1-Score**: 0.80

The **Random Forest** model provided the best results in terms of accuracy and overall performance.
