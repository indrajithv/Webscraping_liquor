# Liquorland GTIN Extractor

## Overview

The Liquorland GTIN Extractor is a Python script designed to extract product information such as Brand, Title, Price, and GTIN (Global Trade Item Number) from the Liquorland website ([Liquorland Website](https://www.liquorland.com.au/offers)).

This script utilizes the requests and BeautifulSoup libraries for web scraping to extract product links from the Liquorland website. It then employs the Selenium library with a Firefox webdriver to navigate to each product page and extract the required information.

## Requirements

- Python
- requests
- beautifulsoup4
- selenium
- pandas
- Mozilla Firefox

## How to Use

1. Ensure you have Python installed on your system.
2. Install the required libraries using pip:
    ```
    pip install requests beautifulsoup4 selenium pandas
    ```
3. Make sure you have Mozilla Firefox installed.
4. Clone or download the script from the repository.
5. Run the script using Python.
6. The script will start extracting product information from the Liquorland website and display each product's Brand, Title, Price, and GTIN.
7. Once the script finishes running, the extracted data will be stored in an Excel file for further analysis.

By using this script, you can efficiently extract product information from the Liquorland website, streamlining the process of gathering data for analysis or other purposes.
