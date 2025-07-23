
# Vanshika Karun - LoR DApp

This is a decentralized Letter of Recommendation (LoR) application built using Solidity for smart contracts and React for the frontend interface. The smart contract is deployed on the Sepolia testnet and interacts with a user-friendly React-based frontend.

---

## Features

- Request and approve LoR on-chain
- Connect your wallet to interact
- Secure and decentralized letter issuance

---

## Folder Structure

```
LOR mod11/
├── contracts/
│   └── LOR.sol              # Main Smart Contract
├── scripts/
│   └── deploy.js            # Deployment Script
├── frontend/
│   ├── public/
│   └── src/                 # React Frontend Code
└── hardhat.config.js
```

---

## Getting Started

### 1. Install Dependencies

For backend (root folder):

```bash
npm install
```

For frontend:

```bash
cd frontend
npm install
```

---

## Smart Contract Deployment

### 2. Configure Environment Variables

Create a `.env` file in the root folder and add the following:

```env
PRIVATE_KEY=your_private_key
SEPOLIA_RPC_URL=https://sepolia.infura.io/v3/YOUR_PROJECT_ID
```

### 3. Compile Contracts

```bash
npx hardhat compile
```

### 4. Deploy to Sepolia

```bash
npx hardhat run scripts/deploy.js --network sepolia
```

After deployment, note the contract address shown in the terminal. You'll use this in the frontend.

---

## Running the Frontend

```bash
cd frontend
npm start
```

Open `http://localhost:3000` in your browser and connect your wallet (e.g., MetaMask) to interact with the application.

---

## Deployment Proof

Screenshots included in Screenshots folder
---