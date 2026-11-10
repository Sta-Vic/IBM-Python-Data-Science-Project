# IBM-Python-Data-Science-Project
📊 Financial Data Science Case Study: Fundamental Growth (Tesla) vs. Market Sentiment Short Squeeze (GameStop)

**Overview:
**
Stock valuation is driven by a complex interplay of fundamental earnings growth and market psychology. In this project, completed as part of the IBM Python Project for Data Science certification, I developed a Python-based analytical workflow to extract, clean, and visualize historical stock prices against quarterly corporate revenue for Tesla (TSLA) and GameStop (GME).

Technical Workflow & Tools:

- Financial API Integration (yfinance): Automated the retrieval of daily historical trading records from IPO to present.

- HTML Web Scraping (requests, BeautifulSoup): Extracted unstructured quarterly revenue tables directly from web sources.

- Data Wrangling (Pandas): Transformed raw text strings into clean numerical series using regex pattern matching (.str.replace(r',|\$', "", regex=True)), handled missing values, and standardized datetime indices.

- Time-Series Visualization (Matplotlib): Generated synchronized dual-axis subplots comparing share price ($US) and quarterly revenue ($US Millions).

**Executive Findings:
**
- Tesla (TSLA): Demonstrates a classic fundamental growth trajectory—between 2018 and 2021, quarterly revenue scaled past $10B, driving a parallel exponential rise in share price and penalizing short sellers.

- GameStop (GME): Illustrates a market-sentiment anomaly—while quarterly revenues followed a cyclical holiday pattern with a gradual post-2018 decline, the stock experienced an unprecedented vertical spike in early 2021 driven by retail investors (the WallStreetBets short squeeze), completely decoupled from immediate earnings.
