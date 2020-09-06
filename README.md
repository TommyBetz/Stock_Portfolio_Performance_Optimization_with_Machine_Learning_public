# Churn Classification - Logistic Regression model and Artificial Neural Network

## Project Goal
Applying Machine Learning for Long Position Stock Portfolio Performance Optimization

- The code for this project is private.
- The project overview is available at https://bit.ly/stock_portfolio_project


## Tasks
- Scraping and processing public analyst ratings and targets to predict NASDAQ stock prices 30 days ahead.
- Applying models of type neural network (Keras: KNN, ANN) and regression (scikit-learn: ElasticNet, Ridge, Lasso, simple linear regression) with k-fold cross-validation.
- Building an algorithm that dynamically and continuously selects the best model to predict the stock with the highest return.

## Findings
My model:
 • only includes long positions and does not include any derivatives or leverage.
 • is either in line with the chosen market indices (NASDAQ and S&P 500) with the exception of 2018 or is able to outperform the market.
 • depends heavily on the market's performance, meaning this model is not recommended when the market is in a downturn.
