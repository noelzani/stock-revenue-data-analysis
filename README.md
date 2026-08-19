#  Stock and Revenue Data Analysis Dashboard

##  Overview

This project analyzes historical **stock prices** and **company revenue data** for **Tesla (TSLA)** and **GameStop (GME)**.

It was completed as part of the **IBM Data Science Professional Certificate** and demonstrates the use of Python for data extraction, web scraping, data cleaning, and visualization.

The project combines historical stock-market data retrieved using `yfinance` with revenue data collected through web scraping. The resulting datasets are processed and visualized to examine stock price and revenue trends over time.

##  Project Objectives

- Retrieve historical Tesla and GameStop stock data using `yfinance`
- Extract historical company revenue data using web scraping
- Clean and prepare datasets using `pandas`
- Explore historical stock and revenue data
- Create visualizations comparing stock prices and revenue over time

##  Technologies Used

- **Python**
- **Jupyter Notebook**
- **pandas**
- **yfinance**
- **BeautifulSoup**
- **Requests**
- **Plotly**

##  Data Collection

### Stock Data

Historical stock-market data was retrieved using the `yfinance` library for:

- **Tesla:** `TSLA`
- **GameStop:** `GME`

The data includes historical information such as:

- Date
- Open price
- High price
- Low price
- Closing price
- Trading volume

### Revenue Data

Historical revenue data for Tesla and GameStop was extracted from HTML pages using:

- `requests`
- `BeautifulSoup`

The extracted data was converted into pandas DataFrames and cleaned by removing currency symbols, commas, null values, and empty entries.

##  Data Visualization

The project creates dashboards for both companies showing:

1. **Historical share price**
2. **Historical revenue**

These visualizations make it possible to examine how each company's stock performance changed alongside its revenue over time.

##  Repository Structure

```text
stock-revenue-data-analysis/
│
├── Revenue Data and Building a Dashboard.ipynb
└── README.md
```

##  Running the Project

Install the required Python libraries:

```bash
pip install yfinance pandas requests beautifulsoup4 plotly
```

Then open:

```text
Revenue Data and Building a Dashboard.ipynb
```

Run the notebook cells in order to reproduce the analysis and visualizations.

##  Course

This project was completed as part of the **IBM Data Science Professional Certificate** on Coursera.
