# Cryptocurrency Market Analysis

## Overview

This project analyzes real-time cryptocurrency market data collected through the CoinGecko API. The objective was to explore market structure, asset performance, trading activity, and short-term market behavior using Python and data analysis techniques.

The project follows a complete analytics workflow, starting from API data collection and ending with visualization and insight generation. The findings are presented through an interactive web-based dashboard for easier interpretation.

---

## Objective

Cryptocurrency markets generate large volumes of data every day. While prices and market metrics are publicly available, meaningful insights often require additional analysis.

This project focuses on answering questions such as:

* Which cryptocurrencies dominate the market?
* Which assets recorded the strongest gains and losses?
* How concentrated is trading activity?
* What does short-term market sentiment look like?
* Is there any relationship between market size and daily performance?

---

## Data Source

Data was collected using the CoinGecko API.

The analysis uses market information for the top 100 cryptocurrencies, including:

* Market Capitalization
* Market Cap Rank
* Current Price
* Trading Volume
* 24-Hour Price Change Percentage

The API response was received in JSON format and processed using Pandas.

---

## Methodology

The project was completed using the following workflow:

1. Collect data from the CoinGecko API
2. Convert the JSON response into a Pandas DataFrame
3. Clean and structure the dataset
4. Perform exploratory data analysis
5. Create visualizations to identify trends and patterns
6. Generate insights from the results
7. Present findings through an interactive dashboard

---

## Analysis Performed

### Market Capitalization Analysis

Examined the largest cryptocurrencies by market value and evaluated overall market concentration.

### Top Gainers Analysis

Identified assets with the strongest positive price movement over the previous 24 hours.

### Top Losers Analysis

Analyzed cryptocurrencies that experienced the largest declines during the observation period.

### Trading Volume Analysis

Studied trading activity to understand where liquidity was concentrated.

### Market Sentiment Analysis

Calculated the average 24-hour return across the dataset to assess short-term market conditions.

### Correlation Analysis

Explored the relationship between market-cap rank and daily returns.

---

## Tools Used

* Python
* Requests
* Pandas
* Matplotlib
* Plotly
* CoinGecko API
* HTML
* CSS
* JavaScript

---

## Key Findings

* Bitcoin remained the largest cryptocurrency by market capitalization and continued to dominate the market.
* Market value was heavily concentrated among a small number of leading assets.
* Several lower-ranked cryptocurrencies recorded the strongest short-term gains.
* Trading activity was primarily concentrated among Bitcoin, Ethereum, Tether, and USDC.
* The average 24-hour return across the dataset indicated negative short-term market sentiment during the observation period.
* Correlation analysis showed only a weak relationship between market-cap rank and daily returns.

---

## Dashboard

Live Dashboard:

https://clinquant-crumble-1a5090.netlify.app/

---

## Skills Demonstrated

* API Integration
* JSON Data Processing
* Data Cleaning and Transformation
* Exploratory Data Analysis
* Statistical Analysis
* Data Visualization
* Dashboard Development
* Insight Generation

---

## What I Learned

This project provided practical experience working with real-time API data and converting raw JSON responses into structured datasets for analysis.

It also strengthened my understanding of exploratory data analysis, visualization, and communicating analytical findings in a clear and interpretable format.

---

## About Me

**Tanmay Bisen**

LinkedIn: https://www.linkedin.com/in/tanmay-bisen-1a4443293/
