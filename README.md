# Stock_Dashboard_Python-Streamlit

## Overview

This Streamlit application provides a comprehensive, interactive dashboard for real-time stock price analysis and visualization. Users can explore stock data, view technical indicators, and analyze price movements across different time periods.

## Features

### Key Capabilities
- Real-time stock data retrieval
- Customizable time period selection
- Multiple chart types (Candlestick and Line)
- Technical indicators (SMA 20, EMA 20)
- Price metrics and historical data display

### Dashboard Components
- Interactive stock price chart
- Key performance metrics
- Historical price data table
- Technical indicators table
- Sidebar with quick stock price snapshots

## Prerequisites

### Required Libraries
- streamlit
- plotly
- pandas
- yfinance
- ta
- pytz

### Python Version
- Python 3.8+

## Installation

1. Clone the repository:<br />
git clone https://github.com/121910317007/Stock_Dashboard_Python-Streamlit.git<br />
cd Stock_Dashboard_Python-Streamlit

2. Create a virtual environment and Activate:<br />
python -m venv venv<br />
venv\Scripts\activate

3. Install required dependencies:<br />
pip install -r requirements.txt

## Usage

Run the Streamlit application:<br />
streamlit run path_to_python_file/stock_dashboard.py

### Dashboard Controls
- Ticker: Enter a stock symbol (e.g., AAPL, GOOGL)
- Time Period: Select from 1 day, 1 week, 1 month, 1 year, or max
- Chart Type: Choose between Candlestick and Line charts
- Technical Indicators: Add SMA 20 or EMA 20 to your chart

## Sidebar Features
- Real-time prices for AAPL, GOOGL, AMZN, MSFT
- Quick stock price overview
- Informational section about the dashboard

## Technical Details

### Data Sources
- Yahoo Finance (via `yfinance`)
- Real-time and historical stock data
- Timezone-aware data processing

### Technical Indicators
- Simple Moving Average (SMA)
- Exponential Moving Average (EMA)
