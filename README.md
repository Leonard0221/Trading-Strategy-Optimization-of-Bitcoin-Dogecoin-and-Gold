# Trading Strategy Optimization of Bitcoin, Dogecoin, and Gold in the Cryptocurrency Market

## Overview

Nowadays, financial activities have become an integral part of people’s lives, with trading being a popular avenue for potential profits. However, the outcomes of trading can vary greatly, and this can be attributed not only to the choice of assets but also to the trading strategies employed. This project aims to explore and optimize trading strategies for Bitcoin, Dogecoin, and Gold in the cryptocurrency market.

## Models

### Model I - Volatile Asset Price Forecasting Model

The primary objective of Model I is to forecast asset prices accurately to form the foundation for trading strategy formulation. The model follows a prudent approach of predicting one day ahead in each run. To achieve accurate forecasts, the ARIMA (AutoRegressive Integrated Moving Average) model is applied after testing and manipulating the stationary data. Carefully selected hyperparameters for ARIMA emphasize recent price data to predict future price movements effectively. The model demonstrates high accuracy, with an R-squared value of over 0.98 for all assets.

### Model II - Strategy Improvement Model

In Model II, the focus shifts to the development of the trading strategy. The dynamic programming method is utilized to break down the five-year investment period into day-to-day investment decisions. Each day, the model performs constrained minimization of multivariate scalar functions using the Python package scipy. By implementing this model, a remarkable return of approximately 770% is achieved by the end of the 5-year investment period.

The objective function of the model considers the maximum next-day profit rate while also penalizing fluctuations. This allows for the analysis of different investor risk profiles, with risk-preferred investors earning more than risk-averse investors due to the significant fluctuations that cryptocurrencies can experience within a short timeframe.

## Sensitivity Analysis

The project includes a sensitivity analysis to ensure the stability of the models. The results demonstrate promising ultimate returns with different initial budgets. However, an increase in commission fees can reasonably reduce the overall return. Based on these findings, appropriate advice is provided to investors accordingly.

## Early Timeframe Testing

Through testing the trading strategy in early timeframes, it is evident that implementing the strategy when Bitcoin prices are lower can lead to significantly increased ultimate returns. For instance, if the model starts the investment before 2016, investors can earn over 8000% returns compared to their initial investment.

## Evaluation of Trading Strategies

During the evaluation of various trading strategies, it becomes evident that focusing on larger cryptocurrencies like Bitcoin is advisable. These cryptocurrencies exhibit promising growth with relatively lower volatility. Conversely, the value of smaller cryptocurrencies like Dogecoin can be highly volatile, experiencing dramatic increases but also sharp declines in a short span. To avoid over-allocating in Dogecoin and potentially losing a significant amount when its price drops, the trading strategy must consider both profit rate and punishment for possible fluctuations.

## Final Essay

For detailed insights into our project's methodologies, results, and conclusions, please refer to the [Final Essay.pdf](link-to-the-file) document.

## Disclaimer

The information and results presented in this project are for educational purposes only. Trading and investment decisions should not solely rely on the findings of this study. Always exercise caution and perform additional research before making financial decisions. The authors and contributors to this project are not responsible for any financial losses incurred based on the content of this project.
