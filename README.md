// Objective: 
Predict the next day's closing price of a stock using historical market data and machine learning models.

// Dataset:

1) Source: Yahoo Finance (via `yfinance` Python library)
2) Example Stock: Apple (AAPL)
3) Features used: `Open`, `High`, `Low`, `Volume`
4) Target: Next day's `Close` price

// Models Used:

1. **Linear Regression**  
   1.1 Simple baseline model
   1.2 Evaluates relationship between historical features and next day closing price

2. **Random Forest Regressor**  
   2.1 Ensemble tree-based model
   2.2 Handles non-linear relationships
   2.3 Typically more accurate than linear regression

// Implementation Steps:

1. Load historical stock data using `yfinance`
2. Prepare features (`Open`, `High`, `Low`, `Volume`) and target (next day's `Close`)
3. Split data into training and testing sets
4. Train models: Linear Regression and Random Forest
5. Predict next day's closing price
6. Evaluate model performance (MSE, R²)
7. Plot **actual vs predicted closing prices** for comparison

// Results:

1) Both models predict next-day close prices accurately  
2) Random Forest generally gives lower MSE and better fit  
3) Visualization shows alignment between actual and predicted prices

Author:
Danish Zulfiqar
