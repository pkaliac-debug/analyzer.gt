# ⚡ Deriv Analyzer

A mobile-first, real-time trading analysis tool built for **Deriv Synthetic Indices** (Volatility Index digits trading).

---

## 🚀 Live Demo

> Open `deriv-analyzer-live-4.html` directly in your browser — no installation needed.

---

## 📱 Features

### 🔴 Live Analyzer
- Connects directly to **Deriv's WebSocket API** using your API token (read-only)
- Real-time **last digit tracking** across 10 digits (0–9)
- **Digit frequency battlefield** — color-coded by dominance (GB, 2GB, RB, 2RB)
- **Bias & confidence scoring** — market structure detection with entropy analysis
- **Even/Odd ratio tracker** with visual progress bar
- **Live tick display** with animated cursor trail
- **Market Insights drawer** — Gap Strength, 0&9 Alignment, Neglected Zone, Conditions Met
- **Smart warnings** — competing digit alerts, spottable pattern detection, stop-loss triggers

### 💰 Risk Management
- **Capital setup** with 3 risk modes: Conservative (5%), Balanced (10%), Aggressive (15%)
- **Weekly compounding table** — auto-calculated daily balance, target, stop & stake
- **Daily progress tracker** with P&L progress bar
- **Structure-based stake suggestions** (Weak / Moderate / Strong)
- **Session limits** — max trades, daily loss limit, win streak tracking
- **Recovery mode** — Martingale & Fixed stake recovery calculator

### 📓 Trade Journal
- Log every trade with market, strategy, stake, result & notes
- Win/Loss history with timestamps
- Persistent local storage — data saved in your browser

### 📊 Performance Tab
- Win rate, profit factor, average win/loss metrics
- **Equity curve** bar chart
- **Best trading hours** heatmap
- Win/Loss/Break-even streak tracking

### 📋 Rules Tab
- Built-in trading rules and discipline reminders
- Golden rule highlight
- Common mistakes checklist

---

## 🔐 Setup

1. Go to **Deriv → Account Settings → API Token**
2. Create a token with **Read** permission only
3. Open the HTML file in your browser
4. Paste your token and click **Connect Live**

> Your token is stored locally on your device and only connects directly to Deriv's servers. It is never sent anywhere else.

---

## 📊 Supported Markets

| Symbol | Market |
|--------|--------|
| V10 | Volatility 10 Index |
| V25 | Volatility 25 Index |
| V50 | Volatility 50 Index |
| V75 | Volatility 75 Index |
| V100 | Volatility 100 Index |
| V10 (1s) | Volatility 10 Index (1s) |
| V25 (1s) | Volatility 25 Index (1s) |
| V50 (1s) | Volatility 50 Index (1s) |
| V75 (1s) | Volatility 75 Index (1s) |
| V100 (1s) | Volatility 100 Index (1s) |

---

## ⚙️ Analysis Window

Choose your tick window size: **100 / 250 / 500 / 750 / 1000** ticks — adjustable live from the top bar.

---

## ⚠️ Disclaimer

This tool is for **analytical and educational purposes only**. Trading synthetic indices involves significant financial risk. Always trade responsibly and never risk more than you can afford to lose.

---

## 🛠️ Tech Stack

- Pure **HTML / CSS / JavaScript** — no frameworks, no dependencies
- Connects to `wss://ws.binaryws.com/websockets/v3` (Deriv WebSocket API)
- Fonts: Oxanium + JetBrains Mono (Google Fonts)

---

*Built for serious Deriv digits traders.*
