# MEV Attack Simulation

This GitHub repository contains code and resources for simulating a Miner Extractable Value (MEV) attack. MEV attacks exploit transaction ordering on the blockchain to maximize profits, and this repository provides a practical demonstration of how such an attack can be simulated.

## Overview

- **JavaScript Bot:** The `/scripts` directory contains a JavaScript bot that orchestrates the MEV attack. It performs various actions, including forking the Ethereum mainnet, manipulating contract balances, controlling transaction order, and observing the results.

- **Solidity Smart Contract:** The `/contracts` directory contains a Solidity smart contract named `Attacker.sol`. This contract is deployed and used in the MEV attack simulation. It interacts with Uniswap and manipulates token balances.

## Prerequisites

Before running the MEV attack simulation, ensure you have the following prerequisites:

- [Hardhat](https://hardhat.org/): A development environment for Ethereum that provides the necessary tools for running this simulation.
- Node.js: Ensure you have Node.js installed on your machine.

## Usage

1. Clone this repository to your local machine.

2. Install project dependencies using npm:

   ```bash
   npm install
    ```
3. Run the MEV attack simulation:
    ```bash
    npx hardhat run scripts/sandwichAttack.js
    ```


This command will execute the JavaScript bot and simulate the MEV attack on the Ethereum mainnet fork.

## Results
After running the simulation, you can observe the results, including the balances of the attacker and victim addresses, to see how the MEV attack unfolded.

## Disclaimer
This repository is intended for educational and research purposes only. MEV attacks are a complex and sensitive topic within the blockchain space. Please use this code responsibly and do not engage in any malicious activities on the Ethereum network.

## License
This project is licensed under the MIT License.