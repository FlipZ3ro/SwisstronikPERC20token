# Swisstronik Create a PERC20 token

`Create a PERC20 token, deploy the contract to the Swisstronik network, mint and transfer 1 token to 0x16af037878a6cAce2Ea29d39A3757aC2F6F7aac1`



### Smart Contract
```
0x5bc7d154E8dF2196f0290c48b92A3EB5aFC057a4
```

### Explorer Deploy
```
https://explorer-evm.testnet.swisstronik.com/tx/0x16ecdc128ad3ebb4100b8dc8bba595c0db26de38c5cf6fb96fb31a8fdb2a789a
```
### Explorer Minting
```
https://explorer-evm.testnet.swisstronik.com/tx/0xba22aa995a8b5beb311a61c1aac360e2541098c11fc03c93cb0e1053512296e0
```
### Explorer Transfer
```
https://explorer-evm.testnet.swisstronik.com/tx/0xb2da2cd748db213b9582d1e0f1a9cc9fe264d8f4629e39574310066f22200745
```

### Log Deploy and Mint
 <p align="center">
 <img height="auto" height="auto" src="https://raw.githubusercontent.com/arapzz/images/main/swiss/Screenshot%202023-09-29%20075114.png">
 </p>

### Log Transfer 
 <p align="center">
 <img height="auto" height="auto" src="https://raw.githubusercontent.com/arapzz/images/main/swiss/Screenshot%202023-09-29%20075150.png">
 </p>

     
# Usage
```
npm install --save-dev hardhat
npx hardhat
npm install --save-dev @nomicfoundation/hardhat-toolbox
npm install @openzeppelin/contracts
npm install @swisstronik/swisstronik.js
npx hardhat run scripts/deploy.js --network swisstronik 
npx hardhat run scripts/mint.js --network swisstronik 
npx hardhat run scripts/transfer.js --network swisstronik 
```
