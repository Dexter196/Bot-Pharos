# Bot Pharos – Testnet Utility

A fully automated script tailored for the Pharos Testnet, capable of performing token swaps, PHRS transfers, faucet claims, and daily check-ins.

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
- (Optional) A `proxies.txt` file with proxies listed one per line

## Setup & Installation 🔧

1. Clone this repository:
   ```bash
   git clone https://github.com/Dexter196/Bot-Pharos.git
   cd Bot-Pharos
2. Install Dependencies:
   ```bash
   npm install
3. Create .env (example)
   ```dotenv
   PRIVATE_KEY_1=your_first_private_key
   PRIVATE_KEY_2=your_second_private_key
4. (Optional) Add proxy entries to proxies.txt
   ```perl
   http://user:pass@ip:port
   socks5://user:pass@ip:port

## How To Use🚀
   ```bash
   node index.js
