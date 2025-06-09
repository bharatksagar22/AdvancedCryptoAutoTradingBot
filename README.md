Build a full-stack, web-based **Crypto Auto Trading Bot System** integrated with **Delta Exchange API**, using:

- ⚙️ Backend: Python (FastAPI)
- 🌐 Frontend: React.js + Tailwind CSS
- 🗃️ Database: MongoDB Atlas
- ☁️ Hosting: Render.com (backend + frontend)
- 🔐 API Auth: Secure Delta Exchange key/secret integration

### 🎯 Trading Logic Summary (Default)
- Auto Buy when BTC price drops > 2%
- Auto Sell on:
  • Fixed Take Profit (₹350–₹1000)
  • Fixed Stop Loss (₹200–₹450)
  • **Trailing Stop Loss activates only after Take Profit is breached**
- TSL dynamically trails peak profit and exits on ₹ gap reversal

### 🖥️ Web Dashboard Features:
- Toggle Bot ON/OFF
- Live BTC price + Bot Status
- Configurable SL/TP/TSL ranges
- Real-time trade log with P&L
- CSV export for trade history
- Multi-coin selection panel (BTC, ETH, SOL, etc.)

### 🔁 Advanced Logic Engine:
- 🧠 **Dynamic Strategy Switcher**
  • Based on RSI, EMA, MACD, Grid, DCA conditions
  • Adapts to market structure (range, trend, volatility)

- 📈 **Auto Capital Scaling**
  • Profit → Increase capital/qty
  • Loss → Reduce qty for risk control

- 🔄 **AI Learning Agent**
  • Analyzes past trades (success/failure)
  • Auto-tunes SL/TP/TSL dynamically
  • Learns best time zones + strategies

- 🗓️ **No-Trade Time Zones**
  • Avoid trading during volatile or illiquid windows (e.g., 2–4 AM IST)

- 📡 **News Sentiment Filter**
  • Integrates with GPT/Twitter API
  • Flags news sentiment as Bullish/Bearish
  • Avoids risk during negative events (e.g., FTX crash)

- 📊 **Live Graphs + Backtest Viewer**
  • Equity curve, profit curve on frontend
  • Past strategy performance in chart/table form

- 📱 **Telegram Alert System**
  • "Trade Executed", "SL Hit", "Profit Booked ₹+452.34" alerts
  • Optional email/push integration

- 🔐 **Login + Role Access**
  • Admin: Full control
  • Viewer: Read-only trade monitor

### ⚙️ Configuration (via .env or UI):
- Default SL: ₹300
- Default TP: ₹800
- Default TSL: ₹200
- Trading Time: 24x7 or filtered
- Max Open Trades: 3
- Coins: BTC/ETH/SOL/DOGE toggle
- Strategy Mode: Auto / Manual

### 📦 Deliverables:
- GitHub Repo (frontend + backend)
- MongoDB schema
- Setup docs (Render, .env, API keys)
- React + Tailwind clean UI
- All core features ready for deployment

🧠 The goal is to build a **Smart Auto-Trading Bot with Risk Control + Profit Maximization**, capable of adapting to any market using modular plug-and-play strategy components.

# TenderProcessingSystem
