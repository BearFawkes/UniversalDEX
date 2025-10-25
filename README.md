# UniversalDEX Demo

## Overview
UniversalDEX is a decentralized exchange demo that supports:
- Local and cross-chain token swaps
- Voluntary 1% donation mechanism
- DAO proposals, voting, and upgrade simulation
- Multi-chain liquidity display
- Interactive front-end interface

---

## Features
- **Local & Cross-Chain Swaps**: Swap tokens within a single chain or across multiple chains.  
- **DAO Governance**: Create proposals, vote, and simulate upgrades.  
- **Multi-Chain Liquidity**: Track liquidity across different chains in real-time.  
- **Interactive Front-End**: React-based UI with WalletConnect support.

---

## Quick Start

npm install
cd frontend
npm install
cd ..
npx hardhat node --port 8545 --network chain1
npx hardhat node --port 8546 --network chain2
npx hardhat node --port 8547 --network chain3
npx hardhat run scripts/deploy-demo.js --network chain1
frontend/src/App.js
cd frontend
npm start
