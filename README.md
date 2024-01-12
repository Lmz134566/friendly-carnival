# friendly-carnival
## Overview
 friendly-carnival is a custom ERC-20 token implemented on the Ethereum blockchain.
 ## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Transaction Information](#transaction-information)
- [Burn Functionality](#burn-functionality)
- [License](#license)

## Features

- ERC-20 Standard: friendly-carnival follows the ERC-20 standard, making it compatible with a wide range of decentralized exchanges (DEXs) and wallet services.
- Ownership: The contract includes ownership capabilities, allowing the owner to perform privileged actions.
- Transaction Information: Functions to retrieve and display transaction information, enhancing transparency.
- Burn Functionality: A bonus  that enables the owner to burn a specified amount of tokens, reducing the total supply.
  
<img width="1119" alt="Screenshot 2024-01-12 at 6 03 39 PM" src="https://github.com/Lmz134566/friendly-carnival/assets/146177749/6f5f9e3f-f5a9-4c4f-885f-42c0f7e9e8e0">

## Usage

1. **Deploy the Contract:**
   - Deploy the contract on the Ethereum blockchain. Pass the address of the initial owner to the constructor.

2. **Interact with the Contract:**
   - Use any Ethereum wallet or DApp browser to interact with the deployed contract.
   - The owner can burn tokens using the `burn` function.
   - Retrieve transaction information using the provided functions.

3. **Integrate with Your Application:**
   - Integrate friendly-carnival into your decentralized application or token-based system by interacting with the contract's address.

## Transaction Information

- **Latest Transaction Timestamp:**
  - Function: `getLatestTransactionTimestamp`
  - Returns the timestamp of the latest transaction in a human-readable format.
  
- **Transaction Sender:**
  - Function: `getTransactionSender`
  - Returns the address of the transaction sender.

- **Transaction Receiver:**
  - Function: `getTransactionReceiver`
  - Returns the address of the transaction receiver.

## Burn Functionality

- **Burn Tokens:**
  - Function: `burn`
  - Only the owner can call this function to burn a specified amount of tokens, reducing the total supply.

## License

This project is licensed under the GNU GPLv3 License - see the [LICENSE](LICENSE) file for details.
