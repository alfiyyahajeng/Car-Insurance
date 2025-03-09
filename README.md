# 🚗Car Insurance Prediction Using Decision Tree Classifier
This repository contains a machine learning model to predict whether a prospective customer will purchase a car insurance policy offered by a sales representative.

## 🔑Problem Statement
The goal is to build a Machine Learning model that predicts whether a prospective customer will decide to purchase or not the car insurance policy offered by a sales representative. The model uses a Decision Tree Classifier as the core algorithm, and it incorporates SMOTE (Synthetic Minority Over-sampling Technique) to handle class imbalance in the dataset.

## 🗃️Dataset
The dataset used for training the model is available on Kaggle: https://www.kaggle.com/datasets/kapturovalexander/pagila-postgresql-sample-database?select=film.csv

## Usage
1. Clone the repository: https://github.com/alfiyyahajeng/Car-Insurance.git
2. Run the Jupyter notebook to train the model and evaluate performance.
3. The trained model will be saved as a pickle file (model.pkl) for later use.
```python
with open('modelDT','wb') as file:
    pickle.dump(model, file)
```
