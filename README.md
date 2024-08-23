# Netflix-Stock-Price-Prediction-using-LSTM-GRU-and-Bidirectional-LSTM

This repository provides a comprehensive guide to predicting Netflix's stock closing prices using three powerful Recurrent Neural Network (RNN) architectures: Long Short-Term Memory (LSTM), Gated Recurrent Unit (GRU), and Bidirectional LSTM. The project aims to explore the efficacy of these models in time series forecasting, specifically focusing on the stock market data for Netflix.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models Overview](#models-overview)
  - [LSTM](#long-short-term-memory-lstm)
  - [GRU](#gated-recurrent-unit-gru)
  - [Bidirectional LSTM](#bidirectional-lstm)
- [Preprocessing](#preprocessing)
  - [Data Scaling](#data-scaling)
  - [Train-Test Split](#train-test-split)
- [Model Training](#model-training)
  - [Hyperparameter Tuning](#hyperparameter-tuning)
  - [Training Process](#training-process)
  - [Model Evaluation](#model-evaluation)


## Introduction
Predicting stock market prices is a challenging task due to the inherent volatility and complexity of financial markets. However, with the advent of deep learning techniques, specifically Recurrent Neural Networks (RNNs), it has become possible to capture temporal dependencies in time series data, which is crucial for accurate forecasting.

This project explores three RNN-based models—LSTM, GRU, and Bidirectional LSTM—to predict Netflix's stock closing prices. By comparing the performance of these models, we aim to identify the most effective approach for time series forecasting in financial markets.

## Dataset
The dataset used in this project consists of historical stock market data for Netflix, obtained from [Kaggle](https://www.kaggle.com/code/aspillai/nflx-stock-exploratory-data-analysis/input?select=nflx_2014_2023.csv). The data includes the following features:
- Date
- Open
- High
- Low
- Close
- Adj Close
- Volume

For this project, we focus solely on the 'Close' prices to predict future closing prices.
