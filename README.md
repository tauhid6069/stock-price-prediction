# Stock Price Prediction using Recurrent Neural Networks (RNN)

This project applies **Recurrent Neural Networks (RNNs)**, specifically **LSTMs**, to forecast stock price trends based on historical financial data. The notebook demonstrates the complete workflow from preprocessing stock market data to training, evaluating, and visualising predictions.

---

## 📌 Project Overview
Financial markets generate highly sequential and time-dependent data. RNNs are designed to capture temporal dependencies, making them well-suited for stock price forecasting.

This project trains an **LSTM model** to predict future stock closing prices using past stock values.

---

## ✨ Features
- Load and preprocess historical stock price dataset  
- Normalize and window time-series data for training  
- Build and train an **LSTM model with TensorFlow/Keras**  
- Visualize predicted vs actual stock price trends  
- Evaluate performance with error metrics  

---

## 📂 Repository Structure
```
.
├── notebooks/
│   └── rnn-for-stock-price-prediction.ipynb
├── requirements.txt
└── README.md
```

---

## 🚀 Getting Started

### 1) Clone the repo
```bash
git clone https://github.com/tauhid6069/stock-price-prediction.git
cd stock-price-prediction
```

### 2) Install dependencies
```bash
pip install -r requirements.txt
```

### 3) Run the notebook
```bash
jupyter notebook notebooks/rnn-for-stock-price-prediction.ipynb
```

---

## 📊 Models Used
- **Recurrent Neural Networks (RNNs)**  
- **Long Short-Term Memory (LSTM)**  

---

## 📈 Evaluation Metrics
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  

---

## 📂 Dataset
This project requires a **historical stock price dataset**.  
You can use:
- **Google Stock Price** dataset

---

## 👤 Author
**Md Tauhidul Islam**  
[LinkedIn](www.linkedin.com/in/tauhidul-islam) 
