# IBMpythonproject
Python Project for Data Science - Tesla vs GameStop stock &amp; revenue trends

This project is part of Coursera IBM Data Analyst, where we use yfinance (open-source tool that uses Yahoo's publicly available APIs) to extract Tesla/GameStop stock data and Webscraping techniques (using BeautifulSoup and Pandas) to extract Tesla/GameStop revenue data, which is then further cleaned to remove commas,  '$', null or empty strings from the DataFrame.

In order to extract the Quarterly Revenue data, .findall method is used to identify the exact table in the parsed data. The specified table cells are then appended to the empty DataFrame.

The Tesla and GameStop stock and revenue data were then plotted on a graph using the `make_graph` function. This is to visualise the trends from period of 2010-2021 (Tesla) and 2003-2021 (GameStop).

One of the more notable observations is that even though GameStop's share price drastically increased in 2021, its revenue had been fluctuating throughout the years. This observation can be explained in which individual investors on the Reddit forum WallStreetBets began buying large amounts of GameStop stock, thus driving its stock price sharply upward. 
