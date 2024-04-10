# EVM Subnets - ERC20 Token and Vault Smart Contracts

## Overview

Welcome to the Avalanche Subnets repository! Here, you'll find two essential Solidity smart contracts: `ERC20.sol` and `vault.sol`. The `ERC20.sol` contract establishes the foundation for an ERC-20 token, complete with fundamental functions such as transfer, approve, mint, and burn. Meanwhile, the `vault.sol` contract acts as a secure storage solution for the ERC-20 token, enabling users to deposit and withdraw tokens while managing the overall supply and individual balances.

## Getting Started with Remix:

### Prerequisites:

1. Install Remix IDE on your web browser.
2. Ensure compatibility with an Ethereum wallet (e.g., MetaMask) for interacting with contracts on the Ethereum blockchain.

### Steps:

1. Open Remix IDE:
   - Access Remix IDE through your preferred web browser.

2. Import Contracts:
   - Copy the contents of `ERC20.sol` and `vault.sol`.
   - Within Remix, create new files named `ERC20.sol` and `vault.sol`.
   - Paste the respective contents into each file.

3. Compile Contracts:
   - In Remix, navigate to the "Solidity" tab.
   - Choose the appropriate Solidity compiler version (e.g., ^0.8.17).
   - Click the "Compile" button to compile the contracts.

4. Deploy Token Contract:
   - Switch to the "Deploy & Run Transactions" tab.
   - Select `ERC20.sol` in the contract dropdown.
   - Click the "Deploy" button to initiate ERC-20 token contract deployment.

5. Copy Token Address:
   - After deployment, copy the token contract address from the Remix console.

6. Deploy Vault Contract:
   - Choose `vault.sol` in the contract dropdown.
   - Paste the ERC-20 token contract address into the constructor parameter for Vault.
   - Click the "Deploy" button to deploy the vault contract.

### Interact with Contracts:

Once deployed, interact with the contracts through the provided functions:
- Connect your EVM Subnet to Remix for transaction execution.

## Authors

- Author: snehaa02

## License:

This project is licensed under the MIT License. Refer to the LICENSE file for details.
