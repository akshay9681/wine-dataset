# wine-dataset
# Wine Classification Using Machine Learning

This project demonstrates the application of machine learning for predicting the wine class based on various features. The dataset used is the famous **Wine Dataset** from the UCI Machine Learning Repository, which contains data on different wines (3 classes) based on 13 chemical properties.

## Objective:
The goal of this project is to:
- Explore the dataset and perform data cleaning and feature engineering.
- Build and evaluate a **Random Forest Classifier** to predict the wine class.
- Evaluate model performance using metrics like **Accuracy**, **Classification Report**, and **Confusion Matrix**.

## Dataset:
- **Features**: 13 chemical properties related to wine composition (e.g., alcohol content, color intensity, flavonoids).
- **Target**: Wine class (3 possible classes).

## Steps:
1. Load the dataset and perform exploratory data analysis (EDA).
2. Preprocess the data (standardization).
3. Train a **Random Forest Classifier** and evaluate its performance.
4. Visualize the results using confusion matrix and classification report.

## Results:
- The **Random Forest Classifier** achieved an accuracy of 1.00 on the test set.
- The **Classification Report** provides details on precision, recall, and F1-scores for each class.

## Installation:
Clone the repository and install dependencies.

```bash
git clone https://github.com/yourusername/wine_classification.g
cd wine_classification
pip install -r requirements.txt
