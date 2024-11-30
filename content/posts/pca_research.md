+++
author = ["Taylor Agarwal"]
title = "Principal Component Analysis for Clustering Stock Portfolios"
date = "2024-11-29"
summary = "My peer-reviewed undergrad research paper on applying machine learning to the US stock market."
+++

## Abstract

**Motivation**: Due to the sheer size of the stock market and its dependencies on several factors, a catch-all method of determining stock performance continues to elude the public. Recent developments in machine learning have opened the door to new possibilities for a predictive algorithm. Principal Component Analysis (PCA) is one such tool that has allowed for the discovery of hidden interconnectivity in large data sets. We use PCA alongside k-means clustering to obtain groups of stocks with similar historical structure with the potential to assist in predictive stock management.

**Results**: In just over five seconds, our algorithm groups a hundred stocks from the New York Stock Exchange with mean correlation 0.2483 into fifty portfolios with mean correlation 0.4299. On average, the stocks in these fifty portfolios experienced price increases and decreases on the same day 65.34% of the time in the sample time frame of 4/17/2000 to 11/10/2017. The algorithm can be extended to encompass more stocks.

**Implications**: This algorithm provides a means to identify stocks with similar structure in both the short and long term. Stocks belonging to the same portfolio after clustering are shown to have positive and negative returns at the same time within the user defined periods of time.

[Full Paper](https://journals.librarypublishing.arizona.edu/azjis/article/id/2384/)
