
# CustomToken Smart Contract

A custom ERC20 token contract based on the OpenZeppelin library.

## Description

This Solidity smart contract implements a custom ERC20 token named "Harsh" with the symbol "HRS". It extends the OpenZeppelin `ERC20` contract and adds additional functionality for minting and burning tokens. The contract also inherits from `Ownable`, providing access control mechanisms.

## Getting Started

### Installing

To use this smart contract, you need to have access to a development environment with the Solidity compiler and access to the OpenZeppelin library. You can install the necessary dependencies using the following commands:

1. Clone the repository:
   ```sh
   git clone https://github.com/LiveOnGithub/ETH-AVAX_Mod-2.git
   cd ETH-AVAX_Mod-2
   ```

2. Install the OpenZeppelin library (if not already installed):
   ```sh
   npm install @openzeppelin/contracts
   ```

### Executing program

To deploy and interact with the `CustomToken` smart contract, follow these steps:

1. Compile the contract:
   ```sh
   npx hardhat compile
   ```

2. Deploy the contract (using Hardhat as an example):
   ```sh
   npx hardhat run scripts/deploy.js
   ```

3. Interact with the contract using your preferred Ethereum wallet or web3.js.

## Help

If you encounter any issues or have questions about using the smart contract, you can reach out to the contract's author or community members.

## Authors

- Moksh Verma 
- 22BCT10059@cuchd.in

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.

