# Ethereum DApp Supply Chain Tracker

The Ethereum DApp demonstrates a Coffee Beans Supply Chain flow between a seller and buyer. The user story is similar to any commonly used supply chain process. A seller can add items to the inventory system stored in the blockchain. A buyer can purchase such items from the inventory system.<br>
A seller can mark an item as shipped, and similarly a buyer can mark an item as received.

# UML Diagrams

Below you can check the UML diagrams for the supply chain.



# Activity Diagram

![image](https://user-images.githubusercontent.com/40601380/147713816-1ead236c-a6bd-44b2-9e4a-6322fa17bad0.png)

 <br><br>
 
# State Diagram

![image](https://user-images.githubusercontent.com/40601380/147713745-2262a8ca-0f6c-4c4a-9b5b-d1c483766fce.png)
 <br><br>
 
 # Class Diagram
 
 ![image](https://user-images.githubusercontent.com/40601380/147713860-ec22f794-5ab5-4dab-8465-263b0cd2e68f.png)

 
  <br><br>
  
  # Sequence Diagram
  
  ![image](https://user-images.githubusercontent.com/40601380/147713949-ebf2f261-ffec-4d23-9341-17a289825727.png)

<br><br>

The DApp User Interface should look like the following:
![image](https://user-images.githubusercontent.com/40601380/147781260-05a000d4-e1b1-4aba-80a3-fdc29f9fe681.png)

<br><br>

# Transaction History
![image](https://user-images.githubusercontent.com/40601380/147781385-6a014280-a0c0-4816-83e3-895ea5c13391.png)
<br><br>

# Getting Started
<br>
These instructions will get you a copy of the project up and running on your local machine for development for notes on how to deploy the project on a live system. <br>

# Installing 
A step by step walk through of how to get your development env running <br>
Clone this repository: <br>
```
git clone https://github.com/dina-25/Supply-Chain-Tracker
```
Install all required npm packages as listed in package.json 

```
npm install
```
Launch Ganache:<br>
```
ganache-cli -m "mnemonic"
```
Your Terminal should look like this:
![image](https://user-images.githubusercontent.com/40601380/147782547-43748972-c222-4a3f-bdf5-22dcd3235583.png)

In a separate terminal window, Compile smart contracts:
```
truffle compile
```
Your terminal should look something like this:
![image](https://user-images.githubusercontent.com/40601380/147782689-99c1bd49-a602-4992-ba9d-22c28dd7acdb.png)

<br>
Test smart contracts: <br>

```
truffle test
```
All 10 tests should run sucessfully <br>

![image](https://user-images.githubusercontent.com/40601380/147782824-9392597b-8f8d-4562-9cc8-6ad1c78ddd78.png)
<br>

Now launch the DApp, in a separate terminal:<br>
```
npm run dev
```
# Deploy smart contract on a public test network (Rinkeby)
The smart contract is deployed on the Ethereum Rinkeby test network: <br>
```
truffle migrate --network rinkeby
```
- Transaction ID : 0x089609f15d95ded796d7e8f9315513eee03807fdd787a6afe88bbb9d33afca2f <br>
- Contract address: 0x34f08a380270a16C6895e254616faF260fdA78B0 <br>

# Libraries
- ganache-cli : "v6.12.2" <br>
  Local Ethereum blockchain<br>
- lite-server : "^2.6.1"<br>
  Web server for local testing<br>
- truffle-plugin-verify: "^0.5.20"<br>
  Verify deployed Contracts on Rinkeby Test-network<br>
- truffle-hdwallet-provider: "^1.0.27" <br>
  HDWalletProvider for Infura deployment
- truffle : "5.4.22"<br>
  Framework for deployment of smart contracts
- Web3js: "1.2.1"
  Ethereum Javascript API

# Versions
- Truffle v5.4.22 <br>
- Solidity >0.5.16 <br>
- Node v14.5.0 <br>
- Web3.js v1.4.3 <br>

# License
- MIT license
- Copyright 2021 &copy; [Dina Elsayed](https://github.com/dina-25)


