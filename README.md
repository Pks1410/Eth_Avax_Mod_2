# Project Title: Pokémon NFT Marketplace

This is an NFT Marketplace based on Solidity, where users can buy, view, and sell back Pokémon-themed NFTs.

## Description

The application has the following functionality:

* If MetaMask is installed, the Button "Please connect your MetaMask wallet" will be available.
* If an account is connected, options will be available to view and buy NFTs, check the user’s NFTs, and sell NFTs back to the marketplace.
* View NFTs: Display available NFTs in the marketplace.
* Buy NFT: Users can purchase an NFT by doing a transaction. If the NFT is sold out, it cannot be purchased again.
* View My NFTs: Users can see the NFTs they have purchased.
* Sell NFT: Users can sell their purchased NFTs back to the marketplace.

## Getting Started

### Installing

* Users can clone this repository to their local system or download the zip file.
* Users are required to install Node.js before executing the program.

### Executing Program / Starter Next/Hardhat Project

After cloning the GitHub repository, follow these steps to get the code running on your computer:

1. Inside the project directory, in the terminal type:

```shell
npm i
```

2. Open two additional terminals in your VS Code.

3. In the second terminal type:

```shell
npx hardhat node
```

4. In the third terminal, type: 

```shell
npx hardhat run --network localhost scripts/deploy.js
```

5. Back in the first terminal, to launch the front-end enter the command:

```shell
npm run dev
```

After this, the project will be running on your localhost. 
Typically at http://localhost:3000/

## Help

To Understand the Hardhat commands on can use this command in terminal:

```
npx hardhat help
```

## Authors

- Name: Prakhar Sahu
- MetacrafterID: Prakhar1410 (1410sahu.prakhar@gmail.com)
- Loom Video Link: https://www.loom.com/share/aed4dc4049294a1d9250ecc863a2eb1d?sid=3bfcbf7c-f03b-4892-8f2c-abe46cf4dbf9


## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
