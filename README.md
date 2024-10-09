# Decentralized Exchange (DEX)

## Overview
This project is a simple, efficient Decentralized Exchange (DEX) that allows users to trade between Ethereum (ETH) and ERC20 tokens, as well as between different ERC20 tokens. The DEX operates on the principles of decentralization, allowing users to maintain full control over their assets without the need for intermediaries. Additionally, it features a Liquidity Pool/Reserve to ensure smooth trades with minimal slippage.

## Features
- **ETH to Token Trades:** Seamlessly swap between Ethereum (ETH) and ERC20 tokens.
- **Liquidity Pool/Reserve:** Supports a liquidity pool to facilitate trades and ensure liquidity for smooth transactions.
- **Token to Token Trades:** Users can directly trade between two different ERC20 tokens.
- **Token Trade Permissions:** Requests user permission for each token trade, ensuring security and transparency in all transactions.

## How it Works
1. **Trading ETH and Tokens:** Users can exchange Ethereum (ETH) for any ERC20 token listed on the platform and vice versa.
2. **Liquidity Pool/Reserve:** The DEX uses a liquidity pool to manage and facilitate trades, reducing slippage and ensuring that trades can be completed efficiently.
3. **Token to Token Trading:** Users can trade ERC20 tokens directly without needing to convert to ETH first, streamlining the trading process.
4. **Permission Requests:** Each time a user initiates a token trade, the DEX will ask for permission to interact with the token, ensuring control and security at every step.

## Getting Started

### Prerequisites
- **Node.js** and **npm** installed on your machine.
- **Solidity** knowledge for smart contract interaction.
- A **MetaMask wallet** or similar Ethereum wallet for interacting with the DEX.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/SanRishikesh7/ERCX.git
   cd DEX
