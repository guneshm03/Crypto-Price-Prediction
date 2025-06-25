# 🧠 Cryptocurrency Price Prediction (2018–2024)

This project predicts future cryptocurrency prices using historical market data and an LSTM neural network. I used real Bitcoin (BTC-USD) price data from 2018 to 2024, cleaned and prepared it, and built an LSTM model to forecast prices and evaluate performance.

---

## 📁 Dataset

- **Name**: `crypto_market_data_2018_2024.csv`
- **Description**: Contains daily open, high, low, close, and volume data for various cryptocurrencies from 2018 to 2024.

---

## 🛠️ Technologies Used

- Python (Google Colab)
- Pandas, NumPy, Matplotlib
- Scikit-learn
- TensorFlow + Keras (LSTM)
- MinMaxScaler (for feature scaling)

---

## 📈 Key Features

- Data Cleaning & Preprocessing (handling missing/zero values)
- Feature Scaling with MinMaxScaler
- LSTM Model trained to predict next-day closing price
- Model evaluation using RMSE, MAE, MSE
- Future forecasting for the next 30 days
- Visualization of:
  - Actual vs Predicted prices
  - Training & validation loss
  - Future price trends

---

## 📊 Example Output
![plot (1)](https://github.com/user-attachments/assets/7125497b-30e6-4df1-a7ef-dd5f854af65f)
![plot (2)](https://github.com/user-attachments/assets/a54bb0af-eafb-46f3-800f-cca0ba07c73c)
![plot (3)](https://github.com/user-attachments/assets/bc4d108c-98e2-4e3a-9bb9-f7482a0948d2)




---

## 🔮 What's Next?

In future updates, I plan to:
- Integrate technical indicators (e.g., RSI, MACD)
- Try GRU or Transformer models
- Backtest predictions against real market movement

---

## 🚀 How to Run

1. Clone this repo
2. Open the Jupyter notebook (`Chatgpt_project_one_crypto.ipynb`) in Google Colab or locally
3. Upload the CSV file (`crypto_market_data_2018_2024.csv`)
4. Run all cells in sequence

or just click below:
📓 [View the Full Notebook](Project_crypto_prediction_lstm.ipynb)

---

## 🤝 Acknowledgments

Built with guidance from ChatGPT and a passion for learning how AI can be applied to financial data.
