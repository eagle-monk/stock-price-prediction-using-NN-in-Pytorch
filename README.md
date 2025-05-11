# stock-price-prediction-using-NN-in-Pytorch
This project implements a stock price prediction model using a feedforward neural network built with PyTorch. It trains on historical stock data and forecasts future prices, focusing on minimizing prediction error through Root Mean Squared Error (RMSE).

# 📈 Stock Price Prediction using Neural Networks in PyTorch

This project demonstrates how to use a feedforward neural network (NN) implemented in **PyTorch** to predict stock prices based on historical data. It showcases model training, evaluation using RMSE, and visualization of prediction performance.

---

## 🔧 Project Overview

- **Objective:** Predict future stock prices using a neural network.
- **Approach:** Supervised learning using historical price data (Open, High, Low, Close, Volume, etc.)
- **Framework:** PyTorch (for model development and training)

---

## 📁 Project Structure

├── data/ # Historical stock data (CSV)
├── models/ # Saved PyTorch models
├── notebooks/ # Jupyter notebooks for experimentation
├── utils.py # Utility functions for preprocessing
├── model.py # Neural Network architecture
├── train.py # Training script
├── evaluate.py # Evaluation and visualization
├── requirements.txt # Required packages
└── README.md # Project overview


---

## 📊 Results

| Metric        | Value      |
|---------------|------------|
| Train RMSE    | 122.604385     | on BAJFINANCE.NS
| Test RMSE     | 167.22308     | on BAJFINANCE.NS

> A noticeable difference between training and test RMSE suggests room for generalization improvement, may vary in diffent stocks

---

## 📌 Features

- Cleaned and preprocessed stock market dataset
- Simple feedforward NN using `torch.nn`
- Training loop with loss tracking and optimizer
- RMSE-based performance evaluation
- Price prediction visualization using `matplotlib`

---

## 📦 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt

Main Libraries Used:
PyTorch

Pandas

NumPy

Matplotlib

🚀 How to Run
Prepare your data
Place your stock price CSV in the /data folder.

Train the model

bash
Copy
Edit
python train.py
Evaluate and visualize

bash
Copy
Edit
python evaluate.py
📈 Sample Prediction Plot
(Insert a matplotlib prediction-vs-actual graph here)

🛠️ Future Improvements
Add recurrent models like LSTM or GRU for time-series context

Incorporate technical indicators (MACD, RSI, etc.)

Perform hyperparameter optimization (grid search / Optuna)

Deploy using Streamlit or Flask

📬 Contact
For questions, suggestions, or collaboration:

Name: OMM Narayan Tikolia
Email: otikolia@gmail.com
GitHub: https://github.com/eagle-monk
