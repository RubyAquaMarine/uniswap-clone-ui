This project was bootstrapped with [Create Eth App](https://github.com/paulrberg/create-eth-app) and the
[Uniswap v2](https://github.com/paulrberg/create-eth-app/tree/develop/templates/react/uniswap-v2) template.

This template contains 2 packages:

- [contracts](/packages/contracts)
- [react-app](/packages/react-app)

The React app implements a basic example for how to connect and pull data from the
[Uniswap v2](https://thegraph.com/explorer/subgraph/uniswap/uniswap-v2) subgraph.

## What is Uniswap v2?

Uniswap V2 is the second iteration of the Uniswap, a protocol for automated token exchange on Ethereum. Read more about it in the [official documentation](https://uniswap.org/docs/v2/).

## How to regenerate the project

Run: yarn create eth-app my-eth-app --template uniswap-v2
More: https://github.com/paulrberg/create-eth-app

## How to start
- yarn install
- update the configuration in ./packages/react-app/src/config.js
- yarn run react-app:start
