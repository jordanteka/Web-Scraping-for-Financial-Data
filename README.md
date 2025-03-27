Forex Rates Scraper

Project Overview

This project is a Python-based web scraper that extracts real-time Forex exchange rates from Investing.com. It gathers data on major currency pairs, including bid price, ask price, high/low prices, and percentage changes. The extracted data is saved in a CSV file for further analysis.

Features

Scrapes live Forex rates from Investing.com

Extracts currency pairs, bid/ask prices, and rate changes

Saves data to a structured CSV file for easy analysis

Uses BeautifulSoup and Requests for web scraping

 Installation & Setup

1Install Dependencies

Ensure you have Python installed, then install the required libraries:

pip install requests beautifulsoup4 pandas

2 Run the Script

Execute the Python script to fetch the latest Forex rates:

python forex_scraper.py

3 Check the Output

After running the script, you'll find a forex_rates.csv file in the project directory containing the extracted data.

 Sample Output

Currency Pair

Bid Price

Ask Price

High Price

Low Price

Change

Change Percent

EUR/USD

1.1025

1.1027

1.1050

1.1000

+0.0020

+0.18%

GBP/USD

1.2500

1.2503

1.2520

1.2480

-0.0015

-0.12%

 Technologies Used

Python: Main programming language

Requests: Fetches HTML content from Investing.com

BeautifulSoup: Parses and extracts relevant Forex data

Pandas: Structures and saves data in CSV format

 Next Steps

Enhance Scraper: Add support for more currency pairs

Automate Data Collection: Schedule daily scraping

Data Visualization: Create charts for Forex trends using Matplotlib/Seaborn

License

This project is open-source under the MIT License. Follow this project if you find it useful!

