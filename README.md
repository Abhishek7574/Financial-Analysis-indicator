# Strategic Indicators

This project performs quantitative analysis on a given stock/equity/crypto ticker symbol (`tag`) over a specified time period using historical price data from the Yahoo Finance API. The goal is to identify reliable trading strategies for specific markets.

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Indicators Summary](#indicators-summary)
- [User Inputs](#user-inputs)
- [Usage](#usage)
- [Disclaimer](#disclaimer)
- [Configuration](#configuration)

## Project Overview
This program analyzes market data for a specific `tag` (e.g., a stock or cryptocurrency) to determine the best trading strategy by evaluating different indicators and providing buy/sell signals. The analysis is focused on finding a strategy that works well for specific market conditions.

## Objectives
- Analyze historical price data to identify market trends.
- Evaluate various technical indicators to inform trading decisions.
- Provide empirical analysis to guide the selection of a reliable trading strategy.

## Indicators Summary
1. **Moving Average Convergence Divergence (MACD):** Trend-following momentum indicator showing the relationship between two moving averages.
2. **Simple Moving Average (SMA):** Calculates the average price over a specified time period to smooth out fluctuations.
3. **Exponential Moving Average (EMA):** A weighted moving average that responds more to recent price changes.
4. **Double Exponential Moving Average (DEMA):** A smoother moving average that reduces lag, helping identify trends and reversals.
5. **Relative Strength Index (RSI) / Money Flow Index (MFI):** Oscillators used to identify overbought or oversold conditions.
6. **On-Balance Volume (OBV & OBV_EMA):** Momentum indicators measuring buying and selling pressure based on volume.
7. **Bollinger Bands (BB):** Indicators measuring volatility and potential price reversal points.
8. **Exponential Moving Average 3X Leveraged (3X Lever):** Identifies entry and exit points for leveraged trading.

## User Inputs
- `tag`: Stock/equity/crypto ticker symbol
- `start`: Initial date
- `end`: End date
- `period`: Time interval for some indicators

## Usage
- For general use, run the entire notebook using **Runtime > Run all**.

## Disclaimer
This tool is for educational purposes and is not financial advice. Use at your own risk.

## Configuration
- **Python Version:** Ensure compatibility with the required version.
- **Helper Installs/Uninstalls:** Install necessary libraries and dependencies.
- **Imports:** Import relevant libraries for analysis.
