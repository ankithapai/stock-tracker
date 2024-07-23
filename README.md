# StockVis

## Getting Started:

- Clone this repository to your local machine.
- Using a local server (such as HTTP Simple Server), open the **index.html** file.

## Dataset Description:

All the data used for this visualization is located in the **Data** folder.

- **Stock Data:** Contains historical stock data from 2019 to 2023 for the top 50 tech companies on the Nasdaq stock exchange, including daily records of opening, highest, lowest, closing prices, adjusted closing prices, and trading volumes.

- **News Data:** This dataset features stock news data generated by a script, covering 1000 articles per company from 2019 to 2023. Each record includes the article date, company name, title, and view count.

- **Transaction Data:** This dataset contains transactions done by an investment firm from 2019 to 2023. Each record contains date, stock sold, stock bought, amount, and a list of values indicating the current holdings of the firm. This data was generated using a script

## System Overview:

- **Overview:** The line chart presents a dynamic view of trading volumes, with a user-defined date range for detailed analysis. It allows the selection of up to 15 stocks from a preset group of 50 companies, offering personalized insights when the data is refreshed based on new selections. It aims to showcase the trends and fluctuations in market activity within the specified timeframe for user-specific portfolios.

- **Volume Distribution:** This stream graph chart visualizes the percentage share of traded volume for various stocks across a year. Each stock is color-coded, with the X-axis plotting the date and the height of each area segment representing the stock's volume percentage. The chart's purpose is to display how the trading volume for each stock compares and contributes to the total over time.

- **Traded Volume:** This composite chart displays the traded volume for individual stocks against time, with a bar graph for aggregated trading volumes and a line chart to indicate a trend in stock price. It illustrates the relationship between time and trading activity from a volume perspective.

- **Traded Value:** This composite chart visualizes the traded value, calculated based on stock price and volume, in the form of an area chart for each selected stock. It helps in analyzing the market movements for each stock within the selected timeframe.

- **News:** This beeswarm chart depicts the distribution and visibility of news articles for selected stocks over time. Each circle represents an article, color-coded by company, with its size reflecting the number of views. The chart's aim is to visualize the relationship between publication date, volume of news, and reader engagement.

- **Transaction Data:** This chord diagram illustrates an investment firm's portfolio activity. Arcs symbolize different stocks, with their thickness indicating the amount invested. Ribbons connect the stocks to show capital movement. The surrounding bar graph quantifies the final holdings as a percentage of the portfolio. The diagram's purpose is to demonstrate the relationships between the entry, and exit strategies, and the invested amounts in various stocks

- **Candlestick Chart:** This chart is an extension of the existing system which fits in our use case. It helps in getting an in-depth understanding of the stock price movements over the defined period. To complement this, a drop-down menu is implemented for the user to select the price movement of the specific stock.