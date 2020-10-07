# Portfolio Balancer

Smart contracts for the defi asset manager app.

## Install

The smart contracts are created with the OpenZeppelin framework. For more information go to https://docs.openzeppelin.com/openzeppelin

Install node packages
`npm install`

## Deploy smart contract to local blockchain

If you don't have gannache run

`npm install -g ganache-cli`

Run a fork of the mainnet on your local blockchain

`ganache-cli --fork https://mainnet.infura.io/v3/<YOUR_INFURA_PROJECT_ID> --i 999`

If you don't have an Ifura API key, here's how to get one: https://medium.com/jelly-market/how-to-get-infura-api-key-e7d552dd396f

Deploy PortfolioBalancer smart contract

`npx oz deploy`

Copy paste the smart contract address into defi asset manaager frontend app
