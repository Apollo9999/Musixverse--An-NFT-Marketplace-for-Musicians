# Musixverse

<img src="./musomatic_home.png" alt="Musomatic Home"/>

<br/>
Musixverse is a decentralized platform where musicians can put up music/songs as NFTs. These NFTs can then be traded and each time an NFT gets traded, the musician will receive a certain percent of the trade as royalty! The main essence of the platform is to uplift music creators as they really do not get enough recognition and monetary benefits or royalties from the current available sources.



### Smart Contract and Backend

<p align="left">
<img src = "https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white"/>
<img src = "https://img.shields.io/badge/Solidity-e6e6e6?style=for-the-badge&logo=solidity&logoColor=black"/>
</p>

### Other

<p>IPFS, Ganache, Truffle, Web3.js, Metamask, Infura, Moralis, Zapier, Stream</p>

## How to setup

-   Fork the repo to your account

-   Clone the forked repo to your local system using `git clone https://github.com/<your-username>/Musixverse--An-NFT-Marketplace-for-Musicians

-   Connect your local repo to the upstream using `git remote add upstream https://github.com/Apollo9999/Musixverse--An-NFT-Marketplace-for-Musicians

-   Run `npm install` to install npm dependencies

-   Start the local development blockchain on Ganache

-   Connect Metamask to local Ganache blockcahin

-   Run `truffle migrate --reset` in the terminal

-   Run `npm start` to start the React application

## How to contribute?

-   **DO NOT** make and push changes to the main branch!

-   **Always** keep your main/working branch in sync with the main repository `git pull upstream main` on the branch you are working on locally.

-   **Always create a new branch** before making any changes `git checkout -b <new-branch-name>`, never ever make any changes directly on the master/main branch.

## Running the Test Script

Just run: `truffle test`

## Migrate the Contract after making any changes inside the contracts folder

`truffle migrate --reset`

## Testing in Truffle console

-   Run: `truffle console`

-   `Musomatic.deployed().then(function(instance) {contract = instance})`

-   Test the deployed contract:

    `contract.address`

    `contract.name()`

    `contract.symbol()`

-   To check the created song:
    `contract.songs(0)`

## Migrating to Polygon Testnet

-   `truffle migrate --network polygonTestnet`
