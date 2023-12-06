# Sentimental-Detective.
####### Sentiment Analysis and Stock Price Correlation.







you can find the project presentation here. 
https://prezi.com/view/12XFcMsAPFgTuY0LX2s2/ . 

Overview

This project focuses on analyzing social media sentiment data to explore its correlation with stock price movements. The sentiment analysis is performed on tweets related to specific stocks, and the correlation is examined to understand potential relationships.
Table of Contents

    Project Description
    Prerequisites
    Setup
    Data Collection
    Data Preprocessing
    Sentiment Analysis
    Stock Price Data
    Data Integration
    Exploratory Data Analysis
    Enhancements
    Conclusion

Project Description

This project involves:

    Collecting and preprocessing social media data (tweets) related to specific stocks.
    Performing sentiment analysis on the cleaned tweet data.
    Fetching historical stock price data for relevant stocks.
    Analyzing the correlation between sentiment scores and stock price movements.

Prerequisites

    Python 3.x
    Jupyter Notebook
    Required Python packages (listed in requirements.txt)

Setup

    Clone the repository to your local machine.

    bash

git clone https://github.com/yourusername/sentiment-stock-correlation.git

Navigate to the project directory.

bash

cd sentiment-stock-correlation

Install required packages.

bash

    pip install -r requirements.txt

Data Collection

    Configure Twitter API credentials in config.py.
    Run the collect_tweets.py script to gather tweet data.

Data Preprocessing

    Execute the preprocess_data.py script to clean and preprocess the collected tweets.

Sentiment Analysis

    Run sentiment analysis using the sentiment_analysis.py script.

Stock Price Data

    Fetch historical stock price data using Yahoo Finance API (see fetch_stock_prices.ipynb).

Data Integration

    Merge sentiment scores with stock price data using the merge_data.ipynb notebook.

Exploratory Data Analysis

    Explore and visualize data relationships using analyze_data.ipynb.

Enhancements

    Implement lag features, technical indicators, and market volatility measures (see suggestions in the README).
