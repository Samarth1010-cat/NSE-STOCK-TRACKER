# NSE Stock Market Performance Tracker

## About This Project
This is a data analytics portfolio project. I created a Python script to automatically download 2 years of daily stock market data for 10 major Indian companies. I cleaned the data, calculated moving averages, and built an interactive dashboard to visualize the trends.

## Tools I Used
* **Python (Pandas, yfinance):** To extract and clean the data.
* **Power BI:** To build the interactive data visualizations.

## 🧠 Challenges & What I Learned
To ensure this project reflects real-world data tasks, here are the main challenges I worked through:
* **Handling API Structures:** I learned how to manage and flatten multi-level column indexes that financial APIs often return, turning them into a standard, readable dataframe.
* **Date Hierarchies in BI:** When importing time-series data into Power BI, it defaults to grouping dates by Year/Quarter. I learned how to override automatic hierarchies to accurately plot continuous, day-by-day line charts.
* **Financial Logic in Code:** Successfully translated standard market formulas (like percentage change from Open to Close) into automated Python code rather than relying on Excel formulas.

## Files in this Repository
1. `stock_dashboard.pbix`: The final interactive Power BI dashboard.
2. `stock_tracker.ipynb`: The Python code used to get the data.
3. `nse_10_stock_tracker_data.csv`: The cleaned dataset.
