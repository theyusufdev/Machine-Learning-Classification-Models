# 🌸 Iris Dataset Classification Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange)
![Machine Learning](https://img.shields.io/badge/Topic-Classification-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

This project demonstrates a comparative analysis of different machine learning algorithms on the famous **Iris Dataset**. The goal is to classify Iris plant species based on their botanical measurements using supervised learning techniques.

## 📖 Project Overview

The Iris dataset contains 150 samples from three different species of Iris (Setosa, Versicolor, and Virginica). Four features were used for classification:
* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

This project implements and compares three standard classification algorithms to evaluate their performance on this dataset.

## ⚙️ Algorithms Used

The following Scikit-Learn algorithms were implemented:

1.  **Support Vector Classifier (SVC):** Finds the optimal hyperplane that maximizes the margin between classes.
2.  **Logistic Regression:** A statistical model that uses a logistic function to model binary/multiclass dependent variables.
3.  **Naive Bayes (GaussianNB):** A probabilistic classifier based on Bayes' theorem with an assumption of independence between features.

## 🏆 Results & Evaluation

All models were trained and tested on the dataset. The accuracy scores achieved on the test set are as follows:

| Algorithm | Accuracy Score |
|-----------|----------------|
| **SVC** | **100%** |
| **Logistic Regression** | **100%** |
| **Naive Bayes** | **100%** |

### 💡 Insight
All three models achieved **perfect accuracy (1.0)**. This indicates that the classes within the Iris dataset are highly distinct and linearly separable (particularly the *Setosa* class). The high performance also confirms that the data preprocessing and train-test split were handled correctly.

