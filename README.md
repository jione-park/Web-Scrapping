# Web-Scrapping
Irvine tech hub project

# Introduction

This project focuses on analyzing the stock market data of Samsung Electronics, a leading global technology company. Through web scraping, data manipulation, and visualization techniques, we aim to uncover meaningful insights from the stock market trends of Samsung Electronics. This analysis not only serves as a practical application of data science in finance but also provides valuable information for investors and market analysts.


# Dataset
- Website & Link
  
: Samsung Electronics' Daily Market Price

link: <https://finance.naver.com/item/sise_day.nhn?code=005930>

The dataset used in this project is obtained through web scraping of Samsung Electronics' daily market price data from Naver Finance. The data spans across several months, providing a comprehensive view of the stock's performance over time. Key variables in the dataset include:

- Date: The date of the stock data entry (YYYY.MM.DD).
- Closing Price: The stock's value at the end of the trading day.
- Open: The stock's value at the beginning of the trading day.
- High: The highest value of the stock during the trading day.
- Low: The lowest value of the stock during the trading day.
- Volume: The number of shares traded during the day.
- The primary focus of the analysis is the 'Closing Price' of the stock, examining its fluctuation over time and its relationship with other variables.

# Analysis
## Q1: Average Daily Volume Analysis

![Figure_1](https://github.com/jione-park/Web-Scrapping/assets/105265104/11ec6261-dfe3-404c-9b96-d83b24162b13)

This line graph demonstrates the stock's daily trading volume over time, juxtaposed with its average value throughout the entire period. A red horizontal line indicates the average trading volume, while the blue line represents daily volumes.
Insights:
Average Trading Interest: The average line suggests a consistent trading interest in Samsung Electronics' stock.
Market Response: Peaks in volume could signal market reactions to corporate or economic events.

## Q2: Price Fluctuation Analysis

![Figure_2](https://github.com/jione-park/Web-Scrapping/assets/105265104/8bc6fc69-f476-4e04-b2b3-895b010fc831)

A histogram that shows the frequency of daily price differences, highlighting days with unusual highs and lows. The red line indicates the average price difference across the period.
Insights:
Market Stability: Days clustered around the average suggest stable market conditions.
High Volatility Indicators: Days far from the average may point to specific impactful events, signaling investor caution.

## Q3: Volume and Price Trend Correlation

![Figure_3](https://github.com/jione-park/Web-Scrapping/assets/105265104/94224e71-c9fd-4d4c-8f36-b61a91ac7228)

This double-axis graph depicts the relationship between the stock's closing prices and traded volumes over time, revealing the interplay between stock value and market activity.
Insights:
Volume and Price Dynamics: The graph can be used to discern whether high-volume days correspond to significant price movements, offering strategic insights for trading.
