# Build Checklist App

# Overview

This repository contains the source code and resources for the project "Checklist App". This project serves as a hands-on guide for individuals looking to develop their first decentralized application (DApp) on the Ethereum blockchain.


# Project Structure
## contracts:
This directory contains the Solidity smart contracts for the Ethereum blockchain. Explore the SimpleStorage.sol contract used in the tutorial.

## frontend: 
The front-end of the decentralized application (DApp) built with HTML, CSS, and JavaScript. It interacts with the Ethereum blockchain using the Web3.js library.

## backend: (Optional) 
If applicable, include a backend folder for server-side logic, databases, or other supporting components.

## tests: 
This folder includes test scripts to ensure the proper functioning of smart contracts. It's good practice to write tests for your smart contracts.


# Prerequisites

Before starting with this project, ensure you have the following:

    - *Node.js* installed
    - *Truffle* framework installed
    - *Ganache* or another Ethereum development blockchain for testing
    - A web browser with MetaMask or another Ethereum wallet extension installed

# Getting Started

## Clone this repository to your local machine:

git clone https://github.com/your-username/blockchain-first-dapp.git


## Navigate to the project directory:

cd blockchain-first-dapp

## Install project dependencies:

npm install

## Compile and migrate the smart contracts:

truffle compile
truffle migrate

## Start the development server for the DApp:

npm run dev

Open your web browser and navigate to http://localhost:3000 to interact with the DApp.

# Additional Resources
Ethereum Documentation
Solidity Documentation
Truffle Documentation