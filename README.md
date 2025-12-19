# 🪙 Stablecoin Algorithmic Engine

A decentralized, exogenous collateralized algorithmic stablecoin system, similar to DAI but simplified.

## 🚀 How it Works
- **Collateral:** Users deposit ETH or BTC (wrapped).
- **Minting:** Users can mint stablecoins against their collateral.
- **Stability:** The system uses Chainlink Oracles to maintain the price peg ($1).
- **Liquidation:** If collateral value drops below a threshold, the system triggers liquidation to remain solvent.

## 🛠️ Tech Stack
- **Solidity** (Smart Contracts)
- **Foundry / Hardhat** (Development Framework)
- **Chainlink** (Price Oracles)

## 📁 Key Contracts
1. **DSCEngine.sol**: The core logic for minting/burning and collateral management.
2. **StableCoin.sol**: The ERC20 token contract.

## 🔧 Setup
1. Clone: `git clone [Your-Repo-Link]`
2. Install: `forge install` or `npm install`
3. Test: `forge test`
