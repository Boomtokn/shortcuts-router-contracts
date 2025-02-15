# Shortcuts Router Contracts  

## Overview  
**Shortcuts Router Contracts** is a smart contract repository designed to optimize and streamline token swaps, liquidity routing, and DeFi interactions across multiple blockchain networks.  

## Features  
- **Optimized Routing** – Efficiently find the best token swap paths.  
- **Multi-Chain Compatibility** – Supports major blockchain networks like Ethereum, BSC, and Base.  
- **Gas Efficiency** – Reduces transaction costs using smart routing mechanisms.  
- **Security & Audits** – Built with best practices in Solidity to ensure security.  

## Repository Structure  
shortcuts-router-contracts/
│── contracts/             # Smart contract source code
│── scripts/               # Deployment and interaction scripts
│── test/                  # Unit tests for contract functionality
│── deployments/           # Deployment addresses and configurations
│── README.md              # Project documentation
│── hardhat.config.js      # Hardhat configuration for contract testing and deployment
│── package.json           # Dependencies and project metadata
│── .gitignore             # Files to ignore in version control
## Smart Contracts  
| Contract | Description |
|----------|------------|
| `Router.sol` | Core contract for handling multi-hop swaps and liquidity routing. |
| `LiquidityManager.sol` | Manages liquidity pool interactions and rebalancing. |
| `FeeManager.sol` | Handles protocol fees and revenue sharing. |

## Deployment  
### Prerequisites  
- Node.js & npm  
- Hardhat  
- A Web3 wallet (e.g., MetaMask)  

### Install Dependencies  
```sh
npm install
