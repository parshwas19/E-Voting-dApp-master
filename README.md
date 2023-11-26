# EVoting on Ethereum - Project Overview

## Project Description
"EVoting on Ethereum" is a blockchain-based voting system powered by Ethereum. It leverages the security and transparency of blockchain technology to facilitate a reliable voting process.

## Key Components

### Smart Contracts
- [VoteLibrary.sol](https://github.com/parshwas19/EVoting-on-Ethereum/blob/main/contracts/VoteLibrary.sol): Defines structures for votes, parties, and voter identities.
- [VoteTracker.sol](https://github.com/parshwas19/EVoting-on-Ethereum/blob/main/contracts/VoteTracker.sol): Manages voting operations, party registration, and user identity verification.

### Frontend Application
- HTML files for various interfaces like admin login, party registration, voting portal, etc.
- [app.js](https://github.com/parshwas19/EVoting-on-Ethereum/blob/main/src/js/app.js): JavaScript file handling the frontend logic and interaction with Ethereum smart contracts.

### Configuration and Deployment
- [truffle-config.js](https://github.com/parshwas19/EVoting-on-Ethereum/blob/main/truffle-config.js): Configuration file for Truffle, a development framework for Ethereum.
- Migration scripts for deploying contracts to the Ethereum network:
  - [1_initial_migration.js](https://github.com/parshwas19/EVoting-on-Ethereum/blob/main/migrations/1_initial_migration.js)
  - [2_deploy_contract.js](https://github.com/parshwas19/EVoting-on-Ethereum/blob/main/migrations/2_deploy_contract.js)

### Package Management
- [package.json](https://github.com/parshwas19/EVoting-on-Ethereum/blob/main/package.json): Lists project dependencies and metadata.

## Functionality
- Voter registration and verification.
- Party registration for elections.
- Secure voting process with vote tracking.
- Viewing election results.

## Technology Stack
- Ethereum for blockchain functionality.
- Solidity for smart contracts.
- JavaScript and jQuery for frontend interaction.
- Truffle for Ethereum development and testing.

## Installation and Setup
- Clone the repository.
- Install dependencies using `npm install`.
- Configure Truffle and deploy contracts to Ethereum network.
- Run the frontend application.

## Developer Notes
- Ensure Ethereum client compatibility.
- Test smart contracts thoroughly before deployment.

---

