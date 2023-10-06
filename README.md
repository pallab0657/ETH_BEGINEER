# MINT BURN Smart Contract METACRAFTERS

A simple Solidity smart contract for a custom token called MyToken.

## Description

This Solidity smart contract implements a basic token with the following features:

1. Public variables to store token details, including Token Name, Token Abbreviation, and Total Supply.
2. A mapping of addresses to token balances.
3. A `mintSupply` function that allows the contract owner to mint (create) new tokens by increasing the total supply and the balance of a specified address.
4. A `burnSupply` function that allows the contract owner to burn (destroy) tokens by deducting the total supply and the balance of a specified address.
5. The `burnSupply` function includes conditionals to ensure that the balance of the address is greater than or equal to the amount to be burned.

## Getting Started

### Prerequisites

Before deploying and interacting with this smart contract, you need:

- A development environment for Ethereum smart contracts, such as Remix, or Hardhat for local deployement.
- Ether to cover gas fees for deploying and interacting with the contract on the Ethereum network.

### Installing

1. Clone this repository or copy the smart contract code to your development environment.

### Deploying the Smart Contract

1. Compile the smart contract in your development environment.
2. Deploy the smart contract to the Ethereum network of your choice.

### Interacting with the Smart Contract

1. Once deployed, you can use Ethereum wallet software or web3.js to interact with the contract.
2. Call the `mintSupply` function to create new tokens.
3. Call the `burnSupply` function to burn (destroy) tokens.

## Help

If you encounter any issues or have questions, feel free to reach out for assistance.

## Authors

- Pallab

## License

This project is licensed under the MIT License. See the CODE file for details.
