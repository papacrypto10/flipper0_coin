# 🚀 Flipper0 Smart Contract

## 🌐 Overview

The `Flipper0` contract is an ERC20 token with additional functionalities like burnability, snapshots, and voting. It's built on top of the OpenZeppelin library to ensure security and reliability.

## ✨ Features

- **🪙 ERC20 Standard**: Implements the ERC20 token standard, providing basic token functionalities like `transfer`, `approve`, and `balanceOf`.
  
- **🔥 Burnable**: Allows token holders to destroy their tokens, reducing the total supply.
  
- **📸 Snapshot**: Enables capturing the token state at a certain block, allowing for functionalities like retrospective queries and secure voting.
  
- **🔒 Ownable**: Provides basic authorization control functions, simplifying the implementation of user permissions.
  
- **📝 Permit**: Allows for gasless transactions where the transaction sender is different from the transaction signer.
  
- **🗳️ Votes**: Provides functionalities for token-based governance.

## 🛠️ Prerequisites

- 📝 Solidity ^0.8.9
- 📦 OpenZeppelin Contracts 4.9.2

## 📦 Installation

To install the OpenZeppelin library, run:

```bash
npm install @openzeppelin/contracts@4.9.2
```

## 📖 Usage

### 🏗 Constructor

The constructor initializes the token with a name (`Flipper0`), a symbol (`F0`), and mints an initial supply of `21,000,000` tokens to the message sender.

### 📸 Snapshot

The `snapshot` function allows the owner to capture the current state of the token, enabling functionalities like retrospective queries and secure voting.

### ➕ Overrides

The contract also includes several internal functions that are overrides required by Solidity for multiple inheritance.

## 📜 License

This project is licensed under the MIT License.
