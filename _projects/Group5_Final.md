---
name: The Magnificent Seven and S&P 500 ETF Data Analysis
tools: [Python & several Python Libraries]
image: assets/pngs/plot1_1.png
description: This project showcases interactive visualizations using Python.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---
# Project Name
The Magnificent Seven and S&P 500 ETF Data Analysis

## Project Goal
This project aims to provide insights through the analysis of daily stock data from Magnificent Seven (consisting of seven top US technology companies, including Apple, Microsoft, Amazon, Google, Facebook, Tesla, and Netflix) and the S&P 500 ETF, in order to help investors understand market trends and industry dynamics. The core goal of the project is to design and implement a series of data visualization tools that can reveal the performance, volatility, interrelationships, and correlation with the overall market trends of these stocks.

## Data Source Description

- **Name of the dataset**: This dataset contains stock prices and trading volume information obtained from Yahoo Finance. Specifically, we have focused on the following stocks: Apple (AAPL), Microsoft (MSFT), Amazon (AMZN), Google (GOOGL), Facebook (FB), Tesla (TSLA), Netflix (NFLX), and the S&P 500 ETF (SPY);
- **Obtain source**: The data is obtained through Yahoo Finance's public API and downloaded using the yfinance Python library;
- **Access**: Data can be accessed using the yfinance library through any device with an Internet connection. The yfinance library encapsulates Yahoo Finance's API, making data retrieval simpler and more convenient;
- **License**: The data provided by Yahoo Finance is mainly used for personal and non-commercial purposes. The yfinance library is released under the MIT license.



## Data Visualizations
Below are the interactive charts that created using Python:

### Plot 1 Trend Chart

[![Trend Chart](https://raw.githubusercontent.com/Vincent-Zhul/Vincent-Zhul.github.io/main/assets/pngs/plot1_1.png)]


#### Description

Create a trend chart to show the adjusted closing price trend of "Magnificent Seven" technology companies and the Nasdaq Composite Index. By observing curves of different colors, we can evaluate the changes in stock prices of each company over time and compare them with the overall performance of the Nasdaq index. If most stock price curves show a trend similar to the Nasdaq index, it indicates that the performance of these technology stocks is closely related to the overall market; If a company's stock price trend significantly deviates from the Nasdaq index, it may indicate that the company has been affected by specific market forces or internal events.

### Plot 2 Average transaction volume analysis chart

[![Average transaction volume analysis chart](https://raw.githubusercontent.com/Vincent-Zhul/Vincent-Zhul.github.io/main/assets/pngs/plot2.png)]

#### Description

This bar chart can be used to display the average daily trading volume of a selected company over a certain time range. Through this approach, investors can quickly identify which stocks have high liquidity, which may mean that these stocks are easier to buy and sell and usually receive more market attention. A higher trading volume usually indicates higher liquidity, which is an important indicator for investors who want to quickly enter and exit the market. Trading volume can also serve as an indicator of market interest in a particular stock. An abnormally high trading volume may indicate significant news or event driven events. Stocks with high trading volume may have greater price fluctuations, which is a key factor for traders seeking high volatility trading opportunities.

### Plot 3 Box Plot

[![Box Plot](https://raw.githubusercontent.com/Vincent-Zhul/Vincent-Zhul.github.io/main/assets/pngs/plot3.png)]

#### Description

Purpose: A box plot provides a visual summary of the distribution of a dataset. It highlights the median, quartiles, and potential outliers within the data.

Use in Finance: For stock prices, it can show the range of closing prices over a period, identify stocks with high volatility, and detect outliers that might indicate unusual trading activity.

### Plot 4 Correlation Heatmap

[![Correlation Heatmap](https://raw.githubusercontent.com/Vincent-Zhul/Vincent-Zhul.github.io/main/assets/pngs/plot4.png)]

#### Description

Purpose: A correlation heatmap visualizes the correlation coefficients between pairs or groups of variables.

Use in Finance: This helps in understanding how different stocks move in relation to each other, which is crucial for diversification and risk management in a portfolio. High correlation coefficients indicate that stocks tend to move together, whereas low correlation coefficients suggest more diversification benefits.

### Plot 5 Moving Average Line Chart

[![Moving Average Line Chart](https://raw.githubusercontent.com/Vincent-Zhul/Vincent-Zhul.github.io/main/assets/pngs/plot5.png)]

#### Description

Purpose: A moving average smooths out price data by creating a constantly updated average price. This helps in identifying trends over a period.

Use in Finance: The moving average is useful for detecting trends and potential turning points in stock prices, providing insights for entry and exit trading strategies.

### Plot 6 Volume Weighted Average Price (VWAP)

[![Volume Weighted Average Price](https://raw.githubusercontent.com/Vincent-Zhul/Vincent-Zhul.github.io/main/assets/pngs/plot6.png)]

#### Description

Purpose: VWAP gives the average price a stock has traded throughout the day, based on volume and price. It is important because it provides traders with insight into both the trend and value of a stock.

Use in Finance: Traders use VWAP to ensure they are getting a favorable price on their trades relative to the volume-weighted price, which can be particularly useful for large orders.

### Plot 7 Daily Return Distribution Chart

[![Daily Return Distribution Chart](https://raw.githubusercontent.com/Vincent-Zhul/Vincent-Zhul.github.io/main/assets/pngs/plot7.png)]

#### Description

Purpose: This chart shows the frequency distribution of daily returns of a stock, helping to understand its volatility and the normality of its return distribution.

Use in Finance: Analyzing the distribution helps in risk assessment, where wider distributions indicate higher volatility and potential for large price swings, impacting investment decisions.

### Plot 8 Accumulated Revenue Chart

[![Accumulated Revenue Chart](https://raw.githubusercontent.com/Vincent-Zhul/Vincent-Zhul.github.io/main/assets/pngs/plot8.png)]

#### Description

Purpose: This chart accumulates revenue calculations over a period to show growth or decline.

Use in Finance: Although "revenue" here is an abstract notion (assuming revenue from sales at closing price multiplied by volume), this can illustrate trading volume and revenue potential over time, useful for analyzing market activity and liquidity trends.

### Plot 9 Interactive Scatter Plot

[![Interactive Scatter Plot](https://raw.githubusercontent.com/Vincent-Zhul/Vincent-Zhul.github.io/main/assets/pngs/plot9.png)]

#### Description

Purpose: An interactive scatter plot allows for dynamic visualization where users can explore specific data points by interacting with the plot.

Use in Finance: This can be used to investigate relationships between different variables (like closing price and volume), spot anomalies, and identify patterns across different time frames or conditions.






<div class="left">
{% include elements/button.html link="https://finance.yahoo.com/quote/SPY?.tsrc=fin-srch" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/Vincent-Zhul/Vincent-Zhul.github.io/blob/main/python_notebooks/IS445_Data_Viz_Final_Proj.ipynb" text="The Notebook" %}
</div>

