# Bot Pharos – Testnet Utility

A fully automated script tailored for the Pharos Testnet, capable of performing token swaps, PHRS transfers, faucet claims, and daily check-ins — optimized for maximizing potential airdrop rewards.

## Features 🌟

- 🔁 **Automated Token Swaps**: Randomly swaps WPHRS ↔ USDC / USDT
- 💸 **PHRS Transfers**: Sends small PHRS amounts to newly generated addresses
- 🚰 **Faucet Interaction**: Claims daily testnet tokens if eligible
- 📆 **Daily Check-Ins**: Automates check-in tasks to collect points
- 🌐 **Proxy Support**: Compatible with HTTP/SOCKS proxies (via `proxies.txt`)
- 🧠 **Multiple Wallets**: Operates multiple wallets

## Requirements 🧩

- Node.js (version 18+ recommended)
- npm or yarn installed
- `.env` file with your private key(s) set as:
  PRIVATE_KEY_1=YOUR_RIVATE_KEY
  PRIVATE_KEY_2=YOUR_PRIVATE_KEY
  etc...
- (Optional) A `proxies.txt` file with proxies listed one per line

## Setup & Installation 🔧

1. Clone this repository:
   `git clone https://github.com/yourusername/Bot-Pharos.git
   cd Bot-Pharos`
2. Install Dependencies:
   `npm install`
