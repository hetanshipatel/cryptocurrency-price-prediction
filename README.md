# Cryptocurrency Price Prediction Models

This repository contains the final project for my MSc Data Science at the University of Hertfordshire. The project compares different machine learning models for predicting cryptocurrency prices, specifically Bitcoin and Ethereum, using data from Yahoo Finance. The models explored include **LSTM (Long Short-Term Memory)**, **Bi-LSTM (Bidirectional LSTM)**, and **Random Forest Regression**.

## Project Overview

The goal of this project is to evaluate and compare three machine learning models to predict the price trends of Bitcoin and Ethereum. The project is developed using Python and Jupyter notebooks, and it involves training the models on historical data from Yahoo Finance.

### Key Features:
- **Data Source**: Historical data for Bitcoin and Ethereum (BTC-GBP and ETH-GBP) from Yahoo Finance.
- **Models Implemented**:
  - **Random Forest Regression**
  - **LSTM (Long Short-Term Memory)**
  - **Bi-LSTM (Bidirectional LSTM)**
- **Evaluation Metrics**: RMSE, MSE, MAE, and R² for model performance evaluation.
- **Best Performing Model**: Random Forest Regressor showed the best accuracy with the lowest RMSE for both Bitcoin and Ethereum.

## File Descriptions

### `data/`
- **BTC-GBP.csv**: Contains historical Bitcoin price data in GBP.
- **ETH-GBP.csv**: Contains historical Ethereum price data in GBP.

### `notebooks/`
- **Final_Code.ipynb**: Jupyter notebook containing the code for data preprocessing, model training (LSTM, Bi-LSTM, Random Forest), and evaluation. This file is intended to be run on Google Colab.

### `reports/`
- **Final Project by Hetanshi Patel.pdf**: The final project report, including the methodology, results, and analysis.

