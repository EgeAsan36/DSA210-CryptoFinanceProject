# DSA210-CryptoFinanceProject

Comparative analysis of cryptocurrency markets and traditional financial indicators. A data science project exploring correlations, volatility patterns, and macroeconomic influences across different asset classes. DSA210 Term Project.

## Contents
- [Project Overview](#project-overview)
- [Motivation](#motivation)
- [Data Sources](#data-sources)
- [Research Questions & Hypotheses](#research-questions--hypotheses)
- [Methodology](#methodology)
- [Analysis Plan](#analysis-plan)


## Project Overview

Through an analysis of their performance metrics, behavior, and reactions to macroeconomic events, this project seeks to understand how cryptocurrency markets relate to traditional financial markets. I try to comprehend how these various financial ecosystems interact with one another by comparing their risk profiles, volatility trends, and correlation dynamics.

I'll investigate trends in market correlations, volatility patterns, and the effects of outside economic factors on various asset classes using data analysis and visualization. Offering data-driven insights that can aid in comprehending the changing dynamic between the conventional and cryptocurrency markets is the aim.

## Motivation

The integration of cryptocurrencies into the traditional financial environment poses intriguing analytical challenges, which is why I am working on this project. Understanding how digital assets behave in comparison to traditional assets is becoming more and more crucial as they continue to garner widespread attention for a number of reasons.

- **Investment Diversification**: Building more robust portfolios can be facilitated by comprehending correlation patterns between traditional and cryptocurrency assets.
- **Risk Management**: Better risk assessment is made possible by recognizing how various asset classes react to economic developments.
- **Market Evolution**: Monitoring the development of cryptocurrency markets in comparison to more established financial systems offers insights into their long-term integration.

We can go beyond conjecture and offer fact-based insights into the interactions and influences between these markets by conducting a quantitative analysis of these relationships.

## Data Sources

I plan to collect data from the following sources:

### Cryptocurrency Data
- **CoinGecko API**: Historical price data for top cryptocurrencies by market cap, including Bitcoin, Ethereum, and others
- **Binance Historical Data**: OHLCV data, trading volumes and market depth information
- **CoinMarketCap API**: Market capitalization and trading volume data

### Traditional Market Data
- **Yahoo Finance API**: Stock indices (S&P 500, NASDAQ, DJIA), ETFs, and commodity prices
- **FRED (Federal Reserve Economic Data)**: Interest rates, bond yields, inflation rates
- **World Bank Open Data**: Global economic indicators and financial statistics

### Supplementary Data Sources
- **Social Media Sentiment**: Twitter API, Reddit data (from relevant investing and cryptocurrency subreddits)
- **Google Trends**: Search interest data for cryptocurrencies and traditional market terms
- **News Headlines**: Financial news APIs and economic calendar data

I will collect these datasets using Python APIs and web scraping techniques where necessary(After I learn it), ensuring data is properly cleaned and aligned by timestamp for accurate comparison.

## Research Questions & Hypotheses

Based on the professor's feedback, I've focused on three key research questions with clear null and alternative hypotheses:

### 1. Market Correlation Analysis

**Research Question**: How do cryptocurrency markets correlate with traditional financial markets during different economic conditions?

**Null Hypothesis (H₀)**: There is no significant difference in correlation between cryptocurrency and traditional markets during normal market conditions versus market stress periods.

**Alternative Hypothesis (H₁)**: The correlation between cryptocurrency and traditional markets is significantly higher during market stress periods compared to normal market conditions.

### 2. Volatility Convergence Study

**Research Question**: Has cryptocurrency market volatility been converging toward traditional market volatility levels over time?

**Null Hypothesis (H₀)**: There is no significant decrease in the volatility gap between cryptocurrency markets and traditional markets over the study period.

**Alternative Hypothesis (H₁)**: The volatility gap between cryptocurrency markets and traditional markets has significantly decreased over the study period.

### 3. Macroeconomic Impact Assessment

**Research Question**: How do key macroeconomic indicators (inflation rates, interest rates) differently affect cryptocurrency and traditional asset performance?

**Null Hypothesis (H₀)**: Macroeconomic indicators have equal impact on cryptocurrency markets and traditional markets.

**Alternative Hypothesis (H₁)**: Macroeconomic indicators have significantly different impacts on cryptocurrency markets compared to traditional markets.


## Methodology

I will approach this analysis through several complementary methods:

### 1. Exploratory Data Analysis (EDA)
- Descriptive statistics of price movements and returns
- Time series visualization of different asset classes

### 2. Correlation Analysis
- Rolling correlation coefficients between crypto and traditional assets
- Correlation heatmaps across asset classes

### 3. Volatility Analysis
- Comparison of volatility metrics (standard deviation, ATR, etc.)

### 4. Sentiment Analysis
- Basic NLP techniques to quantify market sentiment from social media and news
- Correlation between sentiment indicators and price movements

### 5. Machine Learning Approaches
- Regression models to identify influential factors on asset prices
- Classification models to predict market movements
- Feature importance analysis to determine key drivers

## Analysis Plan

The analytical process will follow these key steps:

### Phase 1: Data Collection and Preprocessing


### Phase 2: Core Analysis


### Phase 3: Advanced Analysis and Modeling


### Phase 4: Synthesis and Reporting





