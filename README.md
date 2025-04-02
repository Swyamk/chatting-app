# Chatting-App (Web3 Chat DApp)

Building and Deploying a Web3 Chat Application (DApp) with Next.js, Hardhat, MetaMask, Solidity & Ethereum.

This decentralized chat application enables secure, private, and censorship-resistant messaging on the Ethereum blockchain. It leverages Next.js for front-end development, Hardhat for smart contract deployment, MetaMask for wallet integration, Solidity for smart contract development, and Ethereum for blockchain functionality.

## Features
- Secure and private blockchain-based messaging.
- MetaMask wallet authentication.
- Decentralized infrastructure with Ethereum smart contracts.
- End-to-end encrypted chat for enhanced privacy.

## Installation and Setup

### Prerequisites
Ensure you have the following installed:
- **Node.js (v18.17.1 or higher)**: [Download](https://nodejs.org/en/download)
- **MetaMask Wallet Extension**: [Download](https://metamask.io/)
- **VS Code Editor**: [Download](https://code.visualstudio.com/download)

### Steps to Set Up the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Swyamk/chatting-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd chatting-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Deploy smart contracts:
   ```bash
   npx hardhat run scripts/deploy.js --network goerli
   ```
5. Start the development server:
   ```bash
   npm run dev
   ```
6. Open the application in your browser:
   ```
   http://localhost:3000
   ```

## Smart Contract Deployment
The smart contracts are written in Solidity and deployed using Hardhat. You can deploy them to the Ethereum testnet (Goerli) or any other EVM-compatible blockchain.

## Technologies Used
- **Next.js** - Frontend framework
- **Solidity** - Smart contract programming language
- **Hardhat** - Ethereum development environment
- **MetaMask** - Wallet authentication
- **Ethereum** - Blockchain network

## Additional Resources
- **Remix IDE for Smart Contracts**: [Remix](https://remix-project.org)

---
This project demonstrates the power of decentralized communication and blockchain-based privacy solutions. Feel free to modify and extend its features based on your use case.

