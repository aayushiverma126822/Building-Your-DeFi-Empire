# Building-Your-DeFi-Empire

Welcome to Avalanche-Subnets! Here, you'll find two essential Solidity smart contracts: `ERC20.sol` and `vault.sol`. These contracts form the backbone of an ERC-20 token ecosystem. `ERC20.sol` establishes the ERC-20 token, while `vault.sol` provides a secure storage solution for managing tokens.

## Getting Started with Remix:

### Prerequisites:

1. Remix IDE: Install Remix IDE on your web browser.
2. Ethereum Wallet: Ensure compatibility with an Ethereum wallet like MetaMask for contract interaction.

### Steps:

1. Open Remix IDE:
   - Launch Remix IDE in your web browser.

2. Import Contracts:
   - Copy the code from `ERC20.sol` and `vault.sol`.
   - Create new files named `ERC20.sol` and `vault.sol` in Remix.
   - Paste the respective code into each file.

3. Compile Contracts:
   - Access the "Solidity" tab in Remix.
   - Choose the appropriate Solidity compiler version (e.g., ^0.8.17).
   - Click "Compile" to compile the contracts.

4. Deploy Token Contract:
   - Switch to the "Deploy & Run Transactions" tab.
   - Select `ERC20.sol` from the contract dropdown.
   - Click "Deploy" to initiate deployment of the ERC-20 token contract.

5. Copy Token Address:
   - After deployment, copy the token contract address from the Remix console.

6. Deploy Vault Contract:
   - Choose `vault.sol` from the contract dropdown.
   - Paste the ERC-20 token contract address into the constructor parameter for Vault.
   - Click "Deploy" to deploy the vault contract.

### Interact with Contracts:

Once deployed, interact with the contracts using their functions:
- Connect your EVM Subnet to Remix for transaction execution.

## License:

This project is licensed under the MIT License. Check the LICENSE file for details.

- - -
