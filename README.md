# 🎯 S/R Zone Pro — Free TradingView Support & Resistance Indicator

**Free TradingView indicator · Auto support resistance zones · Price action S/R detection**

[![Pine Script](https://img.shields.io/badge/Pine%20Script-v5-00b894?style=flat-square&logo=tradingview)](https://tradingview.com/pine-script-docs)
[![TradingView](https://img.shields.io/badge/TradingView-indicator-2196F3?style=flat-square&logo=tradingview)](https://tradingview.com)
[![License](https://img.shields.io/badge/license-Single%20User-blue?style=flat-square)](LICENSE)
[![Alerts](https://img.shields.io/badge/alerts-Price%20Touch%20%7C%20Break-brightgreen?style=flat-square)](https://tradingview.com)

> **Professional TradingView indicator** that auto-detects and draws support & resistance zones based on real price action. No more manual chart markup — color-coded by zone strength, tested by real volume.

<p align="center">
  <img src="https://via.placeholder.com/800x400/1a1a2e/7c3aed?text=S%2FR+Zone+Pro+TradingView" alt="S/R Zone Pro Preview" width="800">
</p>

---

## 📑 Table of Contents
- [What It Does](#-what-it-does)
- [Features](#-features)
- [Why Traders Love This](#-why-traders-love-this)
- [Installation](#-installation)
- [Visual Guide](#-visual-guide)
- [Settings Guide](#-settings-guide)
- [Trading Strategies](#-trading-strategies)
- [FAQ](#-faq)
- [SEO Keywords](#-seo-keywords)

---

## 🎯 What It Does

Auto-detects support & resistance zones using pivot-based calculations — not random lines:

```
                    RESISTANCE ZONE (Major - Tested 5x)
    ════════════════════════════════════════════════  ← Price rejects here
                    │
    ─ ─ ─ ─ ─ ─ ─ ─│─ ─ ─ ─ ─ ─ ─ ─ ─ ─  ← Minor zone
                    │
    ════════════════════════════════════════════════  ← Price bounces here
                    SUPPORT ZONE (Major - Tested 3x)
```

---

## ✨ Features

| Feature | Detail | Why It Matters |
|---------|--------|----------------|
| 📊 **Auto S/R Detection** | Pivot-based with configurable period | No manual drawing — saves hours |
| 🎚️ **Major/Minor Zones** | Color-coded by zone strength | Know which levels matter most |
| 📦 **Zone Boxes** | Visual boxes + horizontal lines | Clear at-a-glance levels |
| 🔔 **Price Touch Alerts** | Get notified when price hits a zone | Never miss a reaction |
| 🎨 **Heikin Ashi Option** | Smoother zones for ranging markets | Better in choppy conditions |
| 📈 **Multi-Timeframe** | Works on 1M to 1W | Scalping to swing trading |
| 🧪 **Test Count** | Shows how many times zone was touched | Stronger zones = more touches |
| 🎯 **Zone Break Alerts** | Separate alert for zone breaks | Confirms trend change |

---

## ❤️ Why Traders Love This

| Problem | S/R Zone Pro Solution |
|---------|----------------------|
| ❌ Manual drawing takes hours | ✅ Auto-detected in real-time |
| ❌ Random lines with no validation | ✅ Pivot-based, volume-validated |
| ❌ Can't tell strong from weak zones | ✅ Color-coded by test count |
| ❌ Cluttered chart with 20 lines | ✅ Clean boxes, major/minor filter |
| ❌ One timeframe only | ✅ Works on ALL timeframes |

---

## 📥 Installation

1. Open **TradingView** → Pine Editor (bottom panel)
2. Copy the contents of `sr-zone-pro.pine`
3. Paste into Pine Editor → Click **"Add to Chart"**
4. Done! Zones appear automatically on your chart.

---

## 🖼️ Visual Guide

### Major vs Minor Zones
- **🟢 Green zones = Support tested 3+ times** → Strong bounce potential
- **🔴 Red zones = Resistance tested 3+ times** → Strong rejection potential
- **🟡 Yellow zones = Minor** → Tested 1-2 times, lower reliability

### Zone Types
| Zone | Color | Test Count | Reliability |
|------|-------|-----------|-------------|
| Major Support | 🟢 Green | 3+ | High |
| Minor Support | 🟢 Pale Green | 1-2 | Medium |
| Major Resistance | 🔴 Red | 3+ | High |
| Minor Resistance | 🔴 Pale Red | 1-2 | Medium |

---

## ⚙️ Settings Guide

| Setting | Recommended | What It Changes |
|---------|------------|-----------------|
| **Pivot Period** | 20 (swing) / 10 (intraday) / 5 (scalp) | Higher = stronger zones, fewer signals |
| **Zone Strength** | 3 | Minimum touches to show a zone |
| **Show Minor Zones** | ON for day trading | OFF for cleaner swing charts |
| **Zone Width** | Auto | Width of visual boxes |
| **Alert on Touch** | ON | Get notified when price hits |
| **Heikin Ashi** | ON for crypto | Smoother in volatile markets |

### Recommended By Trading Style

| Trading Style | Pivot Period | Minor Zones | Heikin Ashi |
|---------------|-------------|-------------|-------------|
| 🏃 Scalping (1M-5M) | 5 | ON | OFF |
| 📊 Day Trading (15M-1H) | 10 | ON | ON |
| 🔄 Swing (4H-Daily) | 20 | OFF | ON |
| 💎 Position (Weekly) | 30 | OFF | OFF |

---

## 📈 Trading Strategies

### Strategy 1: Zone Bounce
```
1. Wait for price to approach a MAJOR zone (3+ tests)
2. Look for rejection candlestick pattern (pin bar, engulfing)
3. Enter at zone edge
4. Stop loss: beyond zone width
5. Target: opposite major zone
```

### Strategy 2: Zone Break & Retest
```
1. Price breaks through a zone with volume
2. Wait for price to RETURN to the broken zone
3. Zone flips: support → resistance (or vice versa)
4. Enter on retest confirmation candle
5. Stop loss: inside the zone
```

### Strategy 3: Zone-to-Zone
```
1. Price bounces off Major Support
2. Ride the move until Major Resistance
3. Book profits at resistance
4. Wait for setup at either zone
```

---

## ❓ FAQ

<details>
<summary><b>Does this work on all markets?</b></summary>
Yes — crypto, forex, stocks, indices, commodities. Any market on TradingView.
</details>

<details>
<summary><b>How is this different from built-in S/R?</b></summary>
TradingView's built-in tools require manual drawing. S/R Zone Pro auto-detects ALL zones, ranks them by strength, and updates in real-time.
</details>

<details>
<summary><b>Does it repaint?</b></summary>
Minor zone colors can update as test counts increase, but the zone levels themselves don't move once confirmed by a pivot.
</details>

<details>
<summary><b>Can I use this with other indicators?</b></summary>
Combines extremely well with volume profile, RSI divergence, and EMA ribbons.
</details>

---

## 🔑 SEO Keywords

`free TradingView indicator` · `support resistance indicator` · `auto S/R zones TradingView` · `price action support resistance` · `pivot point indicator free` · `trading indicator S/R` · `support resistance zone indicator` · `auto support resistance pine script`

---

## 💰 Pricing

**Pay What You Want — Minimum $5 USDT/POL (Polygon)**

Wallet: `0xD404AE6B45Cae3D453D4408de99eC489Ce0fc18e`

Includes: Lifetime updates + documentation.

---

## 📄 License

Single-user license. © Nico
