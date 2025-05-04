# 🤖 Alpaca IBM Trading Bot

A simple Python-based trading bot that uses [Alpaca](https://alpaca.markets) paper trading API to automate buying and selling of IBM stock based on short-term price movement.

---

## 📌 Features

- **Buy Trigger**: Buys when IBM's price drops 2% from the most recent high.
- **Sell Trigger**: Sells when the price rises 3% above the buy price.
- **Real-Time Monitoring**: Checks price every 60 seconds using minute-bar data.
- **Order Fill Handling**: Waits up to 10 seconds for each submitted order to be filled.

---

## 🔧 Requirements

- Python 3.7+
- An Alpaca Paper Trading Account
- API Keys from Alpaca
- Internet connection

---

## 🧪 Setup

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/alpaca-stock-bot.git
cd alpaca-stock-bot
2. Install Dependencies
bash
Copy
Edit
pip install alpaca-trade-api python-dotenv pytz
3. Create a .env File
Create a file named .env in the root of the repo and add your Alpaca keys:

env
Copy
Edit
ALPACA_API_KEY=your_alpaca_api_key
ALPACA_SECRET_KEY=your_alpaca_secret_key
4. Run the Bot
bash
Copy
Edit
python stock_bot.py
⚠️ Disclaimer
This bot is intended for educational and paper trading use only. Do not use it with real money unless you fully understand the risks of algorithmic trading.

