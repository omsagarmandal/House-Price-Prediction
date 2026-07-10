# House Price Prediction

Beginner-friendly machine learning project that predicts house prices using linear regression.

## Overview

This project estimates house prices from features like size, room count, location, and age, using a linear regression model trained on the Kaggle "House Prices: Advanced Regression Techniques" dataset.

## Project structure

House-Price-Prediction/  
├── data/                  # train.csv, test.csv  
├── notebooks/        # Jupyter/Colab notebooks  
├── src/                    # Python scripts  
├── models/            # saved trained models  
└── images/            # charts and graphs

## Tools

*   Python
*   Pandas, NumPy
*   Matplotlib, Seaborn
*   Scikit-learn

## How to run

1.  Clone this repo
2.  Install requirements: pip install -r requirements.txt
3.  Open the notebook in Jupyter or VS Code
4.  Run the cells step by step

## Dataset

Kaggle's House Prices - Advanced Regression Techniques dataset.

## Model

Linear Regression.

## Results

*   MAE: 20,388.65
*   RMSE: 51,973.14
*   R2: 0.6478

An R2 of 0.65 means the model explains about two thirds of the variance in price, a reasonable baseline for a first pass with plain linear regression. Feature engineering or a tree-based model would likely close some of the gap.

## Author

Om Sagar