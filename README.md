# 📈 MarketMood — Real-Time Consumer Sentiment for Financial News

## Overview

**MarketMood** is a Chrome extension that overlays real-time consumer sentiment directly onto financial news articles and stock tickers as you browse.  
It bridges the gap between traditional financial reporting and the emotional drivers that increasingly move stock prices today.

---

## Why Sentiment Matters

> Tesla's recent earnings report missed Wall Street expectations — yet the stock **skyrocketed** after hours.  
> Traditional analysis predicted a fall, but *consumer sentiment* — driven by optimism and online buzz — overpowered fundamentals.  

This is no longer an isolated case: **sentiment is now a key market driver.**  
Despite this shift, **real-time sentiment insights remain invisible** across major finance platforms.  
Traders and investors must dig through forums, Twitter feeds, and dashboards — a fragmented, slow process that risks missing the moment.

---

## 🔧 What MarketMood Does

- 🔎 **Detects** stock tickers and option contracts while browsing financial sites.
- ⚡ **Fetches** live sentiment scores and recent news from trusted APIs.
- 🎯 **Overlays** clear visual indicators next to each detected ticker:
  - 🟢 Positive  
  - 🟡 Neutral  
  - 🔴 Negative
- 📌 **Displays** detailed sentiment breakdowns in a popup window.

---

## Installation

### Install dependencies:
```
npm install
```
### Start the development server:
```
npm run dev
```
## Load the Extension

1. Run the build command: `npm run build.`
2. Go to `chrome://extensions/` in your Chrome browser.
3. Enable `Developer mode`.
4. Click `Load unpacked` and select the `dist` folder from the project.


