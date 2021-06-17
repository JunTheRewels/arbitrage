# m3_hw_arbitrage

This file examines historical arbitrage opportunities for bitcoin during the first 3 months of 2018 across 2 different exchanges: Bitstamp and Coinbase.

The first section collects the data by importing required libraries and dependencies as well as the data from the csv files and creating dataframes from them with Date as the index column.

The second section prepares the data by removing null items, converting all items to floats and ensuring there is no duplicated data.

Next it analyzes the data by isolating the "Close" price columns, describing them and plotting them. Then it focuses in on 3 dates across the full range, plotting the exchanges together on each date to compare prices and determine arbitrage spread.

Finally it isolates profitable spreads accounting for trade costs and plots them for each of the dates, calculates the profit in dollars, and plots that as well as the cumulative sum for each day.