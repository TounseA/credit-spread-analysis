# Credit Spread Dataset 

This dataset contains macroeconomic and market data pulled from [fredapi](https://pypi.org/project/fredapi/) and [yfinance](https://pypi.org/project/yfinance/). The dataset consists of monthly data spanning from 2000 - 2025.

### Dataset Dictionary

| Feature | Description |
| ------- | ----------- |
| `spread`  | Moody's BAA-rated corporate bond yield spread |
| `unrate`  | Unemployment rate |
| `fedfunds` | Policy interest rate (Federal Funds Rate) |
| `yield_curve` | Yield curve slope (10Y - 2Y) |
| `vix_monthly` | Monthly VIX average | 
| `sp500_monthly` | S&P 500 monthly compounded retunrs |
| `vix_lag1` | Lagged VIX (1 month lag of `vix_monthly`)|
| `fedfunds_delta` | Monthly change in policy interest rates |
| `inflation_yoy` | Year-on-year changes in inflation (CPI) |
| `production_yoy` | Year-on-year changes in industrial production | 

**Note:** All features are aligned to a monthly start (`MS`) frequency. 