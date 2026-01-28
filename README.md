# 📈 Time Series Forecasting Project

## 📌 Problem Statement
This project focuses on forecasting complex multivariate time series data using deep learning models enhanced with attention mechanisms.  
We compare modern architectures (LSTM + Attention, Transformer Encoder) against traditional benchmarks (ARIMA, SARIMA) and analyze attention weights for interpretability.

---

## ⚙️ Project Workflow

1. **Dataset**  
   - Synthetic multivariate time series with trend, seasonality, noise, and lagged dependencies.

2. **Preprocessing**  
   - Scaled using MinMaxScaler  
   - Converted into supervised sequences (window size = 12)

3. **Models Implemented**  
   - ARIMA  
   - SARIMA  
   - LSTM  
   - LSTM + Attention  
   - Transformer Encoder

4. **Evaluation**  
   - Metrics: MAE, RMSE, MAPE  
   - Rolling-Origin Cross Validation (ROCV)  
   - Hyperparameter tuning for Attention model

5. **Interpretability**  
   - Visualization of attention weights to highlight temporal focus

---

## 📊 Final Model Performance

- **Model**: Tuned LSTM + Attention  
- **LSTM Units**: 128  
- **Learning Rate**: 0.001  
- **Batch Size**: 64  
- **Epochs**: 100  
- **MAE**: 0.0492  
- **RMSE**: 0.0700  
- **MAPE**: 8.1590%

---

## ✅ Completed Tasks

- ✅ Dataset generated and preprocessed  
- ✅ Baseline models: ARIMA, SARIMA, LSTM  
- ✅ Attention-based model implemented  
- ✅ Hyperparameter tuning completed  
- ✅ Final metrics reported (MAE, RMSE, MAPE)  
- ✅ Attention weights visualized

---

## 🔗 Open Notebook in Google Colab
[Click here to run the notebook in Colab](https://colab.research.google.com/github/MercyFlora/Timeseries/blob/main/final_proj.ipynb)

---

## 💡 Insights & Next Steps

- Larger LSTM units + moderate learning rate + bigger batch size + more epochs improved accuracy.
- Future improvements:
  - Explore wider hyperparameter ranges
  - Try advanced tuning strategies like Bayesian optimization

