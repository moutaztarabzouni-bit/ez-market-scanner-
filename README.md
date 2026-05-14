# 📊 Professional Market Scanner

> A personal research tool for US stock market analysis — live prices, technical indicators, AI-powered narratives, and investment strategy frameworks.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Live Demo](https://img.shields.io/badge/Demo-Live-brightgreen)](#)
[![No Backend](https://img.shields.io/badge/Backend-None-orange)](#)
[![Self Contained](https://img.shields.io/badge/Deploy-Static-blueviolet)](#)

![Scanner Preview](docs/preview.png)

---

## ⚠️ Important Disclaimer

**This is a personal research and educational tool — NOT licensed financial advice.**

- Not a regulated trading platform
- AI analysis may contain errors (hallucinations, outdated data)
- All signals are algorithmic, not human-verified
- Past performance does not guarantee future results
- **Always consult a licensed financial advisor before making investment decisions**

See [LEGAL DISCLAIMER & LIABILITY WAIVER](#-legal-disclaimer--liability-waiver) at the bottom of this README for full terms.

---

## ✨ Features

### Core Scanning
- 🔍 **Market Scan** — Discover top 30 US stock opportunities ranked by Health Score
- 📈 **Any Stock** — Deep technical analysis for any ticker (RSI, MACD, MA50/200)
- 💼 **Portfolio Tracker** — Live P&L with auto-refresh
- 🔔 **Price Alerts** — Browser notifications when targets are hit
- 👁 **Watchlist** — Monitor entry/target/stop levels
- 📜 **History** — Save last 10 scans for comparison

### Advanced Analysis
- 🏛️ **Elite Engine** — 4 investment strategy frameworks:
  - Warren Buffett (Value)
  - Peter Lynch (GARP)
  - Stanley Druckenmiller (Macro)
  - William O'Neil (CAN SLIM)
- 💧 **Liquidity Analysis** — VIX, HYG, yield curve interpretation
- 🌡️ **Sector Heatmap** — Live performance of 11 S&P sectors
- 📰 **Live News Ticker** — Streaming headlines from Bloomberg, Reuters, WSJ, CNBC

### Bot Health & Safety
- 🛡️ **Bot Health Indicator** — Real-time 12-point health check
- 🛠️ **Auto-Repair Engine** — Detects and fixes 9 types of issues automatically
- 🔒 **Defense Layer** — 10 safe utility functions prevent crashes
- ✅ **Manifest Integrity** — 30 checksummed critical functions

### UX
- 🎨 Dark + Light themes
- ⌨️ Keyboard shortcuts (`S` to scan, `?` for help)
- 📱 Mobile responsive
- ♿ Accessible (ARIA labels, semantic HTML)

---

## 🚀 Quick Start

### Option 1: Open Directly (Easiest)
1. Download `index.html`, `styles.css`, and `app.js` to a folder
2. Open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge)
3. Click **▶ Scan Market** to start

### Option 2: Local Server (Recommended)
```bash
# Using Python
python3 -m http.server 8000

# Using Node
npx serve .

# Then open: http://localhost:8000
```

### Option 3: Deploy to GitHub Pages
1. Fork this repository
2. Go to **Settings** → **Pages**
3. Select branch: `main`, folder: `/ (root)`
4. Your scanner will be live at `https://YOUR-USERNAME.github.io/REPO-NAME/`

### Option 4: Deploy to Netlify / Vercel
- Drag the folder to [Netlify Drop](https://app.netlify.com/drop)
- Or import the repo to [Vercel](https://vercel.com/new)

---

## 🔑 API Keys

### Required: None for basic use
The scanner works out of the box with embedded **Finnhub** access for live prices.

### Optional: Claude API Key (for AI features)
For AI-powered analysis (Bull/Bear narratives, Portfolio Doctor, Elite Engine):

1. Get a key from [Anthropic Console](https://console.anthropic.com/)
2. Click **🔑 Add Claude Key** in the header
3. Paste your key (starts with `sk-ant-`)
4. Key is stored locally in your browser only

---

## 📡 Data Sources

| Source | Purpose | API |
|---|---|---|
| **Finnhub.io** | Live prices, candles, news | Free tier |
| **Anthropic Claude** | AI analysis, market discovery | User-provided |
| **Web Search** | News from Bloomberg, Reuters, WSJ, CNBC, FT, MarketWatch | Via Claude |

All data fetched directly from your browser — **no backend, no proxy, no tracking**.

---

## 📁 Project Structure

```
market-scanner/
├── index.html       # Main HTML structure (8 panels)
├── styles.css       # All styles (~1,600 lines)
├── app.js           # Application logic (~5,900 lines)
├── README.md        # This file
├── LICENSE          # MIT License
└── docs/
    └── preview.png  # Screenshot for README
```

### Single-File Build
A self-contained single-file build is also available as `market_scanner_trading_v5.9.html` for those who prefer one file.

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|---|---|
| `S` | Scan Market |
| `R` | Refresh Prices |
| `T` | Toggle Theme (Dark/Light) |
| `H` | Show Bot Health |
| `1` – `9` | Switch tabs |
| `?` | Show all shortcuts |

---

## 🛠️ Technology Stack

- **HTML5** — Semantic, accessible markup
- **CSS3** — Custom properties, grid, flexbox, animations (no framework)
- **Vanilla JavaScript (ES6+)** — No dependencies, no build step
- **Web APIs** — Fetch, LocalStorage, Notifications, Service Worker (PWA-ready)

**No build tools required.** Just open the HTML.

---

## 🌐 Browser Support

| Browser | Minimum Version |
|---|---|
| Chrome / Edge | 90+ |
| Firefox | 88+ |
| Safari | 14+ |
| Opera | 76+ |

Mobile browsers fully supported (iOS Safari, Chrome Android).

---

## 🤝 Contributing

This is a personal project, but suggestions and bug reports are welcome:

1. Open an [Issue](https://github.com/YOUR-USERNAME/REPO-NAME/issues) for bugs or feature requests
2. Fork the repo and submit a Pull Request for improvements
3. Follow the existing code style (no formatter — just be consistent)

---

## 📊 Project Stats

- **Functions**: 180+
- **HTML**: ~780 lines
- **CSS**: ~1,660 lines
- **JavaScript**: ~5,890 lines
- **Total**: ~430 KB (single file build)
- **Dependencies**: 0
- **Build steps**: 0

---

## 🗺️ Roadmap

- [ ] Crypto support (BTC, ETH, etc.)
- [ ] Backtesting module
- [ ] Custom alerts via email
- [ ] Multi-language support (Arabic, Spanish, French)
- [ ] Export reports to PDF
- [ ] Dark mode auto-switch by time

---

## 👨‍💻 Author

**Al-Moutaz Billah Tarabzouni**

- X (Twitter): [@Moutaz_ez](https://x.com/Moutaz_ez)
- Instagram: [@3z_tarabzouni](https://instagram.com/3z_tarabzouni)
- LinkedIn: [al-moutaz-billah-tarabzouni](https://linkedin.com/in/al-moutaz-billah-tarabzouni)

---

## 📜 License

MIT License — see [LICENSE](LICENSE) for details.

---

## ⚖️ Legal Disclaimer & Liability Waiver

**1. NO FINANCIAL ADVICE.** This software is a personal research and educational tool only. It does NOT constitute, and shall never be construed as, investment advice, financial advice, trading advice, brokerage services, securities recommendations, tax advice, legal advice, or any other regulated professional service. The developer is NOT a licensed financial advisor, broker, dealer, investment adviser, or fiduciary in any jurisdiction.

**2. NO WARRANTY OF ACCURACY.** All data, prices, indicators, signals, scores, news, analyses, and AI-generated content are provided "AS IS" and "AS AVAILABLE" without any warranty of any kind, express or implied, including but not limited to warranties of accuracy, completeness, reliability, timeliness, fitness for a particular purpose, or non-infringement. Data is sourced from third parties (Finnhub, Anthropic Claude AI, public news sources) and may contain errors, delays, hallucinations, or omissions.

**3. FULL LIABILITY WAIVER.** To the fullest extent permitted by applicable law, the developer, contributors, and any affiliated parties shall NOT be liable for any direct, indirect, incidental, special, consequential, punitive, or exemplary damages — including but not limited to financial losses, lost profits, lost capital, lost opportunities, trading losses, missed gains, emotional distress, or any other damages — arising from or related to the use of, inability to use, or reliance upon this tool, its data, or its outputs.

**4. USER ASSUMES ALL RISK.** By accessing or using this tool, you acknowledge and agree that: (a) you are solely responsible for your own investment decisions; (b) you will independently verify all information before acting on it; (c) you understand that trading and investing in securities, commodities, currencies, derivatives, and other financial instruments involves substantial risk of loss, including total loss of capital; (d) past performance does not guarantee future results; and (e) you accept full responsibility for any and all consequences of using this tool.

**5. NO FIDUCIARY RELATIONSHIP.** Use of this tool does NOT create any fiduciary, advisory, contractual, or professional relationship between you and the developer. You should consult qualified, licensed professionals — including financial advisors, attorneys, and tax accountants regulated in your jurisdiction — before making any investment, financial, legal, or tax decisions.

**6. INDEMNIFICATION.** You agree to indemnify, defend, and hold harmless the developer and any affiliated parties from and against any and all claims, liabilities, damages, losses, costs, expenses, and fees (including reasonable attorneys' fees) arising from your use or misuse of this tool, your violation of these terms, or your violation of any applicable laws or regulations.

**7. JURISDICTION & CHANGES.** This tool is provided globally and may not comply with local financial regulations in every jurisdiction. It is your responsibility to determine whether use of this tool is legal in your country. The developer reserves the right to modify, suspend, or discontinue this tool and these terms at any time without notice.

---

**BY USING THIS TOOL, YOU EXPLICITLY ACKNOWLEDGE THAT YOU HAVE READ, UNDERSTOOD, AND ACCEPT THIS DISCLAIMER AND LIABILITY WAIVER IN FULL. IF YOU DO NOT AGREE, DO NOT USE THIS TOOL.**

---

⭐ **If this project helped you, please star the repo!**
