# Stock-Market-Trend-Prediction-Using-Sentiment-Analysis
This project aims to predict stock price movements based on sentiment analysis of financial news headlines. We fine-tune a BERT model for sentiment analysis on financial news and then scrape the archives of the Economic Times website to gather news headlines from the past year. Using the trained BERT model, we infer sentiment scores for these headlines. Finally, we use the sentiment analysis output and other factors to design a machine learning model to predict whether the stock price will increase or decrease.

# Introduction
Stock price prediction is a challenging task that involves analyzing various factors, including market trends, company performance, and news sentiment. This project focuses on using financial news headlines to predict stock price movements. We leverage state-of-the-art natural language processing (NLP) techniques, specifically BERT (Bidirectional Encoder Representations from Transformers), for sentiment analysis and machine learning models for prediction.

# Fine-tuning BERT for Sentiment Analysis
We fine-tune a pre-trained BERT model on a dataset of financial news articles labeled with sentiment scores (positive, negative, neutral). The fine-tuned model learns to understand the sentiment expressed in financial news, which is crucial for predicting stock price movements.

# Data Collection
We scrape news headlines from the archives of the Economic Times website spanning the past year. The headlines serve as input data for our sentiment analysis model. Additionally, we collect historical stock price data and other relevant financial indicators to use as features for our prediction model.

# Sentiment Analysis
Using the fine-tuned BERT model, we infer sentiment scores for the scraped news headlines. The sentiment scores indicate the polarity of sentiment expressed in each headline, which will be used as features for our stock price prediction model.

# Stock Price Prediction Model
We design a machine learning model that takes the sentiment analysis output, along with other financial indicators, as input features to predict whether the stock price will increase or decrease. We experiment with various machine learning algorithms and evaluate their performance to identify the most accurate model for stock price prediction.
