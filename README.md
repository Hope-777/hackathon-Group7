# ScholarSlice

This Python script utilizes optical character recognition (OCR) techniques, natural language processing (NLP) models, and deep learning models to extract information from scientific publication images (PNG files), generate titles, and summarize their content. It then outputs the results to an Excel file.

## Dependencies

- *ERC20 Compliant:* Fully compatible with the ERC20 standard, ensuring interoperability with a wide range of services and platforms in the Ethereum ecosystem.
- *Mintable:* Authorized accounts (e.g., the contract owner) can generate new tokens, facilitating flexible supply management.
- *Burnable:* Token holders can reduce the circulating supply by destroying a portion of their tokens, enhancing value through scarcity.
- *Transferable:* Tokens can be easily transferred between accounts, enabling seamless transactions within the network.

## Contract Details

- *Name:* NinteyOne
- *Symbol:* 91
- *Blockchain:* Ethereum

## Functions

### Constructor

Initializes the contract, setting the token details and the initial owner.

Parameters:
- initialOwner: The address that will be granted the ownership of the contract.

### burn

Allows token holders to destroy a specified amount of their tokens, reducing the total supply.

Parameters:
- amount: The amount of tokens to be burned.

### mint

Enables the contract owner to create new tokens and assign them to a specified address.

Parameters:
- to: The address that will receive the newly minted tokens.
- amount: The amount of tokens to be minted and assigned.

### transfer

Overrides the standard ERC20 transfer function to include custom logic, if necessary.

Parameters:
- recipient: The address to receive the tokens.
- amount: The amount of tokens to be transferred.

## Deployment and Usage

To deploy the 91Token contract, you will need an Ethereum wallet with enough Ether to cover the gas fees and a development environment configured for Solidity and Ethereum smart contract deployment (e.g., Truffle, Hardhat).

1. *Setup Development Environment:* Ensure that your development environment is properly set up for Solidity and Ethereum smart contract development.
2. *Deploy Contract:* Use your preferred tooling to compile and deploy the contract to the Ethereum network.
3. *Interact with Contract:* After deployment, you can interact with the contract's functions using Ethereum wallets or programmatically through Ethereum libraries such as web3.js or ethers.js.