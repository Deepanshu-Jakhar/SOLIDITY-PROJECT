# DeepanshuToken Smart Contract

## Overview

`DeepanshuToken` is a simple token contract built with Solidity. It lets you create, mint, and burn tokens.

## Features

- **Token Info**: Name, symbol, and total supply.
- **Balance Tracking**: Keeps track of everyone's tokens.
- **Minting**: Create and give new tokens to someone.
- **Burning**: Destroy tokens from someone's balance.

## How It Works

### Main Parts

- `deepanshuTokenName`: Name of the token.
- `deepanshuTokenSymbol`: Symbol of the token.
- `deepanshuTotalSupply`: Total number of tokens.
- `deepanshuBalances`: Tracks token balances for addresses.

### Constructor

Sets the token name, symbol, and initial supply. The deployer gets all the initial tokens.

### Functions

- **mint**: Create new tokens and give to a specific address.
- **burn**: Destroy tokens from a specific address (must have enough tokens).

## Getting Started

### Requirements

- **Solidity**: Version 0.8.18
- **Ethereum Wallet**: e.g., MetaMask
- **Node.js**: For running scripts and tests

### Deployment

Use [Remix IDE](https://remix.ethereum.org/):

1. Paste the contract code in Remix.
2. Compile the contract.
3. Deploy with the required parameters (`_name`, `_symbol`, `_initialSupply`).

### Usage

Interact with the contract using your Ethereum wallet or a web3 interface.

## License

Licensed under the MIT License.

## Contact

For questions, contact [Deepanshu](mailto:your-email@example.com).
