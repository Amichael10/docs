---
description: Using solidity
---

# 🚧 Deploying EVM Contracts

Follow the steps below to contribute to Genadrop

1. create a .env file and add the rpc url for the respective chain you want to deploy to.
2. Make sure Hardhat is installed, checkout the scripts under the Scripts folder
3. In your console, `run yarn hardhat run --network (network-name) (script-name)` i.e `yarn hardhat run --network avax scripts/deployMarket.js` to deploy on avax network(check the hardhatconfig.js file to see the various network tags)
4. The script runs and returns the Deployed Contract address
