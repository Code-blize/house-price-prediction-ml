# House Price Prediction: Ensemble Methods vs Deep Learning

This project compares the performance of ensemble learning methods and deep learning models for house price prediction on a real-world tabular dataset.

## Overview

The goal of this project is to evaluate how traditional ensemble methods such as Random Forest and Gradient Boosting perform against a Multi-Layer Perceptron (MLP) on a regression task.

The analysis showed that **Gradient Boosting** achieved the best performance, suggesting that ensemble methods can outperform deep learning on structured tabular data.

## Dataset

- **Source:** [House Price Prediction Challenge - Kaggle](https://www.kaggle.com/datasets/anmolkumar/house-price-prediction-challenge)
- **Size:** 29,451 training samples
- **Features:** 12 variables including location, size, and amenities
- **Target:** House prices in Lacs

## Tools and Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- KaggleHub
- Jupyter Notebook

## Models Implemented

### Ensemble Methods
- **Random Forest** — R² Score: 0.7436
- **Gradient Boosting** — R² Score: 0.7774

### Deep Learning
- **Multi-Layer Perceptron (MLP)** — R² Score: 0.5656  
  - 2 hidden layers (64, 32 neurons)
  - ReLU activation
  - Adam optimizer

## Key Findings

- **Gradient Boosting** achieved the best overall performance with the lowest RMSE
- **Ensemble methods** outperformed deep learning on this tabular dataset
- The most important predictive features included **square footage, longitude, and latitude**
- The MLP showed potential, but would require further tuning to compete

## Results Visualization

### Model Performance Comparison
![Model Comparison](https://github.com/user-attachments/assets/5877f51a-fad4-4153-b853-a9cae878de48)

### Feature Importance Analysis
![Feature Importance](https://github.com/user-attachments/assets/794d3edb-c92e-4885-83f7-56dfb86934d3)

## How to Run

### Option 1: Google Colab
[Open in Colab](https://github.com/Code-blize/house-price-prediction-ml/blob/main/Obasi_Uzoma%20B.%20Module%201.ipynb)

### Option 2: Local Setup

```bash
git clone https://github.com/Code-blize/house-price-prediction-ml.git
cd house-price-prediction-ml
jupyter notebook "Obasi_Uzoma B. Module 1.ipynb"
