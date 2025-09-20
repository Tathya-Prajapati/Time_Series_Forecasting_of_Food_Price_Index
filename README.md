# 📈 Time Series Forecasting of Food Price Index (FPI)

A research project focused on building and comparing statistical and deep learning models to forecast the Food Price Index (FPI)-a key economic indicator used to track global food price trends. This study explores hybrid modeling techniques to improve prediction accuracy in the presence of seasonal, nonlinear, and volatile data patterns.

---

## Project Objectives

- Forecast future values of the Food Price Index (FPI) using various time series models.
- Compare classical statistical models (ARIMA, SARIMA, SARIMAX) with deep learning models (RNN, LSTM, GRU).
- Performed exploratory data analysis and stationarity tests (ADF), ACF/PACF analysis.

---

## Key Features

- **Exploratory Data Analysis (EDA):** Trend, seasonality, ADF test, ACF/PACF plots.
- **Statistical Models:** ARIMA, SARIMA, SARIMAX (with exogenous variables).
- **Deep Learning Models:** RNN, LSTM, GRU (built using Keras & TensorFlow).
- **Performance Metrics:** RMSE, AIC for evaluation and comparison.
- **Hybrid Modeling:** Integrating domain knowledge from statistical analysis into neural models for better generalization.

---

## Technologies Used

| Category       | Tools / Libraries                      |
|----------------|----------------------------------------|
| Programming    | Python                                 |
| Statistical ML | ARIMA, SARIMA, SARIMAX (statsmodels)   |
| Deep Learning  | Keras, TensorFlow                      |
| Visualization  | Matplotlib                             |
| Evaluation     | RMSE, AIC                              |

---

## Project Structure

```plaintext
├── dataset/                  # Raw and cleaned FPI datasets
├── notebooks/                # Jupyter notebooks for EDA and modeling
├── results/                  # Graphs, plots, and performance metrics
├── README.md                 # Project overview
└── report/                   # Final research paper (PDF)
