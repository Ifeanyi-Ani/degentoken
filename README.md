# DegenToken Smart Contract Deployment

This repository contains a set of scripts and a Solidity smart contract for deploying and interacting with the DegenToken smart contract on the Ethereum blockchain. DegenToken is an ERC-20 token with additional functionality for setting item costs, redeeming items, and tracking player items.

## Prerequisites

Before using these scripts, make sure you have the following installed:

- Node.js and npm: [Download Here](https://nodejs.org/)
- Hardhat: A development environment for Ethereum. Install it globally using npm: `npm install -g hardhat`

## Getting Started

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/Ifeanyi-Ani/degentoken.git
   cd degentoken
   ```

2. Install project dependencies:

   ```
   npm install
   ```

3. Configure your Ethereum network settings in the `hardhat.config.js` file. You can specify the network, provider URL, and other settings as needed.

4. Deploy the DegenToken smart contract by running the deployment script:

   ```
   npx hardhat run scripts/deploy.js
   ```

   This will compile the smart contract, deploy it to the specified network, and display the contract's address in the console.

5. You can also interact with the deployed contract using the provided scripts or by creating your own Ethereum applications.

## Script Descriptions

- `scripts/deploy.js`: Deploys the DegenToken smart contract to the Ethereum network specified in `hardhat.config.js`.

## Usage

You can customize and extend the provided scripts and smart contract according to your project's requirements. The DegenToken contract provides methods for minting, burning, setting item costs, redeeming items, transferring tokens, and more.
