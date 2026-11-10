# IBM-Python-Data-Science-Project
Analyzing Historical Stock/Revenue Data and Building a Dashboard (Tesla &amp; GameStop)

**Hello everyone!
**
I have completed the final project for the IBM Python Project for Data Science course: Analyzing Historical Stock/Revenue Data and Building a Dashboard.

Stepping into the role of a Data Analyst at an investment firm, I built an end-to-end Python pipeline in Jupyter Notebook to compare fundamental business performance against market stock valuation for Tesla (TSLA) and GameStop (GME):

API Market Data Extraction (yfinance): Extracted full historical share price datasets (period="max") for both Tesla and GameStop, resetting DataFrame indices for time-series alignment.

Financial Web Scraping (requests & BeautifulSoup): Parsed HTML quarterly revenue tables, isolated target <tbody> elements, and cleaned currency formatting ($ and commas) and null records using Pandas regular expressions.

Comparative Dashboard Visualization (Matplotlib): Plotted dual time-series dashboards via make_graph to evaluate revenue trends alongside share price trajectories.

Key Analytical Insight: The visualizations clearly contrast Tesla’s fundamental growth (where share price surged in tandem with scaling quarterly revenue between 2018 and 2021) against GameStop’s 2021 short-squeeze anomaly (where retail market sentiment drove an extreme price spike despite declining seasonal revenue).

GitHub Project Notebook: https://github.com/Sta-Vic/IBM-Python-Data-Science-Project

I would greatly appreciate your peer review and feedback, and I am happy to review your submissions in return. Thank you!
