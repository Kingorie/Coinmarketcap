# Overview

This Python script uses Selenium to scrape cryptocurrency market data from CoinMarketCap. The data includes information about the top cryptocurrencies such as name, market cap, price, 24-hour percentage change, 7-day percentage change, and 24-hour trading volume.

# Prerequisites

Make sure you have the following Python libraries installed:

* Selenium
* Pandas

# Instructions
* Download and install the ChromeDriver executable.
* Update the webdriver.Chrome() line with the path to the ChromeDriver executable on your system.
* Run the script.

# Script Overview
* The script uses Selenium to open the CoinMarketCap historical data page.
* It locates cryptocurrency data elements using XPaths.
* Data for each cryptocurrency (Name, Marketcap, Price, % 24H, % 7D, Vol_24h) is extracted into separate lists.
* A list of dictionaries (result) is created to store the data.
* The script prints the number of cryptocurrencies and the names of each cryptocurrency (for confirmation).
* The data is then structured into a DataFrame using the pandas library.
* The resulting DataFrame (result_df) is printed.

# Note

You can also customize the script to save the data to a CSV file or other formats.

Feel free to modify the script according to your specific needs or integrate it into your data analysis pipeline.
