# Ajmer Time Series Analysis

This project forecasts a 5-year temperature trajectory for Ajmer, India, comparing statistical models (SARIMA) against curve-fitting models (Facebook Prophet).

### 5-Year Temperature Forecast (SARIMA)
![SARIMA Forecast](sarima_forecast.png)

### SARIMA Diagnostics
I verified the model successfully captured seasonal patterns leaving only random noise:
![SARIMA Diagnostics](sarima_diagnostics.png)

### Facebook Prophet Forecast
Notice how Prophet handles the massive 1860s missing data gap by widening its confidence interval:
![Facebook Prophet Forecast](prophet_forecast.png)
