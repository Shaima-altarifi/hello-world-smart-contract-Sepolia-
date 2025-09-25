# Hello World Smart Contract (Sepolia)

A simple Solidity smart contract built with Hardhat that stores and updates a message on the blockchain.  
The contract includes:
- A constructor to set the initial message.
- A function to update the message.
- An event emitted whenever the message is updated.

## Tech Stack
- **Solidity** (v0.8.x)
- **Hardhat** for development and testing
- **Ethereum Sepolia Testnet** for deployment

## Getting Started

### 1. Install dependencies
```bash
npm install

npx hardhat compile

npx hardhat run scripts/deploy.js --network sepolia

npx hardhat run scripts/interact.js --network sepolia

Developed by Shaima Altarifi 
