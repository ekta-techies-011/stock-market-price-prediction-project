# 📈 Stock Market Price Prediction Project

This is a stock price prediction web application built using **Streamlit**, **Machine Learning models**, and **stock data**.  
It predicts the **future price of a stock** (e.g., MSFT - Microsoft) for upcoming days and also provides graphical visualizations.

---

## 🚀 Features

- 📊 Predict stock prices using **Linear Regression** and **Random Forest**
- 📈 Visualize past stock trends and future predictions
- 🔐 Simple **Login/Signup system** using `users.json`
- 📁 Upload your own dataset (`.csv`) or use default (MSFT)
- 📉 Technical indicators and performance evaluation metrics
- 📦 Easy to deploy and run

---

## 🧠 Machine Learning Models Used

- **Linear Regression** – For trend-based price prediction
- **Random Forest Regressor** – For more accurate prediction using ensemble learning
- **Random Forest Classifier** – For Buy/Sell signal prediction (if included)

---

## 🗂️ Project Structure
📁 stock-market-price-prediction-project/
├── app.py # Main Streamlit app
├── demostockprice.ipynb # Jupyter notebook for ML model
├── MSFT_data.csv # Sample dataset (Microsoft stock)
├── users.json # Stores user login info
├── requirements.txt # Python dependencies
└── README.md # This file


---

## ⚙️ How to Run the Project

### 🖥️ 1. Clone the repository
```bash
git clone https://github.com/ekta-techies-011/stock-market-price-prediction-project.git
cd stock-market-price-prediction-project

## INSTALL THE DEPENDICIES
pip install -r requirements.txt

##RUN THE APP
streamlit run app.py





