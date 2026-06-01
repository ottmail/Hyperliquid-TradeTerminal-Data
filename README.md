# Hyperliquid-TradeTerminal-Data
This demo website shows data of all Hyperliquid Trade Terminal pairs with pricing, OI, 24h change etc. Give it a try.

A lightweight, zero-dependency live dashboard for tracking real-time TradFi and Cryptocurrency markets via the Hyperliquid API. 

This terminal is designed for traders who need a fast, auto-refreshing overview of the markets—whether you are tracking standard crypto pairs, major indices, or crypto-adjacent equities like HUT and Bitminer. It runs entirely in your browser with no build steps, trackers, or backend required.

## ✨ Features

* Real-Time Data Streams: 15-second auto-refresh cycles for live price action, open interest, and 24h volume.
* Auto-Discovery & Categorization: Automatically pulls and categorizes assets into sectors (AI Infra, Memory, Crypto, FX, Commodities, etc.).
* Advanced Metrics: Instantly view 1h funding rates and calculated Funding APRs alongside leverage limits.
* Movers Panel: Automatically surfaces the top 3 gainers, losers, and volume leaders over a 24-hour period.
* Local Favorites: Star your most tracked assets to pin them to a dedicated tab (data is saved locally in your browser).
* Single-File Architecture: The entire application (HTML, CSS, JavaScript) is contained within a single `index.html` file.

🚀 How to Use

Because this is a static, single-file web app, its pretty easy to use it:

Visit the live GitHub Pages deployment here: 

🛠️ Built With

* Vanilla JavaScript - No frameworks, just fast native execution.
* CSS3 - Custom styling with CSS variables and flexbox/grid layouts.
* Hyperliquid API - Pulling from `api.hyperliquid.xyz/info`.

⚠️ Disclaimer

This dashboard is for informational purposes only and does not constitute financial advice. Funding rates and prices are pulled directly from public APIs and may be subject to latency.
