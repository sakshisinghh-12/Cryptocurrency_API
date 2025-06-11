# Cryptocurrency_API

# Crypto Market Analytics & Email Alert System

An automated Python project that extracts real-time cryptocurrency market data from the CoinGecko API, identifies top gainers and losers, saves them into timestamped CSV files, and sends daily email reports — all scheduled to run every morning automatically.

# Features

- **API Integration**: Fetches data for 250+ cryptocurrencies from the CoinGecko API.
- **Data Cleaning & Transformation**: Selects relevant columns, calculates price changes, and sorts top 10 gainers and losers.
- **Data Export**: Saves the complete dataset and filtered top 10/ bottom 10 into timestamped `.csv` files.
- **Email Reporting**: Sends an automated email with the summary and CSV attachment.
- **Daily Automation**: Uses the `schedule` library to run the full pipeline daily at 8 AM.
- **Credential Handling**: (Recommend using `.env` file for sensitive info - see below)
