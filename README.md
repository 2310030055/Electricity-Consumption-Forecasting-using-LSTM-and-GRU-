# Electricity-Consumption-Forecasting-using-LSTM-and-GRU-
Electricity Consumption Forecasting using LSTM and GRU predicts future household power usage from historical data. By leveraging deep learning sequence models, it captures temporal patterns to support efficient energy management and smart grid optimization.

## 📌 Project Overview

This project predicts electricity consumption using deep learning models (LSTM & GRU).
We preprocess household electricity data, train forecasting models, and compare their performance.

The notebook is designed for Google Colab so you can run it end-to-end with GPU acceleration.

## 📂 Project Structure
```
├── Electricity_Forecasting_LSTM_GRU.ipynb   # Main Colab Notebook
├── artifacts/                               # Saved models & predictions
│   ├── lstm_model.keras
│   ├── gru_model.keras
│   ├── test_predictions.csv
│   └── next24_forecast.csv
├── data/                                    # (Optional) Place your custom dataset here
└── README.md
```

## ⚙️ Features
- Data preprocessing & resampling to hourly consumption

- Scaling and sequence creation for time series forecasting

- Two models implemented:

     1) LSTM (Long Short-Term Memory)

     2) GRU (Gated Recurrent Unit)

- Model training with EarlyStopping & LR scheduling

- Performance evaluation with RMSE, MAE, MAPE

- Plots:

   1. Training loss curves

   2. Actual vs Predicted consumption

   3. Next 24-hour forecast

Export models & results for reuse

## 📊 Dataset
We use the Individual Household Electric Power Consumption dataset from the
UCI Machine Learning Repository.

By default, the notebook downloads it automatically.

## 🚀 How to Run (in Google Colab)

1. Open the notebook: [Link to Google Colab](https://colab.research.google.com/)
2. Change runtime to GPU:  
   **Runtime** → **Change runtime type** → **GPU**
3. Run all cells:  
   **Runtime** → **Run all**

---

### ✅ Results:

- **Metrics**:  
  - RMSE  
  - MAE  
  - MAPE

- **Plots**:  
  - Predictions vs Actuals

- **Forecast**:  
  - 24-hour ahead forecast

- **Artifacts Saved**:
  - Models (`.keras` files) + CSVs in `artifacts/`

## 🛠️ Tech Stack

- Python 3

- TensorFlow / Keras

- NumPy, Pandas, Matplotlib

- scikit-learn

## 📜 License

This project is licensed under the MIT License – feel free to use and modify.
