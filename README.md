# Time Series Forecasting with ARIMA

## Overview
To show how to use `pandas` and `statsmodels` libraries for forecasting with ARIMA and several of its variants. Several jupyter notebooks introduce the topic in a gradual fasion, starting with an introduction to forecasting and ending with seasonal ARIMA with exogenuous variables aka SARIMAX.

## Problem Statement
- How to build ARIMA models for stationary and non-stationary time series?
- How to evaluate ARIMA models?
- How to produce future forecasts using fitted ARIMA models?
- How to visualize forecasts?

## Methods/Architecture
- ARIMA
- SARIMA
- SARIMAX

## Requirements
```bash
numpy
pandas
statsmodels
matplotlib
scikit-learn
ipykernel
python-dotenv
```
## Project Structure

```basic
├── data/              # Dataset files
│   ├── processed/     # Cleaned and processed data
│   └── raw/          # Original data
├── notebooks/         # Jupyter notebooks
├── .gitignore        # Git ignore file
├── README.md         # Project documentation
└── requirements.txt  # Dependencies
```

## Setup and Installation
```bash
git clone https://github.com/oalotaik/time-series-forecasting-with-ARIMA.git
cd time-series-forecasting-with-ARIMA
pip install -r requirements.txt
```


## Citation
If this project was useful for your research, please cite:
```bash
@article{Alotaik2025project,
  title={time-series-forecasting-with-ARIMA},
  author={Alotaik, O.},
  year={2025}
}
```


