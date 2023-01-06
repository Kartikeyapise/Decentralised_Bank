### project details

1. This Project is an attempt to simulate a Decentralised banking system which hosts it’s entire backend on blockchain where users can deposit, withdraw, and send funds to other users in a secure and decentralised manner, publicly available and irrevocable manner.
2. Users can own multiple accounts
3. Each User can have a maximum of 3 accounts
4. Every Account can have maximum of 4 owners
5. Withdrawing funds from an account should need approvals of all the account owners.

### Steps to run the bloackchain network locally:

### create a dir, Initialise a project and then. install hardhat:

mkdir hardhat
npm init
npm install --save-dev hardhat
npx hardhat

### Spin up a test hardhat network with nodes on localhost

### after this you can see all the network logs in the console

npx hardhat node

### Connect to this test network using any client/wallet like metamask using these credentials:

Network Name: Hardhat
Network URl: http://127.0.0.1:8545/
chain id: 31337
Currency Symbol: HardhatETH

### Deploy smart contracts using a script in hardhat:

npx hardhat node
npx hardhat run --network localhost scripts/deploy.js

### Run all test cases:

npx hardhat test
