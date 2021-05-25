# Stock-Scraper
Some *messy* python scripts that I wrote and/or compiled from various sources for personal use

This code contains methods to scrape financial data and rankings for given stock inputs. This data can be used to analyze trends, find out which financial rankings are more accurate over time, and more(These methods aren't in this repository).

If you do "python scrapeHelper.py" It'll save the zacks and yahoo rankings for a given list of stock symbols to a single file (20 max at the moment)

If you do "python pe.py" It'll take a stock csv obtained from https://www.nasdaq.com/market-activity/stocks/screener , and it'll scrape yahoo finance and save the parsed information about each stock in a file, in a dated folder. (Takes a while)

There are methods which scrape financial articles for sentiment analysis which will be uploaded sometime in the future


Not all of this code is original, credits to those who wrote some of the methods (I've forgotten who)
