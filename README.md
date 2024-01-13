# Bitcoin Price Prediction and Trading Strategy

This repository contains code for predicting Bitcoin prices using an ARIMA model and implementing a mean-reversion trading strategy.

## About the Project

The project consists of two main parts:

1. **Bitcoin Price Prediction:**
   - The notebook `Untitled11.ipynb` uses historical Bitcoin price data to train an ARIMA model.
   - The model is evaluated using root mean squared error (RMSE), and predictions are plotted against actual outcomes.

2. **Mean-Reversion Trading Strategy:**
   - The script `mean_reversion_strategy.py` implements a simple mean-reversion trading strategy based on ARIMA predictions.
   - Trading metrics such as capital evolution, gross profit, net profit, win rate, and others are calculated and printed.

## Prerequisites

- Python 3.x
- Libraries: numpy, pandas, statsmodels, matplotlib, seaborn, scikit-learn

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/bitcoin-price-prediction.git
   cd bitcoin-price-prediction
   ```
## Results
- The ARIMA model's predictions are visualized and compared with actual Bitcoin prices.
- Trading metrics such as net profit, win rate, and risk-reward ratio are printed for the mean-reversion strategy.
