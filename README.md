# UniversalDEX# UniversalDEX Demo

## Features
- Local and cross-chain swaps
- Voluntary 1% donation
- DAO proposals, voting, and upgrade simulation
- Multi-chain liquidity display
- Interactive front-end

## Quick Start

1. Install dependencies:
```bash
npm install
cd frontend
npm install
cd ..
npm run start-node1
npm run start-node2
npm run start-node3
npm run deploy-demo
const DEX_ADDRESS = "0xYourDEXAddress";
const DAO_ADDRESS = "0xYourDAOAddress";
const TOKEN_A_ADDRESS = "0xYourTokenA";
const TOKEN_B_ADDRESS = "0xYourTokenB";
npm run start-frontend
npm test

---

# **5. Front-End Pre-Filled Configuration**

- All components (`WalletConnect.js`, `SwapForm.js`, `LiquidityDisplay.js`, `DAOVoting.js`) are ready to connect to the deployed local contracts.
- Multi-chain swaps can be simulated by changing the **Destination Chain ID** input in the swap form.
- DAO proposals and voting are fully functional via the `DAOVoting` component.
- Voluntary 1% donation is toggled per swap.

---

# **6. Running Everything End-to-End**

1. Clone the repo.  
2. Install dependencies (`npm install && cd frontend && npm install`).  
3. Start 3 Hardhat nodes (`npm run start-node1`, etc.).  
4. Deploy contracts (`npm run deploy-demo`).  
5. Update front-end addresses in `App.js`.  
6. Launch front-end (`npm run start-frontend`).  
7. Interact with demo: add liquidity, swap tokens, toggle donations, vote in DAO.  
8. Run automated tests (`npm test`) to validate functionality.

