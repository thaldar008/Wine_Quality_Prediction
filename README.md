# 🍷 Wine Quality Analysis

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-green.svg)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A comprehensive data science project analyzing wine quality using machine learning techniques. This repository contains exploratory data analysis, feature engineering, and predictive modeling to classify wine quality based on physicochemical properties.

## 🎯 About the Project

This project analyzes the **Wine Quality Dataset** from the UCI Machine Learning Repository. The goal is to predict wine quality (rated 0-10) based on various physicochemical properties such as:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol

### Key Features
- 📊 **Exploratory Data Analysis (EDA)** with visualizations
- 🔍 **Feature Correlation Analysis** 
- 🤖 **Machine Learning Models** (Random Forest, SVM, Logistic Regression)
- 📈 **Model Evaluation** with accuracy metrics and confusion matrices
- 🎨 **Interactive Visualizations** using matplotlib and seaborn

## 📊 Dataset

The dataset includes two variants:
- **Red Wine** (1599 samples)
- **White Wine** (4898 samples)

## ⚙️ Model Comparison & Results
We implemented four distinct machine learning models. The **Random Forest** model emerged as the most effective solution.

| Model | Accuracy | Class 1 (Outstanding) F1-Score |
| :--- | :--- | :--- |
| **Random Forest** | **80.0%** | **0.83** |
| **Logistic Regression** | 74.0% | 0.76 |
| **Linear SVM** | 72.0% | 0.74 |
| **RBF SVM** | 65.62% | -- |

### 🏆 Top Performer: Random Forest
With an **80.0% accuracy**, the Random Forest Classifier outperformed the linear models. It was particularly effective at identifying "Outstanding" wines, achieving the highest F1-score.
