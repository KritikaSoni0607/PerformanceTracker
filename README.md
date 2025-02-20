# PerformanceTracker

## Overview
The **PerformanceTracker** is a Solidity smart contract that allows users to record and retrieve their performance scores. Each user can store their score along with a timestamp, ensuring trackable and immutable performance data.

## Features
- Users can record their performance scores.
- Anyone can retrieve stored performance data by providing a user's address.
- Ensures only valid scores are recorded.

## Smart Contract Details

### Data Structures
- **Performance struct:** Stores the user's `score` and `timestamp`.
- **Mapping:** `performances` associates an Ethereum address with a `Performance` record.
- **Owner:** The contract deployer is assigned as the owner.

### Functions
- `recordPerformance(uint256 _score)`: Allows a user to record their performance score.
- `getPerformance(address _user)`: Retrieves the performance details (score and timestamp) of a given user.

## Requirements
- Solidity version `^0.8.0`
- Compatible Ethereum Virtual Machine (EVM) environment

## Deployment
1. Compile the contract using a Solidity compiler (e.g., Remix, Hardhat, Truffle).
2. Deploy it on an Ethereum-compatible blockchain.
3. Interact with the functions via web3.js, Ethers.js, or directly in Remix.

## License
This project is licensed under the **MIT License**.

## Smart Contract Address
```
0x83EB0194b00f25F6Ef728f2a4b0817A5184ad97A
```

