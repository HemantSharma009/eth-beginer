# eth-beginer
# MyToken Smart Contract
# Overview
The MyToken smart contract is a basic implementation of a custom ERC20-like token on the Ethereum blockchain. This contract allows the creation (minting) and destruction (burning) of tokens while keeping track of balances for each address.

# Features
Public Token Details: The contract stores and provides public access to the token's name, abbreviation, and total supply.
Balance Mapping: The contract maintains a mapping of addresses to their respective token balances.
Mint Function: Allows the creation of new tokens and adds them to the total supply and the specified address's balance.
Burn Function: Allows the destruction of tokens, reducing both the total supply and the specified address's balance, with checks to ensure sufficient balance.
Events: Emits events for minting and burning actions to facilitate off-chain tracking and logging.
# Contract Details
# Public Variables
tokenName: The name of the token.
tokenAbbrv: The abbreviation of the token.
totalSupply: The total supply of tokens.
# Mappings
balances: A mapping from addresses to their respective balances.
# Events
Mint: Emitted when tokens are minted.
Burn: Emitted when tokens are burned.
# Functions
# mint
Mints new tokens, increasing the total supply and the balance of the specified address.


# burn
Burns tokens, decreasing the total supply and the balance of the specified address. Ensures that the address has sufficient balance to burn.


# Deployment
To deploy the contract, use a tool like Remix, Truffle, or Hardhat. Make sure to have a compatible version of Solidity (0.8.18) and sufficient ETH in your account for gas fees.

# License
This project is licensed under the MIT License. See the SPDX-License-Identifier at the top of the contract for more details.

