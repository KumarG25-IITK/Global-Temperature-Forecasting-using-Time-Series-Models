# Ajmer Time Series Analysis
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

This project forecasts a 5-year temperature trajectory for Ajmer, India, comparing statistical models (SARIMA) against curve-fitting models (Facebook Prophet).

### 5-Year Temperature Forecast (SARIMA)
![SARIMA Forecast](sarima_forecast.png)

### SARIMA Diagnostics
I verified the model successfully captured seasonal patterns leaving only random noise:
![SARIMA Diagnostics](sarima_diagnostics.png)

### Facebook Prophet Forecast
Notice how Prophet handles the massive 1860s missing data gap by widening its confidence interval:
![Facebook Prophet Forecast](prophet_forecast.png)
