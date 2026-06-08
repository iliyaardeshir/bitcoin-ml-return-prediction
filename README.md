# Bitcoin Daily Return Prediction Using Machine Learning

## Project Overview

This project investigates whether machine learning models can predict next-day Bitcoin log returns using technical indicators.

The study compares two models:

- Artificial Neural Network
- Random Forest

## Data

Bitcoin price data (BTC-USD) from Yahoo Finance.

Period: 2018–2024  
Frequency: Daily  
Target variable: Next-day log return

## Models

Two machine learning models are used:

- Artificial Neural Network (ANN)
- Random Forest

## Evaluation Metrics

- RMSE
- MAE
- R-squared

## Results

| Model | RMSE | MAE | R² |
|---|---:|---:|---:|
| ANN | 0.02609 | 0.01857 | -0.0007 |
| Random Forest | 0.02692 | 0.01958 | -0.0656 |

## Conclusion

The ANN model slightly outperformed the Random Forest model.  
However, both models show negative out-of-sample R² values, indicating that predicting daily Bitcoin returns remains highly challenging.
