# ScholarSlice

This Python script utilizes optical character recognition (OCR) techniques, natural language processing (NLP) models, and deep learning models to extract information from scientific publication images (PNG files), generate titles, and summarize their content. It then outputs the results to an Excel file.

## Dependencies

- *nltk:* For natural language processing tasks such as tokenization.
- *pytesseract:* Python wrapper for Google's Tesseract-OCR Engine.
- *PIL:* Python Imaging Library for opening, manipulating, and saving many different image file formats.
- *spacy:* For named entity recognition (NER) tasks.
- *transformers:* Hugging Face's Transformers library for utilizing pre-trained deep learning models.
- *pandas:* For handling tabular data efficiently.



### Usage

- Place your PNG files containing scientific publication images in a directory.
- Modify the directory_path variable in the script to point to this directory.
- Run the script.
  The script will process each PNG file, extract text, generate titles, summarize the content, and store the results in an Excel file.

### burn

Allows token holders to destroy a specified amount of their tokens, reducing the total supply.

Parameters:
- amount: The amount of tokens to be burned.

### Output

The script generates an Excel file containing three columns:

- Title: Extracted title from the publication.
- Authors: Likely authors extracted using named entity recognition (NER).
- Alternative Titles: Alternative titles generated based on the summary of the publication content

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
