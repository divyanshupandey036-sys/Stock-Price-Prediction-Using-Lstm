# Stock-Price-Prediction-Using-Lstm
Stock Market Trend Prediction using LSTM and Streamlit. A deep learning-based web application that forecasts future stock trends using historical market data, TensorFlow, and Yahoo Finance.
# 📈 Stock Market Trend Prediction using LSTM

A Deep Learning-based Stock Market Forecasting Application that predicts future stock price trends using historical stock market data and Long Short-Term Memory (LSTM) networks.

The application fetches real-time stock data from Yahoo Finance, preprocesses the data, trains an LSTM model, and provides stock trend predictions through an interactive Streamlit dashboard.

---

## 🚀 Features

- Real-time stock data collection using Yahoo Finance
- Data preprocessing and normalization
- LSTM-based Deep Learning model
- Historical stock price visualization
- 50-Day Moving Average Analysis
- 100-Day Moving Average Analysis
- Actual vs Predicted Stock Price Comparison
- Next-Day Stock Price Prediction
- Interactive Streamlit Web Interface

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| TensorFlow / Keras | Deep Learning |
| LSTM | Time Series Forecasting |
| Streamlit | Web Application |
| Pandas | Data Processing |
| NumPy | Numerical Computation |
| Scikit-learn | Data Scaling |
| Matplotlib | Data Visualization |
| Yahoo Finance API | Stock Data Collection |

---

## 📊 Project Workflow

### 1. Data Collection
Historical stock market data is collected using the Yahoo Finance API.

### 2. Data Preprocessing
- Remove missing values
- Select closing prices
- Normalize data using MinMaxScaler

### 3. Sequence Generation
Create time-series sequences using previous stock prices to predict future values.

### 4. Model Training
Train an LSTM Neural Network using historical stock price data.

### 5. Prediction
Generate future stock price predictions based on learned market patterns.

### 6. Visualization
Display:
- Historical Prices
- Moving Averages
- Actual vs Predicted Prices
- Future Price Prediction

---

## 📂 Project Structure

```text
StockMarketPrediction/
│
├── app.py
├── requirements.txt
├── stock_lstm_model.h5
├── scaler.pkl
├── README.md
│
├── screenshots/
│   ├── dashboard.png
│   ├── prediction.png
│
└── assets/
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/StockMarketPrediction.git

cd StockMarketPrediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
streamlit run app.py
```

---

## 📈 Model Architecture

The project uses a Long Short-Term Memory (LSTM) Neural Network.

### Architecture

```text
Input Layer
     ↓
LSTM Layer (50 Units)
     ↓
LSTM Layer (50 Units)
     ↓
Dense Layer (25 Units)
     ↓
Output Layer (1 Unit)
```

The model learns historical stock market trends and predicts future price movements.

---

## 🎯 Objective

The primary objective of this project is to apply Deep Learning techniques to financial time-series forecasting and demonstrate the effectiveness of LSTM networks in predicting stock market trends.

---

## 📊 Output

The application provides:

- Historical Stock Price Chart
- Moving Average Analysis
- Actual vs Predicted Price Graph
- RMSE Evaluation Score
- Next-Day Stock Price Forecast

---

## 🔮 Future Enhancements

- Multi-Stock Comparison
- News Sentiment Analysis
- Candlestick Charts
- Portfolio Recommendation System
- Transformer-based Forecasting Models
- Real-Time Prediction Dashboard

---

## 📚 Learning Outcomes

Through this project, the following concepts are implemented:

- Machine Learning
- Deep Learning
- Recurrent Neural Networks (RNN)
- Long Short-Term Memory (LSTM)
- Time Series Forecasting
- Data Visualization
- Model Evaluation
- Streamlit Deployment

---

## 👨‍💻 Author

**Divyanshu Pandey**

Machine Learning & Data Science Enthusiast

---

## ⭐ If you found this project useful, please give it a star!
