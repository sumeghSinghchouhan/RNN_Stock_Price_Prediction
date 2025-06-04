Stock Price Prediction Using RNNs
Objective
The objective of this assignment is to try and predict the stock prices using historical data from four companies IBM (IBM), Google (GOOGL), Amazon (AMZN), and Microsoft (MSFT).

We use four different companies because they belong to the same sector: Technology. Using data from all four companies may improve the performance of the model. This way, we can capture the broader market sentiment.

The problem statement for this assignment can be summarised as follows:

Given the stock prices of Amazon, Google, IBM, and Microsoft for a set number of days, predict the stock price of these companies after that window.

Business Value
Data related to stock markets lends itself well to modeling using RNNs due to its sequential nature. We can keep track of opening prices, closing prices, highest prices, and so on for a long period of time as these values are generated every working day. The patterns observed in this data can then be used to predict the future direction in which stock prices are expected to move. Analyzing this data can be interesting in itself, but it also has a financial incentive as accurate predictions can lead to massive profits.

Data Description
You have been provided with four CSV files corresponding to four stocks: AMZN, GOOGL, IBM, and MSFT. The files contain historical data that were gathered from the websites of the stock markets where these companies are listed: NYSE and NASDAQ. The columns in all four files are identical. Let's take a look at them:

Date: The values in this column specify the date on which the values were recorded.

Open: The values in this column specify the stock price on a given date when the stock market opens.

High: The values in this column specify the highest stock price achieved by a stock on a given date.

Low: The values in this column specify the lowest stock price achieved by a stock on a given date.

Close: The values in this column specify the stock price on a given date when the stock market closes.

Volume: The values in this column specify the total number of shares traded on a given date.

Name: This column gives the official name of the stock as used in the stock market.

There are 3019 records in each data set. The file names are of the format \<company_name>_stock_data.csv.
