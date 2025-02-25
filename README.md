# Stock Prediction
## Introduction

This repository contains implementations of two models for stock price forecasting and automated trading:

1. **Stock Price Prediction Model:** A transformer-based deep learning model that analyzes historical stock data and technical indicators to predict future price movements with high accuracy.
2. **PPO-Based Trading Agent:** A reinforcement learning model utilizing the **Proximal Policy Optimization (PPO)** algorithm to make trading decisions (Buy, Sell, Hold) in a simulated environment, aiming to maximize cumulative returns.

These models offer complementary functions—one focuses on price forecasting, while the other executes trading strategies based on market conditions.

## Dataset

The models are trained using high-frequency trading data from the **XNAS ITCH Dataset**, which includes order book updates, executed trades, and market activity details. Access the dataset here: [XNAS ITCH Dataset](https://databento.com/datasets/XNAS.ITCH).

## Installation

To set up the project, clone the repository and install dependencies:

```bash
git clone https://github.com/adi-tya-singh/Stock-Recommendation.git
cd Stock-Recommendation
pip install -r requirements.txt
```





