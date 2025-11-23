Stock Trend Analyzer
Overview
Stock Trend Analyzer is a Python-based GUI application that lets users visualize, analyze, and predict trends for popular stocks and the S&P 500 
 index. It utilizes up-to-date data, moving averages, and machine learning for analysis—all accessible via a modern Tkinter dashboard.

Features
Real-time stock data and price charts

Moving average visualizations

Next-day price predictions using linear regression

Top performer discovery based on historical returns

Intuitive black-themed interface for clarity

Technologies/Tools Used
Python 3.x

Tkinter for GUI

yfinance for stock data

matplotlib for charting

scikit-learn for predictions

pandas, numpy for data handling

Steps to Install & Run

Clone the repository:
bash
git clone https://github.com/yourusername/stock-trend-analyzer.git
cd stock-trend-analyzer

Install dependencies:
bash
pip install -r requirements.txt

Run the application:
bash
python main.py
Instructions for Testing
Use the sidebar to select a stock and view its chart and statistics.

Click "Show Best Stocks" to compare recent performance.

Check displayed predictions for estimated next-day prices.

Screenshots
