# Creating-ERC-20-Token-on-Ethereum
A simple ERC-20 style token smart contract built in Solidity with functions for transfer, approve, transferFrom, and balance management. Deployed and tested using Remix IDE.

# MyToken (MTK)

## Overview
MyToken is a simple ERC-20 compatible token built on Ethereum for learning purposes.  
This token demonstrates how cryptocurrency tokens work internally using Solidity.

---

## Token Details
- *Name:* MyToken  
- *Symbol:* MTK  
- *Decimals:* 18  
- *Total Supply:* 1,000,000 MTK (minted to the deployer)

---

## Features
- ✔ Standard ERC-20 style implementation  
- ✔ Transfer tokens between addresses  
- ✔ Approve spending for another address  
- ✔ Transfer tokens using allowance (transferFrom)  
- ✔ Emits Transfer and Approval events  
- ✔ Full balance tracking  

---

## How to Deploy
1. Open *RemixIDE* → https://remix.ethereum.org  
2. Create a new file named MyToken.sol  
3. Paste the entire smart contract code  
4. Compile with Solidity *0.8.x*  
5. Go to *Deploy & Run Transactions*  
6. Select *Remix VM (Prague)*  
7. Enter total supply (Example: 1000000000000000000000000)  
8. Click *Deploy*  

---

## How to Use

### 🔹 Check Balance
```solidity
balanceOf(address) → uint256
