# TradingView CSV Datafeed Demo (Public)

Public, non-commercial, no paywall demo showing:
- CSV → TradingView UDF-style datafeed (/config, /symbols, /search, /history, /time)
- Demo chart (Lightweight Charts)
- Intended for evaluation of TradingView Charting Library (non-trading)
  
Live demo: [https://<your-demo>.vercel.app](https://mayuragravkar-dev.github.io/tv-csv-datafeed-demo)

Run locally:
  npm install
  npm start
  # open http://localhost:8080

Use your CSV:
- Put file at data/sample.csv with headers: time/open/high/low/close[/volume]
- Or set env: CSV_PATH=/abs/path/to/your.csv npm start

Notes:
- This repo is public and non-commercial.
- Once granted access, the site will embed the TradingView Charting Library using this datafeed.

Contact email: agravkarmayur18@gmail.com
