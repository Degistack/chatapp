# Chat App using Blockchain

This project demonstrates Chat application using Blockchain.

Technologies used:

Frontend framework: NextJS
Smart contract: Solidity
Ethereum development environment: Hardhat
Ethereum Web Client Library - Web3.js
Local Blockchain: Hardhat node

Prerequisites
Node.js installed on your local machine
MetaMask Chrome extension installed in your browser

Run locally
Clone the repo
git clone https://github.com/Degistack/chatapp

Install the dependencies
npm i ethers
npm web3modal

Configure hardhat
npx hardhat

To spin up a local network,
npx hardhat node

Deploy
npx hardhat run scripts/deploy.js --network localhost

Configure
Modify the constant ChatAppAddress with the address which you get during deployment

Run the app
npm run dev

1. Clone this repository

```sh
git clone github.com/Degistack/chatapp
```

2. Install the dependencies

```sh
npm install
```

3. Run the local node

```sh
npx hardhat node
```

4. Deploy to localhost

```sh
npx hardhat run scripts/deploy.js --network localhost
```

5. Start the app

```sh
npm start
```
