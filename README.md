# Retail_Store_Sales_Forecasting
📌 Methodology used for sales forecasting
1. 🧪 Exploratory Data Analysis (EDA)
  Conducted univariate analysis, time series visualization, and seasonal decomposition to identify key trends, seasonality, and patterns in historical sales data.

2. 📈 Feature Analysis
  Analyzed business drivers:

  Promotion Lift: +10.14%

  Holiday Lift: +37.76%

  These findings highlight the significant influence of promotional campaigns and holidays on sales performance.

3. 🧠 Statistical Analysis
  Performed stationarity checks using:

  Augmented Dickey-Fuller (ADF) Test

  KPSS Test

4. 🛠️ Feature Engineering
   Generated:

  Lag features

  Time-based features (month, day, week, etc.)

  Seasonality encodings

  These enriched the dataset to enhance forecasting accuracy.

5. 🤖 Model Selection & Training
  Evaluated the following forecasting models:

  Naive

  Simple Exponential Smoothing

  ARIMA

  SARIMA

  Holt-Winters

  The Holt-Winters model performed best based on MAE, RMSE, and MAPE.

6. 🔮 Forecasting
  Used the optimized Holt-Winters model to forecast sales for the next six months.



