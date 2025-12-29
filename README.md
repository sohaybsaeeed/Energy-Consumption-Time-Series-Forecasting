# Energy-Consumption-Time-Series-Forecasting
1. Data Preprocessing
Parses datetime from separate Date/Time columns

Resamples to hourly frequency for stable patterns

Handles missing values appropriately

2. Feature Engineering
Temporal Features: Hour, day of week, month, weekend indicator

Cyclical Encoding: Sine/cosine transformation for hour (preserves cyclical nature)

Lag Features: Previous hour, same hour yesterday, same hour last week

Rolling Statistics: 3-hour, 24-hour, and 7-day moving averages

3. Three Forecasting Models
ARIMA: Traditional time series model for baseline

Facebook Prophet: Handles seasonality and holidays automatically

XGBoost: Gradient boosting with engineered features

4. Model Evaluation
MAE (Mean Absolute Error): Average absolute difference

RMSE (Root Mean Square Error): Penalizes larger errors more

5. Visualizations
Last 7 days of consumption

Daily and weekly patterns

Forecast vs actual comparison

Model performance comparison

Feature importance (XGBoost)
