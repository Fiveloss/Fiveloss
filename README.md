<p align="center">
  <img src="banner.gif" alt="Silverhand Buys" width="100%">
</p>

<h3 align="center">Live, on-chain tools for Telegram token communities on Robinhood Chain</h3>

<p align="center">
  <a href="https://t.me/SilverhandBuysBot"><img alt="Telegram" src="https://img.shields.io/badge/Telegram-@SilverhandBuysBot-2df59a?logo=telegram&logoColor=white&labelColor=0e1621"></a>
  <a href="https://github.com/Fiveloss/silverhand-buys"><img alt="Source" src="https://img.shields.io/badge/source-open-2df59a?logo=github&logoColor=white&labelColor=0e1621"></a>
  <a href="https://github.com/Fiveloss/silverhand-buys/blob/main/LICENSE"><img alt="AGPL-3.0" src="https://img.shields.io/badge/license-AGPL--3.0-c9d1da?labelColor=0e1621"></a>
</p>

---

<img src="card.gif" alt="An animated buy post" width="440" align="right">

### ⚡ [Silverhand Buys](https://github.com/Fiveloss/silverhand-buys)

A Telegram buy bot: add it to your token's group or channel and every buy lands in the chat the moment it hits the chain.

- 🎞 an animated market-cap card with every post
- 🆕 new holders, 💼 position changes, 🐋 whales, 👨‍💻 dev buys
- 🔴 sells too, if you want them
- 🚀 posts of their own for new market-cap highs and a filling curve
- 📊 `/stats` and 🏆 `/top` right in the chat
- 🌐 English and Русский · forum topics · channels
- 🔒 reads only its own commands, never asks for keys

**[➕ Add to your chat](https://t.me/SilverhandBuysBot)** · **[📖 Source](https://github.com/Fiveloss/silverhand-buys)**

<br clear="right">

---

<p align="center">
  <img src="vpn-banner.gif" alt="Silverhand VPN" width="100%">
</p>

<p align="center">
  <a href="https://t.me/fiveloss_VPNbot"><img alt="Telegram" src="https://img.shields.io/badge/Telegram-@fiveloss__VPNbot-ff2b3d?logo=telegram&logoColor=white&labelColor=0e1621"></a>
  <a href="https://quaynet.online"><img alt="Website" src="https://img.shields.io/badge/web-quaynet.online-ff2b3d?logo=googlechrome&logoColor=white&labelColor=0e1621"></a>
</p>

<img src="vpn-card.gif" alt="Auto · Fastest: the app pings every server and picks the quickest" width="440" align="left">

### 🔴 [Silverhand VPN](https://quaynet.online)

A paid VPN you buy and manage in Telegram or on the web. One link works in Happ, INCY, v2rayN and other apps.

- ⚡ **Auto · Fastest** picks the quickest server by itself
- 📶 Wi-Fi, LTE with Salamander, XHTTP for strict networks
- 🌍 Poland and Estonia · Russian sites skip the tunnel
- 🛡 ads cut on the servers, no browsing history kept
- 🩺 connection check and speed test built in
- 💳 card, SBP or crypto · 🎁 gifts · 🌐 Русский

**[🤖 Open the bot](https://t.me/fiveloss_VPNbot)** · **[🌐 quaynet.online](https://quaynet.online)**

<br clear="left">

---

### 🛠 How it's built

**Silverhand Buys**: `Python` · `aiogram 3` · `SQLite` · `Pillow` · `ffmpeg` · `systemd`

No web3 library: logs, ABI and keccak are decoded by hand, and every chain fact the bot relies on is checked against mainnet before it starts. Prices come from the trade events themselves, so the public RPC gets a handful of calls every three seconds.

**Silverhand VPN**: `Python` · `aiogram 3` · `aiohttp` · `SQLite` · `Xray-core` · `Hysteria2` · `Caddy`

One process runs the bot, the web shop and the payment webhooks. Every payment is re-checked with the provider before a key is issued, and the subscription carries its own routing rules, so the app needs no setup beyond adding the link.

<p align="center"><sub>Not paper hands. Silver hands.</sub></p>
