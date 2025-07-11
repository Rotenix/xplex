# NASDAQ Stock Analysis Data Model

## Overview

This data model analyzes 45 NASDAQ stocks across diverse sectors using technical indicators to assess risk factors and performance metrics. The model is designed to minimize risk exposure while maximizing performance potential through comprehensive technical analysis.

## Dataset

- **Stocks Analyzed**: 45 NASDAQ-listed companies
- **Sector Coverage**: Diverse sectors for comprehensive market representation
- **Analysis Type**: Technical indicator-based risk and performance assessment

## Model Structure

### Input Variables (Risk Factors)
*Objective: Minimize for improved efficiency and reduced risk exposure*

| Variable | Description | Purpose |
|----------|-------------|---------|
| **ATR** | Average True Range | Volatility measure indicating price movement range |
| **BB_Width** | Bollinger Bands Width | Volatility measure showing price band expansion/contraction |
| **Volatility** | Price Standard Deviation | Statistical risk measure of price fluctuation |
| **Williams_R_Abs** | Williams %R Absolute Value | Overbought/oversold risk indicator |
| **Beta** | Market Risk Coefficient | Systematic risk relative to market movements |

### Output Variables (Performance Factors)
*Objective: Maximize for enhanced performance potential*

| Variable | Description | Purpose |
|----------|-------------|---------|
| **RSI_Norm** | RSI Normalized (0-1 scale) | Momentum strength indicator |
| **MACD_Signal** | MACD Signal Strength | Trend momentum and directional change |
| **ADX** | Average Directional Index | Trend strength measurement |
| **OBV_Change** | On-Balance Volume Change | Volume momentum and price validation |
| **Price_ROC** | Price Rate of Change | Price performance over time |
| **Volume_ROC** | Volume Rate of Change | Liquidity and market interest indicator |

## Model Objectives

### Risk Management
- **Minimize Input Variables**: Lower ATR, BB_Width, Volatility, Williams_R_Abs, and Beta values indicate reduced risk exposure
- **Volatility Control**: Multiple volatility measures provide comprehensive risk assessment
- **Market Risk Awareness**: Beta coefficient helps understand systematic risk exposure

### Performance Optimization
- **Maximize Output Variables**: Higher values in performance factors indicate stronger potential returns
- **Momentum Analysis**: RSI and MACD provide insight into price momentum and trend direction
- **Volume Confirmation**: OBV and Volume ROC validate price movements through volume analysis
- **Trend Strength**: ADX helps identify the strength of prevailing trends

## Technical Indicators Explained

### Risk Indicators
- **Average True Range (ATR)**: Measures market volatility by calculating the average of true ranges over a specified period
- **Bollinger Bands Width**: Indicates volatility by measuring the distance between upper and lower Bollinger Bands
- **Williams %R**: Momentum oscillator measuring overbought/oversold conditions
- **Beta**: Measures a stock's volatility relative to the overall market

### Performance Indicators
- **Relative Strength Index (RSI)**: Momentum oscillator ranging from 0-100, normalized to 0-1 scale
- **MACD (Moving Average Convergence Divergence)**: Trend-following momentum indicator
- **Average Directional Index (ADX)**: Measures trend strength regardless of direction
- **On-Balance Volume (OBV)**: Cumulative volume indicator relating volume to price changes
- **Rate of Change (ROC)**: Momentum indicator measuring percentage change over time
