# Foundry NFT

This project is a collection of smart contracts for creating and interacting with Non-Fungible Tokens (NFTs) on the Ethereum blockchain.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js and npm
- Solidity compiler (solc)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/username/foundry-nft.git
cd foundry-nft
```

2. Install libraries
```bash
make install
```

3.Create .env with next variables
 - SEPOLIA_URL - your provider link with api key for sepolia network (use Alchemy or Infura)
 - MAINNET_URL - same as previous but for Mainnet
 - ETHERSCAN_API_KEY - etherscan api key to have posibility automaticly verify deployed contract
 - PRIVATE_KEY - private key for wallet which YOU USE ONLY FOR TESTING PURPOSES, DO NOT EXPOSE KEYS FROM WALLETS WITH FUNDS