# MT5 Trading Bot

Learning project: connect Python to MetaTrader 5 and build a trading bot step by step.

## Setup
1. Create conda env: `conda create -n mt5_env python=3.14 -y`
2. Activate: `conda activate mt5_env`
3. Install: `pip install -r requirements.txt`
4. Copy `.env.example` to `.env` and fill in your MT5 demo credentials.

## Scripts
- `stage1_connect.py` — connect to MT5 and print last 10 H1 candles of EURUSD.