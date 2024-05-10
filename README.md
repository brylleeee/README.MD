# Project Title

This Solidity project implements a basic token with minting and burning functionalities.

## Description

SimpleCoin allows users to mint and burn a custom token. It includes features to track the total supply and individual balances.

### Public Variables

name: String variable storing the token name (e.g., "SimpleCoin").
symbol: String variable storing the token abbreviation (e.g., "SC").
totalSupply: Public variable of type uint representing the total number of tokens in circulation.

### Mappings

balances: Mapping that stores the balance of each address (address => uint).

### Functions

mint(address recipient, uint amount): This function mints a specified amount of tokens and assigns them to the recipient address. It increases both the totalSupply and the balance of the recipient by the amount.

burn(address account, uint amount): This function destroys a specified amount of tokens held by the account address. It reduces both the totalSupply and the balance of the account by the amount. However, it includes a conditional check to ensure the account has sufficient balance before burning.

## Authors

Contributors names and contact info

ex. Jerome Brylle M. Melgarejo
