# ML-Driven Statistical Arbitrage Trading Bot

This repository documents a project aimed at building a machine learning-driven statistical arbitrage trading bot. The goal is to develop a system that not only automates trading based on quantitative strategies but also serves as a comprehensive portfolio piece to demonstrate proficiency in data science, machine learning, and algorithmic trading.

## Overview

The project is divided into distinct phases:
- **Research and Exploration:** Understanding the fundamentals of statistical arbitrage, including concepts like mean reversion, cointegration, and pairs trading. Our research has been documented in `docs/statarb_research.md`, which covers the theoretical foundations, historical context, and key methodologies.
- **Data Collection and Preprocessing:** Developing a robust data pipeline to fetch, clean, and store historical market data using Python libraries (e.g., `yfinance`). The module for data collection is implemented in `src/data_collection.py`.
- **Strategy Development (Upcoming):** Integration of machine learning techniques and backtesting modules to develop, simulate, and refine our trading strategy.

## Current Progress

- **Research Documentation:**  
  - Completed a detailed review of statistical arbitrage concepts.
  - Documented key insights and relevant resources in `docs/statarb_research.md`.
  - **Sources:**  
    - [Wikipedia – Statistical Arbitrage](https://en.wikipedia.org/wiki/Statistical_arbitrage) :contentReference[oaicite:0]{index=0}  
    - [Using Python for Statistical Arbitrage](https://medium.com/@deepml1818/python-for-statistical-arbitrage-pairs-trading-strategy-development-0e778e7ebdcb) :contentReference[oaicite:1]{index=1}

- **Data Collection Module:**  
  - Implemented a Python script in `src/data_collection.py` to download historical price data for stocks (using tickers like AAPL and MSFT) via the `yfinance` library.
  - The fetched data is stored as CSV files in the `data/raw/` directory.
  - **Sources:**  
    - [Best Python Libraries for Trading](https://mayerkrebs.com/best-python-libraries-for-trading/) :contentReference[oaicite:2]{index=2}

## Repository Structure (Current)


## Next Steps

1. **Data Preprocessing & Exploration:**  
   - Expand our data pipeline to clean and preprocess raw data.
   - Create Jupyter notebooks for exploratory data analysis and visualization.

2. **Strategy Development:**  
   - Start integrating statistical methods and machine learning models.
   - Begin developing the trading strategy, including signal generation and backtesting.

3. **Documentation & Continuous Learning:**  
   - Keep updating the `docs/learning_journal.md` with insights, challenges, and new learnings.
   - Maintain detailed commit messages to track progress for portfolio purposes.

## Getting Started

To replicate our setup:
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ml-statarb-trading-bot.git
    cd ml-statarb-trading-bot
    ```
2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the data collection module:
    ```bash
    python src/data_collection.py
    ```

## Final Thoughts

This project is a living portfolio piece that reflects ongoing learning and practical implementation in quantitative finance. By combining rigorous research with hands-on development, it aims to provide a robust example of applied data science and machine learning in the context of algorithmic trading.

