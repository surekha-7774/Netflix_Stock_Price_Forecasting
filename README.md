# Netflix_Stock_Price_Forecasting
The stock market is a place where people buy and sell shares of companies. It's like a marketplace where investors can trade stocks and other types of investments. There are rules and regulations in place to ensure fair and orderly transactions.
### To better understand the problem at hand, let's establish our objective. Stock market analysis can be broadly divided into two categories: Fundamental Analysis and Technical Analysis.

### 1. Fundamental Analysis: 
This involves assessing a company's potential profitability by analyzing its current business environment and financial performance.

### 2. Technical Analysis:
This involves studying charts and using statistical data to identify patterns and trends in the stock market.
For this article, our focus will be on technical analysis. We will be using a dataset containing Netflix stock prices from February 2018 to Februrary 2022 to develop a model that can predict future stock prices. Let's get started!

### Here are the key points to understand:

### Dataset Variables: 
The dataset includes several variables such as Date, Open, High, Low, Close, Adj Close and volume.
<br>
1. Open and Close represent the starting and final prices of the stock for a given day. ####2. High and Low indicate the maximum and minimum prices of the stock during the day. ####3. Volume represents the number of shares traded on that day.

### Weekend and Holiday Considerations: 
The stock market is closed on weekends and public holidays. In the dataset, certain date values are missing, such as 10/2/2018, 11/2/2018, and 24/2/2018.
<br>
1. 11/2/2018 and 24/2/2018 are missing because they fall on the weekend.
<br>
2. Target Variable: The calculation of profit or loss is typically based on the closing price of a stock for the day. Therefore, in this analysis, we will consider the Adj Close price as the target variable.
<br?
By keeping these points in mind, we can proceed with our analysis.
