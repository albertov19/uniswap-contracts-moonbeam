# Deploy Uniswap V2 to Moonbase Alpha (or Standalone node)

This is a Hardhat setup to deploy the necessary contracts of Uniswap.

## Get Started

Clone repo:
``` 
git clone https://github.com/albertov19/uniswap-contracts-moonbeam/
cd uniswap-contracts-moonbeam
```

Install packages:
```
npm i
```

Modify the private keys as you wish in the `hardhat.config.js` file.

Deploy the contracts (Standalone):
```
npx hardhat run --network standalone scripts/deploy-uniswap.js
```

Contracts will be deployed if node is running.
