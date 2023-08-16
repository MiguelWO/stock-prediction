# Stock Index Analysis Project

## Overview

This project focuses on analyzing historical daily price data for stock indexes from various countries. The data is sourced from Kaggle and covers multiple decades for most stock exchanges. The goal of this project is to gain insights into the behavior of these indexes, identify patterns, trends, and anomalies, and potentially build predictive models.

## Table of Contents

- [Data](#data)
- [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Feature Engineering](#feature-engineering)
- [Statistical Analysis](#statistical-analysis)
- [Conclusion](#conclusion)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Data

The dataset consists of daily price data for various stock indexes from different countries, including the United States, China, Canada, Germany, Japan, and more. The prices are quoted in the national currency of each exchange. The dataset is sourced from Yahoo Finance.

## Data Cleaning and Preprocessing

- Checked for missing values, outliers, and inconsistencies.
- Normalized data to account for different base currencies.
- Handled missing values using interpolation and forward-filling.

## Exploratory Data Analysis (EDA)

- Visualized price trends over time for each index.
- Calculated statistics like mean, standard deviation, and correlations between indexes.
- Identified patterns, trends, and anomalies in the data.

## Feature Engineering

- Created additional features including moving averages, RSI, and volatility measures.
- Converted daily prices into both simple returns and log-returns.

## Statistical Analysis

- Conducted tests for stationarity.
- Explored autocorrelation and partial autocorrelation functions for time series modeling.

## Conclusion

This project provides a comprehensive analysis of stock index data, offering insights into historical price trends, relationships between indexes, and potential modeling opportunities. Further analysis or modeling can be built upon the insights gained from this project.

## Dependencies

This project requires the following libraries:

- pandas
- numpy
- matplotlib
- seaborn




