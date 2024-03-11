# Web Scraping Project: Amazon Stock Data Extraction

This project demonstrates a basic web scraping technique to extract historical stock data from a webpage using Python libraries such as BeautifulSoup and Pandas.

## Overview

In this project, we scrape historical stock data from a webpage containing Amazon's share prices. We extract the data using the requests library to download the webpage and then parse the HTML content with BeautifulSoup. Finally, we organize the extracted data into a structured DataFrame using Pandas.

## Requirements

To run this project, ensure you have the following dependencies installed:

- Python (>=3.6)
- Pandas (1.3.3)
- Requests (2.26.0)
- BeautifulSoup4 (4.10.0)
- html5lib (1.1)
- lxml (4.6.4)

You can install these dependencies using pip or conda package manager.

## Usage

1. Clone the repository or download the project files.
2. Install the required dependencies listed above.
3. Run the provided Python script to perform the web scraping and extract the Amazon stock data.
4. The extracted data will be stored in a Pandas DataFrame named `amazon_data`.
5. You can access and analyze the extracted data within your Python environment or export it to different formats for further analysis.

## Files Included

- `scrape_amazon_stock_data.py`: Python script for web scraping and extracting Amazon stock data.
- `README.md`: This file providing an overview of the project and instructions for usage.

## Acknowledgments

This project is part of the IBM Developer Skills Network Python for Data Science course (PY0220EN) provided by IBM.

