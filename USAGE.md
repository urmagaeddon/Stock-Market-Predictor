📄 USAGE.md


This guide explains how to use StockPredictorinator to make predictions.

This will:
Download S&P 500 historical data

Generate features

Train a model

Backtest results

Print metrics

2. Key Functions
Backtesting
python

predictions = backtest(sp500, model, predictors)
Runs a rolling-window backtest, retraining the model at each step.

Precision Score
python

from sklearn.metrics import precision_score
precision_score(predictions['Target'], predictions['Predictions'])
Measures how often positive predictions are correct.

3. Extending the Model
Add new predictors (e.g., RSI, MACD, sentiment analysis).

Replace RandomForest with other ML models (XGBoost, LSTM).

Adjust n_estimators and min_samples_split for optimization.

4. Example Output

Precision Score: 0.57
Predictions Distribution:
0    1420
1     980
dtype: int64
