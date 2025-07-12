# Mint-Nft-Pharos

A script to automatically mint FaroSwap NFTs on the Pharos testnet using multiple wallets.

## Requirements
- Node.js >= 16
- All packages in `package.json` installed

## Installation
1. Install Node.js if you haven't already: https://nodejs.org/
2. Install the required packages:
   ```bash
   npm install
   ```

## Configuration
- Set the mint contract address in the `config.js` file:
  ```js
  module.exports = {
    TO_ADDRESS: '0x7fb63bfd3ef701544bf805e88cb9d2efaa3c01a9' // mint contract address
  };
  ```
- Add the private keys of your wallets to the `pk.txt` file, one private key per line.

## Usage
Run the mint script: node run.js
