Stock and Revenue Data Analysis Dashboard

Overview

This project analyzes historical stock prices and company revenue data for Tesla (TSLA) and GameStop (GME). It was completed as part of the IBM Data Science Professional Certificate.

The project combines stock-market data retrieved with Python and revenue data collected through web scraping. The resulting datasets are cleaned and visualized to compare historical share prices with company revenue trends.

Project Objectives

Retrieve historical Tesla and GameStop stock data using yfinance

Extract historical revenue data through web scraping

Clean and prepare the collected data using pandas

Display and inspect the resulting datasets

Create interactive visualizations comparing stock price and revenue over time

Technologies Used

Python

Jupyter Notebook

pandas

yfinance

BeautifulSoup

requests

Plotly

Data Collection

Stock Data

Historical stock data is retrieved with the yfinance library for:

Tesla (TSLA)

GameStop (GME)

The historical data is stored in pandas DataFrames and the index is reset to make the date available as a regular column.

Revenue Data

Historical revenue data for Tesla and GameStop is extracted from HTML pages using requests and BeautifulSoup. The extracted data is organized into DataFrames and cleaned by removing currency symbols, commas, and empty values.

Visualization

The project uses Plotly to visualize:

Historical stock prices

Historical company revenue

Separate dashboards are generated for Tesla and GameStop, allowing stock-price movements to be viewed alongside changes in revenue.

Repository Contents

Revenue Data and Building a Dashboard.ipynb — Jupyter Notebook containing the complete analysis

README.md — Project documentation

Running the Notebook

Install the required Python packages:

pip install yfinance pandas requests beautifulsoup4 plotly

Then open the notebook in Jupyter Notebook, JupyterLab, VS Code, or another compatible environment and run the cells in order.

Course

This project was completed as part of the IBM Data Science Professional Certificate on Coursera.
