# OrdTrader

## Overview

OrdTrader is a decentralized trading platform for Bitcoin Ordinals. It utilizes an escrow system to facilitate secure and trustless peer-to-peer (P2P) trading. This project aims to provide a user-friendly interface for setting up trades, monitoring progress, and ensuring secure transactions using multi-signature wallets.

## Features

- **Secure Escrow System:** Multi-signature wallets to hold Ordinals until trade conditions are met.
- **User-Friendly Interface:** Intuitive UI for creating and managing trades.
- **Automated Transactions:** Automatically handle the locking and release of Ordinals.
- **Transaction Fee Management:** Covers network fees for a seamless user experience.
- **Trade Monitoring:** Real-time updates on the status of trades.
- **User Authentication:** Secure registration and login using JWT.

## Technology Stack

- **Backend:** Python, Flask
- **Frontend:** React.js
- **Bitcoin Integration:** bitcoinlib (Python)
- **Database:** SQLite (for development), PostgreSQL (for production)
- **Authentication:** JWT (JSON Web Tokens)

## Getting Started

### Prerequisites

- **Python 3.7+**
- **Node.js 14+**
- **npm (Node Package Manager)**
- **Bitcoin Node** (testnet for development)

### Installation