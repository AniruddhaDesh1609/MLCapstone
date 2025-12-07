# IntroMLCapstone

This repository contains the full implementation for my Intro to Machine Learning Capstone Project, focusing on house price prediction using classical and literature-based machine learning models.  
The project uses the Ames Housing dataset and evaluates multiple algorithms, including Linear Regression, Ridge Regression, Neural Networks, XGBoost, and a Cluster-wise Hybrid Ridge model.

---

## Repository Structure

### Jupyter Notebooks (Model Implementations)

- 01_LinearRegression.ipynb  
  Implements baseline Linear Regression with preprocessing, training, evaluation, and visualization.

- 02_RidgeRegression.ipynb  
  Ridge Regression with L2 regularization tuning and error analysis.

- 03_NeuralNetwork_regression.ipynb  
  Custom neural network implementation using numpy, training curves, and predictions.

- 04_XGBoost.ipynb  
  XGBoost model with hyperparameter tuning and feature importance visualization.  
  Inspired by the paper "An Optimal House Price Prediction Algorithm: XGBoost".

- 05_Clusterwise_Ridge_Hybrid.ipynb  
  Hybrid model combining clustering and Ridge Regression.  
  Inspired by the paper "Unveiling Location-Specific Price Drivers: A Two-Stage Cluster Analysis for Interpretable House Price Predictions".

---

## Data Files

- train.csv  
- test.csv  

Dataset link: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview

---

## Figures Used in the Final Report

Figures include:  
Actual vs predicted plots, residual distributions, training vs validation loss curve (Neural Network), XGBoost feature importance, and hybrid model scatterplot.

---

## Papers Referenced

1. An Optimal House Price Prediction Algorithm: XGBoost  
2. Unveiling Location-Specific Price Drivers: A Two-Stage Cluster Analysis for Interpretable House Price Predictions

---

## How to Run

1. Install dependencies:
   pip install numpy pandas scikit-learn xgboost matplotlib seaborn

2. Open any notebook:
   jupyter lab

3. Run cells sequentially to reproduce preprocessing, training, evaluation, and visualizations.

---

## Final Report

The final report (IEEE format) summarizes:  
Dataset, preprocessing, methodology, classical models, literature models, evaluation, discussion, limitations, and conclusion.

---

## Author

Aniruddha Deshpande  
University of North Carolina at Charlotte  
Email: adeshp25@charlotte.edu
