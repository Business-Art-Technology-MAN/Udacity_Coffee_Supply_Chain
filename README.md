# Udacity Coffee Supply Chain Project

This repository containts an Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

## Project Rubric
### UML Diagrams (ctrl+ click to open in new tab)
* [Activity Diagram](UMLDiagrams/CoffeeSupplyChain_ActionDiagram.png)
* [Sequence Diagram](UMLDiagrams/CoffeeSupplyChain_SequenceDiagram.png)
* [State Diagram](UMLDiagrams/CoffeeSupplyChain_StateDiagram.png)
* [Class Diagram](UMLDiagrams/CoffeeSupplyChain_ClassDiagram.png)

### Libraries Built With

* [truffle-assertions](https://www.npmjs.com/package/truffle-assertions) -Used to bridge compatibility between Truffle v5 and solc v0.4.24
* [sol2uml](https://github.com/naddison36/sol2uml#solidity-2-uml) - library which help generate UML Data/Class diagrams.

### IPFS
* IPFS was not used
    * I would have liked too but it seems the npm libraries have changed and I ran out of time.

### Contract Deployed to Rinkeby
[Deployed Contract Etherscan link](https://rinkeby.etherscan.io/address/0x93ef038de3265c0c1240d6a9d109e1f362b2743a)

Contract Address: 0x93ef038de3265c0c1240d6a9d109e1f362b2743a
Transaction ID (TxHash): 0x5fe5f8593ed44efd00c4b600eb03809af275c4501d05ec91277f1098439da7ff
## Installing locally

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Please make sure you've already installed ganache-cli, Truffle and enabled MetaMask extension in your browser.

### Installing

A step by step series of examples that tell you have to get a development env running

Clone this repository:

```
git clone https://github.com/Business-Art-Technology-MAN/Udacity_Coffee_Supply_Chain
```

Install all requisite npm packages (as listed in ```package.json```):

```
npm install
```
To test locally.
Launch Ganache:

```
ganache-cli -m "spirit supply whale amount human item harsh scare congress discover talent hamster"
```
In a separate terminal window, Compile/test smart contracts:

```
truffle migrate
truffle test
```

All 10 tests should pass.

To test the functionality with the boiler plate front-end.
In a separate terminal window, launch the DApp:

```
npm run dev
```

## Built With

* [Ethereum](https://www.ethereum.org/) - solc v0.4.24
* [Truffle Framework](https://truffleframework.com/) - v5.1.47 - a development framework for Ethereum
* [Ganache-cli](https://www.trufflesuite.com/ganache) - Ganache CLI v6.12.0 (ganache-core: 2.13.0)
* [truffle-assertions](https://www.npmjs.com/package/truffle-assertions) -Used to bridge compatibility between Truffle v5 and solc v0.4.24
* [sol2uml](https://github.com/naddison36/sol2uml#solidity-2-uml) - library which help generate UML Data/Class diagrams.


## Authors

This repo is cloned from Udacity Coffee Supply Chain project. [Github](https://github.com/udacity/nd1309-Project-6b-Example-Template)
* **Joseph Mitchell** - [Github](https://github.com/Business-Art-Technology-MAN)
- Implemented the project requirements with minimal updates to the front-end and boiler plate code.
## Acknowledgments

* Solidity
* Ganache-cli
* Truffle
* truffle-assertions
* sol2uml
* Works Cited - repos I reviewed while implementing my solution
    * [garima94921](https://github.com/garima94921/Ethereum-SupplyChain-Dapp)
    * [caliskimmer](https://github.com/caliskimmer/Udacity-Blockchain-SupplyChainTracker)