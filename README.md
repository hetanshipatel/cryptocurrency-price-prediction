# Comparative Analysis of Machine Learning Models for Cryptocurrency Price Prediction

## Project Overview

This project aims to compare the performance of three machine learning models for predicting cryptocurrency prices:

1. **Long Short-Term Memory (LSTM)**
2. **Bidirectional LSTM (Bi-LSTM)**
3. **Random Forest Regression**

Using historical price data for Bitcoin (BTC) and Ethereum (ETH), we analyze which model performs best for price prediction based on metrics like RMSE, MSE, and MAE.

## Repository Contents

- **BTC-GBP.csv**: Historical price data for Bitcoin.
- **ETH-GBP.csv**: Historical price data for Ethereum.
- **Final_Code.ipynb**: Python code written in Jupyter Notebook (Colab-compatible) that performs data preprocessing, model training, and evaluation.
- **Final Project by Hetanshi Patel.pdf**: Final project report, detailing methodology, results, and conclusions.
- **README.md**: Project documentation and instructions for replication.

## Installation and Setup

### Prerequisites

Ensure you have the following installed on your system:

- Python 3.7+
- Jupyter Notebook or Google Colab
- Required Python libraries (listed in `requirements.txt`):
  - `tensorflow`
  - `scikit-learn`
  - `pandas`
  - `numpy`
  - `matplotlib`

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/cryptocurrency-price-prediction.git
   ```

2. Navigate to the project directory:

   ```bash
   cd cryptocurrency-price-prediction
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Running the Project

### Option 1: Using Jupyter Notebook

1. Open a terminal and navigate to the project folder.
2. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Open the file `Final_Code.ipynb` in the Jupyter interface.
4. Execute the cells sequentially to preprocess data, train models, and evaluate results.

### Option 2: Using Google Colab

1. Open [Google Colab](https://colab.research.google.com/).
2. Click on **File > Upload Notebook** and upload `Final_Code.ipynb`.
3. Execute the cells sequentially.

## Project Workflow

1. **Data Preprocessing**:
   - Load and clean the datasets (`BTC-GBP.csv` and `ETH-GBP.csv`).
   - Normalize the data for machine learning models.

2. **Model Training**:
   - Train LSTM, Bi-LSTM, and Random Forest models on the datasets.

3. **Model Evaluation**:
   - Evaluate performance using metrics like RMSE, MSE, and MAE.
   - Visualize actual vs predicted prices.

## Results

- **Bitcoin**:
  - Best Model: Random Forest
  - RMSE: 0.0132

- **Ethereum**:
  - Best Model: Random Forest
  - RMSE: 0.0113

The Random Forest Regressor outperformed both LSTM and Bi-LSTM models for predicting cryptocurrency prices.

## Conclusion

This study demonstrates the effectiveness of machine learning models for cryptocurrency price prediction. The Random Forest model provides the most accurate predictions, making it a reliable choice for dynamic markets like cryptocurrency.

## Author

**Hetanshi Kachhiya Patel**

This project was submitted as part of the MSc Data Science program at the University of Hertfordshire.

---

**Disclaimer:** The project is for academic purposes only and does not provide financial advice. Cryptocurrency markets are volatile, and predictions should not be solely relied upon for investment decisions.
