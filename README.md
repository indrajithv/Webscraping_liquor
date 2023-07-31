## Liquorland GTIN Extractor

## Overview

This Python script extracts product information, including Brand, Title, Price, and GTIN (Global Trade Item Number), from the Liquorland website (https://www.liquorland.com.au/offers).

The script utilizes the requests and BeautifulSoup libraries to scrape the product links, and the Selenium library with a Firefox webdriver to navigate to each product page and extract the required information.

## Requirements
- Python
- requests
- beautifulsoup4
- selenium
- pandas
- Mozilla Firefox

The script will start extracting product information from the Liquorland website and display each product's Brand, Title, Price, and GTIN

Once the script finishes running, the extracted data will be stored in excel.
