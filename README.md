# r/WallStreetBets Sentiment Analysis and Stock Prediction
**CSE342 - Statistical Machine Learning Course Project**

This Git Repository consists of our codes for the SML Project: Sentiment Analysis on r/WallStreetBets and predicting the success of their Market Strategies, CSE342 - Statistical Machine Learning Course Project

**Team Members:**
Ritika Thakur: 2022408
Saksham Singh: 2022434

## Abstract

This project aims to build a simple ML model that allows users to judge whether the market decisions in r/WallStreetBets - the biggest Reddit community for stock trading - are safe for an average person to invest in, and thus automates this process. We have developed a Sentiment Analysis Model and a Stock Prediction model, with future integration of the two being a part of our future scope.

## Problem Statement and Motivation

Social media platforms like Reddit's r/WallStreetBets have become influential forums for stock investment discussions. However, analyzing the vast amount of unstructured data generated by these communities poses a significant challenge. This project aims to develop an AI-driven solution that leverages sentiment analysis on r/WallStreetBets posts to identify potentially lucrative investment opportunities and predict the future value of these stocks.

## Dataset Details

### Sentiment Analysis
We utilized the Reddit-WallStreetBets-Posts dataset on Kaggle, featuring 53K posts from r/WallStreetBets dating from 29-09-2020 to 16-08-2021. The dataset contains post titles, bodies, timestamps, and scores. We preprocessed the data by removing special characters, URLs, and single characters, and then conducted sentiment analysis.

### Stock Prediction Model
We used Yahoo Finance's dataset and the YFinance Python library for stock data. The dataset provides open, high, low, and close prices of every trade day for major listings on Nasdaq. We divided the dataset into train (65%) and test (35%) sets for predicting stock values.

## Literature Review

### Sentiment Analysis
- Hutto, C.J., & Gilbert, E.E. (2014): Introduces the VADER sentiment analysis tool for social media text.
- Kiritchenko, S., & Mohammad, S.M. (2018): Compares sentiment analysis approaches.
- Rosenthal, S., et al. (2015): Presents sentiment analysis challenge focusing on Twitter data.

### Stock Prediction Model
- Fischer, T., & Krauss, C. (2018): Investigates LSTM networks for financial market predictions.
- Tsantekidis, A., et al. (2017): Explores deep learning techniques for price direction prediction in stock market.

## Proposed Architecture

### Sentiment Analysis
1. Text Preprocessing
2. Sentiment Analysis using VADER
3. Feature Engineering
4. Data Visualization
5. Temporal Analysis
6. Correlation Analysis
7. Word Clouds
8. Model Evaluation

### Stock Prediction Model
We used TensorFlow's Sequential model with LSTM and Dense layers for stock prediction, focusing on Apple and Microsoft stocks.

## Results

### Sentiment Analysis
- VADER proved effective in capturing sentiment trends within r/WallStreetBets posts.
- Identified correlations between sentiment and stock discussions.

### Stock Prediction Model
- LSTM demonstrated good regression capability for stock prediction.
- Future predictions showed fluctuations, but overall effectiveness in capturing trends.

## Analysis of Results

### Sentiment Analysis
- VADER algorithm effectively analyzed sentiment trends in r/WallStreetBets posts.
- Identified correlations between sentiment and stock movements.

### Stock Prediction Model
- LSTM proved effective in capturing stock trends based on historical data.

## References

- Inspired by Michael Reeves and Greg Hogg's YouTube videos.
- Wall Street Bets Kaggle dataset.

This project aims to provide valuable insights for investors navigating the complexities of stock market discussions on social media platforms like r/WallStreetBets.
