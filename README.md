# Paytr protocol smart contracts

You can find all our smart contracts in this repository.
At the moment there's one main contact, `Paytr.sol`.

Looking to use the Paytr protocol for your project? Check out our documentation [here](https://paytr.gitbook.io/product-docs/).

## Truffle test

All the tests are located in the `test/paytr.test.js`file.
Run `npm install` to install the dependencies.

We recommend to fork Goerli testnet and unlock an account which holds a lot of USDC, by using this command:
`ganache --fork https://goerli.infura.io/v3/YOURKEY --wallet.unlockedAccounts="0x75C0c372da875a4Fc78E8A37f58618a6D18904e8"`

Open a new terminal window and run `truffle test --network myFork`.