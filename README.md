# Task 1 – Simple Token Smart Contract

## Description
This is a simple ERC-20-like smart contract for a basic token transfer system using Solidity. Written and deployed as part of the CodTech Blockchain Internship.

## Tools Used
- Solidity
- Hardhat
- Ethers.js
- Replit (Node.js environment)

## Contract Features
- Token Name: AnishToken
- Symbol: SGT
- Transfer function to send tokens between accounts

## Deployment Steps
1. Compiled using:
   ```bash
   npx hardhat compile
   ```

2. Deployed using:
   ```bash
   npx hardhat run scripts/deploy.js
   ```

3. Deployment Output:
   ````
   Token deployed to:
   0x5FbDB2315678afecb367f032d93F642f64180aa3
   ````