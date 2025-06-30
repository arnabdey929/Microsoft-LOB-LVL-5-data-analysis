# Microsoft-LOB-LVL-5-data-analysis
An in-depth analysis of Microsoft Limit Order Book history data

## Data Cleaning
LOB data needs to be thoroughly understood, the bid and ask prices, and the same is done in the $1^{st}$ section of the notebook.
## Market Microstructure Analysis
-Average Bid-Ask spread over time, and the order depths show the supply and demand for the stocks.

-Mid Price Changes show the average of the best bid and ask prices over time.

-Price imbalance is an important factor, and in this case turned out to be the most prominent factor.

-Order Flow Imbalances shows the differences between the buy and sell orders at some specific price level.

-Buy and sell crossings show when the mid price crosses the previous ask or bid.
## Predicting Short-Term Price Movement
-First we need to generate trainable data and corresponding labels.

-In the notebook, I have compared Random Forests, Logistic Regressor, and XGBoost as classical ML models, and an MLP for comparison.
## Trading Signal Generation and Backtesting
-In the notebook is shown the order size logic with fixed order size 1. We buy/sell/hold according to the signal of mid-price movement.

-Backtesting framework has been shown using P&L per trade logic, Sharpe ratio, and Maximum drawdown.
## Real-Time feasibility
-Finally, we use SHAP and Permutation importance to see which features are the most important factor in making decisions

# Reference
Rama Cont slides
