PREREQUISITES:

1. Python

2. Anaconda(Optional)

3. Jupyter Notebook:
Jupyter notebook is a very popular and flexible development environment which lets us write and execute python code, display the output and any kind 
of visualization or plot, etc. in the same document. however, it is always advisable to install Python with Anaconda environment on your system as well.

4. Financial Markets:
Basic finance knowledge will be helpful we also included basic terminologies in report and jupyter notebook.


STEPS TO FOLLOW BEFORE START:

This project consists of 4 python notebook and requiered data.

We have included manual which contains information on how to run this project from start.


DESCRIPTION:

1.ScrapeStockData.ipynb

  Introduction:

    This notebook connects to the site "https://www.tickertape.in/screener" and gets the data by webscrapping using selenium webdriver into "stock-data.csv"

  Attributes Extracted:
    •	Stock Name
    •	Sub-Sector
    •	Market Cap
    •	Closing Price
    •	PE-ratio
    •	Five Year Growth
    •	Alpha
    •	Beta
    •   Five Year Historical Revenue Growth


2.StockDataProcessing.ipynb

  Introduction:

    This notebook processes the stock-data.csv" file and divides the companies into large-cap, medium-cap and small-cap companies and exports them to "large-cap.csv", "medium-cap.csv" and "small-cap.csv". Also, It gives a "top-6-large-cap.csv" file which contains top 6 large-cap companies extracted considering the following conditions:

    •   Five Year Historical Revenue Growth > 0
    •   0 < Beta < 1
    •   Max(Alpha) & Max(Five Year Growth)


3.ScrapeCompanyData.ipynb

  Introduction:

    This notebook connects to the "https://finance.yahoo.com" and gets the data for the companies for which the analysis is done in next part by webscrapping through selenium webdriver and exports into csv files with names of that appropriate companies.

  Attributes Extracted:
    •	Date
    •	High
    •	Low
    •	Open
    •	Close
    •	Volume
    •	Adj Close

4.Stock Analysis and Prediction.ipynb

  Introduction:

    Stock market investment is most underrated form of investment in India and people used to invest in gold, real estate, FD  because they don't understand the market and feels that it is too risky to invest their hard earned money. In India only 4% of population invest in stocks. In this project we analys the market and try to conclude that market is safe and best form of investment one could imagine. For this we use data mining and data science concepts.Data Science has inarguably been the hottest domain of the decade, asserting its need in every single sphere of corporate life. It was not long ago when we discovered the massive potential of incorporating ML/AI in the financial world.Data Science has been incremental in providing powerful insights (which people didn't even know existed ) and helped massively increase efficiency, helping everyone from a scalp trader to a long term debt investor. Accurate predictions, unbiased analysis, powerful tools that run through millions of rows of data in the blink of     an eye have transformed the industry in ways we could've never imagined.

  Topics covered in this notebook:

    -Why to invest in stocks.
    -Analysis of change in price of the stock overtime?
    -What was the simple moving average of the various stocks?
    -What was the daily return of the stock on average?
    -Analysis of the relationship between volume and daily return
    -Analysis correlation between different stocks daily returns
    -risk analysis of various stocks
    -Trade Calls - Using Bollinger Bands
    -Trade Call Prediction using Classification
    -Beta Calculation using regression for various stocks
    -Diversification analysis using Clustering
    -Predicting the closing  stock price of mindtree limited using LSTM

You can refer to the notebooks for more details about each section

Project team:

1. Abhishek Reddy(2111062,tareddy21@iitk.ac.in)
2. Deepak kumar(21111023,dkumar21@iitk.ac.in)
3. Mandar Dhake(2111405,mkdhake21@iitk.ac.in)
4. Yash Patil(21111410,yashpp21@iitk.ac.in)

