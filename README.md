# Web3 - Full Tutorial

The demo contains a basic web3 app and smart contract for minting NFTs.

- See it in action in the [Web3 NFT Tutorial](https://youtu.be/meTpMP0J5E8) on YouTube.
- Follow the full [Web3 Tutorial](https://fireship.io/lessons/web3-solidity-hardhat-react-tutorial) on Fireship.

## Usage

```bash
git clone <this-repo>
npm install

# terminal 1 per far girare Hardhat Runtime Environment
npx hardhat node

# terminal 2 per compilare e creare il network in locale
npx hardhat compile
npx hardhat run scripts/sample-script.js --network localhost

# terminal 3 
npm run dev
```

Update the deployed contract address in `components/Home.js` 


# per matic network
npx hardhat run scripts/sample-script.js --network matic